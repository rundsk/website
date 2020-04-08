<Banner title="Version Feature">
  Documentation components are available since version 1.3.
</Banner>

## Glitch

<Glitch id="hello-tensorflow"></Glitch>

```html
<Glitch id="hello-tensorflow"></Glitch>
```

Property | Type | Description | Default
---|---|---|---
`id` | `string` | The id of the Glitch app you want to embed. | [Required]
`file` | `string` | The name of the file that you want to show first. | `""`

## Asciinema

<Asciinema id="146112"></Asciinema>

```html
<Asciinema id="146112"></Asciinema>
```

Property | Type | Description | Default
---|---|---|---
`id` | `string` | The id of the Asciinema recording you want to embed. | [Required]

## CodeSandbox

<CodeSandbox id="github/zeit/next.js/tree/master/examples/hello-world"></CodeSandbox>

```html
<CodeSandbox id="github/zeit/next.js/tree/master/examples/hello-world"></CodeSandbox>
```

Property | Type | Description | Default
---|---|---|---
`id` | `string` | The id of the CodeSandbox you want to embed | [Required]
`file` | `string` | The path to the file that you want to show first. | `""`
`view` | `""`, `"preview"`, `"editor"` | The view to display. Default is preview and editor. | `""`