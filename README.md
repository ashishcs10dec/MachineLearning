# Ensemble Learning

Ensemble modeling in machine learning operates the predictions from multiple models to generate the final model which provide better overall performance. Ensemble modeling helps to generalize the learning based on training data, so that it will be able to do predictions accurately on unknown data.

Modeling is one of the most important step in machine learning pipeline. The main motivation behind ensemble learning is to correctly combine weak models to get a more accurate and robust model with bias-variance trade off.

Ensemble learning can be classified in three different types Bagging, Boosting and Stacking.
# Bagging:
The working principle is to build several base models independently and then to average them for final predictions.
# Boosting:
Boosting models are built sequentially and tries to reduce the bias on final predictions.
# Stacking:
The predictions of each individual model are stacked together and used as input to a final estimator to compute the prediction.

# Bagging
<img width="338" alt="image" src="https://github.com/user-attachments/assets/6a0718c1-310a-4573-a311-f98f821a6148">

1. In bagging we build independent estimators on different samples of the original data set and average or vote across all the predictions.
2. Bagging is a short form of *Bootstrap Aggregating. It is an ensemble learning approach used to improve the stability and accuracy of machine learning algorithms.
3. Since multiple model predictions are averaged together to form the final predictions, Bagging reduces variance and helps to avoid overfitting. Although it is usually applied to decision tree methods, it can be used with any type of method.
4. Bagging is a special case of the model averaging approach, in case of regression problem we take mean of the output and in case of classification we take the majority vote.
5. Bagging is more helpfull if we have over fitting (high variance) base models.
6. We can also build independent estimators of same type on each subset. These independent estimators also enable us to parallelly process and increase the speed.
7. Most popular bagging estimator is 'Bagging Tress' also knows as 'Random Forest'
