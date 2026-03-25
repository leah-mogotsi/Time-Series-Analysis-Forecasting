# Time-Series-Analysis-Forecasting
---

**Project:** **COVID-19 Time Series Analysis**

**Author:** Leah T. Mogotsi
**Date Completed:** 25 March 2026
**Institution:** Ed Tech Africa

---

**Project Description**

This project analyses the progression of COVID-19 confirmed cases and deaths across the United States using real-world data collected by Johns Hopkins University. The analysis covers 3,342 counties across 58 states and territories from January 2020 to March 2023. The project performs exploratory data analysis to identify trends, regional differences, and periods of rapid spread, before building an ARIMA time series model to forecast future daily deaths.

---

**Project Requirements**

The following Python libraries are required to run this project:

pandas
numpy
matplotlib
seaborn
statsmodels
scikit-learn

To install all dependencies, run the following command in your terminal:

pip install pandas numpy matplotlib seaborn statsmodels scikit-learn

---

**Dataset**

The dataset is sourced from the Johns Hopkins University CSSE COVID-19 GitHub repository. The two files used are:

time_series_covid19_confirmed_US.csv
time_series_covid19_deaths_US.csv

These can be downloaded directly from:
https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data/csse_covid_19_time_series

Alternatively the notebook loads them automatically from the raw GitHub URL — no manual download is required.

---

**How to Run**

1. Open the notebook file COVID19_Analysis.ipynb in Google Colab or Jupyter Notebook
2. If using Google Colab, no additional setup is needed — all libraries are pre-installed
3. If running locally, install the required libraries using the pip command above
4. Run each cell in order from top to bottom
5. All charts and outputs will generate automatically

---



---

**Notes**

This project was completed as part of a Data Science and Analytics course. The ARIMA model is trained on national-level daily death data. All visualisations are generated inline within the notebook.
