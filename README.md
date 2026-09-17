# Awesome UI

A single-page interface showcase built to practise advanced CSS — layered
gradients, transitions, scroll behaviour and responsive layout — without
reaching for a framework.

Live: **[brutall100.github.io/Awsome-ui-main](https://brutall100.github.io/Awsome-ui-main)**

## Stack

Plain HTML, CSS and JavaScript. The only outside pieces are normalize.css,
Font Awesome for icons and the Lato typeface from Google Fonts, all loaded
from a CDN.

## Layout

```
index.html    all sections, top to bottom
index.css     layout, gradients, animation
index.js      interactive behaviour
img/          artwork
```

The page is composed of six full-width sections (`.a-section` through
`.f-section`), each exploring a different layout or animation idea.

## Running locally

No build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server
```
