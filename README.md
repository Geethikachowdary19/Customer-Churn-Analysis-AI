# Customer Churn Analysis and Prediction Using Data Analytics and AI

**Author:** Anumolu Sri Sai Geethika  
**Program:** AICTE | IBM SkillsBuild Data Analytics with AI Internship 2026

## Project description
This project explores customer churn in a fictional telecom dataset and compares Logistic Regression and Random Forest classifiers. It includes data cleaning, exploratory data analysis, visualizations, preprocessing, model evaluation, and business recommendations.

## Dataset
- IBM Telco Customer Churn sample dataset
- Direct CSV: https://raw.githubusercontent.com/IBM/telco-customer-churn-on-icp4d/master/data/Telco-Customer-Churn.csv
- Source repository: https://github.com/IBM/telco-customer-churn-on-icp4d
- Published sample: 7,043 records and 21 original columns.

## Technologies
Python, Jupyter Notebook, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn.

## Files
- `AnumoluSriSaiGeethika_CustomerChurnAnalysis.ipynb` — code and analysis
- `requirements.txt` — dependencies
- `AnumoluSriSaiGeethika_ProjectReport.docx` — project report
- `README.md` — project overview and setup

## How to run
1. Install Python 3.10 or newer.
2. Open a terminal in the folder containing these files.
3. Install dependencies: `python -m pip install -r requirements.txt`
4. Start Jupyter: `jupyter notebook`
5. Open the `.ipynb` file and choose **Run > Run All Cells**.
6. An internet connection is needed to download the CSV. If the download fails, download the CSV from the URL above and change the notebook's `pd.read_csv(DATA_URL)` line to `pd.read_csv("Telco-Customer-Churn.csv")`.

## Outputs
The notebook produces charts, churn-rate summaries, a model-comparison table, a classification report, a confusion matrix, and an ROC curve. Metrics are computed when the notebook runs; do not claim a score before running it.

## Limitations and responsible use
This is an educational example, not a production system. The data is a snapshot from a fictional company; associations do not prove causation. Predictions should support human review, not be the sole basis for customer decisions.

## References
- https://github.com/IBM/telco-customer-churn-on-icp4d
- https://pandas.pydata.org/docs/
- https://scikit-learn.org/stable/
