# European Food Policy & Obesity Analysis

Comparative exploratory analysis of food policy instruments and obesity outcomes across European countries using publicly available data.



# Project Overview

This repository investigates the relationship between selected food policy measures and population obesity outcomes across European countries.

The project brings together publicly available policy and health data to explore whether countries with different food-policy environments show differences in obesity prevalence.

The analysis is designed as a reproducible health economics and public-health research project using Python and publicly available evidence.

The project focuses on:

* Food policy instruments implemented across European countries
* Population obesity prevalence
* Cross-country differences in policy environments
* Descriptive comparisons between policy exposure and obesity outcomes
* Exploratory statistical analysis
* Data visualisation
* Limitations of cross-country observational comparisons

The analysis is exploratory and does not interpret associations as causal effects.



# Research Question

**How do obesity prevalence and selected food-policy environments differ across European countries, and what patterns can be observed between policy measures and population obesity outcomes?**

A secondary objective is to examine whether simple cross-country comparisons can identify areas that could support further health-economic or policy research.



# Project Structure


european-food-policy-obesity-analysis/
│
├── data/
│   └── Raw and processed datasets used in the analysis
│
├── figures/
│   └── Generated visualisations and analytical figures
│
├── notebooks/
│   └── Python notebooks containing data preparation,
│       analysis and visualisation
│
├── README.md
├── .gitignore
└── .gitattributes
```



# Data Sources

The project uses publicly available data from official or established sources.

The datasets are used to describe:

* Obesity prevalence
* Population characteristics
* Food-policy instruments
* Country-level policy differences

Where possible, source information and data provenance are documented alongside the analytical files.

The project does not use proprietary healthcare datasets or simulated individual-level patient data.



# Methodology

The analysis follows a reproducible workflow:

1. Identify relevant publicly available European health and policy data.
2. Import and inspect the datasets using Python.
3. Clean and harmonise country-level observations.
4. Define the food-policy variables used in the analysis.
5. Link policy information with obesity prevalence data.
6. Generate descriptive statistics.
7. Compare obesity prevalence across different policy environments.
8. Produce exploratory visualisations.
9. Examine simple statistical associations where appropriate.
10. Interpret results in light of the observational nature of the data.
11. Document limitations and potential areas for further research.



# Analytical Approach

The project primarily uses descriptive and exploratory methods rather than attempting to establish causal effects.

Analytical components include:

* Country-level comparisons
* Summary statistics
* Policy classification
* Obesity prevalence comparisons
* Exploratory correlation analysis
* Data visualisation

The analysis is intended to identify patterns and generate research questions rather than provide definitive estimates of the causal impact of individual food policies.



# Why This Matters

Obesity is influenced by multiple interacting factors, including diet, physical activity, socioeconomic conditions, healthcare access, commercial environments and public policy.

Food-policy interventions such as taxation, product reformulation, marketing restrictions and food-labelling policies are therefore relevant areas for health-policy and health-economic research.

A cross-country analysis can provide an initial framework for investigating how different policy environments correspond with population health outcomes.



# Limitations

Several limitations should be considered when interpreting the results.

### Observational data

Country-level associations cannot establish that a particular policy caused a difference in obesity prevalence.

### Cross-country comparability

Countries differ in demographic structure, healthcare systems, dietary patterns, socioeconomic conditions and methods of measuring obesity.

### Policy heterogeneity

Food policies can differ substantially in design, implementation, coverage and enforcement.

### Confounding

Observed differences in obesity prevalence may reflect factors other than food policy.

### Ecological analysis

The analysis uses country-level data and therefore cannot be interpreted as evidence about individual-level behaviour or treatment effects.



# Reproducibility

The project is designed so that the main analytical workflow can be reproduced using the files contained in this repository.

The analysis is implemented in Python, with notebooks documenting the data preparation, analytical steps and visualisations.

All data sources used in the analysis are publicly available.



# Tools

The project uses:

* Python
* pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

Additional Python packages are documented in the project environment where applicable.



# Project Outputs

The `figures/` directory contains visualisations generated during the analysis.

These outputs are intended to communicate:

* Differences in obesity prevalence
* Differences between policy environments
* Cross-country patterns
* Exploratory relationships between food policy and obesity outcomes



# Future Extensions

Potential extensions of the project include:

* Expanding the number of European countries
* Adding additional food-policy instruments
* Incorporating policy implementation dates
* Examining changes in obesity prevalence over time
* Adding socioeconomic and demographic controls
* Testing alternative policy classifications
* Applying panel-data methods where suitable longitudinal data are available
* Extending the analysis toward a health-economic evaluation of specific food-policy interventions




Saffa Mariam
MSc Health Economics and Management
University of Bologna

GitHub: https://github.com/saffam

Portfolio: https://saffam.github.io/
