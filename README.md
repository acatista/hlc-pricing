# Helocrene Studio — Pricing Page

A single static page (`index.html` + `style.css`) built from the finalised
package-list PDF. No build step, no dependencies — just plain HTML/CSS.

```
index.html
style.css
fonts/
  Geist-VariableFont.ttf
  Testuale-Regular.ttf
assets/
  logo.svg
```

## Editing content

All copy lives directly in `index.html`:
- The two package cards (name, price, timeline, description, spec lists)
  are under `<section class="pricing">`.
- The "Optional Collaterals" accordions are under
  `<section class="collaterals">`. Each `<details class="accordion">`
  is one dropdown category — add or remove `<li>` items freely.

## Going live

See the deployment steps shared alongside this file for connecting your
own domain via GitHub Pages.
