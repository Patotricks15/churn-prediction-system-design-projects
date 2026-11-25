# Churn Prediction System Design Projects

A portfolio of independent customer churn systems. Each project starts from a
clearly defined churn label and a transparent baseline, then adds richer models,
survival analysis, uplift, explanations, and drift monitoring in later projects.

Each project is its own GitHub repository with a reproducible pipeline, a
time-ordered evaluation, and a README that records the data, label definition,
split, metric, and main limitation.

## Projects

| # | Name | Dataset | Main method | Repository |
|---|------|---------|-------------|-------------|
| 1 | Churn Label and Baseline | Online Retail II (UCI) | Recency rule and logistic regression on RFM features | [churn-label-and-baseline](https://github.com/Patotricks15/churn-label-and-baseline) |
| 2 | Gradient-Boosted Churn Classifier | Olist Brazilian E-Commerce (non-commercial licence) | Gradient boosting on time-ordered features, compared with the baseline | [churn-gbm-classifier](https://github.com/Patotricks15/churn-gbm-classifier) |
| 3 | Time to Churn (Survival Analysis) | Online Retail II (UCI) | Kaplan-Meier and Cox models, hand-written and tested | [churn-time-to-event](https://github.com/Patotricks15/churn-time-to-event) |
| 4 | Retention Uplift Model | None yet: needs a real retention-offer experiment | Design only, no results | [retention-uplift-model](https://github.com/Patotricks15/retention-uplift-model) |
| 5 | Churn Explanations | Olist Brazilian E-Commerce (non-commercial licence) | Per-customer explanations of the churn model | [churn-explanation](https://github.com/Patotricks15/churn-explanation) |
| 6 | Churn Drift Monitoring | Olist Brazilian E-Commerce (non-commercial licence) | Monthly drift checks and a retrain trigger | [churn-drift-monitoring](https://github.com/Patotricks15/churn-drift-monitoring) |

Projects 2, 3, 5 and 6 have not been run on real data yet; their notebooks were written but not executed. Project 4 is design only.

## Scope

This is part of a larger churn portfolio plan with six projects. Projects are
added here as they are completed; each repository listed above is self-contained
and can be cloned, tested, and run independently.
