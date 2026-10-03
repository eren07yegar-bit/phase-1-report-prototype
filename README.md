# Phase 1 — Research report prototype

Persian, RTL, scroll-first review prototype forked from the original Example 14 `research-feature-explainer.html`. The copied template's article shell, base styles, expandable sections, and callout language are retained and adapted. Report passages, tables, worksheets, and diagrams are selected from the source research.

- **Live preview:** https://eren07yegar-bit.github.io/phase-1-report-prototype/
- **Download all files:** https://github.com/eren07yegar-bit/phase-1-report-prototype/archive/refs/heads/master.zip
- **Source repository:** https://github.com/eren07yegar-bit/phase-1-report-prototype

The sample contains 11 report sections plus the cover and a contents index listing all 14 chapters. It is not the complete report or a PDF. No page-flip or magazine viewer is included. Chapter preview entries for sections outside the prototype point to excerpts in the contents list.

## Run locally

Open `index.html` in a browser. For local Persian fonts and worksheet storage, serve this folder with a static server, for example:

```powershell
python -m http.server 8000
```

Then visit `http://127.0.0.1:8000/`.

All fonts and icons are included locally. Worksheet answers stay in the current browser's local storage and are not sent to a server.

## Attribution and licenses

The base HTML template identifies itself as Copyright 2026 Anthropic PBC, SPDX-License-Identifier: Apache-2.0. It is adapted in this prototype; see `NOTICE` and `LICENSE-APACHE.txt`. The Vazirmatn fonts are distributed under the SIL Open Font License in `assets/fonts/OFL.txt`.
