# ⚠️ EPOCHALYPSE — Y2K38 Countdown

> Countdown to the Unix Year 2038 Problem — when signed 32-bit integers overflow and time resets to 1901.

**Live demo:** `https://BinaryFIX.github.io/epochalypse`

---

## What is Y2K38?

On **January 19, 2038 at 03:14:07 UTC**, Unix systems that store time as a signed 32-bit integer will hit their maximum value:

```
2,147,483,647
```

One second later, the counter overflows and rolls back to **−2,147,483,648** — which corresponds to **December 13, 1901**.

This event is known as the **Y2K38 problem**, the **Unix Millennium Bug**, or colloquially as the **Epochalypse**.

---

## Features

- ⏱ Real-time countdown — days, hours, minutes, seconds
- 📊 Progress bar showing elapsed time since Unix Epoch (1970-01-01)
- 🖥 CRT scanline + vignette effect
- 🌧 Matrix rain background
- 📡 Scrolling ticker with system warnings
- 🕐 Live UTC clock

---

## Deploy on GitHub Pages

1. Fork or clone this repository
2. Go to **Settings → Pages**
3. Set Source to `main` branch → `/ (root)`
4. Click **Save**
5. Your site will be live at `https://BinaryFIX.github.io/epochalypse`

---

## Tech Stack

Pure HTML + CSS + JavaScript — no dependencies, no frameworks, no build step.

---

## License

MIT
