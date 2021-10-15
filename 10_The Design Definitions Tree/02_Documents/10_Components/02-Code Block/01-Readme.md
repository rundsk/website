<Banner title="Version Feature">
  Documentation components are available since version 1.2.
</Banner>

# Examples

## Basic Usage

Usually you’ll be using fenced code blocks (\`\`\`) when authoring Markdown.
These get automatically converted to a `<CodeBlock>`.

```
alert('Hello World!');
```

## Documenting Components

As any other code, components can be documented using the `<CodeBlock>`, too.

<CodeBlock>
	<Color color="#001dff">Blue</Color>
</CodeBlock>

```html
<CodeBlock>
	<Color color="#001dff">Blue</Color>
</CodeBlock>
```

## Code Highlighting

In order to use code highlighting you need to add information about the language used to the code block. When using fenced code blocks (\`\`\`) you write the name of the language directly after the opening ticks. When using the `<CodeBlock>` component, a `language` property is used.

~~~markdown
```js
alert("highlight this code");
```
~~~

```html
<CodeBlock language="js">
	alert("highlight this code");
</CodeBlock>
```

## Adding a Title

Some code snippets benefit greatly from an added title. Here we want to show
what the contents of a file called `fib.js` look like. To add a title you can
set the `title` property of the `<CodeBlock>` component:

<CodeBlock title="fib.js" language="js">
function fib(n) {
  return n < 2 ? n : fib(n - 1) + fib(n - 2);
}
</CodeBlock>

```html
<CodeBlock title="fib.js" language="js">
function fib(n) {
  return n < 2 ? n : fib(n - 1) + fib(n - 2);
}
</CodeBlock>
```

## Displaying the content of a file

A `<CodeBlock>` component can also load and display the content of a file stored in the DDT:

```html
<CodeBlock src="data.json"></CodeBlock>
```
