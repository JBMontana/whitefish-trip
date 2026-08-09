# Whitefish Trip Itinerary

A single-page itinerary for a family trip to Whitefish, Montana — August 10–17, 2026.

Published with GitHub Pages. No build step, no dependencies — everything lives in `index.html`.

## Features

- Day-by-day timeline for all 8 days, with times, notes, and who's going.
- Per-person filter — tap a name to highlight just that person's plans and dim the rest.
- `Booked` / `Optional` status badges.
- Babysitting hand-offs shown on the events that have them.
- Add and remove events from the page itself. These are stored in the browser's `localStorage`, so **they are per-device and not shared** between viewers.
- Countdown that switches to "Day N of 8" once the trip begins.
- Light and dark themes, mobile-first.

## Note on contents

This is a public copy with personal details trimmed: people are shown by initials or short names, and venue names are abbreviated. The full version is kept privately.

## Running locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000
