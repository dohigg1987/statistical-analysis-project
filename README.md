# Pell Grant Share and Graduate Earnings in US Four-Year Institutions

This project is a statistical analysis in Python of whether the share of undergraduates receiving Pell Grants is associated with median earnings ten years after entry. It loads and prepares the data, computes descriptive statistics, builds four visual models, and performs a Spearman rank correlation test. The written findings are in `Statistical_Analysis_Report.pdf`.

**Dataset:** College Scorecard, most recent institution-level data (U.S. Department of Education), listed on Data.gov: https://catalog.data.gov/dataset/college-scorecard-c25e9 (data portal: https://collegescorecard.ed.gov/data). The file `college_scorecard_subset.csv` contains all 6,273 institutions and 23 of the original 3,308 columns.

## Files

- `analysis.ipynb`: the analysis notebook
- `Statistical_Analysis_Report.pdf`: written report with citations
- `college_scorecard_subset.csv`: the dataset used
- `requirements.txt`: package versions created with `pip freeze`
- `figures/`: charts produced by the notebook

## How to Run

Install Python 3.10 or higher, then:

```
git clone https://github.com/dohigg1987/statistical-analysis-project.git
cd statistical-analysis-project
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```

Choose Kernel > Restart & Run All. The notebook reads the CSV from the same folder and writes the figures to `figures/`.

To regenerate the requirements file in your own environment, run `pip freeze > requirements.txt`.
