App Rating Predictor - Google Play Store
This project builds a machine learning model to predict app ratings using metadata from the Google Play Store. The goal is to identify promising apps worth promoting—boosting visibility for quality new entrants in the market.

🔍 Problem Statement
Google aims to spotlight high-potential apps via enhanced recommendations. To support this initiative, we predict which apps are likely to achieve high user ratings using features such as size, reviews, price, install count, category, and content rating.

⚙️ Workflow Summary
Data Cleaning: Size unit conversion, price and installs parsing, sanity checks

Exploratory Data Analysis: Visualizing outliers and distributions

Feature Engineering: Log transformation, encoding categorical variables

Model Building: Linear Regression to predict app ratings

Evaluation: R² on train and test sets
