# Exploratory Policy and Obesity Analysis

## Purpose

This analysis examines cross-country associations between obesity
prevalence and selected policy indicators.

The analysis uses publicly available country-level data and is
intended as an exploratory health-policy analysis.

## Variables

### Outcome

- Obesity Prevalence (%)

### Explanatory variables

- Policy Count
- Instrument Diversity

## Statistical Analysis

An exploratory ordinary least squares (OLS) regression was estimated:

Obesity Prevalence ~ Policy Count + Instrument Diversity

Additional analyses include:

- Pearson correlation
- Spearman correlation
- Residual diagnostics
- Q-Q diagnostic plot
- Cook's distance
- Coefficient confidence intervals

## Sample

The final regression contains 27 country-level observations.

## Main Results

R-squared: 0.1965

Adjusted R-squared: 0.1296

Overall F-test p-value: 0.0724

The coefficient estimates are reported in:

`statistical_results.csv`

## Interpretation

The analysis identifies statistical associations within the observed
cross-country dataset.

These results should not be interpreted as evidence that policy
count or policy instrument diversity causes changes in obesity
prevalence.

Cross-country differences may reflect demographic, socioeconomic,
health-system, environmental and other factors that are not included
in the model.

## Limitations

- Small country-level sample.
- Cross-sectional design.
- Potential omitted-variable bias.
- Possible differences in obesity measurement across countries.
- Policy indicators are descriptive measures.
- Associations should not be interpreted as causal effects.

## Reproducibility

All analytical outputs are stored in this directory.

The analysis was conducted using Python, pandas, NumPy,
Matplotlib and statsmodels.