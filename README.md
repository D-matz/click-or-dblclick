get different URL depending on if you click or double click

## Install
```html
<script src="https://cdn.jsdelivr.net/gh/D-matz/click-or-dblclick/click-or-dblclick.js"></script>
```

## Usage

hx-ext="click-or-dblclick" to use extension

dblclick-url="/otherURL" to set URL to otherURL only on double click

dblclick-target="#otherTarget" to set target to otherTarget only on double click

One click will go to your normal URL, double click will go to your dblclick-url

```html
<button hx-target="#res1"
hx-get="/click-or-dblclick/apple"
hx-ext="click-or-dblclick" dblclick-url="/click-or-dblclick/banana" dblclick-target="#res2"
hx-trigger="click delay:0.3s, dblclick">
  Click or Double Click
</button>

<div id="res1">click button to make me an apple</div>
<div id="res2">double click button to make me a banana</div>
```

## Example

https://d-matz.github.io/click-or-dblclick/
