# wine-prediction

### Overview

This wine data was taken from https://www.winemag.com/?s=&drink_type=wine.

Predict the price of a bottle of wine based on various features.

### Instructions

- Fork and Clone this repository
- Read into Pandas, https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.read_json.html
- Perform EDA
- Split Data into Train and Test datasets
- Standardize features if necessary
- Perform a `Ridge Regression` cross-validation on various values of `alpha`
- Plot `R2` vs various levels of `alpha` on training and validation sets
- Plot `beta values` vs various levels of alpha
- Choose the best `alpha`
- Perform final model training using best `alpha`
- Get final `R2` score for test dataset
- Add and commit any and all changes
- Push your results back to your forked repository

### Data Dictionary

- country: The country that the wine is from
- description
- designation: The vineyard within the winery where the grapes that made the wine are from
- points: The number of points WineEnthusiast rated the wine on a scale of 1-100 (only reviews with score >= 80)
- price: The cost for a bottle of the wine
- province: The province or state that the wine is from
- region_1: The wine growing area in a province or state (ie Napa)
- region_2: Sometimes there are more specific regions specified within a wine growing area
- taster_name
- taster_twitter_handle
- title: The title of the wine review, which often contains the vintage if you're interested in extracting that feature
- variety: The type of grapes used to make the wine (ie Pinot Noir)
- winery: The winery that made the wine
