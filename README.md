# Mum's Painted Passport

A watercolour "around the world" birthday site for Mum's 55th (9 November).

Open `index.html` in a browser. Everything is in that one file; the photos are in `photos/`.

## Adding photos

1. Put the photo in `photos/<country>/` (e.g. `photos/italy/rome-fountain.jpg`).
2. In `index.html`, find `const STOPS = [` and add an entry to that country's `photos` list:

```js
{ src: "photos/italy/rome-fountain.jpg", w: 1050, h: 1400, caption: "Your caption here." }
```

Add `wide: true` for a landscape photo. `w` and `h` are the image size in pixels.
