Project Name: Classification of Road Accident Severity Using Machine Learning Techniques

Project Description:

As part of our MSc module - 'Machine Learning', Patrick and I were tasked to apply various machine learning techniques to a dataset of our choice, to solve either a classification or a regression task. The dataset had to be gathered, explored, and pre-processed beforehand, using techniques we had learned throughout the module, to obtain a more consolidated, and prepared dataset, that our machine learning models could train efficiently on.

Patrick and I decided to look at road accident data in the UK. We wanted to see whether we could build models that could predict the severity of traffic accidents (with target variable: 1 - fatal, 2 - serious, 3 - slight) based on the data collected from each individual accident (33 initial features). The data was gathered from the popular machine learning site; Kaggle.

We used several methods to transform and prepare our data, including the removal of redundant or duplicated features, dimension reduction based on feature selection, re-formatting feature types and using One-Hot Encoding, over-/under- sampling data to handle class imbalance, and finally splitting the dataset into training and testing subsets.

The three machine learning techniques we decided to use were Random Forests, K-Nearest Neighbours, and Support Vector Machines. Some information about these three techniques has been provided within the project document. It was important for us to experiment with the models by varying their hyperparameters (learning rate, number of trees, number of nearest neighbors, etc.) in an attempt to optimize their performance for the dataset we were using.

A comparison of the models has been completed, with a further look at the confusion matrices for each of the techniques and calculations of Accuracy, Precision, Recall, and F-score has been made.
