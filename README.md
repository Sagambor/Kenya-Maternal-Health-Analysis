# Kenya-Maternal-Health-Analysis
Analysis of Kenya DHS data (1989–2022) exploring trends in skilled antenatal care coverage and the relationship between delivery setting and maternal healthcare access. The analysis focuses on two questions:

1. Has access to skilled antenatal care improved over time, and what does the trend 
suggest about future coverage?
2. Is place of delivery associated with the likelihood of receiving skilled antenatal care?

## Projects

**Project 1 — Trend & Forecast**  
Visualises skilled ANC coverage across nine survey rounds, tests for a monotonic 
trend using the Mann-Kendall test, and projects coverage to 2030 using linear regression.

**Project 2 — Logistic Regression**  
Builds a binary classification model to examine whether health facility delivery 
and skilled birth attendance are associated with high ANC coverage at the national level.

## Dataset

Source: [DHS Program](https://dhsprogram.com) — Kenya National Access to Healthcare indicators.  
The dataset contains national-level aggregated survey estimates. It is not individual-level microdata.

## Tools & Libraries

- Python 3
- pandas, numpy
- matplotlib, seaborn
- scipy, scikit-learn

## Key Findings

- Skilled ANC coverage rose from 77.6% in 1989 to 97.9% in 2022 (+20.3 percentage points)
- The Mann-Kendall test shows a positive trend (τ = 0.444) though not statistically 
significant at n = 9
- Linear forecast projects near-universal coverage (~99%) by 2030
- Health facility delivery is positively associated with high ANC coverage (OR = 1.57)

## Limitations

This analysis uses aggregated national survey data. Associations observed at the 
survey-year level may not hold at the individual level (ecological fallacy). 
Individual-level DHS microdata would be needed for causal inference.

## Author
Sagambor
