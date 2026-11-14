---
name: paper-data-collection
description: Turn a confirmed data plan into inventoried, cleaned and documented datasets ready for analysis, including download instructions for sources the working environment cannot reach, file inventories, cleaning decisions and an exploratory check of the design's premises. Use after the topic is confirmed, in parallel with or before the literature review. Do not use for modelling or results.
---

# Paper Data Collection

Data that cannot be downloaded is not data. Every file is inventoried, every cleaning decision is written down, and the raw files are never altered.

Apply the repository's [working principles](../../PRINCIPLES.md) throughout.

## Workflow

1. From the data plan, list every dataset: provider, URL or menu path, period, granularity, format, encoding, size and access mode. Check which sources the working environment can reach; many public portals cannot be reached from a cloud environment and the user must download them.
2. For files the user downloads, give one batched set of instructions: exact page, filters (region, year), export button, file naming convention, and where to put the files. Mention size limits (chat attachments have a cap; the project file space does not).
3. On arrival, inventory each file in the shared notes file: name, path, size, format and encoding, row and column counts, a few sample rows marked as copied data, and anything surprising. Later stages read the notes instead of re-reading the files.
4. Check the data against the design before cleaning: overlapping or subset datasets, categories introduced mid-series, missing days, date typos, zero or negative values that are real market features rather than errors, and units that differ from what the paper will claim (for example traded energy versus total generation). Test each series against what is physically possible before trusting its label ([principle 26](../../PRINCIPLES.md)): profile it by hour of day, season and year and look for values the named quantity cannot take (solar output after sunset, a capacity factor above one, a negative share). Explain any such value from the provider's definition, or remove it with a stated rule, keep the unfiltered series as a sensitivity case, and write the finding into the shared notes so later stages do not rediscover it.
5. Build processed tables with scripts kept in the project's code folder, from raw files kept unchanged. Document each fix in the script and in the notes (what, why, how many rows). Record scope caveats that must appear in the paper.
6. Run an exploratory analysis that tests the premises of the design (for example whether the price profile has the shape the design assumes). Report any finding that changes the design before modelling starts.
7. Deliver a data note: table of sources, coverage, cleaning decisions and caveats. It becomes the data table and the Data subsection of the manuscript.

## References to read when needed

- Inventory and cleaning conventions: [references/inventory-and-cleaning.md](references/inventory-and-cleaning.md)

## Boundary

Collection ends when the processed tables, the notes file and the data note exist. Modelling and results belong to paper-data-analysis.
