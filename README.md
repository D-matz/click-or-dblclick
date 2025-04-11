get different URL depending on if you click or double click

## Install
```html
<script src="https://cdn.jsdelivr.net/gh/D-matz/click-or-dblclick/click-or-dblclick.js"></script>
```

## Usage

```html
<button hx-target="#target"
  hx-get="/defaultURL"
  hx-ext="click-or-dblclick" dblclick-url="/otherURL"
  hx-trigger="click delay:0.3s, dblclick">
    click once for defaultURL, double click for otherURL
</button>
```

## Example

https://d-matz.github.io/click-or-dblclick/
