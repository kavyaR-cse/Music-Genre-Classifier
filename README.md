🎵 Music Genre Classification using Random Forest

Overview :

This project classifies songs into different music genres using a Random Forest machine learning model.
The dataset contains audio features (like tempo, energy, etc.) for each song, and the model predicts the genre based on these features.

This project demonstrates:

-Data preprocessing

-Model training and evaluation

-Confusion matrix visualization

-Feature importance analysis

-Manual prediction demo

Dataset:

Public dataset: [Wine dataset used as a proxy for music genres]

Features include numeric values representing song characteristics

Target labels mapped to genres:

0 → Classical

1 → Jazz

2 → Rock

How It Works :

1.Load the dataset and map numeric labels to genre names.

2.Split dataset into training and testing sets.

3.Train a Random Forest classifier on the training data.

4.Evaluate the model using:

-Accuracy

-Confusion matrix

-Analyze feature importance to see which features influence genre prediction the most.

-Predict the genre of a new song using the trained model.

Usage :  

Open the notebook source_code.ipynb in Google Colab or Jupyter Notebook.

Run all cells from top to bottom.

Check outputs:

Accuracy score

Confusion matrix

Feature importance plot

Manual prediction demo

Outputs : 

Confusion Matrix 

Feature Importance

Manual Prediction Demo

Requirements : 

Python 3.x

Libraries: pandas, scikit-learn, matplotlib, seaborn

Install them via:

pip install pandas scikit-learn matplotlib seaborn

Conclusion:

This project shows how machine learning can classify songs into genres based on audio features.
It also demonstrates model evaluation, feature analysis, and manual prediction, making it a complete mini ML system.

