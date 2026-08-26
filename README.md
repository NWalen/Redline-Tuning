# Redline Tuning

A free, no-install tuning calculator for Forza Motorsport and Forza Horizon. Pick a goal, punch in your car's current numbers from the in-game Tune menu, and get calculated starting-point values for every tuning page.

**Live site:** https://nwalen.github.io/Redline-Tuning/

## What it does

Choose one of five presets — **All-Around**, **Top Speed**, **Drag**, **Drift**, or **Wet** — and work through tabs that mirror the game's tune screens:

- **Gearing** — final drive and individual gear ratios, scaled to your goal
- **Alignment** — camber, toe, and caster targets based on preset and drivetrain
- **Antiroll / Springs / Damping** — front-rear balance shifted to fight understeer (or encourage sliding, on the Drift preset)
- **Brake** — balance and pressure
- **Differential** — accel/decel lock and center balance, showing only the diffs your drivetrain actually has
- **Aero** — downforce front and rear
- **Tires** — pressure targets plus a recommended compound

Suggestions adapt to your drivetrain (FWD / RWD / AWD), so the same preset produces different numbers for a nose-heavy AWD sedan than for a mid-engine RWD car.

## Features

- **Garage** — save your cars in the browser and switch between them from the sidebar. Everything stays on your device; nothing is uploaded anywhere.
- **Copy tune** — one click builds a clean text summary of the full setup, ready to paste into Discord or a group chat.
- **Light and dark theme** — follows your system setting automatically.
- Works on desktop and mobile.

## How to use it

1. Open the live site and enter your car's name, drivetrain, and class.
2. Pick the preset that matches what you want the car to do.
3. On each tab, type the values currently shown in your in-game Tune menu into the left box — the suggested value appears on the right.
4. Set the in-game sliders to the suggested values, then hit **Save to garage** so the car's there next time.

## A note on the numbers

Forza doesn't expose a tuning API, so these are calculated starting points — derived from your car's own current setup using directions and proportions that generally hold for each goal — not dyno-verified values for your exact car. Confirm a slider can actually reach a suggested value before applying it, and fine-tune by feel (and tire temps) once you're on track.

## Running it yourself

The whole app is a single self-contained `index.html` — no build step, no dependencies, no backend. Fork this repo and enable GitHub Pages, or just open the file in a browser.
