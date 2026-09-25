# Design reference

Staged exports from the Figma Home page (file `yoBjhf6JH8vpwbETUmrsHZ`, frame `313:315`), downloaded 2026-09-21 because Figma MCP asset URLs are short-lived.

- `figma/home-full.png` — full-page render (470×2400 thumbnail of the 1425×7283 frame).
- `figma/<section>/export.png` — 1x render of that section, the visual source of truth.
- `figma/<section>/raw_N.*` — original image fills found in the section, in Figma's traversal order (unnamed — open them to identify).
- `figma/<section>/svg_N.svg` — vector icons/logos from that section.
- `figma/categories/variants/` — image fills from all five Product Categories panel variants (component set `151:733`).

These are reference inputs, not runtime files. Files actually used by the site are copied, with meaningful names, into `frontend/public/home/<section>/`.
