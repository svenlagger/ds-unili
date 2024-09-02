# Supervised Learning
## KNN (K-Nearest Neighbor)
Simple and illustrative explanation here: https://www.youtube.com/watch?v=0p0o5cmgLdE

## SVM (Support Vector Machines)
Kerner trick: https://www.youtube.com/watch?v=Js2oAqEN_h0

## Linear vs Logisitic Regression
While linear regression predicts a Y value to a given X value (in R^2), logistic regression provides a probability displayed as a Y value for classification to any given X value in R^2.
https://www.youtube.com/watch?v=yIYKR4sgzI8

## Tree-based models
Illustrative YouTube playlist: https://www.youtube.com/playlist?list=PLM8wYQRetTxAl5FpMIJCcJbfZjSB0IeC_
### Decision Tree
Entropy (log base 2): \
![image](https://github.com/user-attachments/assets/59115e09-3807-484d-a530-cfc985b66e77) \
Minimize entropy, maximize information gain IG: \
![image](https://github.com/user-attachments/assets/80d22513-05ca-4514-92b8-c34ae0293023) \
$w_i$ is the relative size of a child with respect to a parent.
### Regression Tree
Very similar to standard decision trees, but for predicting the value of the target variable the average of target variables from the training data of a leaf node is used. As the name suggests this is used to do a regression and not a classification as with a standard decision tree. Splitting of nodes is done by variance reduction (variance is used as a measure of impurity): \
![image](https://github.com/user-attachments/assets/7fd5bc0b-ab94-4ac9-ae65-631489579b7b) \
![image](https://github.com/user-attachments/assets/de998cde-c6e4-4fdb-864a-882696082322) \
$w_i$ is the relative size of a child with respect to a parent. Splitting of nodes is done as long the desired depth of a tree has NOT been reached.

## Ensemble Learning
### Random Forest
Multiple decision trees with bootstraped data that then derive a final result from a "majority vote": https://www.youtube.com/watch?v=v6VJ2RO66Ag&list=PLM8wYQRetTxAl5FpMIJCcJbfZjSB0IeC_
### AdaBoost
https://www.youtube.com/watch?v=LsK-xG1cLYA
### Gradient Boosting
https://www.youtube.com/watch?v=lOwsMpdjxog



