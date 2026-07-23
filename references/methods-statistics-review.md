# Methods and Statistical Review

## Cross-Document Consistency Matrix

For every study or analysis, compare:

- recruited N, excluded N, final N, cell Ns, and degrees of freedom;
- conditions, coding, reference groups, and manipulation labels;
- focal product, context, platform, procedure, and warning or recovery materials;
- construct names, item counts, anchors, reliability, and validity statistics;
- outcome definitions and coding;
- model number, estimator, covariates, bootstrap samples, and reported paths;
- text, tables, figures, appendices, and supplementary files.

## Reporting Rules

- Report exact p-values when available, using `p < .001` rather than `p = .000`.
- Use consistent decimal precision within a result family.
- Distinguish SD from SE and confidence intervals from prediction intervals.
- Include degrees of freedom for t, F, and chi-square tests where required.
- Identify the scale of logistic coefficients and indirect effects.
- State coding and reference categories for categorical predictors and interactions.
- Use “not statistically significant” rather than “no effect.”
- Avoid describing a marginal p-value as support unless the hypothesis and threshold were prespecified.
- Do not infer full mediation from a nonsignificant direct effect.
- Do not infer causal mediation solely from PROCESS output when design or temporal ordering is insufficient.

## Causal-Language Test

Random assignment may support causal claims about manipulated variables under the implemented manipulation. It does not automatically support causal claims about measured intermediate variables, unmanipulated variables, untested mechanisms, outcomes beyond the observed measure, or populations and settings beyond the sample.

Use comments when causal interpretation depends on assumptions not reported.

## Covariates

Flag data-driven covariate selection, post-treatment controls, controls affected by the manipulation, inconsistent covariate use across analyses, and robustness claims that depend on one specification.

## Measurement and Manipulation

Flag:

- duplicated item sets under different construct labels;
- reverse-coded items without clear scoring treatment;
- one-item versus multi-item mismatch;
- manipulation checks that measure a neighboring construct;
- confounded manipulations changing tone, information amount, visual design, and social cues simultaneously;
- outcome proxies described more strongly than their operationalization warrants.
