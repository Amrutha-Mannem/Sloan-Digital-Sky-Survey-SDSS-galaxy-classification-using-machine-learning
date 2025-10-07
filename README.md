# Sloan-Digital-Sky-Survey-SDSS-galaxy-classification-using-machine-learning
Machine learning project for classifying galaxies from the Sloan Digital Sky Survey (SDSS) dataset. Includes data preprocessing, visualization, outlier handling, feature selection, and model training using algorithms like Random Forest and SVM for accurate galaxy type prediction.
📖 Overview

The SDSS Galaxy Classification project uses machine learning to classify galaxies based on their photometric and spectroscopic properties from the Sloan Digital Sky Survey (SDSS) dataset.

The goal is to predict the subclass of a galaxy (e.g., STARFORMING, STARBURST, AGN) using numerical features such as u, g, r, i, z magnitudes. This project demonstrates data preprocessing, feature engineering, model training, and evaluation for astronomical data analysis.

🛠️ Tech Stack

Language: Python
Platform: Google Colab / Jupyter Notebook

Libraries Used:

numpy – Numerical computations

pandas – Data cleaning and manipulation

matplotlib & seaborn – Data visualization

scikit-learn – Machine learning models and evaluation metrics

imblearn – SMOTE oversampling for imbalanced data

pickle – Model saving and loading

📂 Dataset

Source: Sloan Digital Sky Survey (SDSS)
File Used: sdss_100k_galaxy_form_burst.csv

Example Columns:

objid	specobjid	class	subclass	u	g	r	i	z
123	456	GALAXY	STARFORMING	18.9	17.5	16.8	16.5	16.4
🧩 Features

Data Preprocessing:

Handle missing values (NaN, -9999)

Encode categorical labels (e.g., subclass)

Remove outliers using IQR method

Normalize or scale numeric data

Exploratory Data Analysis (EDA):

Visualize subclass distribution (pie charts, barplots)

Correlation heatmaps of numeric features

Boxplots for feature spread and outliers

Model Training:

Decision Tree Classifier 🌳

Random Forest Classifier 🌲

Logistic Regression 🔹

Evaluation Metrics:

Accuracy

Precision, Recall, and F1-Score

Confusion Matrix

💻 How to Run in Google Colab

Open Google Colab
.

Upload the dataset CSV file (sdss_100k_galaxy_form_burst.csv).

Open the notebook file sdss_galaxy_(1)_(3) (2).ipynb.

Run all cells sequentially to preprocess data, train models, and view evaluation results.

Example code snippet to load data in Colab:

import pandas as pd

# Upload dataset
from google.colab import files
uploaded = files.upload()

# Load CSV
data = pd.read_csv('sdss_100k_galaxy_form_burst.csv', delimiter=' ')
data.head()

📈 Project Workflow

Data Collection – Obtain galaxy data from SDSS.

Exploratory Data Analysis (EDA) – Visualize subclass distributions and relationships.

Data Preprocessing – Clean and encode data, handle missing values and outliers.

Feature Selection & Engineering – Identify and use significant galaxy parameters.

Model Training & Testing – Apply ML algorithms and evaluate their performance.

Result Visualization – Display feature correlations, accuracy, and subclass distribution.

Model Saving – Save trained model with pickle for reuse.

🔮 Future Enhancements

Integrate deep learning models (e.g., CNNs for image-based galaxy classification).

Deploy the model as a web app using Streamlit or Flask.

Add real-time SDSS API integration for live predictions.

Implement feature importance analysis for interpretability.

📚 References

Sloan Digital Sky Survey (SDSS)

Scikit-learn Documentation

Imbalanced-learn Documentation

📝 License

This project is licensed under the MIT License – see the LICENSE file for details.

👩‍💻 Developer

Name: Amrutha Varshini Mannem
Email: varshinimannem32@gmail.com
