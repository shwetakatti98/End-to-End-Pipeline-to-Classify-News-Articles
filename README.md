# End-to-End-Pipeline-to-Classify-News-Articles
ECE219 - Project 1
The aim of this project is to build an end-to-end pipeline to classify the given dataset of news articles. The classification of this text data is done by first performing feature extraction using a TF-IDF matrix, the dimensionality of the matrix is then reduced using two methods: PCA and NMF. These extracted features are then classified using a few simple classification models such as SVM, Linear/Logistic classification. To evaluate and diagnose the classifiers, we plot the ROC plot and confusion matrix. We also use metrics such as accuracy, precision, and F1 score to evaluate the classifiers. We perform a grid search and cross-validation to find the optimal combination of hyperparameters. Multiclass classification and GLoVE word embeddings are also explored in this project.

The four files are as follows:
- Q1-Q7.ipynb : Includes splitting the dataset, feature extraction, dimensionality reduction and classification algorithms.
- Q8(Grid_Search_Uncleaned).ipynb : Builds and performs the grid search pipeline for uncleaned data.
- Q8(Grid_Search_Cleaned).ipynb : Builds and performs the grid search pipeline for cleaned data.
- Q9(Multiclass) : Includes multiclass classification of the given dataset.
- Q10-Q13(GLoVE).ipynb : Includes GLoVE embeddings.
