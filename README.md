# Minilogue XD Field Guide

An interactive study guide for the Korg minilogue xd synthesizer. One static page, no build step, no backend.

- **Explore**: a playable 3D panel. Drag a knob to turn it, tap a switch to step it, press the keys to play.
- **Lessons**: twelve short lessons that follow the signal path from oscillators to effects.
- **Recipes**: eight patches that set the panel and explain why each setting is there.
- **Quiz**: ten random questions per round.

The sound comes from a simplified one-voice Web Audio model, so the real instrument sounds richer. Page references follow the 63-page owner's manual.

## Run locally

Open `index.html` in a browser, or serve the folder:

```sh
npx serve .
```

## Deploy

The site is a single `index.html` at the repository root. On Vercel, import the repository and keep the defaults (framework preset "Other", no build command, output directory `.`).

## Disclaimer

An unofficial project. Not affiliated with or endorsed by KORG Inc.; minilogue is their trademark.
