---
layout: page
title: GIT partie 1
permalink: git1.html
---

**7 décembre 2021:** Premier volet du cours sur GIT.

## Questions fondamentales Git

### Qu'est-ce que Git ?

Git est un logiciel de gestion de versions décentralisé. C'est un puissant outil de collaboration, indispensable dans tous les types de projets informatiques.

### D'ou vient GIT

Git a été créé en 2005 par Linus Torvalds (le créateur de Linux).

### Que signifie le mot Git ?

Selon Wikipédia: « quand on lui a demandé pourquoi il avait appelé son logiciel “git”, qui est à peu près l'équivalent de “connard” en argot britannique, Linus Torvalds a répondu “je ne suis qu'un sale égocentrique, donc j'appelle tous mes projets d'après ma propre personne. D'abord Linux, puis Git.” ».

### À quoi sert Git ?

- Permet de synchroniser un projet entre plusieurs collaborateurs.
- Offre un historique précis de toutes les modifications d'un projet.

---

## Exemples de ce que Git permet d'éviter

Quand on s'échange par email les versions successives d'un document Word...

![](img/git/final-doc.gif)

Voilà ce que ça donnerait si on nommait ainsi les issues de secours:

![](img/git/file-names-on-fire.jpeg)

C'est pour éviter ces problèmes qu'on a inventé les logiciels de gestion de versions.

## Comment fonctionne Git ?

Git est un logiciel pouvant fonctionner en ligne de commande, on lui "parle" en utilisant des commandes, telles que `pull`, `push`, `clone`, `add`, `commit`...

Le principe: 

1. En utilisant des commandes Git, on enregistre des "snapshots" qui conservent l'état du projet à un point précis.
2. On synchronise les modifications locales avec un serveur distant. Git s'occupe de fusionner les modifications.

### La notion de Commit

La commande **Commit** est centrale dans Git: c'est cette commande qui crée un nouvel "instantané" dans 

### Les états des fichiers

Le livre "Pro Git" donne une bonne explication des "trois états" dans lesquels peuvent se trouver les fichiers:

Git gère **trois états** dans lesquels les fichiers peuvent résider : `modifié`, `indexé` et `validé`.

- **Modifié** (*Modified*) signifie que vous avez modifié le fichier mais qu’il n’a pas encore été validé (*committed*).
- **Indexé** (*Staged*) signifie que vous avez marqué un fichier modifié dans sa version actuelle pour qu’il fasse partie du prochain instantané du projet.
- **Validé** (*Committed*) signifie que les données sont stockées en sécurité dans votre base de données locale.

Ceci nous mène aux trois sections principales d’un projet Git : le répertoire Git, le répertoire de travail et la zone d’index.

### Quelques termes et commandes

`repository`

C'est un dossier de travail géré avec Git. Le dossier où se trouvent tous les fichiers. Il peut s'agir d'un repository **local** (sur votre ordinateur) ou **distant** (*remote*) - par exemple sur Github.

<video width="640" height="360" controls>
  <source src="video/repo.mp4" type="video/mp4">
</video>

`git commit`

Ajoute un **commit** comprenant toutes les modifications indexées.

<video width="640" height="360" controls>
  <source src="video/git-commit.mp4" type="video/mp4">
</video>

`git branch <nombranche> [<commit>]`

Crée une branche sous ce nom qui démarre au commit actuel (ou au commit que vous aurez spécifié, si vous avez indiqué un ID de commit).

<video width="640" height="360" controls>
  <source src="video/git-branch.mp4" type="video/mp4">
</video>

`git merge <autrebranche>`

Fusionne "autrebranche" dans la branche actuelle, s'il n'y a pas de conflit.

<video width="640" height="360" controls>
  <source src="video/merge-conflict.mp4" type="video/mp4">
</video>

#### push, pull, fetch

`git push`

Pousse l'état actuel de "nombranche" dans le repository distant.

`git pull`

Récupère l'état actuel du repository distant vers votre copie locale, et tente de le fusionner dans votre branche actuelle.

`git fetch`

Copie tout le contenu du repository distant vers votre copie locale.

<video width="640" height="360" controls>
  <source src="video/push-pull.mp4" type="video/mp4">
</video>

## Liens utiles: 

- Support de cours dédié à GIT: [https://cours-web.ch/git/](https://cours-web.ch/git/)

Une vidéo d'introduction sympathique: *Débuter avec Git et Github en 30 min*

<iframe width="560" height="315" src="https://www.youtube.com/embed/hPfgekYUKgk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>