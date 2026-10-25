# Aircash in Hungary: market dashboard

A single-page market and business-development dashboard for Aircash's position in Hungary. It is an independent analysis built from public sources and information provided by Aircash. Report date: 20 Oct 2026.

**Status:** internal working version, shared by link and marked `noindex` so search engines skip it.

## What it covers

Five pages, switchable by tab, keyboard arrows or a `#page` link:

| Page | Focus |
|---|---|
| Network | Withdrawal-enabled points by partner (Exclusive Change, OMV), coverage, Budapest share, filterable point list |
| Potential | How today's network compares with potential partner networks such as tobacco shops |
| Market | Electronic versus cash payment share, the central bank's 2030 target range, cash withdrawal and card purchase trends |
| Fees and rivals | Aircash fees by use case, comparison with other payment options, break-even amounts for partner withdrawal versus ATM |
| Plan | Proposed initiatives |

Every chart carries its source line. Sources named in the report: the Aircash Hungary location finder and fee pages, MNB (central bank), KSH, NAV, SZTFH and press coverage.

## How it is built

- One self-contained `index.html` (about 68 KB). No build step, no frameworks, no chart library, no CDN links.
- Charts and tables are drawn with plain JavaScript and SVG.
- Light and dark theme (follows the system, with a manual switch), keyboard-accessible tabs, and printing renders every page.

To view it, open `index.html` in a browser.

## Data notes

Figures are as of the report date, taken from the cited sources. Network counts depend on the Aircash location finder at the time it was queried (20 Oct 2026) and will drift.
