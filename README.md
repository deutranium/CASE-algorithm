# CAPE-algorithm
Implementation of CAPE algorithm proposed in the paper ["Ensuring Fairness under Prior Probability Shifts" by Biswas et al.](https://dl.acm.org/doi/abs/10.1145/3461702.3462596), as a part of Fairness, Privacy and Ethics in AI course (Monsoon'22)

### Abstract
<sup>(from the paper)</sup>

Prior probability shift is a phenomenon where the training and test datasets differ structurally within population subgroups. This phenomenon can be observed in the yearly records of several real-world datasets, for example, recidivism records and medical expenditure surveys. If unaccounted for, such shifts can cause the predictions of a classifier to become unfair towards specific population subgroups. While the fairness notion called Proportional Equality (PE) accounts for such shifts, a procedure to ensure PE-fairness was unknown. In this work, we design an algorithm, called CAPE, that ensures fair classification under such shifts. We introduce a metric, called prevalence difference, which CAPE attempts to minimize in order to achieve fairness under prior probability shifts. We theoretically establish that this metric exhibits several properties that are desirable for a fair classifier. We evaluate the efficacy of CAPE via a thorough empirical evaluation on synthetic datasets. We also compare the performance of CAPE with several state-of-the-art fair classifiers on real-world datasets like COMPAS (criminal risk assessment) and MEPS (medical expenditure panel survey). The results indicate that CAPE ensures a high degree of PE-fairness in its predictions, while performing well on other important metrics.
