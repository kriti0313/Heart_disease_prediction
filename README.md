# Heart_disease_prediction
Heart disease is a leading cause of death worldwide. Machine learning (ML) algorithms can be used to develop predictive models that can help healthcare professionals identify patients at risk of developing heart disease.  There are several ML algorithms that can be used for heart disease prediction, including K-Nearest Neighbors (KNN), Random Forest, Decision Tree, and Logistic Regression. 

# METHODOLOGY
The methodology for building a heart disease prediction model using machine learning algorithms typically involves the following steps:
1)Data collection: Collect patient data including medical history, lifestyle factors, and test results. This data will be used to train and test the machine-learning algorithms.
2)Data pre-processing: Clean and pre-process the data to ensure that it is ready for use by the machine learning algorithms. This may involve removing missing data, handling outliers, and encoding categorical variables.
3)Model training: Train the machine learning models using the pre-processed data. Different machine learning algorithms like the random forest, decision tree, KNN, and logistic regression can be used and compared to select the best-performing algorithm.
4)Model evaluation: Evaluate the performance of the trained models using metrics such as accuracy, precision, recall, and F1-score. Cross-validation techniques like k-fold cross-validation can be used to ensure that the model performance is robust.
5)Model deployment: Once the best-performing model has been identified, it can be deployed for use in clinical settings.

# Algorithms Used 
1.	Logistic Regression-
o	 Logistic regression is one of the most popular Machine Learning algorithms under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables.
o	Logistic regression predicts the output of a categorical dependent variable. Therefore, the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1.
2.	K-nearest neighbor (KNN)-
KNN is the machine learning algorithm and is the most commonly used algorithm. It is preferred when parameters are continuous. In KNN, classification is done by predicting the nearest neighbor. It is preferred over other classification algorithms due to its simplicity and high speed. It can be used to solve both classification and regression problems. The algorithm takes the heart disease data set and classifies whether or not a person has heart disease. KNN captures the idea of calculating the distance between points on a graph. We used KNN to classify and predict people with heart disease based on parameters such as age, sex, etc. It does not need training data for a model generation because the training data is used in the testing stage. It stores all the cases and then classifies new data according to the nearest neighbor.
3.	Random Forest- 
It is also a type of supervised learning. It can be used both for classification and regression. It is also the most flexible and user-friendly algorithm. A forest is made up of trees. It is said that the more trees it has, the more robust a forest is. Random forests create decision trees on randomly selected data samples, obtain predictions from each tree, and select the best solution by voting.
4.	Decision Trees-
A decision tree is a type of supervised learning algorithm classifier, which is easy to understand. They deal with numerical and categorical data. The decision tree resembles the tree structure consisting of internal nodes, branches, and leaf nodes in which each branch represents the values of a given data set, internal nodes Tests on a given attribute and the Leaf nodes show the class to predict or indicate the results of the result. The classification rule starts from the root node to the leaf nodes, depending on the predictive attribute and the given rules.


