# NYC Charter Schools Calendar

An interactive calendar that shows how **54 NYC charter schools** align to the **NYC DoE** calendar — and projects charter holidays for the year ahead.

**Live site:** https://anuragmishraapplications-lab.github.io/nyc-charter-schools-calendar/

## What it does

- **2025–26 tab (actual):** Click any date to see which schools are **open**, **closed**, or **starting/ending** that day. Each day shows a badge with the number of schools closed; first and last days of school are marked per school.
- **2026–27 tab (predicted):** Shows the published DoE calendar with **predicted** charter holidays, color-coded by confidence tier (assume = DoE / likely / verify per school), derived from how tightly charters tracked the DoE in 2025–26.

## How it works

It's a single static page (`index.html`) plus a baked data file (`data.js`) — no build step, no server. Calendar data was parsed from the published charter calendars on newyorkschools.us and the official NYC DoE calendars, then compared date-by-date.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The whole app (HTML + CSS + JS) |
| `data.js` | Parsed calendar dataset (schools, DoE dates, predictions) |

Built for the Charter Learning Collaborative (CLC).
