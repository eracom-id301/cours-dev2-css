---
layout: page
title: CSS Animations
permalink: css-animations.html
---

Les animations CSS sont présentées le 16 novembre par Luca et Dani.

Exercice : [https://replit.com/join/sinqicbikk-dandadan](https://replit.com/join/sinqicbikk-dandadan)

> Votre mission sera de :
> - Changer la couleur du carré pour chaque position
> - Animer ce dernier avec 4 positions différentes
> - Faire en sorte que l'animation se relance à l'envers

Un exemple complété:

[https://replit.com/@Miggix/CSS-Animation-Exercice](https://replit.com/@Miggix/CSS-Animation-Exercice?v=1)

## Ressources

- [Sur cours-web.ch](https://cours-web.ch/css/animations.html)
- [MDN: les transitions](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions)
- [MDN: les animations](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_Animations/Using_CSS_animations)
- [W3Schools: Animations](https://www.w3schools.com/css/css3_animations.asp)

### Les fonctions de timing

Pour une animation fluide, on voudra souvent un mouvement qui connaît des accélérations et des ralentis. On peut préciser ce comportement avec la propriété CSS `animation-timing-function`. Il existe plusieurs réglages par mots-clés: `ease`, `ease-in`, `ease-out`, `ease-in-out` et `linear`.

Si on veut être plus précis, on peut définir une courbe de bézier qui décrit l'accélération. Lea Verou a développé un petit outil permettant de réaliser vos propres courbes de Bézier de manière
visuelle: [https://cubic-bezier.com/](https://cubic-bezier.com/)