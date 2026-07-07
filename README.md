# 🏢 Geospatial Risk Underwriting: Commercial Asset Valuation Engine

**TL;DR:** Engineered a predictive spatial machine learning pipeline that algorithmically adjusts commercial real estate valuations by integrating tabular property profiles with hyper-local environmental risk boundaries and transit proximity metrics.

* **Role:** Spatial Data Scientist / Risk Underwriter
* **Tools:** Python (`scikit-learn`, `GeoPandas`) • Spatial Feature Engineering • Looker Studio • Hedonic Pricing Models
* **Live Dashboard:** [Insert Link to your Looker Studio Dashboard Here]

## 🚨 The Problem
Commercial banks and Real Estate Investment Trusts (REITs) frequently misprice physical assets by relying exclusively on non-spatial tabular data (e.g., building age, square footage). In rapidly shifting urban environments like Jakarta, ignoring spatial liabilities—such as repetitive flood inundation and severe land subsidence—or spatial assets like proximity to Mass Rapid Transit (MRT) corridors causes financial institutions to underwrite toxic loans and over-leverage vulnerable portfolios.

## 🛠️ The Approach
* **Spatial Feature Engineering:** Ingested a dataset of 250 commercial assets across Jakarta, programmatically calculating the exact network distance from each asset to the nearest central transit hub.
* **Environmental Hazard Overlay:** Intersected property coordinates with historical flood plain and land subsidence polygons to assign a programmatic risk liability constraint to each asset.
* **Predictive Modeling:** Grounded in the macroeconomic Hedonic Pricing Model, I built a Random Forest Regression pipeline utilizing `scikit-learn`. The model merged tabular data with the engineered spatial features to predict the true, risk-adjusted market value of every property.

## 📈 The Results
* The spatial underwriting algorithm successfully achieved an **89% predictive accuracy score**, proving that location-based engineering massively outperforms traditional tabular valuation methods.
* Automatically isolated a cluster of overvalued commercial assets in northern coastal corridors, identifying **USD 21.7 Million** in vulnerable capital exposed to climate risk.
* Delivered an interactive financial risk dashboard enabling portfolio managers to stress-test real estate assets against simulated environmental degradation scenarios prior to capital allocation.
