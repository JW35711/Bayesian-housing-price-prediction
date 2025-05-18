# 🏡 Bayesian Housing Price Prediction

This project applies **Bayesian Linear Regression** to predict housing unit prices in Taipei, Taiwan, using real-world data. Beyond point predictions, it captures **uncertainty** through credible intervals and posterior predictive checks — providing a complete probabilistic view.

Built with Python, visualized with love.

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
<pre><code> ``` . ├── data/ # Real estate dataset (from UCI) ├── figures/ # Visualizations ├── report/ # Final project report ├── analysis.ipynb # Core notebook ├── requirements.txt # Python dependencies ├── .gitignore # Git ignore rules └── README.md # You are here ``` --- ## 📸 Sample Visualizations | Predicted vs Actual | Posterior Predictive Check | |---------------------|----------------------------| | ![](figures/figure1.png) | ![](figures/figure3.png) | --- ## 🚀 Getting Started ```bash # Clone the repo git clone https://github.com/JW35711/Bayesian-housing-price-prediction.git # Install dependencies pip install -r requirements.txt # Run the notebook jupyter notebook analysis.ipynb ``` --- ## 📚 Data Source > **Real estate valuation data set** > UCI Machine Learning Repository > https://archive.ics.uci.edu/dataset/501 --- ## 🧠 Author Built by **Zijie Wang** With Huan Li Course: *Bayesian Statistics & Data Analysis* --- ## ✨ License For academic and learning use only. </code></pre>
