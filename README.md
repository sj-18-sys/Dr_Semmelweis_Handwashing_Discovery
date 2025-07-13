# Dr_Semmelweis_Handwashing_Discovery
An exploratory reanalysis of 19th-century maternal mortality data that highlights Ignaz Semmelweis’s critical discovery: enforcing handwashing sharply reduced deaths due to puerperal fever.

---

## Project Overview

This project examines mortality data from two clinics at Vienna General Hospital (1841–1847) to replicate key insights from Semmelweis’s research:
- Compare death rates between Clinic 1 (physicians) and Clinic 2 (midwives)
- Identify the timing and impact of mandatory handwashing
- Quantify how maternal death proportions changed after handwashing was enforced

---

## Data & Tools

- **Dataset**:  
  - `yearly_deaths_by_clinic.csv` – annual births and deaths  
  - `monthly_deaths.csv` – monthly data around the 1847 intervention  
- **Notebook**: `notebook.ipynb` – uses Python (pandas, matplotlib) to clean, analyze, and visualize  
- **Environment**: Jupyter Notebook or Google Colab — install dependencies with:
  ```bash
  pip install pandas matplotlib seaborn
---
## Analytical Steps
Load & review annual data from both clinics

Calculate death proportions and plot differences

Analyze monthly data to pinpoint when handwashing began

Segment data "before" and "after" intervention at ~June 1847

Plot time-series of mortality rates, marking the intervention

Bootstrap analysis to generate a confidence interval on mortality reduction — more robust than simple difference-in-means

---

## Key Findings
Clinic disparity: Clinic 1 consistently had higher mortality rates than Clinic 2

Handwashing effect: Death rates dropped from ~10 % to ~2 % after June 1847

Bootstrap CI: Mortality proportion decreased by approximately 6–10 percentage points with high confidence

This aligns with historical findings: Semmelweis’s chlorinated lime handwashing dropped maternal deaths by ~90 % 

---
## Conclusions & Insights:
Drastic improvement: Introduction of handwashing led to a ~8 pp drop in maternal deaths

Statistical backing: Bootstrap analysis provides uncertainty intervals, reinforcing robustness

Historical context: Supports Semmelweis’s empirical discovery that hand hygiene saves lives 

---
## Extensions & Next Steps:
Expand time coverage to include data beyond 1847

Dive deeper into statistical methods (e.g., Bayesian inference, time-series modeling)

Compare to modern infection-control interventions, especially relevant amid COVID-19 hygiene practices

---

## Acknowledgements:
Historical dataset derived from original records studied by Semmelweis in 1847

Analysis created as part of the “100 Days of Python” Udemy course


---
## About the Author:
Author: sj‑18‑sys

Date: July 2025


