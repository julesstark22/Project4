# Project4

Predicting Housing Prices: Proposal


Introduction: 
The objective of this project is to develop a predictive model that can accurately estimate housing prices. The model will be implemented using Python and will leverage data retrieved from Spark. By analyzing and optimizing the model, we aim to achieve a classification accuracy of at least 75% or an R-squared value of 0.80. 

Data Model Implementation: 
To initiate the project, we will develop a Python script that initializes, trains, and evaluates the predictive model. This script will serve as the foundation for our housing price prediction model. Additionally, we will focus on cleaning, normalizing, and standardizing the data before feeding it into the model. This ensures that the data is consistent and suitable for accurate predictions. Moreover, we will retrieve the necessary data from Spark, depending on availability and feasibility.

Source:
https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

File Names:
Train: train.csv
Test: test.csv

Purpose points: 


Accurate Estimation: The model allows for accurate estimation of housing prices, providing potential buyers, sellers, and real estate professionals with a reliable tool to assess property values. This can aid in making informed decisions regarding buying, selling, or investing in real estate.


Market Analysis By analyzing historical data and current trends, the model can provide insights into the housing market. It will help identify patterns, factors, and variables that influence housing prices, enabling a deeper understanding of market dynamics and assisting in strategic planning.


Risk Management: The model can contribute to risk assessment and management. Lenders and financial institutions can utilize the predictions to evaluate the feasibility of mortgage loans, assess property valuations, and mitigate risks associated with lending.

Data Fields: 

Location and Property
Description
MSSubClass
The building class
MSZoning
The general zoning classification
LotFrontage
Linear feet of street connected to property
LotArea
Lot size in square feet
Street
Type of road access
Alley
Type of alley access
LotShape
General shape of property
LandContour
Flatness of the property
Utilities
Type of utilities available
LotConfig
Lot configuration
LandSlope
Slope of property
Neighborhood
Physical locations within Ames city limits

















Condition and Quality
Description
OverallQual
Overall material and finish quality
OverallCond
Overall condition rating
ExterQual
Exterior material quality
ExterCond
Present condition of the material on the exterior
BsmtQual
Height of the basement
BsmtCond
General condition of the basement
BsmtExposure
Walkout or garden level basement walls
BsmtFinType1
Quality of basement finished area
BsmtFinType2
Quality of second finished area (if present)
HeatingQC
Heating quality and condition
CentralAir
Central air conditioning
Electrical
Electrical system
KitchenQual
Kitchen quality
FireplaceQu
Fireplace quality
GarageQual
Garage quality
GarageCond
Garage condition
PoolQC
Pool quality
Fence
Fence quality
MiscFeature
Miscellaneous feature not covered in other categories










Construction and Building Features
Description
BldgType
Type of dwelling
HouseStyle
Style of dwelling
YearBuilt
Original construction date
YearRemodAdd
Remodel date
RoofStyle
Type of roof
RoofMatl
Roof material
Exterior1st
Exterior covering on house
Exterior2nd
Exterior covering on house (if more than one material)
MasVnrType
Masonry veneer type
MasVnrArea
Masonry veneer area in square feet
Foundation
Type of foundation
Heating
Type of heating
1stFlrSF
First Floor square feet
2ndFlrSF
Second floor square feet
LowQualFinSF
Low quality finished square feet (all floors)
GrLivArea
Above grade (ground) living area square feet
BsmtFullBath
Basement full bathrooms
BsmtHalfBath
Basement half bathrooms
FullBath
Full bathrooms above grade
HalfBath
Half baths above grade
Bedroom
Number of bedrooms above basement level
Kitchen
Number of kitchens
TotRmsAbvGrd
Total rooms above grade (does not include bathrooms)
Fireplaces
Number of fireplaces
GarageType
Garage location
GarageYrBlt
Year garage was built
GarageFinish
Interior finish of the garage
GarageCars
Size of garage in car capacity
GarageArea
Size of garage in square feet
PavedDrive
Paved driveway



OUTDOOR FEATURES
Description
WoodDeckSF
Wood deck area in square feet
OpenPorchSF
Open porch area in square feet
EnclosedPorch
Enclosed porch area in square feet
3SsnPorch
Three season porch area in square feet
ScreenPorch
Screen porch area in square feet
PoolArea
Pool area in square feet
MiscVal
$Value of miscellaneous feature
MoSold
Month Sold
YrSold
Year Sold
SaleType
Type of sale
SaleCondition
Condition of sale


