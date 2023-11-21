---
layout: page
title: Imputation-Assisted Randomization Tests
description: a project with a background image
importance: 1
img: assets/img/2211700580917_.pic.jpg
category: research
related_publications: heng2023designbased
---

Design-based causal inference is one of the most widely used frameworks for testing causal null hypotheses or inferring about causal parameters from experimental or observational data. The most significant merit of design-based causal inference is that its statistical validity only comes from the study design (e.g., randomization design) and does not require assuming any outcome-generating distributions or models. Although immune to model misspecification, design-based causal inference can still suffer from other data challenges, among which missingness in outcomes is a significant one. However, compared with model-based causal inference, outcome missingness in design-based causal inference is much less studied, largely due to the challenge that design-based causal inference does not assume any outcome distributions/models and, therefore, cannot directly adopt any existing model-based approaches for missing data. To fill this gap, we systematically study the missing outcomes problem in design-based causal inference. First, we use the potential outcomes framework to clarify the minimal assumption (concerning the outcome missingness mechanism) needed for conducting finite-population-exact randomization tests for the null effect (i.e., Fisher's sharp null) and that needed for constructing finite-population-exact confidence sets with missing outcomes. Second, we propose a general framework called ``imputation and re-imputation" for conducting finite-population-exact randomization tests in design-based causal studies with missing outcomes. Our framework can incorporate any existing outcome imputation algorithms and meanwhile guarantee finite-population-exact type-I error rate control. Third, we extend our framework to conduct covariate adjustment in an exact randomization test with missing outcomes and to construct finite-population-exact confidence sets with missing outcomes.


[Documentation](https://i-art.readthedocs.io/en/latest/)