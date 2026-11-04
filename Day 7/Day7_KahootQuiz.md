Lesson 7c & 8a  Bayesian Statistics and Intro to Scikit-Learn Quiz 

1. What is the primary purpose of Bayes' theorem in statistical analysis?

A.  To calculate the mean and standard deviation of a dataset.
B.  To update the probability of a hypothesis based on new evidence.
C.  To determine the relationship between two independent variables.
D.  To eliminate uncertainty from statistical predictions.

2. In Bayesian statistics, what does the prior distribution represent?

A.  The probability distribution obtained after analyzing observed data.
B.  The probability of observing the data under a particular hypothesis.
C.  The initial beliefs or uncertainty about a parameter before incorporating the current observations.
D.  The difference between the observed and predicted values.

3. A researcher begins with a Beta(1,1) prior. After 10 coin flips, the researcher observes 7 heads and 3 tails. What is the posterior distribution?

A.  Beta(7,3)
B.  Beta(8,4)
C.  Beta(10,10)
D.  Beta(4,8)

4. As additional observations are collected during Bayesian inference, what generally happens to the posterior distribution?

A.  It becomes increasingly uniform regardless of the observations.
B.  It becomes independent of the likelihood function.
C.  It generally becomes more concentrated around parameter values supported by the data.
D.  It always becomes symmetric around a probability of 0.5.

5. Why can Bayesian methods be particularly useful in scientific machine learning applications?

A.  They eliminate the need for training datasets.
B.  They guarantee more accurate predictions than conventional machine learning models.
C.  They allow uncertainty in model parameters and predictions to be represented using probability distributions.
D.  They automatically remove all measurement errors from observational data.

6. In Scikit-Learn, the feature matrix X is typically organized with which dimensions?

A.  (n_features, n_samples)
B.  (n_samples, n_features)
C.  (n_samples, n_targets)
D.  (n_features, n_classes)

7. Which method is used to train a Scikit-Learn model using a feature matrix X and target array y?

A.  model.predict(X)
B.  model.transform(X)
C.  model.fit(X, y)
D.  model.score(X, y)

8. In the Iris classification example, why was the dataset divided into training and testing sets using train_test_split()?

A.  To increase the total number of observations available for training.
B.  To evaluate how well the trained model performs on data it has not previously seen.
C.  To ensure that the model achieves 100% classification accuracy.
D.  To eliminate the need for selecting model hyperparameters.

9. In the Scikit-Learn tutorial, what was the primary purpose of applying PCA to the Iris dataset?

A.  To classify Iris flowers into their known species.
B.  To calculate the classification accuracy of a trained model.
C.  To reduce the dimensionality of the dataset while retaining important patterns in the data.
D.  To determine the optimal number of training samples.

10. In the handwritten digits classification example, what information does a confusion matrix provide beyond overall accuracy?

A.  The number of features required to train the model.
B.  The optimal learning rate for the classification algorithm.
C.  The distribution of correct and incorrect predictions across individual classes.
D.  The probability distribution of the model's hyperparameters.


** Solutions Key 

1. B — To update the probability of a hypothesis based on new evidence.
Explanation: Bayes’ theorem updates a hypothesis probability by combining prior information with the likelihood of new evidence.

2. C — The initial beliefs or uncertainty about a parameter before incorporating the current observations.
Explanation: A prior distribution describes uncertainty about a parameter before the current observations are incorporated.

3. B — Beta(8,4)
Explanation:For a Beta–Bernoulli model, add heads to α and tails to β: α = 1 + 7 = 8 and β = 1 + 3 = 4. The posterior is Beta(8,4).

4. C — It generally becomes more concentrated around parameter values supported by the data.
Explanation:With informative observations and an appropriate model, the posterior typically becomes more concentrated, reflecting reduced parameter uncertainty.

5. C — They allow uncertainty in model parameters and predictions to be represented using probability distributions.
Explanation:Bayesian approaches quantify uncertainty in parameters and predictions, which is useful when scientific data are noisy, limited, or uncertain.

6. B — (n_samples, n_features)
Explanation:The feature matrix is two-dimensional: rows are samples and columns are features, giving shape (n_samples, n_features).

7. C — model.fit(X, y)
Explanation:The fit(X, y) method learns model parameters from the training data; predict(X) is subsequently used to make predictions.

8. B — To evaluate how well the trained model performs on data it has not previously seen.
Explanation:A held-out test set estimates how well the fitted model generalizes to previously unseen observations.

9. C — To reduce the dimensionality of the dataset while retaining important patterns in the data.
Explanation:PCA projects the four Iris measurements onto two principal components, retaining as much variance as possible for visualization.

10. C — The distribution of correct and incorrect predictions across individual classes.
Explanation:A confusion matrix compares true and predicted class labels and reveals which digits are most frequently confused (such as 2 with 1 or 8).













