# credit-card-fraud-detection
Credit card transaction fraud detection project



### Project Overview


This project aims to develop a machine learning model capable of detecting fraudulent credit card transactions.
The dataset used is highly imbalanced, with a very small percentage of transactions classified as fraudulent. The project addresses this imbalance and builds a model to accurately classify transactions as either fraudulent or legitimate.


### Dataset


Source: The dataset used in this project is a public dataset available on Kaggle.



Description: The dataset contains transactions made by credit cards in September 2013 by European cardholders. It presents transactions that occurred over two days, with 284,807 transactions and only 492 of them being fraudulent.



Features:


The dataset contains 31 columns, including Time, Amount, Class, and 28 anonymized features (V1 to V28).
Class is the target variable where 0 denotes a legitimate transaction and 1 denotes a fraudulent transaction.

#### Requirements


Python 3.x
Jupyter Notebook





#### Usage



Data Preprocessing: Clean and preprocess the dataset using the scripts in the jupyter Notebook.


Model Training: Train the Logistic Regression model.


Model Evaluation: Evaluate the model's performance on the test set.


Run the Jupyter Notebook: To see the full workflow, you can also run the notebook:


jupyter notebook notebooks/fraud_detection.ipynb

#### Results


The model achieved:

Training Accuracy: 94.15%


Test Accuracy: 93.91%



These results indicate that the model can effectively identify fraudulent transactions, though further tuning and testing with other models can be explored for improved performance.

