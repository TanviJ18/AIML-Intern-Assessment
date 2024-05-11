## Machine Learning Model Comparison
In this analysis, seven machine learning models were utilized to predict the sourcing cost. The models included:

1. AdaBoost

2. Decision Tree

3. Extra Tree Regression

4. K-Nearest Neighbors (KNN)

5. Linear Regression

6. Random Forest

7. XGBoost

## Evaluation Metrics
The evaluation of model performance was based on the following metrics:

1. **Mean Absolute Error (MAE)**: MAE quantifies the average magnitude of errors between predicted and actual values, making it a straightforward measure of model accuracy.
2. **Mean Squared Error (MSE)**: MSE calculates the average squared differences between predicted and actual values, offering a more detailed assessment of prediction accuracy by penalizing larger errors more heavily.

3. **R2 Score**: R2 Score evaluates the goodness of fit of a regression model by measuring the proportion of the variance in the dependent variable that is explained by the independent variables, providing insight into the model's predictive capability relative to a simple mean-based model. As a value between 0 and 1, R2 Score of 1 indicates perfect prediction, while a score closer to 0 suggests that the model does not explain much of the variability in the dependent variable beyond the mean.

## Conclusion
In conclusion, the analysis of seven machine learning models for predicting sourcing cost revealed varying degrees of performance across different algorithms. Random Forest emerged as the top performer, exhibiting the lowest error metrics and highest R2 Score, followed closely by the Decision Tree model. K-Nearest Neighbors (KNN) also demonstrated competitive predictive accuracy, ranking third among the models considered. However, Linear Regression showed less favorable performance compared to the other models, indicating limitations in its predictive capability for this task.
