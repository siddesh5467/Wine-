

# Wine Dataset Analysis Notebook

This Jupyter notebook demonstrates the analysis and classification of the Wine dataset using several machine learning models. The dataset contains chemical analysis data for different types of wine, and the goal is to classify wines into their respective classes based on these features.

## Dataset Overview

- **Source**: The Wine dataset is loaded from `sklearn.datasets`.
- **Features**: 13 chemical attributes (e.g., alcohol, malic acid, ash, etc.).
- **Target**: 3 wine classes (labeled as 0, 1, 2).
- **Samples**: 178 instances.

## Notebook Structure

1. **Import Libraries**: Essential libraries for data manipulation, visualization, and machine learning are imported.
2. **Load and Explore Data**: The dataset is loaded into a pandas DataFrame and basic statistics are displayed.
3. **Train-Test Split**: The data is split into training and testing sets.
4. **Model Training**: Four models are trained:
   - K-Nearest Neighbors (KNN)
   - Naive Bayes (GaussianNB)
   - Logistic Regression
   - Support Vector Machine (SVM)
5. **Model Evaluation**: Each model's performance is evaluated using classification reports and accuracy scores.
6. **Model Saving**: The best-performing model (Naive Bayes in this case) is saved using pickle.

## Key Features

- **Data Preprocessing**: The notebook includes steps for data exploration and preparation.
- **Multiple Models**: Compares the performance of different classification algorithms.
- **Visualization**: Uses seaborn and matplotlib for data visualization.
- **Model Persistence**: Saves the trained model for future use.

## How to Use

1. **Run the Notebook**: Open the notebook in Jupyter or Google Colab.
2. **Explore the Data**: Review the dataset and its features.
3. **Train Models**: Execute the cells to train and evaluate the models.
4. **Save Model**: The best model is saved as `bestlomodel.pkl`.

## Dependencies

- Python 3
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn



This README provides a clear overview of the notebook's purpose and how to use it effectively. If you need further details or modifications, let me know!

[1](https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/97486039/471044ae-746f-4821-9041-7cf1ce65d7c9/winedatasets.ipynb)
