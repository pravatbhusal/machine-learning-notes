# Regression Models
Use regression analysis to describe the relationships between a set of independent variables and a continous dependent variable.

Regression analysis produces a regression equation where the coefficients (b0, b1, b2, etc.) represent the relationship
between each independent variable and the continous dependent variable.

Basically, use a regression equation to make predictions by plugging-in independent values to get a dependent value.

### Why Must The Dependent Variable be Continous?
The dependent variable must be continous or the model would attempt to model randomized value, which creates an inaccurate
regression equation that models the independent variables in respect to the dependent variable.

An example of a continous dependent variable is, if x = 1 then y = 5; if x = 2 then y = 10; if x = 3 then y = 15.  
Modelling this equation would be easy with a simple linear regression model: ```y = 5x```

However, if the dependent variable wasn't continous, such as if x = 1 then y = 5; if x = 2 then y = 3; if x = 3 then y = 12.  
This would be more difficult to model with an equation since there seems to be no relationship between x and y.
