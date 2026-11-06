# KeyQuest: Starfighter Edition

> **New: Act 1 · Cold Boot** — open [`act1.html`](act1.html). The story-driven rework: you wake aboard a dark ship and type its five systems back online (Reactor, Life support, Thrusters, Sensors, Navigation) with ORA, the ship AI, on a CRT screen. Each system teaches new home-row keys, with no timer. EN and UA tracks. `index.html` is the original Starfighter build.

A single-file, browser-based typing trainer that turns touch typing into a space shooter. Type English or Ukrainian words to fire weapons at an incoming armada, while a vinyl-style synth soundtrack speeds up and slows down with your typing tempo.

## Features

- **Bilingual curriculum**: 12 progressive levels each for English (QWERTY) and Ukrainian (ЙЦУКЕН), ending in a mixed-language boss wave.
- **Auto-Map**: physical keys type the active track's layout, so you can practise Ukrainian without switching your OS input language.
- **Word Armada combat**: every key fires plasma, Space launches homing missiles, commas trigger an EMP wave, apostrophes and hyphens fire an ion beam, and . ! ? unleash a supernova.
- **Vinyl Groove music**: a Web Audio synth whose pitch and speed follow your typing cadence. Typos cause a record scratch.
- **On-screen keyboard**: highlights the next key, colour-codes finger zones, and shows animated cat paws or cyber hands reaching for each key.
- **Live stats**: WPM, accuracy, combo and score, with a summary after each level.
- **Zen mode** for distraction-free practice.

## Run it

No build step or dependencies to install. Open `index.html` in a modern browser. Tailwind, fonts and icons load from CDNs, so you need an internet connection on first load.

## Controls

| Key | Action |
| --- | --- |
| Any letter | Fire plasma |
| `Space` | Homing missile salvo |
| `Tab` | Retry current wave |
| `Esc` | Reset stats |
| `Space` / `Enter` | Continue after a level |

## Tech

Vanilla JavaScript, HTML5 Canvas, Web Audio API, Tailwind CSS (CDN), Font Awesome.
