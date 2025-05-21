## Solar Potential Analysis – Week 1
This project is part of the Solar Challenge Hackathon. It explores solar energy potential across Benin, Sierra Leone, and Togo using cleaned meteorological datasets, with insights derived from exploratory data analysis and cross-country comparison.

## Project Structure

```bash
solar-challenge-week1/
│
├── data/                     # Raw & cleaned CSV files (not tracked by Git)
├── notebooks/
│   ├── eda_benin.ipynb
│   ├── eda_sierraleone.ipynb
│   ├── eda_togo.ipynb
│   └── compare_countries.ipynb
│
├── outputs/                  # Visualizations (optional)
├── requirements.txt          # All dependencies
├── README.md
└── .gitignore


## Reproducing the Environment

**Clone the repository**
'''bash
  git clone https://github.com/your-username/solar-challenge-week1.git
  cd solar-challenge-week1
'''
** Create a virtual environment **

'''bash
  python -m venv venv
  source venv/bin/activate  # On Windows: venv\Scripts\activate
'''

**Install dependencies**

'''bash
  pip install -r requirements.txt
'''
## Notebooks Overview

**Notebook	Description**
- eda_benin.ipynb	Data cleaning, EDA & visualization for Benin
- eda_sierraleone.ipynb	Same as above for Sierra Leone
- eda_togo.ipynb	Same as above for Togo
- compare_countries.ipynb	Final comparison across the three countries

**Key Outputs**

- Cleaned CSVs: data/benin_clean.csv, data/sierraleone_clean.csv, data/togo_clean.csv

- Visualizations: Boxplots, windroses, scatter plots, summary tables, and more

- Statistical testing: ANOVA and Kruskal–Wallis for GHI comparisons

- Final insights: Which country has the strongest solar potential and why

**Project Highlights**

- Reproducible workflow with Git & branch-based structure

- Thorough EDA and sensor cleaning analysis

- Actionable recommendations for solar investment priorities

- All visualizations and data are explained clearly in each notebook

**Submission Info**
- GitHub link: https://github.com/meron-23/solar-challenge-week1/edit/main

- Final Report included in repo and shared separately as required

**Contributors**
- Meron Muluye – Data Science & EDA

- Solar Challenge support Team



