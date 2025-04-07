# Homework-7

## This homework assignment covers two main problems involving statistical analysis and causal inference using R:

## Problem 1: Arm Folding
- Investigate whether males and females differ in the way they fold their arms (left arm on top   
  vs. right arm on top).
- Calculate sample proportions and the difference in proportions between males and females.
- Construct a 95% confidence interval for the difference and interpret results.
- Explain related statistical concepts including standard error, sampling distributions, and the 
  Central Limit Theorem.

## Problem 2: Get Out the Vote (GOTV)
- Analyze whether receiving a GOTV phone call increased the likelihood of voting in the 1998 
  midterm elections.
- Identify confounders (voted1996, AGE, MAJORPTY) that affect both treatment assignment and 
  outcomes.
- Use nearest neighbor matching (ratio = 5) to balance covariates between treatment and control 
  groups.

After matching, estimate the causal effect of the GOTV call on voting turnout and provide a 95% confidence interval.

## Files Included

Homework7.Rmd: Full RMarkdown document with code, outputs, plots, and explanations.

armfold.csv: Dataset for Problem 1 (Arm Folding).

turnout.csv: Dataset for Problem 2 (GOTV analysis).

