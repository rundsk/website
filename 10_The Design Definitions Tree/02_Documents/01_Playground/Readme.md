# Playgrounds

Playgrounds are used to demonstrate components. To embed a playground 
inside a document use the `<Playground>` tags.

<Playground>
  <Avatar name="Marius Wilms" email="mariuswilms@mailbox.org" />
</Playground>

```html
<Playground>
  <Avatar name="Marius Wilms" email="mariuswilms@mailbox.org" />
</Playground>
```

## Annotating Components

With annotations you can highlight specific points on the playground and add a comment.

<Playground src="annotations.json">
  {Component}
</Playground>

```html
<Playground src="annotations.json">
  {Component}
</Playground>
```

### Annotations File Format

The annotations specification file has to be formatted like this (`annotationColor` is optional):

<CodeBlock src="annotations.json" language="json"></CodeBlock>

## Large Standalone Playgrounds

If you place a document called `playground.md` amongst your 
[documents](/The-Design-Definitions-Tree/Documents) for one 
[aspect](/The-Design-Definitions-Tree/Aspects) in the design 
defintions tree, its contents will be displayed in a large 
[Playground](The-Design-Definitions-Tree/Documents/Components/Playground) 
on the top of the aspect’s page in DSK. This is helpfull to display a
general demo of the aspect, so your users can immediatly see what the
aspect is about. You can see an example of this in the documentation
for some of the frontend’s documentation components, e.g. the
[Banner](The-Design-Definitions-Tree/Documents/Components/Banner).

