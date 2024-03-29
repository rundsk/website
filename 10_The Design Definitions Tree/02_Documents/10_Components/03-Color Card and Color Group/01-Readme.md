<Banner title="Version Feature">
  Documentation components are available since version 1.2.
</Banner>

Moving the mouse over a color card reveals accessibility information about the contrast ratio of black and white to the color. Clicking a color card copies the color’s value.

# Examples

## Single Color

<ColorCard color="#001dff">Blue</ColorCard>

```
<ColorCard color="#001dff">Blue</ColorCard>
```

### Compact

<ColorCard color="#001dff" compact="true">Blue</ColorCard>

```html
<ColorCard color="#001dff" compact="true">Blue</ColorCard>
```

## Color Group

<ColorGroup>
  <ColorCard color="#001dff">Blue</ColorCard>
  <ColorCard color="#FFE874" comment="A juice shade of yellow!">Yellow</ColorCard>
</ColorGroup>

```html
<ColorGroup>
  <ColorCard color="#001dff">Blue</ColorCard>
  <ColorCard color="#FFE874" comment="A juice shade of yellow!">Yellow</ColorCard>
</ColorGroup>
```

### Compact

<ColorGroup compact="true">
  <ColorCard color="#001dff">Blue</ColorCard>
  <ColorCard color="#FFE874">Yellow</ColorCard>
</ColorGroup>

```html
<ColorGroup compact="true">
  <ColorCard color="#001dff">Blue</ColorCard>
  <ColorCard color="#FFE874" comment="A juice shade of yellow!">Yellow</ColorCard>
</ColorGroup>
```

## Color Group from JSON

<ColorGroup src="colors.json"></ColorGroup>

```html
<ColorGroup src="colors.json"></ColorGroup>
```

### File format

The Color Group component expects a file according to the [Lona Color Defintions Spec](https://github.com/airbnb/Lona/blob/master/docs/file-formats/colors.md).

<CodeBlock title="colors.json" src="colors.json" language="json"></CodeBlock>
