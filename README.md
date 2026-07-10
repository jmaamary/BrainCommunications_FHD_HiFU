# BrainCommunications_FHD_HiFU

Statistical analysis code accompanying:

Focused ultrasound ventro-oral thalamotomy alters cortical excitability and improves motor control in focal hand dystonia

Study Authors
Maamary et al 2026

Journal
Brain Communications

Purpose
This repository contains R scripts used to reproduce the statistical analyses, estimated marginal means, tables and figures presented in the manuscript.

Requirements
R >= 4.4

Packages
* lme4
* lmerTest
* glmmTMB
* emmeans
* ggplot2
* dplyr
* tidyr
* boot
* performance
* DHARMa
* haven
* readr
* stringr

Repository contents
Repository contents

01_Clinical_Outcomes.R

* Longitudinal mixed-effects analyses of clinical outcome measures.
* Estimated marginal means.
* Post hoc contrasts.
* Parametric bootstrap testing.

02_MEP_Analysis.R

* Mixed-effects analyses of PAS-induced MEP amplitudes (APB and FDI).
* Estimated marginal means.
* Average post-PAS versus pre-PAS contrasts.
* Pairwise post hoc comparisons.

03_Threshold_Analysis.R

* Mixed-effects analyses of resting and active motor thresholds.
* Estimated marginal means.
* Average post-PAS versus pre-PAS contrasts.
* Pairwise post hoc comparisons.

04_SRC_Analysis.R

* Mixed-effects modelling of stimulus-response curves.
* Type III ANOVA.
* Estimated marginal slope analyses using emtrends().
* Pairwise comparisons of pre- versus post-PAS slopes.
