This program shows the various classification algorithms performed on the heart desease dataset.
Here mainly 4 types of classification algorithm is performed.
1.) K- Nearest Neighbour
   a.) K-Nearest Neighbour is one of the simplest Machine Learning algorithms based on Supervised Learning technique.
   b.) K-NN algorithm assumes the similarity between the new case/data and available cases and put the new case into the category that is most similar to the available categories.
   c.) K-NN algorithm stores all the available data and classifies a new data point based on the similarity. This means when new data appears then it can be easily classified into        a well suite category by using K- NN algorithm.
   d.) K-NN algorithm can be used for Regression as well as for Classification but mostly it is used for the Classification problems.
   e.) K-NN is a non-parametric algorithm, which means it does not make any assumption on underlying data.
   f.) It is also called a lazy learner algorithm because it does not learn from the training set immediately instead it stores the dataset and at the time of classification, it          performs an action on the dataset.
   g.) KNN algorithm at the training phase just stores the dataset and when it gets new data, then it classifies that data into a category that is much similar to the new data.
   h.) For more details you can refer to the official site https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html
2.) Support Vector Machine
   a.) Support Vector Machine or SVM is one of the most popular Supervised Learning algorithms, which is used for Classification as well as Regression problems. However,                  primarily, it is used for Classification problems in Machine Learning.
   b.) The goal of the SVM algorithm is to create the best line or decision boundary that can segregate n-dimensional space into classes so that we can easily put the new data             point in the correct category in the future. This best decision boundary is called a hyperplane.
   c.) SVM chooses the extreme points/vectors that help in creating the hyperplane. These extreme cases are called as support vectors, and hence algorithm is termed as Support             Vector Machine.
   d.) For more details you can refer to the official site https://scikit-learn.org/stable/modules/svm.html
3.) Decision Tree Classifier
   a.) Decision Trees (DTs) are a non-parametric supervised learning method used for classification and regression.
   b.) The goal is to create a model that predicts the value of a target variable by learning simple decision rules inferred from the data features.
   c.) For more details you can refer to https://scikit-learn.org/stable/modules/tree.html
4.) Random Forest classifier
   a.) A random forest is a meta estimator that fits a number of decision tree classifiers on various sub-samples of the dataset and uses averaging to improve the predictive              accuracy and control over-fitting. The sub-sample size is controlled with the max_samples parameter if bootstrap=True (default), otherwise the whole dataset is used to            build each tree.
   b.) For more details refer to https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html
