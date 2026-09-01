# Hi, I'm Mario
### Data Scientist / Data Analyst

I build end-to-end Machine Learning systems, Time Series models, and Customer Analytics pipelines designed to solve practical business problems and drive revenue growth.

- **LinkedIn:** [linkedin.com/in/your-profile](www.linkedin.com/in/mario-rigoni-044b98404)
- **Email:** mrigoni.vi@gmail.com
- **Location:** Italy, Vicenza

---

## Technical Toolkit

| Category | Technologies & Tools |
| :--- | :--- |
| **Languages & Core** | Python (Pandas, NumPy, Polars), SQL (PostgreSQL, BigQuery), Bash, Git |
| **Machine Learning & Stats** | Scikit-Learn, LightGBM, XGBoost, CatBoost, SHAP, Statsmodels |
| **Analytics & Visualization** | Plotly, Seaborn, Matplotlib, Tableau, Power BI |
| **Environments & Workflow** | Google Colab, Jupyter, Docker, Linux, GitHub Actions |

---

## Featured Portfolio Projects

| Project | Domain | Architecture & Stack | Key Metrics & Impact | Link |
| :--- | :--- | :--- | :--- | :---: |
| **Early Warning Churn System** | SaaS / Telco | XGBoost, SHAP, Class-Weighted Learning | **ROC-AUC: 0.84** • €25k+ simulated preserved CLV | [Repo ↗️](https://github.com/MRigoni10/telco-churn-explainable-ai) |
| **Multi-Category Demand Forecasting** | Supply Chain / Retail | LightGBM, Lag/Rolling Features, Multi-Series | **WAPE: ~19%** • Dynamic Safety Stock Sizing | [Repo ↗️](https://github.com/MRigoni10/demand-forecasting-lightgbm) |
| **E-Commerce Customer Segmentation** | E-Commerce / CRM | RFM Framework, Log-Scaling, K-Means Clustering | **Silhouette: 0.42** • 4 Actionable Cohort Strategies | [Repo ↗️](https://github.com/MRigoni10/customer-segmentation-rfm) |

---

## Project Deep-Dives

### 1. [Telco Customer Churn & Explainable AI (SHAP)](https://github.com/MRigoni10/telco-churn-explainable-ai)
* Built an end-to-end early warning churn detection pipeline on ~7k customer records.
* Handled class imbalance natively via XGBoost `scale_pos_weight` and validated using stratified holdouts.
* Integrated SHAP TreeExplainer for macro risk rankings and micro-level customer intervention diagnostics.

### 2. [Multi-Category Demand Forecasting & Inventory Control](https://github.com/MRigoni10/demand-forecasting-lightgbm)
* Developed a unified LightGBM multi-series model to forecast weekly demand across top e-commerce categories.
* Engineered autoregressive lags, rolling moving averages, and calendar seasonalities with zero lookahead bias.
* Evaluated against a strict 10-week out-of-time test split to establish dynamic Reorder Points (ROP).

### 3. [E-Commerce Customer Segmentation (RFM + K-Means)](https://github.com/MRigoni10/customer-segmentation-rfm)
* Cleaned and aggregated 500k+ international retail transactions into customer-level RFM metrics.
* Corrected power-law skewness via logarithmic transformation and scaled features for stable clustering.
* Extracted 4 distinct customer cohorts (Champions, Loyal, At Risk, Hibernating) to personalize CRM retention campaigns.

---

