# DROP IE8

## HTML5

- Form validation
- Geolocation
- `<video>` && `<audio>`

## CSS

- `border-radius` (full support : no graceful degradation/weird HTC-based solutions anymore)
- `box-shadow` (same thing)
- `opacity` (without extra syntax)
- `background-position`'s new syntax (http://tanalin.com/en/blog/2011/09/css3-background-position/)
- `@font-face` : no more EOT files (WOFF may even be enough at all ?)
- `rem` font sizing
- Alpha channel in colors : `rgba`, `hsla`
- Advanced selectors : `:last-child`, `:nth-child`, `:first-of-type`...
- `:empty` : https://developer.mozilla.org/en-US/docs/CSS/:empty
- `:not` : https://developer.mozilla.org/en-US/docs/Web/CSS/:not
- `calc()` : https://developer.mozilla.org/en-US/docs/CSS/calc
- Multiple backgrounds : http://www.css3.info/preview/multiple-backgrounds/
- `background-size` : https://developer.mozilla.org/en-US/docs/Web/CSS/background-size
- `:checked` : http://css-tricks.com/the-checkbox-hack/
- SVG/canvas
- `transform` : https://developer.mozilla.org/en-US/docs/Web/CSS/transform
- proper syntax for `::before` and `::after`

## JS

- jQuery can be avoided for basic stuff (and 2.0 is usable if needed) :

```javascript
$ = document.querySelector.bind(document);
Element.prototype.on = Element.prototype.addEventListener;
$('.lol').on('click', function() {});
```

- Websockets
- `getElementsByClassName`
- `getComputedStyle`
- `addEventListener`
- `function.prorotype.bind`
