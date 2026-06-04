# Neon City Visuals

A small collection of browser-based generative art experiments built around a neon cyberpunk city/rain concept.

This repo was generated with Claude using an algorithmic art / generative art workflow. I did not know how to use that skill at the time, so the repository keeps multiple iterations of the same idea as the piece evolved. The result is a set of interactive p5.js HTML sketches where the viewer can tune seeds, rain, neon colors, buildings, glow, and other parameters.

## What this is

Neon City Visuals is an algorithmic art project, not a traditional static image gallery. Each HTML file runs a live canvas sketch in the browser using p5.js.

The central concept is:

> Cyberpunk rain cascade — data as weather, neon as signal, city as ghost.

Later iterations push the idea toward a moving car/chase feeling, with neon-soaked rain, scrolling city depth, and GIF capture support.

## Iterations in this repo

| File | Notes |
| --- | --- |
| `neon_deluge.html` | Original baseline version of the Neon Deluge sketch. Includes seed controls, rain controls, neon palette controls, regenerate/reset, and PNG export. |
| `neon_deluge_1.html` | Early iteration with the same core concept and interface, preserving another generated version. |
| `neon_deluge_2.html` | Another early saved iteration of the rain/city generative sketch. |
| `neon_deluge_3.html` | Larger iteration with expanded generated code and more developed visual logic. |
| `neon_deluge_4.html` | Adds/experiments with scroll speed controls and a stronger sense of city motion. |
| `neon_deluge_5.html` | Most advanced “Car Chase Edition” iteration. Includes drive speed, neon palette controls, PNG download, and a 3-second GIF recording button. |

If you only want to try one version first, start with:

```text
neon_deluge_5.html
```

## Features

- Interactive p5.js canvas art
- Procedural neon city visuals
- Cyberpunk rain and light streaks
- Seed-based regeneration
- Adjustable rain intensity, speed, glow, building density, and glitch effects
- Custom neon color palette controls
- PNG export
- GIF recording in the latest iteration
- Multiple saved iterations showing the project evolving over time

## How to run

You can open any `.html` file directly in a browser, or run a local server from the repo folder:

```bash
python3 -m http.server 4173
```

Then open:

```text
http://127.0.0.1:4173/neon_deluge_5.html
```

Other versions can be opened by changing the filename, for example:

```text
http://127.0.0.1:4173/neon_deluge.html
http://127.0.0.1:4173/neon_deluge_4.html
```

Stop the server with `Ctrl + C` when finished.

## Controls

Most versions include controls for:

- Seed selection
- Rain intensity
- Rain/fall speed
- Streak length
- Wind or drive motion
- Neon glow
- Building density
- Data glitch amount
- Primary, secondary, and accent neon colors
- Regenerate / reset
- Download PNG

The latest version also includes:

- Record GIF (3s)

## Project context

This was a learning/experiment repo created while exploring AI-assisted creative coding. The files are intentionally kept as separate iterations instead of being merged into one polished app, because the iteration history is part of the project: it shows how the visual idea changed as prompts and generated code were refined.

## Tech used

- HTML
- CSS
- JavaScript
- p5.js
- Claude-generated algorithmic art code

## Notes

Because the sketches use p5.js from a CDN, an internet connection may be needed the first time the files are opened. If a page appears blank, refresh the browser or run it through the local server command above.
