# Referee checklist (template)

Use with protocol item 14 of the paper-review skill and [principle 27](../../../PRINCIPLES.md). Rewrite it for each target journal before the readers start: take the items from (1) the publisher's guidance to its reviewers, (2) the journal's current guide for authors (limits on abstract, highlights and length; review model; required declarations), and (3) the points on which referees of the field usually press (assumptions, validation, uncertainty, generality, overclaiming). Add items for anything specific to the paper (a trained model, an assumed market, a data defect already found).

An item marked ★ is one on which a negative judgement alone could lead to rejection; give each of these to two readers.

How to use it:

- Divide the groups among independent readers so that every item has an owner (for example: A and the cover documents; C; D; E; B; G and H; one senior referee and one technical referee for the ★ items across groups). Readers receive the files and this checklist, not earlier reports.
- Each reader returns one verdict per item: PASS (with the place checked and why it holds), MINOR, MAJOR or NOT ASSESSABLE; every MINOR or MAJOR names the place, quotes the words and proposes a fix.
- Sceptic verifiers then try to refute each finding against the files (does the quote exist, is the number right, is it a defect or taste, is the proposed fix true and within the limits) and note where two readers conflict. Facts about the outside world are checked on primary sources by a separate checker.
- The report to the author is a table by item: who checked it, how and against what, the verdict, what was changed, and where the item had been verified in earlier rounds.

## A. Editor's first screen
- A1 ★ Fit to the journal: the paper is about a question of general interest to the journal's readers, not a local case study; it says what carries over beyond the country studied.
- A2 ★ Novelty: the gap is stated precisely; the claim of being first is worded defensibly and is not contradicted by work the paper itself cites or by obvious recent work.
- A3 ★ Importance: the result matters to the field ; if the measured effect is small, the paper explains why that is a finding and for whom it changes a decision.
- A4 The contributions listed in the Introduction are each delivered by an identifiable part of the Results, and nothing in the list goes beyond what is shown.
- A5 Cover letter: says what is new and why it fits the journal, is consistent with the manuscript in every number and claim, and contains the usual statements (not under consideration elsewhere).
- A6 Length and economy: the length is proportionate to the content; no section, table or figure could be removed without loss; no repetition between sections.
- A7 Title: accurate, complete, discoverable, no unexplained abbreviation.
- A8 Abstract: self-contained; states aim, method, main results with numbers, and the main limitation; every number agrees with the body; within the journal's word limit.
- A9 Highlights: within the journal's count and character limits, each a result (not a description of the paper), each consistent with the body.
- A10 Keywords: specific, not duplicating the title only, suitable for indexing.
- A11 Graphical abstract: readable at small size and consistent with the results.

## B. Introduction, literature and references
- B1 The rationale is clear and the objective or research question is stated at the end of the Introduction.
- B2 ★ The literature is current (the last two to three years included) and covers the strands the paper builds on; no essential work is missing.
- B3 Each cited work supports the sentence it is attached to, as far as can be judged from the text (specific figures attributed to sources are plausible and unambiguous).
- B4 Prior work is represented fairly; the difference from the closest studies is explicit.
- B5 Quality of sources: peer-reviewed where a claim needs it; non-journal sources (notices, data archives, press) used only for facts and identified as such.
- B6 Reference list: every entry complete (authors, title, journal, year, volume, pages or article number, DOI or URL with access date), consistent style, every entry cited and every citation listed, non-English sources marked.

## C. Methods: the model
- C1 ★ The model is specified completely enough to be re-implemented from the text: sets, decision variables, parameters, objective, constraints, timing of information, units; every symbol defined at first use.
- C2 ★ The equations are correct and mutually consistent (objective, constraints, accounting identities, every closed-form result).
- C3 ★ Every assumption that drives a result is stated, justified, and either varied in a sensitivity analysis or named as a limitation.
- C4 The text describes what the code does (is anything in the text ambiguous enough that two implementers would code it differently?).
- C5 Parameter values have a stated source or rationale.
- C6 Software, solver, random seeds and other details needed for reproduction are given.

## D. Methods: forecasts and data
- D1 ★ Any estimated or trained input (a forecast, a fitted model) uses only information available when the decision is taken; training, model selection and evaluation periods are separated and described honestly.
- D2 The accuracy metric is defined exactly (what is normalised by what, over which hours) and its comparability with the literature is addressed.
- D3 Synthetic or stylised inputs are defined exactly, and the paper justifies treating them as references for real ones.
- D4 ★ Data: source, coverage, processing and known defects are described; the series measures what the model needs; representativeness is discussed.
- D5 Comparisons between alternatives are fair, or the differences in the information they use are disclosed.
- D6 The data availability statement is adequate for the journal and for reproduction.

## E. Results
- E1 ★ Numbers in the text agree with the tables and figures.
- E2 ★ Each claim is supported by the evidence shown; verbs are no stronger than the evidence ("shows", "determines", "always").
- E3 ★ Uncertainty: the paper reports enough about sampling variability (random realisations, days, years) to judge whether the differences it interprets are real.
- E4 The sensitivity analyses cover the assumptions on which the conclusions depend, and the text says where a conclusion reverses.
- E5 Tables: informative titles, units, notes, consistent rounding, no table that merely repeats a figure.
- E6 Figures: legible at printed size (fonts, line weights, legends), axes labelled with units, distinguishable without colour where possible, captions self-contained, consistent with the tables.
- E7 The same quantity has the same value wherever it appears (abstract, highlights, cover letter, body, tables, conclusion, supplement).
- E8 The mechanisms offered as explanations are correct (each derived by hand and tested numerically).

## F. Discussion and conclusions
- F1 The comparison with earlier studies is fair: like units, stated caveats.
- F2 ★ The implications for policy and practice follow from the results and stay within what the model can say.
- F3 ★ The limitations are complete and candid; none that a referee would raise first is missing or hidden.
- F4 The conclusions follow from the results, introduce nothing new, and repeat numbers correctly.
- F5 The paper says what generalises beyond the case studied and what does not.
- F6 Statements about institutions (rules, notices, incentive schemes, markets) are precise and sourced.

## G. Presentation
- G1 Structure: sections do what their headings say; the argument can be followed without the supplement.
- G2 Language: clear, grammatical, one variety of English, same term for the same thing throughout.
- G3 Abbreviations are defined at first use in the abstract and again in the body; none is used once only.
- G4 Notation: no symbol with two meanings; units and number formats consistent.
- G5 Cross-references to sections, tables, figures, equations and the supplement point to the right place.
- G6 The Word files render correctly: equations, subscripts, tables within the page, line and page numbers.
- G7 The supplement is cited from the main text, is self-contained and agrees with it.

## H. Journal rules, ethics and integrity
- H1 All parts the journal requires are present (title page information, abstract, keywords, highlights, declarations, figure files, captions).
- H2 Declarations: authorship contributions, competing interests, funding, data availability, use of generative AI; wording in the form the publisher asks for.
- H3 Originality: nothing suggests duplicate publication or overlap with the author's earlier work; text is not recycled.
- H4 Ethics and permissions: no human or animal data; third-party data are used within their licences; nothing is reproduced from other publications without permission.
- H5 Integrity: results are not implausibly clean; figures come from data; anything that looks adjusted is explained.
- H6 Reference style is consistent; sources not in English carry an English title and a language tag.
- H7 The file set is complete and clean: no tracked changes, comments, leftover placeholders, internal notes or characters from another script.
- H8 Reporting of sex and gender: applicability considered (expected: not applicable).
