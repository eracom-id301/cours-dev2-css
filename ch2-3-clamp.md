---
layout: page
title: min, max, et clamp
permalink: clamp.html
---



Clamp, une fonction CSS qui va encore plus loin que `minmax()`. Clamp permet de définir une taille de fonte minimum *et* maximum. Dans la spécification du W3C, il est indiqué que:

* Clamp accepte trois valeurs: valeur minimum, valeur centrale, valeur maximum.
* En cas de conflit, c'est la valeur minimum qui sera appliquée.

Le mot clamp, en anglais, désigne cet outil:

![Un serre-joints](img/clamp.jpg)

Un exemple de taille de fonte "responsive", définie avec clamp:

```css
h1 {
  font-size: clamp(5px, 5vmax, 80px);
}
h2 {
  font-size: clamp(5px, 3vmax, 60px);
}
```

Le résultat de ce code: [https://competent-galileo-9d6914.netlify.app/](https://competent-galileo-9d6914.netlify.app/)


### Ressources

- Support de cours, [Unités CSS](https://cours-web.ch/css/units.html)
- La spécification du W3C: [Comparison Functions: min(), max(), and clamp()](https://www.w3.org/TR/css-values-4/#comp-func), dans *CSS Values and Units Module Level 4*
- [Explication en vidéo](https://css-tricks.com/min-max-and-clamp-are-css-magic/), sur CSS Tricks.



### Erreurs possibles

Si ça ne fonctionne pas:

Attention : si vous mettez un espace entre clamp et la parenthèse ça ne marche pas:

Ecrire `clamp(20px, 10vw, 80px)` au lieu de `clamp (20px, 10vw, 80px)`.


### Ne pas confondre avec vmin, vmax

Les fonctions `min()` et `max()` ne sont pas à confondre avec les unités `vmin` et `vmax`. Ces dernières sont des unités relatives au *viewport*. Rappel des quatre unités *viewport*:

- `vw` :	1% de la **largeur** du *viewport*
- `vh` :	1% de la **hauteur** du *viewport*
- `vmin` :	1% de la plus petite dimension (la plus petite valeur de vh ou vw)
- `vmax` :	1% de la plus grande dimension (la plus grande valeur de vh ou vw)

Voir : 