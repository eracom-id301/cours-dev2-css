---
layout: page
title: CSS Shapes
permalink: css-shapes.html
---

Dans le jargon du web, le terme "CSS Shapes" peut être compris de deux manières: 

### 1) produire des formes avec du CSS:

[https://css-tricks.com/the-shapes-of-css/](https://css-tricks.com/the-shapes-of-css/)

Quelques jolis exemples:

[https://cssicon.space](https://cssicon.space/#/icon/chat)

Mais ce que nous allons traiter aujourd'hui, c'est le module CSS Shapes du W3C:

### 2) CSS Shapes Level 1

Voici une double-page du magazine Harper’s Bazaar. Dans les années 1940, le directeur artistique russe Alexey Brodovitch révolutionne la mise en page en combinant images et textes de manière audacieuse:

![Double page de Harper’s Bazaar](img/css-shapes/BrodovitchCW1.jpg)

En CSS, il est possible d'appliquer des formes au texte avec le module CSS Shapes.

![Exemple de shape-outside](img/css-shapes/exemple-shape-outside.png)

Peut-on l'utiliser dans les navigateurs? La réponse est donné par ce site: 
[https://caniuse.com/css-shapes](https://caniuse.com/css-shapes)

Ce module fonctionne dans:

- Chrome depuis 2014
- Safari depuis 2017
- Firefox depuis 2018
- Edge depuis 2020

Voici la spécification W3C de ce module:

[W3C Candidate Recommendation](https://www.w3.org/TR/css-shapes/), 20 March 2014: "CSS Shapes describe geometric shapes for use in CSS. For Level 1, CSS Shapes can be applied to floats."

## Articles explicatifs

L'article explicatif fondamental:
*[CSS Shapes 101](https://alistapart.com/article/css-shapes-101/)*, par Sara Soueidan, 2014

Autre article fondamental : *[Take A New Look At CSS Shapes](https://www.smashingmagazine.com/2018/09/css-shapes/)*, par Rachel Andrews, en 2018. Firefox vient alors d'implémenter les CSS Shapes.

Enfin, un 3e article très complet avec de bons exemples: *[An Introduction to CSS Shapes](https://tympanus.net/codrops/2018/11/29/an-introduction-to-css-shapes/)*, par Tania Rascia, 2018.

### Le challenge à réaliser


**Lien du code de base:**  
[https://codepen.io/timounfrekan/pen/BadmPeE?editors=1100](https://codepen.io/timounfrekan/pen/BadmPeE?editors=1100)

<p class="codepen" data-height="300" data-default-tab="css,result" data-slug-hash="BadmPeE" data-editable="true" data-user="timounfrekan" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/timounfrekan/pen/BadmPeE">
  Smashing Shapes - Gradients</a> by Audrey (<a href="https://codepen.io/timounfrekan">@timounfrekan</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>

**Objectif demandé:**  
Inverser la position de la forme (la placer dans l'angle supérieur gauche).


### Documentation

[MDN : CSS_Shapes](https://developer.mozilla.org/fr/docs/Web/CSS/CSS_Shapes)

## Exemples


Exemples à explorer: 

- CSS shapes - circle: [https://codepen.io/eracom/pen/JjJgByG](https://codepen.io/eracom/pen/JjJgByG)
- Alternative JSFiddle: [https://jsfiddle.net/mschmalstieg/qmv3cney/2/](https://jsfiddle.net/mschmalstieg/qmv3cney/2/)


- CSS shapes - polygon: [https://codepen.io/eracom/pen/GREVBJm](https://codepen.io/eracom/pen/GREVBJm)



- CSS shapes - circle with image: [https://codepen.io/eracom/pen/mdwNjpB](https://codepen.io/eracom/pen/mdwNjpB)
- Lettrine en CSS shape: [https://codepen.io/eracom/pen/JjJgaOM](https://codepen.io/eracom/pen/JjJgaOM?editors=1100)
- Smashing Shapes - Gradients: [https://codepen.io/rachelandrew/pen/zJNRpL](https://codepen.io/rachelandrew/pen/zJNRpL?editors=1100)

### Exemples avec Clip Path:

- Clip Path polygon sur une image: [https://codepen.io/eracom/pen/rNwXZmj](https://codepen.io/eracom/pen/rNwXZmj)
- Clip Path et animation: [https://codepen.io/team/css-tricks/pen/10c03204463e92a72a6756678e6348d1](https://codepen.io/team/css-tricks/pen/10c03204463e92a72a6756678e6348d1)

Un outil qui aide à comprendre les Clip-Path: [https://bennettfeely.com/clippy/](https://bennettfeely.com/clippy/)
