---
"takumi": patch
---

# Give an inline replaced element its intrinsic width

An `<img>` or `<svg>` with no width or height stretched to the width it was offered, as a block-level box does. CSS 2.1 10.3.2 gives an inline-level replaced element its intrinsic width instead, so an auto-sized inline image no longer inflates the line box it sits in.
