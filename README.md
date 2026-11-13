# durmlife

A small CSS layout helper: a 12-column grid using floated columns and a clearing `.row`.

## Features

- `.col-1` through `.col-12` with percentage widths
- `.row` clearfix (`:before` / `:after`)
- Global `box-sizing: border-box`

## Tech stack

- CSS

## Getting started

There is no demo page. Include `framework.css` in an HTML file and wrap columns in a `.row`:

```html
<link rel="stylesheet" href="framework.css" />

<div class="row">
  <div class="col-6">Left</div>
  <div class="col-6">Right</div>
</div>
```
