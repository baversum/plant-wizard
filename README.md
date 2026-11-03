# 🪴 Plant Wizard

A small, dependency-free web app for plant care: what soil mix each plant group wants, and whether this watering should come with fertilizer — or plain water only.

No account, no server, no tracking. Everything lives in your browser's localStorage, so each device keeps its own counters.

**Try it live: https://baversum.github.io/plant-wizard/**

The app speaks English and French — tap the little flag in the header to switch languages.

## Why watering by observation

Watering calendars don't work. Pots dry at their own pace depending on the season, the weather, and the pot size — and a fixed schedule is a reliable way to drown a plant in October or underwater it in July. Plant Wizard takes the opposite approach: you water when the soil tells you to (dry at 2 cm depth, or a light pot). What the app adds is the answer to the question you're asking yourself at that exact moment: *should this watering carry fertilizer, or would that be pointless — or even harmful?*

Each plant simply remembers how many plain waterings it has had since its last feed, and a winter break is built in (November–February): feeding a resting plant does nothing and the salts just pile up in the soil.

## What's inside

- **My plants** — one card per plant saying "fertilizer with this watering" or "plain water". Add your own plants or remove them freely.
- **Mixes** — substrate recipes per plant group (potting soil, pine bark, pumice, coco coir…), with fertilizer frequency and a few hard-won care notes. Built around pumice as the single mineral: one bag covers everything, hammer-crushed for small pots.
- **Stock** — the short shopping list (substrates, fertilizers) and a substitution table with the dosages that actually change (perlite, clay pebbles, filter sand…).

## On your phone

Open the site, then use your browser's "Add to Home Screen" — it runs full screen, just like a native app.

## Tech

One `index.html`, plain HTML/CSS/JavaScript, zero dependencies and zero build steps. Every push to `main` redeploys the site automatically to GitHub Pages via `.github/workflows/deploy.yml`.
