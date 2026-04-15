# Econometrics-Paper---Reducing-Voting-Inequality-Through-Cost-Mechanisms-
This project investigates voter roll-off behavior with a focus on voter cost reduction - Logistic regression
Econometrics of Voter Roll-Off in Local Elections

This project investigates voter roll-off behavior—the phenomenon where individuals who vote in presidential elections choose not to participate in lower-salience local elections. Using voter-level data from Tempe, Arizona, the analysis focuses on identifying the factors that influence this drop-off, with particular attention to voting convenience mechanisms.

## Research Question

What individual and contextual factors predict whether a presidential voter will also participate in a municipal election?

## Approach
Constructed a merged dataset of:
Presidential election voters
City council election participants (2024)
Defined a binary roll-off indicator (1 = did not vote in local election)
Estimated a series of logistic regression models using statsmodels:
Baseline: effect of Active Early Voting List (AEVL)
Extended models: age, income, and ZIP code fixed effects
Interaction terms to explore heterogeneous effects (e.g., AEVL × income)
## Key Findings
Enrollment in the Active Early Voting List (AEVL) is strongly associated with lower roll-off, suggesting that reducing voting costs increases continued participation.
Higher income is associated with lower roll-off, though the marginal effect of AEVL appears to diminish as income increases.
ZIP-level fixed effects highlight geographic disparities in participation behavior.
## Methods & Tools
Python (pandas, statsmodels, scikit-learn)
Logistic regression and model comparison
Evaluation via accuracy, ROC AUC, and confusion matrices
## Limitations
The analysis is associational, not causal
Potential selection bias (e.g., AEVL enrollment is not random)
Cross-sectional data limits identification of dynamic effects
## Future Work
Incorporate panel data or historical rollout of AEVL to move toward causal inference
Explore quasi-experimental designs (e.g., instrumental variables, policy timing)
Integrate additional demographic and behavioral features
