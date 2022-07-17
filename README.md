# JedMud TUI

JedMud TUI is a experimental terminal user interface for the NodeJs framework. It uses ANSI escape codes to write elements on the screen.

Working example covering most features: https://github.com/jedmud/tui-example

## Slots

Slots define element positions relative to screen parameters. One slot may be used by multiple elements. Also multiple elements instances may get parameters from one slots instance.

Example: https://github.com/jedmud/tui-example/src/examples/slots.js

## Elements

Elements give slots a Behaviour. Each element configuration may have different available options.

Example: https://github.com/jedmud/tui-example/src/examples/box.js

### Official element types

#### Box

#### Prompt

#### Scroller

#### Metrics

#### Timer
