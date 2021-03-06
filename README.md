# Applying Different Scikit-learn and Keras Based Classifiers on Metal Oxide Gas Sensor Dataset
In this project, I collected two open source datasets and applied different machine learning classification techniques using python based Scikit-learn and Keras libraries. Response of various metal oxide gas sensors were collected while they were exposed to different gas mixtures. The aim is to find out and classify the individual gas components in the mixtures. In order to do so, various supervised machine learning classifiers were applied and their performance were compared.
## Dataset Description
Two different datasets were used in this project- One is for binary classification and anothere is for multi-class classification purpose. Both of them were collected from UCI machine learning repository. For a generalized overview of the dataset and different attribute information, head over to the associated links below-

* [Gas sensor array under dynamic gas mixtures Data Set (Binary Classification)](http://archive.ics.uci.edu/ml/datasets/gas+sensor+array+under+dynamic+gas+mixtures)
* [Gas Sensor Array Drift Dataset Data Set (Multi-class Classification)](https://archive.ics.uci.edu/ml/datasets/gas+sensor+array+drift+dataset)

For classification purpose, I pre-processed and made the datasets simpler. The modified datasets can be found here:
[Dataset](https://drive.google.com/drive/folders/1gJy8f3twHl9rANqUMcxG1YMxvbV-cijN?usp=sharing)

## Data Processing Workflow
On both datasets, PCA and t-SNE dimension reduction techniques were applied in order to plot and visualize the relationships between different attributes.The same workflow was followed and the same classifiers were applied on both of the datasets. I applied 10 classical classifiers( non-neural network based) and 1 keras based vanilla neural network classifier. 

### Classical Classifiers
1. K-Nearest Neighbor (KNN)
2. Support Vector Machine (SVM)
3. Gaussian Multinomial Naive Bayes (MultinomialNB)
4. Decision Tree
5. Random Forest
6. Extra Tree
7. Logistic Regression
8. KNN based Bagging
9. Logistic Regression
10. Majority Voting Ensemble Machine

### Neural Network Based Classifier
I also created a 4 layered neural network architecture with 2 hidden layers for classification. The same network was used for both the binary and multi-class classification purposes. 
