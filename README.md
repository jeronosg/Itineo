# Itineo

A clean, single-file trip planner for cruises and travel. No account required — everything lives in your browser.

## Features

- **Trip Details** — cruise line, ship, booking number, cabin, dates, ports, and notes
- **Flights** — outbound and return flights with full leg info (times, seats, confirmation numbers)
- **Itinerary** — port days, sea days, embarkation/disembarkation with arrival/departure times
- **Packing List** — categorized checklist with a progress tracker and suggested starter items
- **Extras & Activities** — hotels, transportation, dining, tours, and anything else before or after the cruise
- **Budget** — automatic cost rollup from cruise, flights, and activities against a custom target
- **Timeline View** — chronological view of your entire trip in one scroll
- **Multiple Trips** — manage several trips and switch between them
- **Share** — generate a compressed share link to send your full itinerary to a travel companion
- **Export / Import** — back up any trip as a JSON file and restore it later
- **Dark Mode** — full dark theme with one click
- **Print** — clean print layout of your trip summary

## Usage

Just open `index.html` in any modern browser — no install, no server, no build step.

All data is stored in `localStorage` and never leaves your device unless you share it.

## Sharing a Trip

1. Go to **Admin → Settings → Generate Share Link**
2. Copy the link and send it to your travel companion
3. They open the link and your full trip loads automatically as a new trip in their planner

The share link uses client-side compression — no server involved.

## Tech

Pure HTML, CSS, and vanilla JavaScript in a single file. Styled with [Tailwind CSS](https://tailwindcss.com) (CDN) and [Font Awesome](https://fontawesome.com) icons.

## License

MIT
