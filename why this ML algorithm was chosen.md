# We choose Random forest model. why? 
We selected Random Forest Regressor as the best performing model among Linear Regression, Decision Tree, and Gradient Boosted Trees based on evaluation metrics such as RMSE and R² score.

Random Forest showed the best balance between accuracy and stability because it builds multiple decision trees and combines their results, which reduces overfitting and improves generalization on unseen data.

Unlike Linear Regression, which assumes a linear relationship between features and the target, Random Forest can capture complex non-linear patterns in the data. It also performed better than a single Decision Tree, which is more sensitive to noise and can easily overfit.

Although Gradient Boosted Trees can sometimes achieve high accuracy, in this case Random Forest provided more consistent and reliable results across the test set, making it the most suitable model for this dataset.

Therefore, Random Forest was chosen as the final model due to its:

Higher prediction accuracy.

Better generalization ability.

Stability on unseen data.

Reduced risk of overfitting.
