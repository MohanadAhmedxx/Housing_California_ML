# Housing_California_ML
Machine learning project using California housing dataset obtained from scikit-learn library dataset section

This projects goes to predict the medianHouse value (( the average price of a house  in certain residential area)) in 100,000$ based on multiple variables like the average of MedianIncome, HouseAge, AverageRooms, AverageBedrooms, Population, AverageOccupancy, latitude and longitude . 

# Basic Process in this project 
- Getting the dataset from sikit-learn library by 
from sklearn.dataset import fetch_california_housing .
- Measurig the multicolinearity between variables using corr() in pandas, visualizing it using heatmap.
- Using XGBoost for modeling using XGBRegressor() and StandardScaler() in multiple ranges between features for scaling to a comparable range.
- Using pipeline to combine  machine-learning steps into one workflow and make sure they are applied in the correct order.

## About housing California dataset 

#### dimension : 20640rows × 9columns

#### Test size = 30% of the data 

#### R² for x_train prediction : 0.9425522464386936
#### MAE for x_train prediction :  0.1853034281894106
#### R² for x_test prediction :  0.8047279130760685
#### MAE for x_test prediction :  0.31150292865712204

The model achieves a higher R² score on the training data (0.943) than on the test data (0.805). Similarly, the MAE is lower on the training set than on the test set.
This difference indicates that the XGBRegressor has learned the training data very well but performs less accurately on unseen data. Therefore, the model shows some degree of overfitting.
However, the test R² of 0.805 indicates that the model still generalizes reasonably well to unseen data.

### How to run ?

1. Download or clone the repository.
2. Make sure Python and Jupyter Notebook are installed.
3. Install the required libraries.
4. Open the .ipynb file using Jupyter Notebook.
5. Run the cells from top to bottom.

* Dataset can't be used unless you open the internet if it is from sikit-learn library generally. 


