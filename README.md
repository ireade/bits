# bits
Snippets of things I re-use but always forget exactly how to write it


## HTML Video

```html
<video controls poster="poster.jpg">
    <source type="video/webm" src="video.webm">
    <img src="poster.jpg" alt="">
</video>
```

## HTML GIF as Video

```html
<video autoplay loop muted playsinline poster="poster.jpg">
    <source type="video/webm" src="video.webm">
    <img src="original.gif" alt="">
</video>
```

## HTML Picture Element

Serve different formats of the same image

```html
<picture>
    <source type="image/webp" srcset="image.webp">
    <img src="image.jpg" alt="">
</picture>
```

