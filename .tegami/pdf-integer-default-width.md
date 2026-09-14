---
"takumi-pdf": patch
---

# Write the CIDFont default width as an integer

The PDF spec types `/DW` as an integer, so a reader that enforces it fell back to the spec default of 1000 and every glyph the entry covered advanced about 1.8x too far.
