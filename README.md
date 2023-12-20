# linear-polynomial_regression1

The goal of this problem is for you to explore how to properly analyze, visualize, split, clean and format data and perform linear regression, polynomial regression and regularization. You will use the happiness data (e.g. happiness data.csv) located here Download here. The data consists of the following attributes:

Country name: name of the country
Year: year data was collected
Life ladder: information about how happy people are
Log GDP per capita: market values of goods and services in a country
Social support: how people feel they are supported by those around them
Healthy life expectancy: rank of the country based on the happiness score
Freedom to make life choices: how much freedom contributes to one’s feeling of happiness
Generosity: have you donated money
Perceptions of corruption: how do people perceive that there is corruption
Positive affect: do you feel happiness, laughter and enjoyment?
Negative affect: do you feel worry, anger or sadness?
Your task is to build a model that given attributes/features: Country name, Log GDP per capita, Social support, Freedom to make life choices, Generosity, Perceptions of corruption, Positive affect and Negative affect, Healthy life expectancy predicts Life ladder (note that this means that you can ignore Year).

IMPLEMENTED BELOW POINTS
1. Data Summary:

The dataset contains information about happiness in different countries, with attributes such as Country name, Year, Life ladder, Log GDP per capita, Social support, Healthy life expectancy, Freedom to make life choices, Generosity, Perceptions of corruption, Positive affect, and Negative affect.
The data is continuous and categorical.
The task is to predict "Life ladder" based on selected features.
2. Data Visualization and Summary:

Displayed statistical values and visualizations for each attribute.
Noticed that "Log GDP per capita," "Social support," and "Healthy life expectancy" have right-skewed distributions.
"Perceptions of corruption" has a long tail, indicating potential outliers.
Attributes with skewed distributions might benefit from log transformation.
3. Attribute Relationships Analysis:

Computed Pearson Correlation Coefficient (PCC) between data attributes and "Life ladder."
Generated scatter plots to visualize relationships.
Identified strong positive correlations between "Life ladder" and attributes like "Log GDP per capita," "Social support," and "Healthy life expectancy."
Identified potential negative correlation between "Life ladder" and "Perceptions of corruption."
Considered features with high correlation for model training.
4. Data Splitting:

Selected 20% of the data for testing, ensuring randomness in the split.
Verified representativeness of the test portion by comparing the distribution of key features with the entire dataset.
5. Linear Regression with Regularization:

Trained Linear Regression models using closed-form solution (Normal Equation), SGD, Ridge, Lasso, and Elastic Net regularization.
Explored impact of penalty term values.
Analyzed impact of batch size and learning rate for SGD.
Displayed training and validation loss for SGD.
6. Polynomial Regression:

Trained Polynomial Regression models and explored validation loss.
Investigated potential overfitting or underfitting.
7. Model Evaluation on Test Data:

Made predictions on the test data using the trained models.
Summarized performance using appropriate evaluation metric.
Discussed results and considered further exploration to increase performance, such as hyperparameter tuning and feature engineering.
This analysis provides insights into the data, relationships, and model performance, facilitating a comprehensive understanding of the happiness dataset.
