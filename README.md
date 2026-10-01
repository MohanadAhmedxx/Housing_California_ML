# Housing_California_ML
Machine learning project using California housing dataset obtained from scikit-learn library dataset section

This projects goes to predict the medianHouse value (( the average price of a house  in certain residential area)) in 100,000$ based on multiple variables like the average of MedianIncome, HouseAge, AverageRooms, AverageBedrooms, Population, AverageOccupancy, latitude and longitude . 

# Basic Process in this project 
- Getting the dataset from sikit-learn library by 
from sklearn.dataset import fetch_california_housing .
- Measurig the multicolinearity between variables using corr() in pandas, visualizing it using heatmap.
- Using XGBoost for modeling using XGBRegressor() and StandardScaler() in multiple ranges between features for normalizing all data to make the model more rapidly .
- Using pipeline to combine  machine-learning steps into one workflow and make sure they are applied in the correct order.

#### housing California dataset 

dimension : 20640rows × 9columns
Test size = 0.3 × Train size 

R_squared for x_test prediction :  0.8047279130760685
absolute mean error for x_test prediction :  0.31150292865712204


