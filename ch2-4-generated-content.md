---
layout: page
title: generated-content
permalink: generated-content.html
---

Le “Generated Content” est une fonctionnalité CSS pratique et de plus en plus utilisée.

Cette méthode utilise les sélecteurs CSS `::before` ou `::after`, pour rajouter des éléments avant ou après le contenu déjà existant.  

Exemple pour générer un cœur bleu avant un texte dans une liste :

```css
.liste::before{ 
  content: "♥"; 
  padding-right: 8px; 
  color: blue; 
} 
```

<p class="codepen" data-height="300" data-default-tab="css,result" data-slug-hash="porerxM" data-editable="true" data-user="eracom" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/eracom/pen/porerxM">
  generated content ♥</a> by Manuel Schmalstieg (<a href="https://codepen.io/eracom">@eracom</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>


Autre exemple: un aplat de couleur en dégradé est apposé "par dessus l'image".

<p class="codepen" data-height="300" data-default-tab="css,result" data-slug-hash="gORNXWz" data-editable="true" data-user="eracom" style="height: 300px; box-sizing: border-box; display: flex; align-items: center; justify-content: center; border: 2px solid; margin: 1em 0; padding: 1em;">
  <span>See the Pen <a href="https://codepen.io/eracom/pen/gORNXWz">
  Generated Content 2</a> by Manuel Schmalstieg (<a href="https://codepen.io/eracom">@eracom</a>)
  on <a href="https://codepen.io">CodePen</a>.</span>
</p>

### Le challenge du jour à compléter :

[https://codepen.io/eracom/pen/wveLPjN?editors=1100](https://codepen.io/eracom/pen/wveLPjN?editors=1100) 


### Usages spectaculaires

Exemples combinant le Generated Content avec de l’animation: 

Le site du WordCamp Europe 2017:

[https://europe.wordcamp.org/2017/](https://europe.wordcamp.org/2017/) 

La page CSS Zen Garden “Steel”, par Steffen Knoeller: 

[http://www.csszengarden.com/219/](http://www.csszengarden.com/219/) 


### Liens utiles

https://www.w3schools.com/cssref/pr_gen_content.asp 

https://www.w3schools.com/cssref/pr_gen_counter-increment.asp 

https://www.smashingmagazine.com/2013/04/css-generated-content-counters/ 