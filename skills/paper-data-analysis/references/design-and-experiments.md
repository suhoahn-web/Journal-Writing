# Design document and experiment ladder

## Design document sections

1. Question, in one sentence, and the hypotheses as testable statements (H1 shape of the cost curve, H2 complement or substitute, H3 which channel carries the value).
2. Setting: the decision-maker, what it must do, the sources it can use, and what is assumed because it is private (for example a flat load).
3. Model: stages, variables, objective and constraints, written out; what is sunk between stages; how real-time settlement works.
4. Experimental variable: how it is controlled. A ladder from perfect foresight through controlled synthetic levels to naive baselines lets cost be traced as a continuous function of accuracy, and the baselines place real, implementable alternatives on the same curve. Control more than one property of the variable when the literature says shape matters (size, bias, persistence).
5. Decision rules: when the value of an input depends on how it is used, solve every rung under at least two rules (for example point and quantile planning) rather than one.
6. Base case and scenario grid, one dimension at a time, with the source of every parameter.
7. Metrics and units; report in the unit the field uses and in one convertible unit (per kWh of load, per MWh of generation, percent of cost).
8. Target journals and the paper type the results will support.
9. Decisions for the user, each with the recommended option.

## Rounds

- Round 1 after design confirmation; round 2 after the literature review; later rounds only for user-requested extensions.
- A new round reproduces the previous base case before anything else is reported.
- Never delete an earlier round; mark it superseded.
- An experiment that needs the user's own model or files is a separate rung, scheduled after the draft if the user prefers, with a note in the results and limitations.
