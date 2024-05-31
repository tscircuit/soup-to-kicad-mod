# @tscircuit/soup-to-kicad-mod

[Issue](https://github.com/tscircuit/tscircuit/issues/156)

Placeholder for converter that converts [tscircuit soup](https://github.com/tscircuit/soup) to kicad mod s-expression.

```ts
import { convertSoupToKicadMod } from "@tscircuit/soup-to-kicad-mod"

const kicadModContent = convertSoupToKicadMod([
  {
    type: "pcb_smtpad",
    center: { x: 0, y: 0 },
    // ...
  }
])
```
