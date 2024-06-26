# Weather-Forecast-Using-Support -Vector -Machine

Rain Prediction Project Using Support Vector Machine 

Tools Used:

Machine Learning Model to predict next-day rain by training classification models on the target variable RainTomorrow using Support Vector Machine.

Work Process: 

1. Importing the preprocessed datasets for training, validation, and testing, where the following data preparation steps have been performed.
2.Splitting a dataset into training, validation & test sets || Filling/imputing missing values in numeric columns || Scaling numeric features to a (0,1) range || Encoding categorical columns as one-hot vectors.
3.Training and interpreting SVM
4. Overfitting & hyperparameter tuning
5. Making predictions on test set
6. Saving a model to disk

Summary and References
The following topics were covered in this project:

Splitting a dataset into training, validation & test sets
Filling/imputing missing values in numeric columns
Scaling numeric features to a (0,1) range
Encoding categorical columns as one-hot vectors
Training and interpreting SVM
Overfitting & hyperparameter tuning
Making predictions on test
Saving model on disk


Support Vector Machine Terminology
Hyperplane: Hyperplane is the decision boundary that is used to separate the data points of different classes in a feature space. In the case of linear classifications, it will be a linear equation i.e. wx+b = 0.

Support Vectors: Support vectors are the closest data points to the hyperplane, which makes a critical role in deciding the hyperplane and margin.

Margin: Margin is the distance between the support vector and hyperplane. The main objective of the support vector machine algorithm is to maximize the margin. The wider margin indicates better classification performance.

Kernel: Kernel is the mathematical function, which is used in SVM to map the original input data points into high-dimensional feature spaces, so, that the hyperplane can be easily found out even if the data points are not linearly separable in the original input space. Some of the common kernel functions are linear, polynomial, radial basis function(RBF), and sigmoid.

Hard Margin: The maximum-margin hyperplane or the hard margin hyperplane is a hyperplane that properly separates the data points of different categories without any misclassifications.

Soft Margin: When the data is not perfectly separable or contains outliers, SVM permits a soft margin technique. Each data point has a slack variable introduced by the soft-margin SVM formulation, which softens the strict margin requirement and permits certain misclassifications or violations. It discovers a compromise between increasing the margin and reducing violations.

C: Margin maximisation and misclassification fines are balanced by the regularisation parameter C in SVM. The penalty for going over the margin or misclassifying data items is decided by it. A stricter penalty is imposed with a greater value of C, which results in a smaller margin and perhaps fewer misclassifications.

Hinge Loss: A typical loss function in SVMs is hinge loss. It punishes incorrect classifications or margin violations. The objective function in SVM is frequently formed by combining it with the regularisation term.

Dual Problem: A dual Problem of the optimisation problem that requires locating the Lagrange multipliers related to the support vectors can be used to solve SVM. The dual formulation enables the use of kernel tricks and more effective computing.
