# JedMud TUI

JedMud TUI is a experimental terminal user interface for the NodeJs framework. It uses ANSI escape codes to write elements on the screen.

Jedmud was developen on NodeJs v16. It may or may not work on other versions.

Working example covering most features: https://github.com/jedmud/tui-example

## Slots

Slots define element positions relative to screen parameters. One slot may be used by multiple elements. Also multiple elements instances may get parameters from one slots instance.

Example: https://github.com/jedmud/tui-example/src/examples/slots.js

## Elements

Elements give slots behavior. Each element configuration may have different available options.

Example: https://github.com/jedmud/tui-example/src/examples/box.js

### Official element types

#### Box

https://github.com/jedmud/tui-example/src/examples/box.js

#### Prompt

https://github.com/jedmud/tui-example/src/examples/prompt.js

#### Scroller

https://github.com/jedmud/tui-example

#### Metrics

https://github.com/jedmud/tui-example

#### Timer

https://github.com/jedmud/tui-example

## How to install example module

```
git clone https://github.com/jedmud/tui-example
cd tui-example
npm i
node .
```
