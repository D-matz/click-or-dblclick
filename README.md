click or double click



```html
<button hx-target="#target"
  hx-get="/defaultURL"
  hx-ext="click-or-dblclick" dblclick-url="/otherURL"
  hx-trigger="click delay:0.3s, dblclick">
    click once for defaultURL, double click for otherURL
</button>
```
