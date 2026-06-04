# Life in Weeks

An interactive, single-file HTML poster generator inspired by [Tim Urban’s “Your Life in Weeks”](https://waitbutwhy.com/2014/05/life-weeks.html). Each dot on the grid is one week of a projected lifespan—filled dots are weeks already lived, hollow dots are weeks ahead.

## Quick start

1. Open `life-in-weeks.html` in any modern browser (Chrome, Edge, Firefox, Safari).
2. Enter your name, date of birth, and projected lifespan (60–100 years).
3. Click **Generate Poster →** to preview the A3 layout.
4. Click **Print / Save PDF** and export or print the poster.

No install, build step, or server required.

## Saving as PDF

Use the browser print dialog:

| Setting      | Value                          |
|-------------|---------------------------------|
| Destination | Save as PDF (or your printer)   |
| Paper size  | A3                              |
| Orientation | Portrait                        |
| Scale       | Actual size / 100%              |
| Margins     | None or minimum                 |

Print styles hide the setup form and toolbar so only the poster is exported. The poster is vector SVG, so PDF output stays sharp at full size.

## Files

| File               | Description                                      |
|--------------------|--------------------------------------------------|
| `life-in-weeks.html` | Complete app: UI, SVG generator, print styles |
| `README.md`        | This file                                        |

## How it works

- **Grid:** 52 columns (weeks) × N rows (years), where N is your projected lifespan.
- **Lived weeks:** Calculated from date of birth to today; capped at total weeks in the grid.
- **Layout:** SVG viewBox `297 × 420` mm (A3 portrait). Screen preview scales down; print CSS forces true A3 dimensions.

## Privacy

Everything runs locally in your browser. No data is sent to a server.

## License

Use and modify freely for personal or non-commercial projects.