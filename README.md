# Lottery Data Analysis

This project focuses on analyzing lottery data, where prizes are distributed to winners among individuals who purchase a chance. The dataset used for this analysis consists of information related to lottery drawings, including the date, weekday, winning numbers, Powerball number, Powerplay value, and jackpot amount. The dataset has a shape of (950, 6), indicating 950 records and 6 columns.

## Dataset

The dataset contains the following columns:

1. **Date**: The date of the lottery drawing.
2. **Weekday**: The weekday on which the lottery drawing took place.
3. **Winning-numbers**: The winning numbers for the lottery drawing.
4. **Powerball**: The Powerball number associated with the drawing.
5. **Powerplay**: The Powerplay value for the drawing.
6. **Jackpot**: The amount of the jackpot for the drawing.

## Analysis Algorithms

In this project, three regression algorithms were applied to the lottery dataset:

1. **Linear Regression**: This algorithm fits a linear equation to the data by minimizing the mean squared error (MSE) between the predicted and actual values.
2. **Ridge Regression**: Ridge regression is a regularization technique that adds a penalty term to the linear regression equation, helping to reduce overfitting.
3. **Lasso Regression**: Lasso regression is another regularization technique that uses a different penalty term to reduce the complexity of the model.

## Analysis Findings

After running the regression algorithms, it was observed that the accuracy of the models, as indicated by the high MSE values, was not satisfactory. To improve the model performance, a cross-validation approach was applied specifically to the linear regression model. This approach helps in assessing the model's performance by splitting the data into multiple subsets and training the model on different combinations of the subsets. By applying cross-validation, the performance of the linear regression model improved significantly.

The results of the cross-validated linear regression model are provided below:

- MSE (Mean Squared Error): [Insert MSE value]
- R-squared Score: [Insert R-squared score]

## Project Analysis Steps

This project involves the following analysis steps:

1. **Data Cleaning**: The dataset is examined for any missing values or inconsistencies and cleaned if necessary.
2. **Outlier Detection**: Outliers are identified and handled appropriately to ensure they do not affect the analysis.
3. **Algorithm Implementation**: Linear regression, ridge regression, and lasso regression are applied to the dataset.
4. **Model Evaluation**: The accuracy of the regression models is assessed using the mean squared error (MSE) metric.
5. **Cross-Validation**: Cross-validation is applied specifically to the linear regression model to enhance its performance.
6. **Conclusion**: A summary of the findings and recommendations for further improvements are provided.

## Conclusion

This project aimed to analyze lottery data using regression algorithms to predict outcomes and assess their accuracy. While the initial regression models showed suboptimal performance, applying cross-validation to the linear regression model significantly improved its predictive capabilities. It is important to note that lottery data analysis involves various factors, and further enhancements and refinements to the models can be explored.

Please refer to the project code and analysis results for detailed implementation and insights.
