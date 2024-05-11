# Machine Learning Model Comparison
In this analysis, seven machine learning models were utilized to predict the sourcing cost. The models included:

1. **AdaBoost**: AdaBoost (Adaptive Boosting) is an ensemble learning method that combines multiple weak learners (typically decision trees) to create a strong classifier. It works by iteratively training weak learners on the data, with subsequent learners focusing more on the instances that were misclassified by previous ones. AdaBoost assigns weights to training instances, with more weight given to difficult-to-classify instances, allowing subsequent models to focus on improving their performance on these instances.

3. **Decision Tree**: Decision trees are versatile and widely used in machine learning for both classification and regression tasks.
They work by recursively splitting the data based on features, aiming to create homogeneous subsets with respect to the target variable.
Decision trees are interpretable and easy to visualize, making them useful for understanding the decision-making process of the model.

4. **Extra Tree Regression**: Extra Trees (Extremely Randomized Trees) is an ensemble learning method similar to Random Forest.
It builds multiple decision trees on random subsets of the training data and uses random thresholds for splitting nodes.
Extra Trees further randomizes the feature selection process compared to Random Forest, leading to potentially higher variance but also reduced bias.

5. **K-Nearest Neighbors (KNN)**: KNN is a non-parametric and instance-based learning algorithm used for classification and regression tasks.
It makes predictions by identifying the k nearest data points (neighbors) to a query instance and averaging their target values (for regression) or selecting the majority class (for classification).
KNN is simple and intuitive but may suffer from high computational costs and sensitivity to the choice of k.

6. **Linear Regression**: Linear regression is a classic and widely used statistical method for modeling the relationship between a dependent variable and one or more independent variables.
It assumes a linear relationship between the input features and the target variable and estimates the coefficients that best fit the observed data.
Linear regression is interpretable and efficient but may not capture complex nonlinear relationships in the data.

7. **Random Forest**: Random Forest is an ensemble learning method that builds multiple decision trees and combines their predictions through averaging (for regression) or voting (for classification).
It introduces randomness during the tree-building process by sampling both data points and features, reducing overfitting and improving generalization performance.
Random Forest is robust, scalable, and often achieves high performance across a wide range of datasets.

8. **XGBoost**: XGBoost (Extreme Gradient Boosting) is an optimized and efficient implementation of gradient boosting machines.
It builds an ensemble of weak learners (typically decision trees) sequentially, with each new learner correcting the errors of the previous ones.
XGBoost employs regularization techniques, tree pruning, and parallel computation to enhance performance and prevent overfitting, making it a popular choice for structured/tabular data tasks.

# Evaluation Metrics
The evaluation of model performance was based on the following metrics:

1. **Mean Absolute Error (MAE)**: MAE quantifies the average magnitude of errors between predicted and actual values, making it a straightforward measure of model accuracy.
2. **Mean Squared Error (MSE)**: MSE calculates the average squared differences between predicted and actual values, offering a more detailed assessment of prediction accuracy by penalizing larger errors more heavily.

3. **R2 Score**: R2 Score evaluates the goodness of fit of a regression model by measuring the proportion of the variance in the dependent variable that is explained by the independent variables, providing insight into the model's predictive capability relative to a simple mean-based model. As a value between 0 and 1, R2 Score of 1 indicates perfect prediction, while a score closer to 0 suggests that the model does not explain much of the variability in the dependent variable beyond the mean.

# Conclusion
In conclusion, the analysis of seven machine learning models for predicting sourcing cost revealed varying degrees of performance across different algorithms. Random Forest emerged as the top performer, exhibiting the lowest error metrics and highest R2 Score, followed closely by the Decision Tree model. K-Nearest Neighbors (KNN) also demonstrated competitive predictive accuracy, ranking third among the models considered. However, Linear Regression showed less favorable performance compared to the other models, indicating limitations in its predictive capability for this task.
