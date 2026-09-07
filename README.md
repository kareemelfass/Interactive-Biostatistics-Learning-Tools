# Interactive Biostatistics Learning Tools

A growing collection of interactive, browser-based learning tools designed to make statistical concepts easier to understand for biomedical, clinical, and public-health researchers.

The tools focus on **learning by seeing and doing**: change inputs, follow calculations, and connect statistical formulas to what happens in the data and graphs.

## Interactive tools

### 1. P-value Lab

Explore how p-values respond to changes in effect size, sample size, variability, and random sampling variation.

**[Open the live P-value Lab](https://kareemelfass.github.io/p-value-lab/)**

**[View the repository](https://github.com/kareemelfass/p-value-lab)**

Topics covered:
- Effect size
- Sample size
- Variability
- Random sampling variation
- Confidence intervals
- Statistical significance

---

### 2. Kaplan–Meier Curve Tutor

Build a Kaplan–Meier survival curve step by step and see exactly how the risk set, events, censoring, conditional survival, calculation table, and curve are connected.

**[Open the live Kaplan–Meier Curve Tutor](https://kareemelfass.github.io/p-value-lab/km-curve/)**

Currently hosted within the P-value Lab repository; it can be separated into its own repository as the collection grows.

Topics covered:
- Number at risk
- Events and censoring
- Conditional survival
- Cumulative survival probability
- Step-by-step Kaplan–Meier calculation
- Tied events
- Connection between the calculation table and survival curve

---

### 3. Confidence Interval Lab

Learn the frequentist meaning of a confidence interval by generating repeated samples and watching which intervals contain the fixed true population parameter.

**[Open the live Confidence Interval Lab](https://kareemelfass.github.io/p-value-lab/confidence-interval/)**

Topics covered:
- Correct frequentist interpretation of a confidence interval
- Long-run coverage under repeated sampling
- Common 95% CI interpretation myth
- Effect of confidence level on interval width and coverage
- Effect of sample size on precision
- Confidence intervals versus Bayesian credible intervals
- Relationship between a 95% CI and a two-sided p-value
- Null values for differences and ratio measures

---

### 4. Q–Q Plot Lab

Build a normal Q–Q plot point by point, connect percentiles to theoretical normal quantiles, and learn how common distributional departures change the plot.

**[Open the live Q–Q Plot Lab](https://kareemelfass.github.io/p-value-lab/qq-plot/)**

Topics covered:
- Percentiles and quantiles
- Normal, skewed, and heavy-tailed distributions
- Step-by-step Q–Q plot construction
- Theoretical normal quantiles
- Right and left skew
- Heavy and light tails
- Outliers and mixture distributions
- Sample-size effects and random sampling variation
- Interactive Q–Q interpretation challenges

---

### 5. KMunicate Kaplan–Meier Lab

Compare a conventional Kaplan–Meier plot with the KMunicate reporting format using the same illustrative data. See how confidence intervals and an extended risk table reveal uncertainty and the participant status behind late follow-up.

**[Open the live KMunicate Kaplan–Meier Lab](https://kareemelfass.github.io/p-value-lab/kmunicate/)**

Topics covered:
- Standard versus KMunicate Kaplan–Meier presentation
- Confidence intervals around survival estimates
- Numbers at risk, cumulative events and cumulative censoring
- The effect of sample size, censoring and treatment effect on interpretation
- Reproducible KMunicate-style plots in R


---

### 6. Penalised Regression Learning Lab

Learn when and why to use penalised regression, then explore ridge, lasso, and elastic net interactively using the same simulated dataset.

**[Open the live Penalised Regression Learning Lab](https://kareemelfass.github.io/p-value-lab/penalised-regression/)**

Topics covered:
- When penalised regression is useful
- Shrinkage and regularisation
- Ridge, lasso, and elastic net
- L1 and L2 penalties
- Lambda and alpha
- Variable selection with lasso and elastic net
- Coefficient paths
- Cross-validation for lambda
- Correlated-predictor selection instability
- Practical method-selection decisions

---

## More tools are coming

This repository is the central index for the **Interactive Biostatistics Learning Tools** collection. Future simulations, calculators, and guided statistical demonstrations will be added here as they are developed.

Each tool is intended to be:
- Interactive
- Educational rather than a black-box calculator
- Easy to use in a web browser
- Focused on practical understanding
- Suitable for beginner and intermediate researchers

## Educational use

These tools are designed for statistical education and demonstration. They are not substitutes for study-specific statistical analysis, appropriate methodological guidance, or validated clinical/research software.

---

Created by **Kareem Elfass**
