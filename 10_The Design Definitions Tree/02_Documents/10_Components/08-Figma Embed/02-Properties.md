# Properties

Property | Type | Description | Default
---|---|---|---
`token` | `String` | Figma API access token. | [Required]
`document` | `String` | ID of the document. | [Required]
`frame` | `String` | Name of the frame to show. | [Required]

## Getting a Token
You can find out how to generate a personal access token in the [Figma API documentation](https://www.figma.com/developers/docs#access-tokens).

## Getting the Document ID
Open the document from which you would like to embed a layer. You can discern its ID by looking at the url: 

```
https://www.figma.com/file/<Document ID>/<Document Name>
```
