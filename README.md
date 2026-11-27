# The Impact of Economic Risk, Financial Risk, and Political Risk on Resource Sustainability

- Method of Moments Quantile Regression and Club Convergence

- A Cross-Country Panel Econometric Analysis Incorporating Foreign Direct Investment and Productive Capacity Factors

<p align="center">

![Method1](https://img.shields.io/badge/Method%201-Moment%20Quantile%20Regression-d1242f)
![Method2](https://img.shields.io/badge/Method%202-Club%20Convergance-1f6feb)
![Period](https://img.shields.io/badge/Period-2000%E2%80%932021-2ea043)
![Countries](https://img.shields.io/badge/Countries-111-8250df)

</p>


## 1. Project Overview

This project is based on my Master's thesis in Economics. It explores how **Foreign Direct Investment** and **Productive Capacity** relate to **Resource Sustainability**, while taking **Economic Risk**, **Financial Risk**, and **Political Risk** into account.

The analysis covers **111 countries from 2000 to 2021**, using Material Footprint per capita as the main measure of resource use.

The project involves:
- Applied econometrics and panel data analysis
- Data collection, cleaning, and analysis
- Econometric testing and diagnostics
- Country-risk and macroeconomic analysis
- Quantitative research and interpretation

📄 **[Read the Full Master's Thesis](thesis/thesis.pdf)**

## 2. Research Question

How are FDI and productive capacity related to resource sustainability across countries, and do these relationships differ depending on country-risk levels, convergence patterns, and material footprint?

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

## 4. Data and Empirical Methodology

The following workflow summarizes the main stages of the empirical analysis, from data collection and preparation to econometric estimation and interpretation.

```mermaid
flowchart TD
    A["1. Research Scope<br/>111 Countries | 2000–2021"]
    
    A --> B["2. Data Collection"]

    B --> B1["Global Material Flows Database<br/>Material Footprint per capita"]
    B --> B2["UNCTAD<br/>Productive Capacity Index"]
    B --> B3["International Country Risk Guide<br/>Economic, Financial and Political Risk"]
    B --> B4["World Development Indicators<br/>FDI and GDP per capita"]

    B1 --> C["3. Data Preparation"]
    B2 --> C
    B3 --> C
    B4 --> C

    C --> C1["Country-Level Panel Construction"]
    C1 --> C2["Variable Definition and Construction"]
    C2 --> C3["Descriptive Statistics and Exploratory Analysis"]

    C3 --> D["4. Preliminary Panel Diagnostics"]

    D --> D1["F-Limer Test<br/>Panel Model Selection"]
    D --> D2["Shapiro–Wilk and<br/>Shapiro–Francia Tests<br/>Normality"]
    D --> D3["Pesaran CD Test<br/>Cross-Sectional Dependence"]
    D --> D4["Pesaran–Yamagata Test<br/>Slope Heterogeneity"]
    D --> D5["Pesaran CIPS Test<br/>Panel Unit Root"]
    D --> D6["Pedroni Test<br/>Panel Cointegration"]

    D1 --> E["5. Club Convergence Analysis"]
    D2 --> E
    D3 --> E
    D4 --> E
    D5 --> E
    D6 --> E

    E --> E1["Log Transformation of<br/>Material Footprint"]
    E1 --> E2["Hodrick–Prescott Filter<br/>Remove Short-Run Fluctuations"]
    E2 --> E3["Phillips–Sul Log-t Test"]
    E3 --> E4["Recursive Clustering<br/>and Club Merging"]

    E4 --> F["6. Final Convergence Groups"]

    F --> F1["Club 1<br/>67 Countries"]
    F --> F2["Club 2<br/>44 Countries"]

    F1 --> G["7. Club-Specific Econometric Analysis"]
    F2 --> G

    G --> G1["Dependent Variable<br/>Material Footprint per capita"]
    G1 --> G2["Main Explanatory Variables<br/>FDI and Productive Capacity"]
    G2 --> G3["Control Variables<br/>Economic, Financial and Political Risk<br/>GDP per capita"]

    G3 --> H["8. Method of Moments<br/>Quantile Regression (MMQR)"]

    H --> H1["Q25"]
    H --> H2["Q50"]
    H --> H3["Q75"]
    H --> H4["Q90"]

    H1 --> I["9. Robustness Analysis"]
    H2 --> I
    H3 --> I
    H4 --> I

    I --> I1["Alternative Specification<br/>Excluding Financial and Political Risk Controls"]

    I1 --> J["10. Results and Interpretation"]

    J --> J1["Club-Specific Results"]
    J --> J2["Quantile-Specific Effects"]
    J --> J3["Tables and Visualizations"]
    J --> J4["Economic and Policy Implications"]
```


## 5. Econometric Methodology

The empirical strategy combines panel-data diagnostics, convergence analysis, and distributional regression.

### 5.1. Panel Data Diagnostics

Before estimating the main models, the study applies panel econometric diagnostic procedures to assess the properties of the dataset and the suitability of the estimation strategy.

The diagnostic framework includes:

- Cross-sectional dependence testing
- Slope heterogeneity testing
- Panel unit-root testing
- Panel cointegration analysis
- Additional specification and statistical diagnostics

### 5.2. Club Convergence Analysis

Following the Club Convergence framework of Phillips and Sul (2007), the study investigates whether countries share a common long-run convergence path in resource sustainability.

Rather than imposing a single convergence pattern on all countries, the approach identifies groups of countries with similar transition and convergence behaviour.

The final empirical analysis distinguishes two convergence clubs:

| Convergence group | Number of countries |
|---|---:|
| Club 1 | 67 |
| Club 2 | 44 |
| **Total** | **111** |

The identified groups are subsequently analysed separately to account for cross-country heterogeneity.

### 5.3. Method of Moments Quantile Regression (MMQR)

The study applies the Method of Moments Quantile Regression developed by Machado and Silva (2019).

Unlike conventional mean regression, MMQR allows the estimated relationships to vary across different points of the conditional distribution of Material Footprint per capita.

The analysis examines the following quantiles:

**Q25 · Q50 · Q75 · Q90**

This approach provides a more detailed understanding of how FDI, productive capacity, and country-risk indicators relate to resource consumption at different distributional levels.

## 6. Tools and Software

- **Python** — Data cleaning and preprocessing
- **R** — Statistical and econometric analysis (Club Convergence) 
- **Stata** — Panel-data estimation and econometric modelling (Method of Moments Quantile Regression)

## 7. Academic Reference

**Thesis title:**

*Investigating the Impact of Foreign Direct Investment and Productive Capacity on Resource Sustainability: Method of Moments Quantile Regression and Club Convergence*

|---|---:|
| **Author** | Amin Mirhaj |
| **Degree** | M.Sc. in Economics |
| **University** | Ferdowsi University |
| **Supervisor** | Dr. Narges Salehnia |
| **Advisor** | Dr. Fariba Osmani |
| **Year** | 2024 |

📄 **[Read the Full Master's Thesis](thesis/thesis.pdf)**

## Keywords

`Resource Sustainability` · `Foreign Direct Investment` · `Productive Capacity` · `Economic Risk` · `Financial Risk` · `Political Risk` · `Panel Data` · `Club Convergence` · `Method of Moments Quantile Regression`

---

<p align="center">
  <em>https://github.com/aminmirhaj/method-of-moment-quantile-regression-econometrics</em>
</p>