# House Prices - Advanced Regression Techniques - Prediction Competition (Kaggle)

This project uses linear regression, Ridge, and Lasso models to predict house prices based on selected features from the House Prices dataset. It includes data cleaning, feature selection, model training, evaluation, and final predictions on the test set.

Run in Google Colab: https://colab.research.google.com/drive/1h5iAn4FqhaRnawwTbtvkK-NQxBRhL12X?usp=sharing

-----------------------------------------------------------------------------------------------------------------------------

**File Descriptions**

*houseprices_jupyter.pynb*: Jupyter Notebook file containing the full machine learning workflow

*train_house.csv*: The training dataset used to train and validate the models 

*test_house.csv*: The test dataset used for making final predictions

*lasso_predictions.csv*: CSV file containing the final predicted house prices generated using the best Lasso regression model

-----------------------------------------------------------------------------------------------------------------------------

**Make sure to replace the following lines with your own file paths:**



df = pd.read_csv('/content/drive/MyDrive/train_house.csv')

test_data = pd.read_csv('/content/drive/MyDrive/test_house.csv')
