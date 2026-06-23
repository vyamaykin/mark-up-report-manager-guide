# Mark Up Report Guide

An interactive, plain-language training guide that helps **MERS Goodwill retail store managers** understand the Mark Up Report (Power BI) and how using it well grows their monthly bonus.

Built for a non-technical audience — no spreadsheets, no jargon. Just a friendly, tap-through tour with hands-on activities.

## What it covers

A 10-screen stepped wizard:

1. **Welcome** — the $0 → $1,000 hook
2. **How your bonus works** — Sales ÷ Goal, the payout table, and why below 100% pays nothing
3. **What "Mark Up" means** — explained with a simple price example
4. **What "Sell-Thru" means** — explained with a visual rack of items
5. **Find the sweet spot** — a live simulator: drag the mark-up slider and watch sell-thru, sales, % of goal, and the bonus dollar figure move (stay under the 15% line)
6. **Reading the store map** — a tap-the-dots activity mirroring the report's scatter plot; find the stores that crossed the 15% threshold
7. **Your store turned red** — a decision scenario
8. **Quick check** — two knowledge questions
9. **This week's game plan** — a tap-to-complete action checklist
10. **Recap** — the three things to remember

## The core idea

Your monthly bonus is driven by **Total Sales vs. your goal**, and Total Sales = average price sold × quantity sold. The Mark Up Report is the lever:

- Mark up too aggressively (past the **15% threshold** → red dots) and items stop selling → sell-thru drops → sales drop → you miss goal → **$0 bonus**.
- Mark up too little and you leave money on the table.
- The report shows the sweet spot: keep mark up under ~15% while protecting sell-through, which **maximizes sales → pushes % of goal up the bonus table → bigger monthly check.**

## Files

| File | Description |
| --- | --- |
| `Mark Up Guide.dc.html` | Source — a single self-contained Design Component (template + logic). Open directly in a browser. |
| `Mark Up Guide.html` | Bundled standalone build. Fully offline — fonts and runtime inlined. Share this with store managers. |
| `support.js` | Design Component runtime (required by the `.dc.html` source). |
| `CLAUDE.md` | Project notes — brand colors, report structure, and the 2026 bonus plan facts. |

## Running it

Just open **`Mark Up Guide.html`** in any modern browser — no install, no internet connection needed.

To work on the source, open `Mark Up Guide.dc.html` (it loads `support.js` from the same folder).

## Brand

MERS / Missouri Goodwill colors:

- Navy `#00263E` · Blue `#0065A4` · Green `#82C341` · Orange `#FD9D0D` · Red `#C1272D` · Periwinkle `#929CD0`
- Light blue tints: `#CCE8F5`, `#F0F6FB`

Headings: **Archivo** · Body: **Public Sans**

## Note on the numbers

The simulator and store map use **illustrative figures** to teach the relationship between mark up, sell-thru, and the bonus. They are not live data. To wire in real per-store numbers from the Mark Up Report, update the values in the logic section of `Mark Up Guide.dc.html`.
