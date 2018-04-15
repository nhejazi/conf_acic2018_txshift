# ACIC 2018 Poster Submission

## Robust Nonparametric Inference for Stochastic Interventions Under Multi-Stage Sampling

## Abstract

Perhaps too often, work in statistical causal inference focuses on the effect of
deterministic interventions, under which, for each unit, the magnitude of the
treatment is set to a fixed value. Under violations of the assumption of
positivity, the evaluation of such interventions faces a host of problems, among
them non-identification and inefficiency. Prior work has proposed a flexible
solution: stochastic shift interventions, under which, in the simplest case, for
each unit, the treatment is set to be an additive shift of the observed value of
the treatment. What's more, in real-life applications, data analyses are often
further complicated by pragmatic sub-sampling schemes, the effects of which
cannot safely be ignored when drawing statistical inferences. Building on much
previous work, we present a novel approach for such settings --- an augmented
targeted maximum likelihood estimator for interventions that shift observed
values of the treatment, with consistency and efficiency guarantees even in the
presence of multi-stage sampling, and we show that this estimator enjoys these
essential theoretical properties by way of a form of multiple robustness
inherited from its constituent parts. After providing a general characterization
of shift interventions, we illustrate the utility of employing our proposed
nonparametric estimator via simulation studies, showing that it attains fast
convergence rates even when incorporating machine learning estimators; moreover,
we introduce a recent software implementation (the "txshift" R package) and
apply this methodology in an investigation of the effects of immune response
biomarkers on HIV vaccine efficacy, contrasting our proposed approach with
several classical techniques. Specifically, we show that our proposed method
obtains efficient inference on a parameter defined as the overall risk of HIV
infection in the vaccine arm of an efficacy trial, under various posited shifts
of the distribution of an immune response biomarker away from its observed
distribution in the efficacy trial. Our proposed technique provides a highly
interpretable variable importance measure -- defined through the formalism of
statistical causal inference -- for ranking multiple immune responses based on
their utility as immunogenicity study endpoints in future HIV-1 vaccine trials
that evaluate putatively improved versions of the vaccine. Time permitting, we
discuss extensions of this approach that consider recent and novel ideas in
stochastic interventions, such as the induction of shifts in the treatment in
terms of the propensity score rather than on the observed treatment scale.

---

## License

&copy; 2018 [Nima Hejazi](https://nimahejazi.org) and [David
Benkeser](https://www.benkeserstatistics.com/)

