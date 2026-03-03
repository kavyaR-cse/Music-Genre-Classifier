🎵 End-to-End Music Genre Classification System

📌 Overview:

This project implements a machine learning pipeline to classify music tracks into genres based on extracted audio features. The system leverages a Random Forest classifier to learn patterns from numerical audio descriptors and predict genre categories.

The goal was to design a structured ML workflow including preprocessing, model training, evaluation, and feature interpretation.

🎯 Problem Statement:

Automatically classifying music genres is challenging due to overlapping audio characteristics across categories. This project builds a supervised machine learning model capable of learning discriminative audio patterns and predicting genre labels accurately.

🛠 Tech Stack:

Python

Pandas

scikit-learn

Matplotlib

Seaborn

📊 Dataset:

Public dataset (Wine dataset used as proxy for structured genre features)

Numerical feature vectors representing song characteristics

Target labels mapped as:

0 → Classical

1 → Jazz

2 → Rock

⚙️ Approach:

Data Preprocessing

Loaded dataset and mapped numeric labels to genre names

Performed train-test split

Ensured clean structured feature inputs

Model Training

Implemented Random Forest classifier

Trained model on structured feature data

Optimized model parameters for better generalization

Model Evaluation

Measured accuracy on test dataset

Generated confusion matrix to analyze misclassifications

Evaluated model stability

Feature Analysis

Computed feature importance scores

Identified key attributes influencing genre prediction

Manual Prediction

Demonstrated prediction on new input feature vector

📈 Results:

Achieved competitive classification accuracy on test dataset

Confusion matrix revealed genre-level performance distribution

Feature importance analysis highlighted dominant predictive features

🚧 Challenges Faced : 

Handling limited and structured proxy dataset

Avoiding overfitting with ensemble model

Interpreting feature importance meaningfully

Ensuring generalization to unseen data

🚀 Future Improvements :

Replace proxy dataset with real audio dataset (e.g., extracted MFCC features)

Implement advanced feature extraction using Librosa

Compare multiple models (SVM, Gradient Boosting, Neural Networks)

Expose trained model via REST API for real-time predictions

Deploy using Streamlit or Flask

▶️ How to Run :
pip install pandas scikit-learn matplotlib seaborn

Open source_code.ipynb in Jupyter Notebook or Google Colab and run all cells sequentially.

📌 Project Outcome

This project demonstrates a complete machine learning workflow including data preprocessing, supervised model training, evaluation, interpretability, and manual prediction forming a structured foundation for scalable AI system development.
