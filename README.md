# SVM-in-Breast-Cancer

Implementation of the Breast Cancer - SVM project

In this code, we first load the breast cancer dataset using load_breast_cancer from Scikit-learn. Then we split the data set into training and test sets using train_test_split. Then we create an SVM model with a linear kernel by calling SVC (kernel='linear'). We fit the model on the training set using .fit(X_train, y_train) and then predict on the test set using .predict(X_test).

Finally, we calculate the accuracy of our model using accuracy_score from Scikit-learn. The accuracy score tells us the percentage of correctly classified samples in the test set. The higher the accuracy, the better our model is at classifying breast cancer samples.
