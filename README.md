# 🏡 Bayesian Housing Price Prediction

This project applies **Bayesian Linear Regression** to predict housing unit prices in Taipei, Taiwan, using real-world data. Beyond point predictions, it captures **uncertainty** through credible intervals and posterior predictive checks — providing a complete probabilistic view.

---

## 🔍 Project Overview

- 📊 **Dataset:** UCI Real Estate Valuation Data Set
- 📍 **Target:** Unit price (NTD/m²)
- 🧠 **Model:** Bayesian linear regression with conjugate priors
- 📦 **Posterior Inference:** Closed-form
- 🎯 **Uncertainty Quantification:** 95% credible intervals + posterior predictive check (PPC)

---

## 🧪 Notebooks

- [`analysis.ipynb`](analysis.ipynb) — Full implementation and analysis
- Includes both:
  - **Model 1**: Simpler 3-feature model
  - **Model 2**: Full-featured 6-variable model with location and time

---

## 📁 Project Structure

- `data/` — Real estate dataset from UCI
- `figures/` — Generated visualizations
- `report/` — Final PDF report
- `analysis.ipynb` — Main notebook
- `requirements.txt` — Dependencies
- `.gitignore` — Git exclusion rules

---

## 📚 Data Source

UCI Machine Learning Repository:  
👉 [Real estate valuation data set](https://archive.ics.uci.edu/dataset/477/real+estate+valuation)

