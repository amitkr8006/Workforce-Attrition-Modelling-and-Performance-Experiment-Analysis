# Workforce Attrition Modelling and Performance Experiment Analysis

This project is a statistical portfolio applying multiple statistical techniques across two applied datasets: (1) the IBM HR Employee Attrition dataset and (2) an athlete performance experiment (trained vs untrained) under four stretching/warm-up conditions. The work focuses on selecting appropriate tests/models, checking assumptions where required, and interpreting results for practical decision-making.

## Objectives
- Use classification and hypothesis testing methods to answer real analytics questions.
- Interpret results using significance tests, effect sizes, and model diagnostics.
- Translate statistical outputs into clear business and experimental conclusions.

## Data Used
- IBM HR Employee Attrition dataset (1,470 employees; 35 variables; attrition Yes/No)
- Athlete performance experiment (trained vs untrained; four within-subject conditions)

## Methods Used
- Logistic regression (attrition prediction + interaction term)
- Kruskal–Wallis test (promotion timing vs tenure/hours)
- Mixed-model ANOVA (stretch/warm-up condition effects + athlete type)
- One-way ANCOVA (education effect on work-life balance controlling job level and satisfaction)

## Key Findings (Highlights)
- Job satisfaction was the most meaningful predictor of attrition; interaction effects were not meaningful, and class imbalance limited attrition detection.
- Years at company varied significantly by promotion timing, while standard hours did not vary.
- Stretching and warm-up significantly improved performance with a very large effect size, and results were consistent for trained and untrained athletes.
- Education had a minimal and non-significant impact on work-life balance after controlling for covariates.

## Outcome
A practical demonstration of statistical testing and modelling across HR analytics and experimental performance data, showing correct method selection, assumption awareness, and clear interpretation.
