# decision-tree

For the introductory competition on Kaggle called the "Titanic: Machine Learning from Disaster" I have mainly used the ML libraries of sklearn in Python.
Models tried : 
  1. Decision Tree Classifier
  2. Random Forest Classifier
  3. Gradient Boost Classifier
  4. SVM
  5. Naive Bayes
Of the models tried Gradient Boost had a higher accuracy score.

I had tried modifications on the Names columns, used one hot encoding for the titles given like "Mr", "Master", "Col", "Mrs" but that resulted in decreased accuracy so I dropped the case.
Classifiying based on the Cabin that they were in, i.e. the section A,B,C,D and performing one hot encoding on them also resulted in decrease in accuracy so I also dropped this idea. 
I am still working on a couple of more ideas to increase the accuracy. My current accuracy score is **0.808**
