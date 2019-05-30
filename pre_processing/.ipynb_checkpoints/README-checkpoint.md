# Pre-Processing
Pre-Processing is needed to clean the data set before we fit it into a statistical model.

### Few Methods of Pre-Processing
1. Encoding Categorical Variables
2. Feature Selection (Dimensionality Reduction)
3. Feature Extraction (Dimensionality Reduction)
4. Splitting Training and Testing Sets
5. Feature Scaling

And many others!

# Feature Selection
A dimensional reduction technique where you select only certain features to use in a machine learning model.

These "features" are the independent variables, and feature selection will help reduce the number of independent variables by determining only the significant variables that contribute to the model.

### Few Methods of Feature Selection
1. Removing features with missing values (or replacing their values with the mean).  
2. Removing features with low variance.  
3. Removing features that are highly correlated to other features.  
4. Removing features that accept a null hypothesis.  

And many others!

# Bias-Variance Trade-Off
If there's more bias to a model, then there's less variance to it.  
If there's less bias to a model, then there's more variance to it.  

<img src="images/bias_variance_tradeoff.png" height="150%" width="150%"></img>
- https://medium.com/datadriveninvestor/bias-and-variance-in-machine-learning-51fdd38d1f86

### Bias
How far off are the predicted values from the actual values?
- High Bias: The average predicted values are very far off from the actual values

High Bias causes the machine learning model to underfit the data.
- This means the model is too simple and doesn't capture the complexity of the data set

### Variance
How scattered are the predicted values from the actual values?
- High Variance: Model performs great on the trained data set, but not well on the testing data set

High Variance causes the machine learning model to overfit the data.
- This implies there's "random noise" present in the training data
    - Random Noise can also be referred to as "outlier" data points
    - When a model is high-variant, then it becomes very flexible (fitted) to the training data points, which would be a problem when making predictions with an unknown or a test data set
    
