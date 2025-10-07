# Sloan-Digital-Sky-Survey-SDSS-galaxy-classification-using-machine-learning
Machine learning project for classifying galaxies from the Sloan Digital Sky Survey (SDSS) dataset. Includes data preprocessing, visualization, outlier handling, feature selection, and model training using algorithms like Random Forest and SVM for accurate galaxy type prediction.
<h2>📖 Overview</h2>

The SDSS Galaxy Classification project uses machine learning to classify galaxies based on their photometric and spectroscopic properties from the Sloan Digital Sky Survey (SDSS) dataset.

The goal is to predict the subclass of a galaxy (e.g., STARFORMING, STARBURST, AGN) using numerical features such as u, g, r, i, and z magnitudes.

This project demonstrates data preprocessing, feature engineering, model training, and evaluation for astronomical data analysis.

<h2>🛠️ Tech Stack</h2>

Language: Python
Platform: Google Colab / Jupyter Notebook

Libraries Used:

🧮 numpy – Numerical computations

📊 pandas – Data manipulation

🎨 matplotlib & seaborn – Data visualization

🤖 scikit-learn – Machine learning algorithms and metrics

⚖️ imblearn – SMOTE oversampling for imbalanced data

💾 pickle – Model serialization and saving

<h2>📂 Dataset</h2>

Source: Sloan Digital Sky Survey (SDSS)
File: sdss_100k_galaxy_form_burst.csv

Example Columns:

objid	specobjid	class	subclass	u	g	r	i	z
123	456	GALAXY	STARFORMING	18.9	17.5	16.8	16.5	16.4
<h2>🧩 Features</h2>
1. Data Preprocessing

Handle missing values and invalid entries (NaN, -9999)

Encode categorical variables (e.g., subclass)

Remove outliers using IQR method

Normalize and scale numeric columns

2. Exploratory Data Analysis (EDA)

Visualize galaxy subclass distribution

Correlation heatmaps for numeric attributes

Boxplots for feature distribution and outliers

3. Model Training

🌳 Decision Tree Classifier

🌲 Random Forest Classifier

🔹 Logistic Regression

4. Evaluation Metrics

Accuracy

Precision

Recall

F1-Score

Confusion Matrix

<h2>💻 How to Run in Google Colab</h2>

Open Google Colab
.

Upload the dataset file sdss_100k_galaxy_form_burst.csv.

Open the notebook sdss_galaxy_(1)_(3) (2).ipynb.

Run all cells sequentially to preprocess data, train models, and visualize results.

Example Code Snippet:

import pandas as pd

# Upload dataset
from google.colab import files
uploaded = files.upload()

# Load CSV file
data = pd.read_csv('sdss_100k_galaxy_form_burst.csv', delimiter=' ')
data.head()

<h2>📈 Project Workflow</h2>

Data Collection – Gather SDSS galaxy data.

Exploratory Data Analysis (EDA) – Visualize subclass distributions and trends.

Data Preprocessing – Clean, encode, and normalize data.

Feature Engineering – Select important numerical features.

Model Training & Testing – Train models and evaluate accuracy.

Result Visualization – Display correlation heatmaps and classification performance.

Model Saving – Store trained model using pickle.

<h2>🔮 Future Enhancements</h2>

Integrate deep learning (CNNs) for galaxy image classification

Deploy model as a Streamlit or Flask web app

Add real-time SDSS API integration

Perform feature importance analysis for interpretability

<h2>📚 References</h2>

Sloan Digital Sky Survey (SDSS)

Scikit-learn Documentation

Imbalanced-learn Documentation

<h2>📝 License</h2>

This project is licensed under the MIT License – see the LICENSE file for details.

👩‍💻 Developer

Name: Amrutha Varshini Mannem<break>
Email: varshinimannem32@gmail.com
