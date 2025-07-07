# ML_project_ReDI

## Predicting Fair Market Value for Used Cars 🚗💰

**Problem Statement:**
● Car buyers/sellers seek a reliable way to estimate prices of used cars.
● Used car pricing is complex due to varying depreciation, mileage, and regional factors.
● Goal: Build a predictive model to estimate used car prices using historical Craigslist listings.

**Dataset Used:**
● Source: Kaggle - Craigslist Cars & Trucks
● Records: ~426,000 used car listings
● Features: 26 columns incl. make, model, year, odometer, fuel type, etc.

**Approach:**
● Use XGBoost Regressor (with log-transformed prices and odometer values) to predict car prices