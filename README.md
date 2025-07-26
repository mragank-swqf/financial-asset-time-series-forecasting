# Financial Time Series Forecasting

This project focuses on modeling and forecasting a financial time series dataset provided during a private competition hosted by my Quantitative Finance cohort. The objective was to build accurate forecasting models using classical time series techniques.

---

## 📊 Problem Statement

Given a historical univariate financial time series, the goal was to:
- Explore trends, stationarity, and patterns
- Build predictive models to forecast future values
- Experiment with exogenous regressors to improve accuracy

---

## 🧠 Methodology

- Exploratory Data Analysis (EDA)
- Stationarity checks using ADF test
- Model selection via:
  - ARIMA, SARIMA
  - AutoARIMA with exogenous features (`x`, `x²`)
- Residual analysis and model validation

Final model: **AutoARIMA with tuned exogenous inputs** (nonlinear transformation of original series).

---

## 🏆 Competition Results

- Hosted as a private Kaggle-style challenge by my Quant Finance cohort.
- Secured **2nd Place** on the leaderboard.

📄 [View Certificate](https://drive.google.com/file/d/15_peDS9CIV63r3rQXwt2TFqMetMLCow2/view?usp=sharing)   
🔗 [Competition Link](https://www.kaggle.com/competitions/time-series-champs-quantitative-finance-cohort-25/overview)

---

## 📁 Repository Structure

- `data/`: Contains the time series CSV file with 800 data points used for training. The goal was to forecast the next 199 values.
- `notebook/`: Main Jupyter Notebook used for exploration, model development, and forecasting.
- `reports/`: 
  - PDF export of the notebook showing results and visualizations.
  - PPTX presentation summarizing methodology and key takeaways, presented post-competition to other participants.
- `certificate/`: 2nd place certificate from the cohort competition.

