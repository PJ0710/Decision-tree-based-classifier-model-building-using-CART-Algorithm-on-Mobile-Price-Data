# Decision-tree-based-classifier-model-building-using-CART-Algorithm-on-Mobile-Price-Data-in-R
This project is focused on building a decision tree classifier model using the CART (Classification and Regression Tree) algorithm on mobile price data using R. The goal is to use this model to predict the price range of a mobile phone based on its attributes.

## Requirements ##
* R 3.x
* rpart package
* caret package
* tidyverse package
* pROC package

## Data ##
The data used in this project is the mobile price data set that can be found on [Kaggle](https://www.kaggle.com/datasets/iabhishekofficial/mobile-price-classification "Mobile Price Classification | Kaggle"). It includes 20 features such as battery power, clock speed, camera, and RAM, as well as the target variable, the price range.

## Model Building ##
The CART algorithm is used to build the decision tree model using rpart package. The data is split into training and testing sets using caret package, with the data being used for training and for testing in 2:1 ratio random split. The model is then fit on the training data and used to make predictions on the test data.

## Evaluation ##
The model's performance is evaluated using accuracy, precision, recall, and F1 score. These metrics are calculated using the test data and the predictions made by the model.

## Conclusion ##
The decision tree classifier model built using the CART algorithm on mobile price data is able to accurately predict the price range of a mobile phone based on its attributes. This model can be used to assist mobile phone manufacturers and sellers in pricing their products.

## Usage ##
1. Clone the repository
2. Install the required packages
3. Run the R script
4. Follow the instructions on the script to understand the code and the analysis

Note: Make sure you have the required data in the same folder as the script.
