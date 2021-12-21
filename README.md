## House Prices - Advanced Regression Techniques (Ames, Iowa Housing Dataset)

### By Joy Moglia, Irene Shaffer, Hanan Sukenik

Our project seeks to create a model to predict housing prices using the Ames, Iowa housing dataset from Kaggle. The dataset includes 79 explanatory variables describing residential homes in Ames, Iowa. Kaggle provides training and test datasets and a text file with a description of the data.

kaggle competition page: https://www.kaggle.com/c/house-prices-advanced-regression-techniques

### Notebook Outline:
- Section 1: EDA
- Section 2: Pre-Processing
- Section 3: Feature Selection
- Section 4: Split Training Data into Train (X_train, y_train) and Dev (X_test, y_test) Sets
- Section 5: Find the Best Model
- Section 6: Hyperparameter Tuning
- Section 7: Generate Predictions using Test Data

In Section 1 of this notebook, we explore the training and test data. In Section 2, we pre-process the data by inspecting the training data for NaN values, creating dummy variables for categorical data, and using scaler transforms to standardize and normalize numerical input variables. In Section 3, we do feature selection. In Section 4, we split our training data into train and dev sets. In Section 5, we test several models: random forest, gradient boosting for regression, support vector, and linear regression. We select the model with the best R-squared value. In Section 6, we conduct hyperparameter tuning using GridSearchCV. In Section 7, we use our final model to generate predictions on the test dataset.

The project includes several files:

- Team3_JoyHananIrene_Final.ipynb - A Jupyter Notebook containing all of the code (Python)
- test.csv- Test dataset
- train.csv- Train dataset
- data_description.txt- Data description text


Enjoy!
