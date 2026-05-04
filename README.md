California Housing Price Prediction
ISOM 835 — Predictive Analytics & Machine Learning | Suffolk University
A regression analysis using the California Housing dataset to identify what drives residential property values across California — and to build a model that estimates median home values from census block-level data.
Dataset
California Housing Prices via Kaggle — 20,640 observations, 10 features, sourced from the 1990 U.S. Census. Target variable: median_house_value.
Approach

Exploratory data analysis across six visualizations
Feature engineering: three ratio-based features derived from raw block-level counts
Compared Linear Regression (baseline) and Random Forest models
Random Forest achieved R² = 0.807 and RMSE = $50,331, outperforming the baseline by ~$22K in prediction error

Key Finding
Median income is the strongest predictor of home value by a wide margin. Ocean proximity and household-level ratio features follow. Raw block-level counts (total rooms, total bedrooms) rank near the bottom.
Tools
Python · Google Colab · pandas · numpy · scikit-learn · matplotlib · seaborn
