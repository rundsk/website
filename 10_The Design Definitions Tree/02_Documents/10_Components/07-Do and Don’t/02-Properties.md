
# Properties

A `DoDontGroup` component can contain any number of `Do`s or `Dont`s as children. They are however all displayed in one line, so more than three is probably a bad idea.

## Do

Property | Type | Description | Default
---|---|---|---
`caption` | `String` | A caption to display underneith the demo | `""`
`background` | `"dotgrid"`, `"checkerboard"`, `"pinstripes"`, `"plain"` | The pattern to use for the background of the demo. | `"dotgrid"`
`backgroundColor` | `CSS Color String (hex, rgba)` | The background color of the demo. | `#F2F6F7`

## Dont

Property | Type | Description | Default
---|---|---|---
`caption` | `String` | A caption to display underneith the demo | `""`
`background` | `"dotgrid"`, `"checkerboard"`, `"pinstripes"`, `"plain"` | The pattern to use for the background of the demo. | `"dotgrid"`
`backgroundColor` | `CSS Color String (hex, rgba)` | The background color of the demo. | `#F2F6F7`
`strikethrough` | `Bool` | Whether the demo should be struck through, in order to emphasize it is a bad example. | `false`