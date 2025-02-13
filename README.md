## Data Analysis - Occupational Health and Safety worker fatality and critical injury in Ontario

#### Overview

This project analyzes workplace fatalities and critical injuries in Ontario using data from the Ministry of Labour. The goal is to identify trends, sector-wise distributions, and key insights to enhance workplace safety and inform policy recommendations.

#### Datasets Used

Fatalities Dataset: Contains workplace fatalities categorized by sector (Construction, Industrial, Mining, Health Care).

Critical Injuries Dataset: Includes workplace injuries reported to the Ministry of Labour, with details on affected sectors.

#### Key Objectives

- Perform exploratory data analysis (EDA) to understand trends and distributions.

- Conduct statistical tests (ANOVA, Kruskal-Wallis, and Mann-Kendall) to find significant differences and trends.

#### Statistical Analysis & Findings

#####  1. Fatality Analysis

ANOVA test results confirmed a significant difference in fatalities across sectors, with the Industrial and Construction sectors having the highest risks.

Mann-Kendall Trend Test indicated no significant trend in fatalities over time, suggesting that fatality rates have remained stable despite safety interventions.

#####  2. Critical Injury Analysis

Kruskal-Wallis test found statistically significant differences in critical injuries across sectors.

Mann-Kendall Trend Test showed an increasing trend in critical injuries (p < 0.01), emphasizing the urgent need for enhanced workplace safety measures.

Spearman’s correlation analysis revealed a strong relationship between critical injuries in different sectors, suggesting shared risk factors.

##### Technologies Used

* Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost)

* Statistical Analysis (Scipy, pymannkendall)

* Data Preprocessing & Cleaning

### How to Use

#### Clone the repository:

`git clone https://github.com/Beena-Kurian/Ontario-Fatalities-Critical-Injuries.git`

#### Install required dependencies:

`pip install -r requirements.txt`

#### Run the analysis scripts in Jupyter Notebook:

`jupyter notebook OHSW_fatality_and_critical_injury.ipynb`

or Run code and markdown blocks using button

### Conclusions & Recommendations

* Fatalities have remained stable, but industrial and construction sectors remain high-risk.

* Critical injuries are increasing, requiring improved workplace safety policies.


