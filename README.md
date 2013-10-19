DROPPING IE 8...

CSS
- support complet de border-radius (plus de dégradation gracieuse ou de support à l'arrache avec PIE pour les cas extrêmes)
- support de box-shadow (même chose)
- plus besoin d'eot ni de syntaxe cheloue pour @font-face (on pourrait limite se contenter de woff ? quid des différentes déclinaisons d'une même font ?)
- support du svg et des canvas !

JS
- possibilité de se passer de jQuery pour les choses basiques :

$ = document.querySelector.bind(document);
Element.prototype.on = Element.prototype.addEventListener;
$('.lol').on('click', function() {});

- ou passage à jQuery 2.0
- websockets !