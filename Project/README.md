# IPL Powerplay Score Prediction

Course project for **EE3111: Statistics** (Jan–May 2026).

## Overview

Developed a machine learning model to predict the total runs scored by an IPL team at the end of the 6-over powerplay, using ball-by-ball data from the first 3 overs and historical match information.

## Methodology

- **Data processing:** Parsed historical IPL ball-by-ball data and match metadata to construct a prediction dataset.
- **Feature engineering:** Extracted match-state statistics, batter and bowler performance metrics, venue statistics, and batter–bowler head-to-head statistics.
- **Model development:** Trained and evaluated XGBoost and Random Forest regressors to predict runs scored during the remaining three overs.
- **Ensemble strategy:** Combined the models using a score-dependent threshold to leverage their complementary predictive strengths.
- **Evaluation:** Compared models using Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE), with analysis of feature correlations, feature importance, and threshold selection.

## Files

- `EE3111_project.pdf` — Project problem statement and evaluation requirements.
- `IPL_score_predictor.ipynb` — Data processing, feature engineering, model training, evaluation, and analysis.

## Objective

Build a data-driven predictor for IPL powerplay scores by leveraging historical cricket statistics and comparing machine learning approaches.


