# Hong Kong School Bus Route Map

A static web page for visualizing 9 Hong Kong school bus routes with route selection, station times, and map overlays.

## Files

- `index.html` — online AMap version. Requires a Web JS API key in the page.
- `schoolbus-amap-online.html` — same as `index.html`.
- `schoolbus-map-design.html` — offline SVG fallback/demo version.

## Privacy

This repository intentionally excludes the original PDF scan and any local/private files.

## AMap setup

Open `index.html` and replace:

```js
const AMAP_KEY = '請填入你的高德Web端Key';
const AMAP_SECURITY_JSCODE = '';
```

with your AMap Web JS API key and optional security jscode.
