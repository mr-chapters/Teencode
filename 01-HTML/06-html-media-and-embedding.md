# HTML Media and Embedding

Websites can contain images, audio, video, and embedded content.

## Images

```html
<img src="images/game.png" alt="Screenshot of the game menu">
```

The `alt` text explains the important content when the image cannot be seen.

## Video

```html
<video controls width="640">
  <source src="video/demo.mp4" type="video/mp4">
</video>
```

Use controls when users need to control playback.

## Audio

```html
<audio controls>
  <source src="audio/theme.mp3" type="audio/mpeg">
</audio>
```

## Embedding external content

An iframe can embed another webpage or service when the provider allows it.

Do not embed unknown or untrusted content without understanding the security and privacy implications.

## Challenge

Create a media page with one image, one audio element, and one video element. Give every image meaningful alternative text.
