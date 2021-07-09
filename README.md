# hands_on_ml
This is a repository for my solutions to the code excersises that are a part of the textbook "Hands-on Machine Learning with Scikit-Learn, Keras, and Tensor Flow" by Aurélien Géron. 

Chapter 3: Titanic

This exercsise focused on the classic Titanic dataset. It focused on practicing the fundamental components of data science, including EDA, data cleaning / imputations using Pipelines, and hyperparameter tuning using RandomizedSearchCV. A random forest model performed best, receiving ~83% accuracy. While suboptimal, and more advanced techniques and better hyperparameter tuning can achieve better results, maximizing accuracy was not the goal of this project.

Chapter 3: MNIST

For this set of exercises, models were trained on the mnist dataset. A GridSearchCV was used to search for the optimal hyperparameters of a KNN classifier, ultimatey achieving 97% accuracy. These exercises also included tasks such as image data augmentation and data visualization. 

Chapter 3: Spam Classifier 

This exercise created a classifier to detect whether a given email is spam or not. It included text-data preprocessing, such as using the nltk Porter Stemmer and a custom transformer class for transforming the eamils. A logistic regression model achieved 96% precision nd 98% recall. 

Chapter 4: Manual Softmax

The coding exercise for this chapter involved creating a manual implementation of the softmax algorithm, achieving 97% accuracy on the Iris dataset. 

Chapter 5: Linear SVC
This chapter's exercsies focused on training support vector machiens on the iris dataset. 

