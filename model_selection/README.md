 # Model Selection
Model selection is the task of selecting a statistical model from a set of candidate models, given the data set.

### Model Selection Algorithms
1. K-Fold Cross Validation

### Ensemble Learning Models
No clue what models to pick? Typically, bagging (Random Forest) and boosting (XGBoost) model are the best to use. These models are also called "ensemble learning" models because they use multiple learners (models) to solve the same problem.

As of 2019 when in doubt, XGBoost is considered a great model to use. To install XGBoost, type:
```conda install -c conda-forge xgboost``` for anaconda or ```pip install xgboost``` for pip

The Python documentation for XGBoost is provided [here](https://xgboost.readthedocs.io/en/latest/python/python_api.html#module-xgboost.sklearn).

# Parameter Tuning
Hyperparameter optimization (or tuning) is the problem of choosing a set of optimal parameters for a statistical model.

### Parameter Tuning Algorithms
1. Grid Search

# Bias-Variance Trade-Off
<img src="images/bias_variance_tradeoff.png" height="50%" width="50%"></img>

https://www.endtoend.ai/blog/bias-variance-tradeoff-in-reinforcement-learning/

### Variance for Dependent Variable (Predicted Values)
How scattered are the predicted values from the actual values?
- High Variance: Model performs great on the trained data set, but not well on the testing data set

High Variance causes the machine learning model to overfit the data.
- This implies there's "random noise" (outlier) present in the training data
    - When a model is high-variant, then it becomes very flexible (fitted) to the training data points, which would be a problem when making predictions with an unknown or a test data set

### Bias for Dependent Variable (Predicted Values)
How far off are the predicted values from the actual values?
- High Bias: The average predicted values are very far off from the actual values

High Bias causes the machine learning model to underfit the data.
- This means the model is too simple and doesn't capture the complexity of the data set