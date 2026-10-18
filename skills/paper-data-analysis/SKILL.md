---
name: paper-data-analysis
description: Write the research design, implement the model, run the experiments in rounds, and deliver results documents with hypothesis verdicts, robustness and the decisions the user must make before writing. Use after the topic is confirmed and the data are collected; the design is revised after the literature review and the experiments rerun. Do not use for topic selection, literature collection or manuscript drafting.
---

# Paper Data Analysis

The experiment is designed on paper first, confirmed by the user, then coded, validated and run in rounds. Every number that reaches a document is traceable to a results file.

## Workflow

1. Write the research design before any code: question and hypotheses; model with equations and the decision stages; the experimental variable and how it is varied (for example a ladder of controlled error levels between perfect foresight and naive baselines); base-case parameters with their sources; scenario grid; metrics and units; first and second target journal; and the decisions the user must make, each with a recommended default.
2. Ask for the decisions in one message with short options and a recommendation; accept "all as recommended". Record the confirmed design in memory.
3. Implement the model as a script with command-line options for every scenario dimension. Validate before running the grid: toy cases with known answers, the perfect-foresight case, channel components that sum to the total, and runtime recorded.
4. Run the first round: base case, the ladder, and robustness along one dimension at a time. Keep result files versioned by round. Write a results document with the plain-language framing paragraph first, the key numbers, a verdict per hypothesis (confirmed, rejected, modified), limitations and the next step.
5. After the literature review, revisit the design. Implement the adopted revisions as a second round that replaces the first, and show that the base case reproduces the first round exactly; a difference means a model error, not a new finding.
6. Extend robustness: years and regions, alternative portfolios, parameter sweeps, sensitivity to the decision rule, and comparisons with external benchmarks (break-even values against published incentives or prices).
7. Deliver the final results document with the decisions the user must make before writing: which result is the main claim, which go to one paragraph or an appendix, and which experiment is left for later. Then hand over to paper-writing.

## References to read when needed

- Design document and experiment ladder: [references/design-and-experiments.md](references/design-and-experiments.md)
- Results documents, tables and figures: [references/results-reporting.md](references/results-reporting.md)

## Boundary

Analysis ends when the results, tables and figures are generated from the result files by code and the user has chosen the main claims. Drafting follows the paper-writing skill. Do not rush from design to draft: first-round results and a draft written before the literature review were set aside and redone.
