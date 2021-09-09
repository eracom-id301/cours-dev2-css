---
layout: page
title: Audio et vidéo
permalink: audio-video.html
---

Cours du 7 septembre 2021

Comment intégrer des fichiers son et vidéo dans une page web.

## Exemples audio

Un exemple simple qui permet de lire un fichier audio mp3:

```html
<audio
  controls
  src="/media/cc0-audio/t-rex-roar.mp3">
    Your browser does not support the <code>audio</code> element.
</audio>
```

Un autre exemple qui propose deux formats (mp3 et ogg):

```html
<audio controls>
  <source src="myAudio.mp3" type="audio/mpeg">
  <source src="myAudio.ogg" type="audio/ogg">
  <p>Votre navigateur ne prend pas en charge l'audio HTML5.
  Voici un <a href="myAudio.mp3">lien vers le fichier audio</a>
  à la place.</p>
</audio>
```

### Quel format audio choisir?

Le format MP3 est aujourd'hui le mieux pris en charge par tous les navigateurs courants:

- Infos sur [caniuse.com : MP3 audio format](https://caniuse.com/mp3) - support global de 98.38%.
- Infos sur [Wikipedia : HTML5 audio](https://en.wikipedia.org/wiki/HTML5_audio)

Autre format audio très bien pris en charge: le codec AAC dans un conteneur MP4. Support global de 98.21% [selon caniuse.com](https://caniuse.com/aac).

## Exemples vidéo

```html
<video controls>
  <source src="rabbit320.mp4" type="video/mp4">
  <source src="rabbit320.webm" type="video/webm">
  <p>Your browser doesn't support HTML5 video. Here is a <a href="rabbit320.mp4">link to the video</a> instead.</p>
</video>
```

### Quel format vidéo choisir?

Le format MPEG-4/H.264 est aujourd'hui le mieux pris en charge par tous les navigateurs courants:

- Infos sur [caniuse.com : MPEG-4/H.264 video format](https://caniuse.com/mpeg4) - support global de 98.19%
- Infos sur [Wikipedia : HTML5 video](https://en.wikipedia.org/wiki/HTML5_video)

### Précision sur les conteneurs et codecs

Dans le domaine du multimédia, il est important de bien séparer le rôle des conteneurs de celui des codecs :

- Un **conteneur** permet de stocker des flux vidéo et audio liés selon une séquence précise. Exemples de conteneurs: MP4, Webm, Ogg, QuickTime, AVI, MKV.
- Un **codec** permet d'encoder (COmpression) et de décoder (DECompression) ces flux. Exemples de codecs vidéo: H.264, H.265, VP9, Ogg Theora. Exemples de codecs audio: AC3, MP3, AAC, Ogg Vorbis.

Le conteneur peut donc être vu comme une boîte (le *contenant*), et les flux comme ce que l'on met à l'intérieur de la boîte (le *contenu*).

Parmi les conteneurs fréquents:

- **MP4** (ou MPEG-4), format conteneur pour encapsuler des données de type multimédia (audio ou vidéo essentiellement). L'extension de nom de fichier généralement associée à ce format est « .mp4 ».
- **WebM** (extensions .webm, .weba), format open-source développé par Google. Peut regrouper des flux vidéo codés en VP9 et des flux audio codés en Vorbis.
- **Ogg** (extensions .ogg, .ogv, .oga, .ogx). Format open-source.
- **QuickTime** (extension .mov) : développé par Apple.

L'article Wikipédia [Format conteneur](https://fr.wikipedia.org/wiki/Format_conteneur) donne plus de précisions.

## Ressources

- [Page MDN sur l'élément audio](https://developer.mozilla.org/fr/docs/Web/HTML/Element/audio)
- [Page MDN sur l'élément video](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)