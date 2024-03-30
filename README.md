Project Title: Predictive Modeling on Weather Data

This project focuses on the application of various machine learning models to a weather dataset. The data undergoes preprocessing and one-hot encoding to prepare it for training and testing. 

The project explores the following models:

1. Logistic Regression: The model is trained and optimized using GridSearchCV to identify the best 'C' parameter. Performance metrics such as accuracy, Jaccard Index, LogLoss, and F1-Score are computed on the test data.

2. K-Nearest Neighbor (KNN): This model is trained with parameters 'n_neighbors', 'algorithm', and 'p' optimized using GridSearchCV. The model's performance is evaluated using the Jaccard Index and F1-Score on the test data.

3. Support Vector Machine (SVM): The SVM model is trained with 'C' and 'kernel' parameters optimized using GridSearchCV. The model's performance is evaluated using the Jaccard Index and F1-Score on the test data.

4. Decision Tree: This model is trained with the 'criterion' parameter optimized using GridSearchCV. The model's performance is evaluated using the Jaccard Index and F1-Score on the test data.

The project concludes by presenting the Accuracy, Jaccard Index, F1-Score, and LogLoss of all models in a tabular format for easy comparison. This project provides valuable insights into the application of machine learning models to weather data, offering a comprehensive comparison of their performances.
