# DROP IE8

## CSS

- `border-radius` (full support : no graceful degradation/weird HTC-based solutions anymore)
- `box-shadow` (same thing)
- `opacity` (without extra syntax)
- `background-position`'s new syntax (ttp://tanalin.com/en/blog/2011/09/css3-background-position/)
- `@font-face` : no more EOT files (WOFF may even be enough at all ?)
- `rem` font sizing
- alpha channel in colors : `rgba`, `hsla`
- advanced selectors : `:last-child`, `:nth-child`, `:first-of-type`...
- `:empty` : https://developer.mozilla.org/en-US/docs/CSS/:empty
- `:not` : https://developer.mozilla.org/en-US/docs/Web/CSS/:not
- `calc()` : https://developer.mozilla.org/en-US/docs/CSS/calc
- Multiple backgrounds : http://www.css3.info/preview/multiple-backgrounds/
- `background-size` : https://developer.mozilla.org/en-US/docs/Web/CSS/background-size
- `:checked` : http://css-tricks.com/the-checkbox-hack/
- SVG/canvas
- transforms

**Note** : I was greatly helped with the above list by [this article](http://blog.goetter.fr/post/56443705444/ie8-must-die "IE8 must die") by Raphael Goetter, although he also included some items that are actually not fully correctly supported by IE9, and therefore don't appear here.

## JS

- jQuery can be avoided for basic stuff (and 2.0 is usable if needed) :

```javascript
$ = document.querySelector.bind(document);
Element.prototype.on = Element.prototype.addEventListener;
$('.lol').on('click', function() {});
```

- websocket support
