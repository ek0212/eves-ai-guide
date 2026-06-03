# Eve's AI Guide

A static personal AI guide published at <https://ek0212.github.io/eves-ai-guide/>.

The site is a single file:

- `index.html` - layout, styles, timeline data, tool shelf, creator list, and source links.

## Update Flow

1. Edit the data arrays in `index.html`.
2. Update the checked date in the page title and hero eyebrow.
3. Recheck model access, pricing, and effort claims against source links before publishing.
4. Verify locally:

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>.
