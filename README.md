# Costco call sheet

A single-page phone tool for phoning Bay Area Costco warehouses and recording 1 oz gold bar
stock, one store at a time.

- 45 warehouses within 100 miles, ordered by driving distance from Walnut Creek, CA
- One shared shelf price at the top (Costco charges the same at every warehouse)
- Per-store Pamp and Generic bar counts with a running total
- Status at a glance: not called / has bars / no stock / **day old** / older, each timestamped
- Sorts by today-first, distance, name, or inventory — day-old entries sink to the bottom
- Saves on the device first, then syncs; entries queue and retry themselves if the signal drops

Open `index.html` in any browser. No build step, no dependencies, no login.

Part of a private personal project. Published here only so the page has a URL to open on a phone.
