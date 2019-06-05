# Classification Models
Use classification to predict the category of a data point.

### Example of a Classification Problem
Let's give a simple Binary Classifiation problem: we want to classify if an image is of a Dog or a Cat.

We can look at multiple factors that distinguish a Dog from a Cat:
- Pointiness of ears
- Snout length
- Eye width
- etc.

These features (independent variables) can help us classify the image in the classification model.

# Model Selection
### If the problem is linear:
- Logistic Regression
    - When you want to observe your predictions by probability
- Support Vector Machine (RBF Linear)
    - When you want to adapt your predictions to your data set

### If the problem is non-linear:
- K-Nearest Neighbors
    - When you have many data points within a small dimension
- Naive Bayes
    - When you want to observe your predictions by probability
    - When your independent variables have little to no correlation
- Decision Tree Classification
    - When you want a clear interpretation of model results
- Random Forest Classification
    - When you want a high performance, with less need for interpretation
- Support Vector Regression (RBF Kernel)
    - When you want to adapt your predictions to your data set

If you're unsure what model to use, perform a from k-Fold Cross Validation and use the model that shows the best results.

If you want to improve your model's performance, perform hyperparameter tuning.