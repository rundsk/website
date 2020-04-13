<Banner title="Version Feature">
  Documentation components are available since version 1.2.
</Banner>

# Examples

## Basic Usage

<Playground>{Component}</Playground>

```html
<Playground>{Component}</Playground>
```

## Configured

<Playground background="pinstripes" backgroundColor="#FED28C">{Component}</Playground>

```html
<Playground background="pinstripes" backgroundColor="#FED28C">{Component}</Playground>
```

For all configuration options see [Properties](?t=properties).

## Annotations

With annotations you can highlight specific points on the playground and add a comment.

<Playground src="annotations.json">{Component}</Playground>

```html
<Playground src="annotations.json">{Component}</Playground>
```

## File Format

The annotations specification file has to be formatted like this (`annotationColor` is optional):

<CodeBlock src="annotations.json" language="json"></CodeBlock>
