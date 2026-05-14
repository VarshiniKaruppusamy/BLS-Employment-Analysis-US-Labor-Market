# U.S. Labor Market Analysis — BLS Nonfarm Payroll Employment (2005–2024)

## Project Overview
A comprehensive exploratory and statistical analysis of U.S. 
nonfarm payroll employment across major industry sectors over 
a 20-year period (January 2005 – December 2024), using data 
from the Bureau of Labor Statistics (BLS) Current Employment 
Statistics (CES) program.

## Business Questions Answered
- What is the long-run trajectory of U.S. employment from 
  2005 to 2024?
- How did the 2008 Great Recession and COVID-19 pandemic 
  impact employment across industries?
- Which sectors are most volatile vs. most stable during 
  economic downturns?
- Is there statistical evidence of a structural break caused 
  by COVID-19?

## Tools & Technologies
- Python (Pandas, NumPy, SciPy, StatsModels)
- Data Visualization: Seaborn, Matplotlib
- Statistical Methods: Pearson & Spearman Correlation, 
  Linear Regression, Welch's t-test, STL Decomposition,
  Durbin-Watson, Herfindahl-Hirschman Index (HHI)
- Dataset: BLS CES Program via data.gov (240 rows × 16 cols)

## Key Findings
- Total nonfarm employment grew at ~22,000 jobs/month 
  over 2005–2024 (R² > 0.90)
- COVID-19 caused ~22M job losses in just two months —
  the sharpest shock in BLS recorded history
- Leisure & Hospitality saw the steepest decline (~49%) 
  but led the post-pandemic recovery
- Government employment is the most stable sector 
  (CV ~1.8%), acting as a countercyclical stabilizer
- Manufacturing is the only sector with a statistically 
  significant negative long-run trend
- Welch's t-test confirmed a structural break attributable 
  to COVID-19 (p < 0.001, large Cohen's d)

## Analytical Techniques
- 12-month rolling mean for trend smoothing
- STL seasonal-trend decomposition (LOESS)
- Hierarchical cluster analysis (Ward linkage, MinMax normalized)
- Year-over-year growth rate analysis
- Sector share of total private employment
- COVID-19 sectoral impact analysis (Feb vs Apr 2020)
- HHI employment concentration measurement
- 12 publication-quality visualizations

## Files
- BLS_Employment_Analysis.ipynb — Main analysis notebook
- BLS_Employment_Analysis_Project2_Group2.ipynb — 
  Group analysis notebook
- Project2_Report.pdf — Full project report

## Data Source
Bureau of Labor Statistics, Current Employment Statistics 
(CES) Program via data.gov
https://catalog.data.gov/dataset/bls-jobs-by-industry-category


