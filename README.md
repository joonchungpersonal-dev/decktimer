# DeckTimer

Elgato Stream Deck-style breathing & wellness timer with pixel-art animations.

**[Try it live](https://decktimer-web.vercel.app/app)**

## Features

- **Evidence-based breathing protocols** — Box Breathing, Coherence (5.5 bpm), 4-7-8, Physiological Sigh
- **Science-backed routines** — Cyclic Sighing, Focus Reboot, Resonance Protocol, Deep Calm, Wind Down
- **Focus: Breathwork + Pomodoro** — 5 min box breathing → 25 min deep work → 1 min cyclic sighing
- **6 pixel-art animations** — Golden retriever on meadow hills, city skyline with window-lighting, mountain goat elevator, night train, soccer side-scroller
- **Playlist builder** — Chain protocols into custom sequences
- **macOS menu bar timer** — Minimize to tray, countdown in the top bar (Electron app)
- **Standalone Seluyanov TUT timer** — For slow-strength training sets

## Stack

Single HTML file. Vanilla JS. No dependencies. Electron wrapper for desktop.

## Run locally

Open `index.html` in a browser. That's it.

For the Electron desktop app with menu bar timer:
```
cd desktop && npm install && npm start
```
