# Sarvatra Physics — V13

Physics simulation library for Class 11 and Class 12.

## Topic animation system
Each topic can now have an optional GIF, WebM, or MP4 animation. The website reads `media.json`.

### Add an animation
1. Upload the animation into `gifs/` or `videos/`.
2. Add one entry to `media.json`.
3. Use this key format:

`class11/01/units-dimensions-errors`

Example:

```json
{
  "class11/01/units-dimensions-errors": "gifs/class11/chapter01/units.gif"
}
```

The topic will automatically show a **Preview** button. GIFs are displayed as images; WebM/MP4 files play muted, looped and inline in a preview window.

## Important
Keep animation files reasonably small. For most physics animations, WebM/MP4 is preferred over large GIFs because it loads faster.


V13 fixes chapter rendering and keeps the hero orbits centered around the S logo on mobile and desktop.
