# UK Road Accidents Analysis (2005–2015)

An exploratory data analysis project examining 1.78 million UK road accident records to identify patterns in severity, weather conditions, speed limits, and long-term safety trends.

---

## Project Overview

Road accidents are one of the most significant preventable causes of injury and mortality in the UK. The Department for Transport collects detailed records of every reported road collision via the Stats19 form. This project applies Python-based exploratory data analysis to identify actionable patterns relevant to road safety policy and transport planning.

This project was completed as part of a personal data portfolio, demonstrating skills in Python, pandas, matplotlib, and seaborn applied to a large, real-world UK government dataset.

---

## Dataset

| Property | Detail |
|---|---|
| Source | UK Department for Transport — Road Safety Data (via Kaggle) |
| Records | 1,780,653 accident records |
| Period | 2005 to 2015 |
| Features | 32 columns |
| Target | Accident severity (Fatal / Serious / Slight) |

---

## Key Findings

- UK roads became measurably safer over the decade, with a consistent year-on-year reduction in total accidents
- Fine weather conditions account for the majority of accidents — higher traffic volume and driver overconfidence in good conditions outweigh the risk posed by adverse weather
- 30mph zones record the highest accident volume (urban density), but 60–70mph rural roads produce a disproportionately higher fatality rate per incident
- Rural roads have a significantly higher fatal accident rate than urban roads despite lower total volumes
- Friday records the highest accident frequency across all days of the week

---

## Analysis Sections

- Accident severity distribution (Fatal / Serious / Slight)
- Year-on-year trend analysis (2005–2015)
- Accidents by day of week
- Weather conditions and accident frequency
- Speed limit vs accident severity and fatal rate
- Urban vs rural comparison
- Monthly accident patterns

---

## Repository Structure

```
uk-road-accidents-analysis/
├── UK_Road_Accidents_Analysis.ipynb   # Full analysis notebook
├── Accidents0515.csv                  # Dataset (DfT Road Safety Data)
└── README.md                          # This file
```

---

## How to Run

### Option 1 — Google Colab (recommended)
1. Upload both `UK_Road_Accidents_Analysis.ipynb` and `Accidents0515.csv` to [Google Colab](https://colab.research.google.com)
2. Run all cells in order

### Option 2 — Local environment
```bash
pip install pandas numpy matplotlib seaborn
jupyter notebook UK_Road_Accidents_Analysis.ipynb
```

---

## Skills Demonstrated

- Large dataset handling (1.78 million records) with pandas
- Data cleaning, missing value handling, and feature engineering
- Categorical variable mapping and label encoding
- Exploratory data analysis with matplotlib and seaborn
- Multi-panel chart layouts and annotated visualisations
- Deriving actionable insights from real UK government data
- Python (pandas, numpy, matplotlib, seaborn)

---

## Author

**S. Ahmed**  
BSc Applied Medical Science (First Class), UK University (2025)

---

## Data Source

UK Department for Transport — Road Safety Data  
[data.gov.uk](https://data.gov.uk/dataset/road-accidents-safety-data)

---

## Limitations and Future Work

- Only reported accidents are included; minor incidents not attended by police are underrepresented
- Correlation does not imply causation; multivariate modelling would be required to confirm relationships
- Future extensions: hour-by-hour analysis, logistic regression for severity prediction, geographic hotspot mapping
