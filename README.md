# hospital-risk-adjusted-cost-ranking

# Ranking Risk-Adjusted Hospital Cost Using Medicare Data

## Overview
This project evaluates how patient complexity affects hospital cost comparisons using CMS Medicare inpatient hospital public use data. A regression-based risk adjustment model is used to estimate expected cost per discharge, and hospital rankings are compared before and after adjustment.

## Key Questions
- How much do hospital rankings change after adjusting for patient risk?
- Do hospitals serving sicker populations systematically benefit from adjustment?
- Which providers appear most cost-efficient after accounting for case mix?

## Data
Source: CMS Medicare Inpatient Hospital Public Use File  

## Methods
- Feature engineering of cost and utilization metrics
- PCA to summarize chronic disease burden
- Log-linear OLS regression with state fixed effects
- Residual-based hospital ranking and value tiering

## Results
- Risk adjustment substantially reshapes hospital rankings
- High-risk hospitals tend to improve after adjustment
- Raw cost metrics alone can misrepresent provider efficiency

## Files
- `risk_adjusted_hospital_ranking.ipynb`: full analysis
- `risk_adjusted_hospital_cost_rankings.pdf`: summary presentation
