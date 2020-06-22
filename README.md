# Python-Capstone-Project

Description: Measure the impact of attribute & class noise on performance of ML algorithms using IRIS dataset.

Methodology: First all the predictor variables are standardized in the dataset and whole dataset is divided into testing and training parts. Then in scenario 1 some attribute noise in the form of random values is added to predictor variables which is further used to train ML models. Then we check the accuracy of classifiers for various levels of noise on test dataset
In case of class noise, a certain proportion of response variables are misclassified in training dataset which are then used to train the models. Then accuracy is checked using test dataset.
