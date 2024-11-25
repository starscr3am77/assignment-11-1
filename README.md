# assignment-11-1
Practical Application Assignment 11.1

# Business Understanding
Given the shape of the dataset, use price as the dependent variable and predict car prices using regression techniques. Identify which features
significantly impact car prices. The independent variables you will use will include year, manufacturer, condition, cylinders, fuel and odometer.

# Data Understanding
In order to get a better understanding of the data, we'll first explore the dataset using the info and head functions. 
We'll then search for missing values using is_null()
We can also check for duplicates using the duplicated() function
We can then look for data consistency issues using the unique() function
The next step would be to look for any outliers in the data
Once the data is fairly clean we can look at feature distributions
Then we'll look for relationships between different variables and look for patterns
And lastly, we'll look at feature relevancy

# Evaluation
Vehicle Age: This is a primary determinant of price. Newer cars typically have higher prices due to lower wear and tear and modern features.
Market Saturation: The clustering of prices below $20,000 suggests a dominant market for affordable used cars.
Outliers in Older Cars: Some older vehicles may have collector’s value or other unique attributes maintaining higher prices.

# Deployment
Based on the data our recommendation to the dealers would be to pay less for used car trade-ins as there appears to be significant market saturation.
They should also consider denying older trade-ins as they will find it difficult to sell.
