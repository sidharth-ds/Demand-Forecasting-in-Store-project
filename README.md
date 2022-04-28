# predicting-Store-Orders-project
* Predicting the number of orders for a product is one of the strategies a business can follow in determining how much to invest in marketing their product.
* If you want to predict the number of orders a company may receive for a particular product, then you need to have historical data about the number of orders received by the company.
* The dataset contains the sales data of supplements that have been collected from Kaggle.

### Dataset:
* It contains 9 features
* Target variable is a continuous variable (quantity of Total_Sales of  each product)

### Data Preprocessing:
* EDA, encodings

### Modelling:
* using XGBoost
* Hyper-parameter tuning :
    * learning rate (as the learning rate (eta) gets lower,it takes many more steps (rounds) to get to the optimum).
    * number of trees (n_estimators)
    
### Evaluation metrics:
* using k-fold Cross-validation:
    * Cross-validation is a technique for evaluating ML models by training several ML models on subsets of the available input data and evaluating them on the complementary subset of the data. 
    * We use cross-validation to detect overfitting.
* We got a R2 score of 60% which is average.

### Improvements:
* We can futher tune the model using "Gridsearch"
* IT looks for an optimal combination of hyperparameter values in a way that it can further improve the performance of a model.
* Using k-fold cross-validation in combination with grid search is a very useful strategy to improve the performance of a machine learning model by tuning the model hyperparameters.
