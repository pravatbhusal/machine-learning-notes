# Regression Models
Use regression analysis to describe the relationships between a set of independent variables and a dependent variable.

We can use training data to train a regression model to approximate a predicted value.

### Example of a Regression Problem
Let's say we want to predict the salary of a person based on age.

We can model age (independent variable) over salary (dependent variable) by fitting it through a regression model.

Once we fit the data set through the model, we can predict the amount of salary a person earns based on age.

# Model Selection
### If the problem is linear:
- Simple Linear Regression
    - When you have 1 feature (single independent variable)
- Multiple Linear Regression
    - When you have several features (several independent variables)
- Polynomial Regression
    - When the the dependent values grow like a polynomial curve
- Support Vector Machine (RBF Linear)
    - When you want to adapt your predictions to your data set

### If the problem is non-linear:
- Decision Tree Regression
    - - When you want a clear interpretation of model results
- Random Forest Regression
    - When you want a high performance, with less need for interpretation
- Support Vector Regression (RBF Kernel)
    - When you want to adapt your predictions to your data set

If you're unsure what model to use, perform a from k-Fold Cross Validation and use the model that shows the best results.

If you want to improve your model's performance, perform hyperparameter tuning.