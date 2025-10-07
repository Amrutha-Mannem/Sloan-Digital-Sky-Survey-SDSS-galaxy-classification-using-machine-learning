# Sloan-Digital-Sky-Survey-SDSS-galaxy-classification-using-machine-learning
Machine learning project for classifying galaxies from the Sloan Digital Sky Survey (SDSS) dataset. Includes data preprocessing, visualization, outlier handling, feature selection, and model training using algorithms like Random Forest and SVM for accurate galaxy type prediction.
📖 Overview

This project focuses on classifying galaxies using data from the Sloan Digital Sky Survey (SDSS). The goal is to predict the galaxy subclass (such as “STARFORMING”, “STARBURST”, etc.) based on various photometric and spectroscopic parameters.

By applying machine learning models and data preprocessing techniques, this project provides valuable insights into galaxy classification, enabling better understanding of celestial objects and their characteristics.

🛠️ Tech Stack

Language: Python
Platform: Google Colab / Jupyter Notebook

Libraries Used:

numpy – Numerical operations

pandas – Data handling and preprocessing

matplotlib & seaborn – Data visualization

scikit-learn – Machine learning algorithms

imblearn – Handling imbalanced datasets (SMOTE)

pickle – Model saving and serialization

📂 Dataset

Source: Sloan Digital Sky Survey (SDSS)
Format: CSV file – sdss_100k_galaxy_form_burst.csv

The dataset contains galaxy attributes such as magnitude values (u, g, r, i, z), object identifiers, and class labels (subclass).

Example Columns:
| objid | specobjid | class | subclass | u | g | r | i | z | ... |
|-------|------------|-------|-----------|---|---|---|---|---|
| 123 | 456 | GALAXY | STARFORMING | 18.9 | 17.5 | 16.8 | 16.5 | 16.4 | ... |

🧩 Features
1. Data Preprocessing

Handle missing values and invalid entries (-9999)

Encode categorical columns like subclass into numerical labels

Apply outlier treatment using IQR method

Perform feature scaling and data cleaning

2. Exploratory Data Analysis (EDA)

Visualized galaxy subclass distribution

Generated correlation heatmaps for feature relationships

Created boxplots for numeric feature outlier detection

3. Model Training

Implemented multiple models including:

🌳 Decision Tree Classifier

🌲 Random Forest Classifier

🔹 Logistic Regression

Balanced data using SMOTE (Synthetic Minority Over-sampling Technique) to improve prediction accuracy.

4. Evaluation Metrics

Models were evaluated using:

Accuracy

Confusion Matrix

Classification Report (Precision, Recall, F1-Score)

📈 Project Workflow

Data Loading – Load and inspect SDSS dataset.

Data Cleaning – Handle nulls, replace invalid entries, remove noise.

EDA – Analyze subclass distribution, visualize feature relationships.

Feature Engineering – Encode labels, handle outliers, scale features.

Model Training – Train and test ML models on processed data.

Model Evaluation – Compare model performance metrics.

Model Saving – Save trained model using pickle for future inference.
🔮 Future Enhancements

Implement deep learning (CNNs) for better feature extraction

Deploy as a web app using Streamlit or Flask

Integrate real-time SDSS data using API calls

Add feature importance visualization for interpretability

📚 References

Sloan Digital Sky Survey (SDSS)

Scikit-learn Documentation

Imbalanced-learn Library

📝 License

This project is licensed under the MIT License – see the LICENSE file for details.

👩‍💻 Developer

Name: Amrutha Varshini Mannem
Email: varshinimannem32@gmail.com
