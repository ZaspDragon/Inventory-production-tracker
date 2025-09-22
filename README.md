# Pallet Tracker — 45 in 8

A lightweight offline web app to track pallet moves and productivity against a goal of **45 pallets in 8 hours** (5.625/hr).

## Features
- Add entries with *Item #*, *Qty*, *From Bin*, *To Bin*, and *Notes*
- Bins auto-format to `LETTER-##-#` (A–L only) and are validated
- Start/End Shift and live stats: elapsed time, pallets moved, rate/hr, projected total vs goal
- Stores data locally in your browser (no server required)
- Export the day’s log to CSV
- Works on phone, tablet, or desktop

## How to use
1. Open `index.html` in any modern browser (you can double-click it).
2. Click **Start / Restart Shift** when you begin.
3. Enter moves as you work. Use `A-10-4` style bins (A–L allowed).
4. Export CSV at the end of the shift if you need to send a report.

## Deploy (optional)
- **GitHub Pages**: push this folder to a repo and enable Pages.
- **Replit / Netlify / Vercel**: serve as static site; no backend needed.

## Customize
- Change the goal by editing `GOAL_TOTAL` or `GOAL_HOURS` near the top of the `<script>` in `index.html`.
- Add fields or columns by expanding the table and the entry object.

