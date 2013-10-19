# DROP IE8

## CSS

- border-radius support (no graceful degradation/weird HTC-based solutions anymore)
- box-shadow support (same thing)
- @font-face : no more EOT files (WOFF may even be enough at all ?)
- SVG/Canvas support

## JS

- jQuery can be avoided for basic stuff (and 2.0 is usable if needed) :

```javascript
$ = document.querySelector.bind(document);
Element.prototype.on = Element.prototype.addEventListener;
$('.lol').on('click', function() {});
```

- websocket support
