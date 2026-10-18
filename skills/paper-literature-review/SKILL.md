---
name: paper-literature-review
description: Collect, archive and read about one hundred full-text SCI/SCIE/SSCI journal papers on a confirmed topic, record each in structured notes, and synthesise the streams into a gap statement, anchor-paper candidates and design revisions. Use after the topic is confirmed and before the research design is frozen or any section is drafted. Do not use for abstract-level prior-work tables or for writing the literature section itself.
---

# Paper Literature Review

The review exists to make the study's difference visible and to test the design against what has been done. It is based only on papers whose full text was obtained, archived and read.

Apply the repository's [working principles](../../PRINCIPLES.md) throughout.

## Workflow

1. Define the streams of literature the topic sits between (typically three to five) and the questions the review must answer: where the gap is, which methods are standard, which papers are closest, which journal and anchor paper fit.
2. Collect candidates in parallel, one agent per stream, from Crossref, publisher sites and reference lists of key papers. Keep a bibliography file with DOI, journal, indexing status, stream, priority and status. Only SCI, SCIE or SSCI journal articles count toward the review; preprints and reports may be read for context but are marked as such and not cited as evidence.
3. Obtain full texts in this order: open-access or publisher HTML reachable from the environment, author manuscripts and arXiv versions, then the user's institutional access (the user's own browser session or a download list). Never bypass robot checks or change browser settings; ask the user once, with the list.
4. Archive every PDF under the project's literature folder with a DOI-to-file index, and record the version read (published, accepted manuscript, arXiv, working paper). A number quoted from a non-published version carries a verify flag until the published version is checked.
5. Apply the stop rule: a paper that cannot be obtained after reasonable attempts is skipped. Collect only the must-have ones (DOI, title, reason) and hand them to the user in one list; do not ask paper by paper.
6. Read each obtained paper in full and write a structured record: question, method, data, matching or settlement rule where relevant, key findings with numbers, limitations and stated future work, relation to this study, and uncertainty about the record itself.
7. Synthesise: an evidence table by stream; a count of papers that name this study's gap as future work; the closest papers and any competing preprints; anchor-paper candidates from the target journal; and a numbered list of design revisions, each tied to the papers that motivate it.
8. Deliver the review document with the plain-language framing paragraph first, then the recommendations. The user decides which revisions to adopt; record the decision, the archive status and the verify list in memory.

## References to read when needed

- Collection, archiving and the stop rule: [references/collection-and-archiving.md](references/collection-and-archiving.md)
- Reading records and synthesis: [references/reading-records-and-synthesis.md](references/reading-records-and-synthesis.md)

## Boundary

The review ends with the gap statement, anchor candidates and design revisions. Changing the model, rerunning experiments and drafting the literature section belong to paper-data-analysis and paper-writing. Papers not obtained are never cited; papers not read are never summarised as if read.
