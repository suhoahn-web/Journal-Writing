# Inventory and cleaning conventions

## Notes file

One shared notes file for all supplied files. Each entry: name, path, size, format, encoding (Korean portals often use CP949), rows and columns, sample rows in a fenced block marked as copied data, and surprises. Correct an entry when it is wrong rather than adding a second one.

## Checks that caught real problems

- Two portal datasets where one is a subset of the other: use one and cross-check the other (they should agree to a fraction of a percent).
- A new category introduced mid-series (for example dispatchable renewables split out from a region's solar and wind): decide whether it affects the analysis and say so in the paper.
- One missing day in a price series: fill with a documented rule, do not interpolate silently.
- Zero and negative prices after a market reform: real, not errors; count them and note the hours.
- Date typos in a raw file (a year written as 2202): fix in code with a comment, never in the raw file.
- A price file whose high and low columns are wrong in one year: use only the column that is consistent.
- Traded energy of plants in the market is smaller than national generation: state the scope in the paper.

## Scripts

- One script per processed table, re-runnable from the raw files, with the cleaning rules as code and comments.
- Scripts print summaries, not whole tables.
- Units in column names; conversion factors as named constants.
