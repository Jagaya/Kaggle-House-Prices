# Kaggle-House-Prices
Collection of different ML-Models used on the House-Prices challenge of Kaggle.
Designed as an experimental environment and not cleaned.

Current project is the design of a complex pipeline to bundle several pre-processing steps.
Implemented:
  1. categorical data:
    1.1. dropNA
    1.2. fillNA
    1.3. feature selection
    1.4. OneHotEncoding
    1.5. OrdinalEncoding
  2. numerical data
    2.1. dropNA
    2.2. fillNA
    2.3. feature selection
    2.4. feature engeneering (sum)

WIP:

TODO:
  - PCA
  - modular approach for pipeline, instead of one long single cell
  - optimization via optuna
