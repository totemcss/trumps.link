# Link

inuitcss plugin based on @suitcss' [utils-link](https://github.com/suitcss/utils-link/)

## Installation

- npm : `npm install --save totem-trumps-link`
- bower : `bower install --save totem-trumps-link`

## Available classes

- `u-link-clean`
- `u-link-block`
- `u-link-go`
- `u-link-back`
- `u-link-complex` & `u-link-complex__target`
- `u-link-stretch` & `u-link-stretch__source`

## Usage 

Link complex exemple

```html
<a class="u-link-complex" href="#">
    Link complex
    <span class="u-link-complex__target">target</span>
</a>
```

Link stretch exemple

```html
<div class="u-link-stretch">
    Link stretch
    <a class="u-link-stretch__source" href="#">source</a>
</div>
```
