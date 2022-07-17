# JedMud TUI

JedMud TUI is a experimental terminal user interface for the NodeJs framework. It uses ANSI escape codes to write elements on the screen.

Working example covering most features: https://github.com/jedmud/tui-example

## Slots

Slots define element positions relative to screen parameters. One slot may be used by multiple elements. Also multiple elements instances may get parameters from one slots instance. Available slot configuration options:

```json
{
    "name": null,
    "parent": null,
    "top": null,
    "right": null,
    "bottom": null,
    "left": null,
    "width": null,
    "height": null,
    "borders": { "left": "", "right": "", "top": "", "bottom": "" },
    "padding": { "left": 0, "right": 0, "top": 0, "bottom": 0 }
  }
```

Slot parameters can be defined in multiple ways:

- left, width
- right, width
- left, right (width will be fluid)
- top, height
- bottom, height
- top, bottom (height will be fluid)

Example: https://github.com/jedmud/tui-example/src/examples/slots.js
