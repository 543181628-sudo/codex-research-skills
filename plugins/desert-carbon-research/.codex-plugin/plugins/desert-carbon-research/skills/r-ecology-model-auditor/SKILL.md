---
name: r-ecology-model-auditor
description: Audit R ecology modelling scripts and result tables, including LMM, GAM, pSEM, nested models, AIC, R2, LRT, BH-adjusted P values, VIF, singular fits, and sample alignment.
---

Use this skill when checking ecological R scripts or result tables.

Always verify:
- input file paths and output directories;
- sample_id alignment across metadata, OTU tables, PCoA axes, and carbon endpoints;
- model formulas and random effects;
- AIC, delta AIC, marginal R2, conditional R2, LRT, BH-adjusted P values, and VIF;
- whether conclusions distinguish block-level significance from single-coefficient significance;
- whether any singular fit, rank deficiency, missing data, or collinearity affects interpretation.

Never modify raw data to force a target statistical result.
