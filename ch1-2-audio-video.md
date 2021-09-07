---
layout: page
title: Audio et vidéo
permalink: audio-video.html
---

Comment intégrer des fichiers son et vidéo dans une page web.

## Exemples audio

```html
<audio
  controls
  src="/media/cc0-audio/t-rex-roar.mp3">
    Your browser does not support the <code>audio</code> element.
</audio>
```

Un autre exemple qui propose deux formats:

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

Voir sur [https://caniuse.com/mp3](https://caniuse.com/mp3)

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

Voir sur [https://caniuse.com/mpeg4](https://caniuse.com/mpeg4)

## Ressources

- [Page MDN sur l'élément audio](https://developer.mozilla.org/fr/docs/Web/HTML/Element/audio)
- - [Page MDN sur l'élément video](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)