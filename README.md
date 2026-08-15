# Stopwatch Web Application

A single-file, browser-based stopwatch with a clock-style analog face, digital readout, and lap tracking. No frameworks, no build step — just open the HTML file.

## Features

- **Start / Pause / Reset** — full control over timing with instant visual feedback (status badge shows `READY`, `RUNNING`, or `PAUSED`)
- **Analog clock face** — 60 tick marks (5 highlighted major ticks), minute-style numbers (5, 10, 15 ... 60), and a sweeping second hand synced to the elapsed time
- **Digital readout** — `MM:SS` with centiseconds, updated every animation frame
- **Lap tracking** — records split time (time since the last lap) and total elapsed time for each lap, newest lap shown first
- **Keyboard shortcuts**
  | Key     | Action        |
  |---------|---------------|
  | `Space` | Start / Pause |
  | `L`     | Record lap    |
  | `R`     | Reset         |
- **Responsive layout** — clock and controls resize for mobile screens (≤600px)

## Files

```
Stopwatch web application.html   # everything — markup, styles, and logic in one file
```

## Usage

1. Open `Stopwatch web application.html` in any modern browser (Chrome, Firefox, Edge, Safari).
2. Click **Start** (or press `Space`) to begin timing.
3. Click **Lap** (or press `L`) while running to record a split — laps appear in the table below the clock.
4. Click **Start** again to pause, or **Reset** (or press `R`) to clear the time and lap history.

No installation, dependencies, or server required.

♥ by Devaki
