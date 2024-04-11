# ML_divorce_Classification-with-5-models
The code performs data preprocessing, machine learning model training, evaluation, and model saving for a binary classification problem on the divorce dataset.
----
Here's the step-by-step explanation of the code:

1. **IMPORT LIBRARIES**: Imports the necessary libraries. In this code, it imports the `pandas` and `numpy` libraries.

2. **Read Data**: Reads the dataset. It reads the file `../dataset/divorce_data.csv` and assigns it to a variable named `unprocessed_data`.

3. **Info & head & describe**: Displays the first few rows of the dataset and provides basic statistics.

4. **EDA (Exploratory Data Analysis)**: Visualizes and explores the dataset. This includes creating count plots, distribution plots, and correlation analysis.

5. **TRAIN-TEST-SPLIT & PREPROCESSING**: Splits the dataset into training and testing sets. It separates the target variable (`Divorce`) from the features and performs any necessary preprocessing steps.

6. **EVALUATE FUNCTION**: Defines a function to evaluate the performance of machine learning models. It computes metrics such as accuracy and F1-score.

7. **MODELING**: Fits various machine learning models to the training data and evaluates their performance on the test data. The models used include Logistic Regression, K-Nearest Neighbors, Random Forests, Naive Bayes, and an Artificial Neural Network (ANN).

8. **SAVE MODELS**: Saves the trained models to disk using the `joblib` library for Logistic Regression, KNN, Random Forests, and Naive Bayes, and the `h5py` library for the ANN model.

9. **VISUALIZATION**: Visualizes the performance of the models using bar plots.

Overall, this code performs data exploration, model training, evaluation, and model saving for a binary classification problem on the divorce dataset.
