# ivanrp14.github.io

The site published on **GitHub Pages**. This repository contains a Vite build output, not the source.

## What's here

```
index.html                          # entry; the <title> is still "Vite + React"
assets/index-*.js                   # bundled JavaScript
assets/index-*.css                  # bundled CSS
images/                             # static images
vite.svg
```

There is no `package.json` and no `src` folder. To change copy or sections, rebuild from the source project and copy `index.html` and `assets/` back.

The React portfolio with sections and languages is in the private `portfolio` repository.

## How to view it locally

Any static server over this folder works. For example, with Node:

```bash
npx serve .
```

On GitHub, the site is served from the `main` branch (or whichever branch Pages is set to) at the repo root.
