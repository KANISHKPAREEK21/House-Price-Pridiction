# House-Price-Pridiction
It is a machine learning project
## Overview
This repository contains code and resources for a house price prediction project.Predicting house prices is a common and valuable machine learning task in the real estate and finance industries. Accurate predictions can help buyers, sellers, and investors make informed decisions.  In this project, we aim to build a machine learning model that can predict the prices of houses based on various features such as size, number of bedrooms, location, and more. 

## Dataset

We use the [House Price Dataset]([https://example.com/dataset](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data)) for training and testing our model. 
### File descriptions
- `train.csv`: The training set.
- `test.csv`: The test set.
- `data_description.txt`: A full description of each column, originally prepared by Dean De Cock but lightly edited to match the column names used here.
- `sample_submission.csv`: A benchmark submission from a linear regression on year and month of sale, lot square footage, and the number of bedrooms.
### Data fields
Here's a brief version of what you'll find in the data description file.

- SalePrice: The property's sale price in dollars. This is the target variable that you're trying to predict.
- MSSubClass: The building class.
- MSZoning: The general zoning classification.
- LotFrontage: Linear feet of street connected to the property.
- LotArea: Lot size in square feet.
- Street: Type of road access.
- Alley: Type of alley access.
- LotShape: General shape of the property.
- LandContour: Flatness of the property.
- Utilities: Type of utilities available.
- LotConfig: Lot configuration.
- LandSlope: Slope of the property.
- Neighborhood: Physical locations within Ames city limits.
- Condition1: Proximity to the main road or railroad.
- Condition2: Proximity to the main road or railroad (if a second is present).
- BldgType: Type of dwelling.
- HouseStyle: Style of dwelling.
- OverallQual: Overall material and finish quality.
- OverallCond: Overall condition rating.
- YearBuilt: Original construction date.
- YearRemodAdd: Remodel date.
- RoofStyle: Type of roof.
- RoofMatl: Roof material.
- Exterior1st: Exterior covering on the house.
- Exterior2nd: Exterior covering on the house (if more than one material).
- MasVnrType: Masonry veneer type.
- MasVnrArea: Masonry veneer area in square feet.
- ExterQual: Exterior material quality.
- ExterCond: Present condition of the material on the exterior.
- Foundation: Type of foundation.
- BsmtQual: Height of the basement.
- BsmtCond: General condition of the basement.
- BsmtExposure: Walkout or garden level basement walls.
- BsmtFinType1: Quality of basement finished area.
- BsmtFinSF1: Type 1 finished square feet.
- BsmtFinType2: Quality of the second finished area (if present).
- BsmtFinSF2: Type 2 finished square feet.
- BsmtUnfSF: Unfinished square feet of basement area.
- TotalBsmtSF: Total square feet of basement area.
- Heating: Type of heating.
- HeatingQC: Heating quality and condition.
- CentralAir: Central air conditioning.
- Electrical: Electrical system.
- 1stFlrSF: First Floor square feet.
- 2ndFlrSF: Second-floor square feet.
- LowQualFinSF: Low-quality finished square feet (all floors).
- GrLivArea: Above-grade (ground) living area square feet.
- BsmtFullBath: Basement full bathrooms.
- BsmtHalfBath: Basement half bathrooms.
- FullBath: Full bathrooms above grade.
- HalfBath: Half baths above grade.
- Bedroom: Number of bedrooms above basement level.
- Kitchen: Number of kitchens.
- KitchenQual: Kitchen quality.
- TotRmsAbvGrd: Total rooms above grade (does not include bathrooms).
- Functional: Home functionality rating.
- Fireplaces: Number of fireplaces.
- FireplaceQu: Fireplace quality.
- GarageType: Garage location.
- GarageYrBlt: Year the garage was built.
- GarageFinish: Interior finish of the garage.
- GarageCars: Size of the garage in car capacity.
- GarageArea: Size of the garage in square feet.
- GarageQual: Garage quality.
- GarageCond: Garage condition.
- PavedDrive: Paved driveway.
- WoodDeckSF: Wood deck area in square feet.
- OpenPorchSF: Open porch area in square feet.
- EnclosedPorch: Enclosed porch area in square feet.
- 3SsnPorch: Three-season porch area in square feet.
- ScreenPorch: Screen porch area in square feet.
- PoolArea: Pool area in square feet.
- PoolQC: Pool quality.
- Fence: Fence quality.
- MiscFeature: Miscellaneous feature not covered in other categories.
- MiscVal: $Value of miscellaneous feature.
- MoSold: Month Sold.
- YrSold: Year Sold.
- SaleType: Type of sale.
- SaleCondition: Condition of sale.
