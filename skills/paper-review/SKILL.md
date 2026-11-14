---
name: paper-review
description: Audit a completed empirical manuscript for submission to a specified journal, section by section, and propose evidence-based minor revisions. Use for consistency, citations, language, tables, figures, references, disclosures, and journal fit. Do not restructure or rewrite the paper without explicit approval.
---

# Paper Review

Treat the manuscript as a completed, key-paper-aligned draft. Review from the target journal's reviewer perspective and make the smallest change that materially reduces rejection risk.

Apply the repository's [working principles](../../PRINCIPLES.md) throughout.

## Protocol

1. Inspect current journal instructions and representative published articles. Separate findings that any journal would raise (consistency, numbers, claims) from those tied to this journal's format (length, highlights, abstract limit); the second kind is proposed as a submission-time adjustment and never as a cut to approved content ([principle 20](../../PRINCIPLES.md)).
2. Review one section at a time, normally beginning with the Abstract.
3. Report each issue with location, exact problem, evidence, priority, and proposed replacement. Do not edit until the user approves.
4. Preserve structure, paragraph count, analytical design, and supported claims. Review is minor-revision-scale correction, not a new manuscript.
5. Record approved changes in a revision ledger and apply them consistently to every affected file. Recheck earlier sections if later changes alter terminology, numbers, claims, or citations. After a change that flips a sign or a direction, re-read every sentence that compares the manuscript with another study ("reversed", "opposite", "the same sign", "unlike"): fixing the parenthesis and leaving the comparison was the first finding of the next pass.
6. Verify against the code and the result files, not only against the text. Sign conventions (bias, error, imbalance), mechanism sentences ("X is costly because …") and institutional rules are checked against the model code, the result components and the reading record of the source paper. The expansion of a named model, dataset or scheme (NAM, EPSIS, RPS) is checked against the source paper before it is written out; a generic expansion of a proper name is wrong. A review that compares prose with prose can find a contradiction and still propose the wrong fix: in one review the definition was right and every direction label and mechanism sentence was reversed; the code decided which.
7. A number check covers derived numbers as well as table cells: row sums, ratios, percentages, interpolated values and "per unit" conversions that the text builds from the tables, each with the formula used. A literature number that the manuscript converts to another unit (per percentage point, per MWh, per year) carries its formula in the text or the ledger; a converted value without one cannot be reproduced and is the first thing a referee recomputes.
8. Findings from a delegated reviewer (an agent or a colleague) are hypotheses. Re-verify every submission-critical finding and its proposed replacement before it enters the report, and record in the ledger which proposals were rejected and why.
9. When the journal's own author guide cannot be reached, state that, use two independent summaries plus the format of two archived articles from the journal, and list the items the author must confirm on the official page before submission.
10. Close the review stage with the author's own read-through ([principle 22](../../PRINCIPLES.md)). Once the submission package is built, hand the author a reading guide in the author's language (per section: the claim in plain words, the key numbers, the judgement points, what changed since the paragraph approvals, a reading order with a time estimate) and, when the author asks, a faithful translation of the whole manuscript with tables and figures placed where they are first discussed. The author's corrections are applied to the source files and the package is rebuilt; the stage is not finished until the author has said the read-through is done.
11. A missing primary source does not stall the stage ([principle 21](../../PRINCIPLES.md)). After two attempts, a sentence that does not change a result is supported by a transparent secondary source or removed, the ledger records the substitution, and the author is told the outcome rather than asked.
12. Before the package is called ready, and after any large revision, run a mock refereeing with independent readers ([principle 25](../../PRINCIPLES.md)). Give each reader one lens (citations against the archived sources; data and institutions; model against code; novelty and positioning as a referee of the target journal; numbers recomputed from the result files; presentation) and the files, not your own conclusions. Have a separate verifier re-check every finding against the files, then re-verify each yourself before editing (item 8). Record the disposition of every finding (applied, modified, rejected, with the reason) next to the ledger. After the revision, send the revised text to fresh checkers who recompute its numbers from the result files, and read their lists of what they verified as well as what they found.
13. Report the review with its evidence. For each group of checks say who checked what against which file, what was changed and why, what was checked and found sound, and what could not be checked (for example a source with no archived full text). A one-line "no problems found" is not a report.


## Priorities

1. Submission-critical: inconsistencies in samples, numbers, results, tables/figures, objectives, variables, models, abbreviations, citations/references, authorship, declarations, anonymity, or journal format; unsupported novelty or causality.
2. Completeness: gap clarity, paragraph connections, reproducibility, results/discussion separation, interpretations, implications, limitations, and conventional language.
3. Copyediting: grammar, articles, prepositions, tense, terminology, decimals, capitalization, hyphenation, captions, fonts, and spacing.

Working notes, assembly headers, "(File: …)" caption notes and verify flags stay in the markdown source until the submission file is produced, and the submission-and-visuals checklist strips them then.

Do not claim to detect a speculative AI watermark. Inspect actual metadata, comments, tracked changes, hidden text, working notes, placeholders, document properties, and required AI disclosure.

## References to read when needed

- Section checks: [references/section-checklists.md](references/section-checklists.md)
- Citation verification: [references/citations-and-evidence.md](references/citations-and-evidence.md)
- Visuals and submission package: [references/submission-and-visuals.md](references/submission-and-visuals.md)
