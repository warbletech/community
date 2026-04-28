# YouTube — @Warble-Tech

Channel: **[youtube.com/@Warble-Tech](https://www.youtube.com/@Warble-Tech)**

## Assets

| File | Use |
|---|---|
| [`banner.svg`](banner.svg) | Channel banner art (2560×1440, safe area centred) |
| [`intro-script.md`](intro-script.md) | First channel-intro video script (~75 s) |
| [`thumbnail-template.svg`](thumbnail-template.svg) | Reusable 1280×720 thumbnail template |

## Render the banner to PNG

YouTube uploads expect a raster image. Pick whichever you have:

```bash
# Option A — rsvg-convert (librsvg, very fast)
rsvg-convert -w 2560 -h 1440 banner.svg > banner.png

# Option B — ImageMagick (slower, but everywhere)
magick -density 300 -background none banner.svg -resize 2560x1440 banner.png

# Option C — headless Chrome (when the others are missing)
chromium --headless --disable-gpu \
  --screenshot=banner.png --window-size=2560,1440 \
  "file://$PWD/banner.svg"

# Option D — open in Figma / Inkscape / Affinity, export 2560×1440 PNG
```

## Upload settings on YouTube

- **Banner**: YouTube Studio → Customisation → Branding → Banner image. Upload the PNG.
- **Watermark**: use `wc_icon_512px.png` from the warble-core repo (`frontend/public/wc_icon_512px.png`).
- **Profile picture**: use the bird mark from the same place.
- **About**: paste the description from [`channel-about.md`](channel-about.md) when that lands.

## Safe area

YouTube shows different crops on different devices. Anything **important** (logo, wordmark, headline) must sit inside the centre **1235×338** rectangle (centred at 1280×720 of the 2560×1440 canvas). Decorative elements (corner birds, gradients) can extend outside.

## Channel positioning (in one paragraph)

> Warble Cloud builds open, GCP-native AI ops — Starling, Reflexion, Murmuration, Brain, FRAKMA. The channel exists to record what we ship in public: live demos, Office Hours, RFC walkthroughs, and the occasional architectural teardown. No ads, no fluff — code on screen, real systems, every video.
