# 🚢 Titanic_EDA
Exploratory Data Analysis**  
> Author: Limithra Shanmugam · AVS Engineering College

---

## Overview

Exploratory Data Analysis (EDA) of the famous Titanic dataset to uncover survival patterns across gender, passenger class, age, and fare.

## Objectives

| # | Question | Finding |
|---|---|---|
| Q1 | Overall survival rate? | **38.4%** survived (342/891) |
| Q2 | Did women survive more than men? | Female: **74.2%** vs Male: **18.9%** |
| Q3 | Highest survival by class? | **1st class: 63.0%** > 2nd: 47.3% > 3rd: 24.2% |
| Q4 | Does age affect survival? | Children prioritized; survivors avg **28.3 yrs** vs 30.6 |

## Folder Structure

```
CodeAlpha_Titanic_EDA/
│
├── data/
│   ├── Titanic.csv          # Raw dataset
│   ├── fig1_overview.png    # Survival overview charts
│   ├── fig2_rates.png       # Rates & correlation heatmap
│   └── fig3_details.png     # Age, fare, embarkation
│
├── notebook.ipynb           # Full analysis notebook
├── report.pdf               # Professional EDA report
└── README.md                # This file
```

## Skills Used

- **Python** — core language
- **Pandas** — data loading, groupby, aggregation
- **NumPy** — numerical operations, correlation
- **Matplotlib** — bar charts, histograms, boxplots, violin plots
- **Seaborn** — countplots, heatmaps
- **ReportLab** — PDF report generation

## Quick Start

```bash
pip install pandas numpy matplotlib seaborn reportlab

# Run the notebook
jupyter notebook notebook.ipynb
```

## Key Insights

1. **Gender** was the strongest predictor — "women and children first" was real policy
2. **Class** reflected lifeboat access — 1st class had 2.6× the survival rate of 3rd
3. **Age** mattered for children; adult age difference between survivors/non-survivors was small
4. **Fare** positively correlates with survival (+0.26) as a proxy for class and deck location

## Dataset

Source: [Kaggle Titanic Dataset](https://www.kaggle.com/datasets/brendan45774/test-file)  
Alternate: [datasciencedojo/datasets](https://github.com/datasciencedojo/datasets)

---

