# The Impact of Economic Risk, Financial Risk, and Political Risk on Resource Sustainability

### Method of Moments Quantile Regression and Club Convergence

#### A Cross-Country Panel Econometric Analysis Incorporating Foreign Direct Investment and Productive Capacity Factors

<p align="center">

![Method1](https://img.shields.io/badge/Method%201-Moment%20Quantile%20Regression-d1242f)
![Method2](https://img.shields.io/badge/Method%202-Club%20Convergance-1f6feb)
![Period](https://img.shields.io/badge/Period-2000%E2%80%932021-2ea043)
![Countries](https://img.shields.io/badge/Countries-111-8250df)

</p>

---

## 1. Project Overview

This repository presents my Master's thesis research in Economics, investigating the relationship between **Foreign Direct Investment (FDI)**, **Productive Capacity (PCI)**, and **Resource Sustainability**, while accounting for **Economic Risk, Financial Risk, and Political Risk**.

The empirical analysis covers **111 countries over the period 2000–2021**. Material Footprint per capita is used as the main indicator of resource use and as the empirical measure of resource sustainability.

The study applies advanced panel econometric techniques to investigate cross-country differences, long-run convergence patterns, and heterogeneous effects across the distribution of material footprint.

The project demonstrates practical experience in:

- Applied econometrics and quantitative economic research
- Panel data analysis and econometric diagnostics
- Data collection, cleaning, integration, and variable construction
- Country-risk indicators and macroeconomic analysis
- Distributional econometric modelling
- Statistical interpretation and research communication

## 2. Research Question

**How do Foreign Direct Investment and Productive Capacity affect Resource Sustainability, and how do these relationships vary across countries with different convergence patterns and levels of material footprint, after accounting for economic, financial, and political risks?**

The research examines whether the relationships between investment, productive capacity, country risk, and resource consumption are homogeneous across countries or differ according to their long-run convergence patterns and distributional characteristics.

## 3. Research Variables

| Variable | Description | Role |
|---|---|---|
| MFP | Material Footprint per capita | Dependent variable |
| FDI | Foreign Direct Investment | Main explanatory variable |
| PCI | Productive Capacity Index | Main explanatory variable |
| ER | Economic Risk | Control variable |
| FR | Financial Risk | Control variable |
| PR | Political Risk | Control variable |
| GDP | GDP per capita | Control variable |

**Risk analysis dimension:** Economic, financial, and political risk indicators are incorporated to account for differences in national economic and institutional conditions when estimating the relationships of interest.

## 4. Econometric Methodology

The empirical strategy combines panel-data diagnostics, convergence analysis, and distributional regression.

### 4.1. Panel Data Diagnostics

Before estimating the main models, the study applies panel econometric diagnostic procedures to assess the properties of the dataset and the suitability of the estimation strategy.

The diagnostic framework includes:

- Cross-sectional dependence testing
- Slope heterogeneity testing
- Panel unit-root testing
- Panel cointegration analysis
- Additional specification and statistical diagnostics

### 4.2. Club Convergence Analysis

Following the Club Convergence framework of Phillips and Sul (2007), the study investigates whether countries share a common long-run convergence path in resource sustainability.

Rather than imposing a single convergence pattern on all countries, the approach identifies groups of countries with similar transition and convergence behaviour.

The final empirical analysis distinguishes two convergence clubs:

| Convergence group | Number of countries |
|---|---:|
| Club 1 | 67 |
| Club 2 | 44 |
| **Total** | **111** |

The identified groups are subsequently analysed separately to account for cross-country heterogeneity.

### 4.3. Method of Moments Quantile Regression (MMQR)

The study applies the Method of Moments Quantile Regression developed by Machado and Silva (2019).

Unlike conventional mean regression, MMQR allows the estimated relationships to vary across different points of the conditional distribution of Material Footprint per capita.

The analysis examines the following quantiles:

**Q25 · Q50 · Q75 · Q90**

This approach provides a more detailed understanding of how FDI, productive capacity, and country-risk indicators relate to resource consumption at different distributional levels.

---

### 5. Tools and Software

- **R** — Statistical and econometric analysis
- **Stata** — Panel-data estimation and econometric modelling

Python-related code is included only where documented in the research materials; it is not presented as the primary implementation of the thesis methodology.

## 6. Academic Reference

**Thesis title:** Investigating the Impact of Foreign Direct Investment and Productive Capacity on Resource Sustainability: Method of Moments Quantile Regression and Club Convergence.

**Degree:** M.Sc. in Economics  
**University:** Ferdowsi University  
**Year:** 2024

📄 **[Read the Full Master's Thesis](thesis/full-thesis.pdf)**

---

## 10. Research Scope and Limitations

This project is an applied cross-country econometric study. Its objective is to estimate and interpret relationships between macroeconomic variables, country-risk indicators, and resource consumption.

The empirical results should be interpreted within the scope of the dataset, model specifications, and econometric methods used in the thesis. The analysis is not a credit-risk scoring system, a causal machine-learning model, or a predictive risk classification system.

---

# 🔑 Keywords

`Resource Sustainability` · `Foreign Direct Investment` · `Productive Capacity` · `Economic Risk` · `Financial Risk` · `Political Risk` · `Panel Data` · `Club Convergence` · `Method of Moments Quantile Regression`

---

<p align="center">
  <em>https://github.com/aminmirhaj/master-thesis-quantitative-econometrics</em>
</p>

<p align="center">
  <a href="https://github.com/aminmirhaj/master-thesis-quantitative-econometrics/blob/main/thesis/full-thesis.pdf">📄 Read the Full Thesis</a>
