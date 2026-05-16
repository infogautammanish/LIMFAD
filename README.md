# LIMFAD - Instagram Account Classification Using Machine Learning

## Overview

LIMFAD is a machine learning project focused on analyzing Instagram account data and classifying account types using multiple profile-based features. The project includes data preprocessing, feature engineering, model training, evaluation, and visualization.

The notebook demonstrates a complete machine learning workflow using Python and Scikit-learn.

---

## Features

* Data cleaning and preprocessing
* Handling missing values and invalid entries
* Feature engineering for better prediction accuracy
* Exploratory Data Analysis (EDA)
* Correlation analysis
* Model training using Random Forest Classifier
* Performance evaluation with accuracy, confusion matrix, precision, recall, and F1-score
* Prediction system for new Instagram accounts
* Visualization using Matplotlib and Seaborn

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset Features

The dataset includes the following Instagram profile-related features:

* Followers
* Following
* Following/Followers Ratio
* Posts
* Posts/Followers Ratio
* Mutual Friends
* Labels (Target Variable)

Additional engineered features:

* Follower_to_Following_Ratio
* Engagement_Ratio
* Network_Score

---

## Machine Learning Workflow

### 1. Data Loading

The dataset is loaded using Pandas.

### 2. Data Cleaning

* Replaced invalid values like `#DIV/0!`
* Converted numeric columns properly
* Filled missing values

### 3. Feature Engineering

Created additional meaningful features to improve model performance.

### 4. Data Preprocessing

* Label Encoding
* Feature Scaling using StandardScaler
* Train-test split

### 5. Model Training

The project uses:

* Random Forest Classifier

Additional experimentation includes:

* Logistic Regression
* Support Vector Machine (SVM)

### 6. Model Evaluation

Evaluation metrics include:

* Accuracy Score
* Precision
* Recall
* F1 Score
* Confusion Matrix
* Classification Report

---

## Project Structure

```bash
LIMFAD/
│
├── LIMFAD.ipynb          # Main Jupyter Notebook
├── LIMFADD.csv           # Dataset file
├── README.md             # Project documentation
└── requirements.txt      # Required dependencies
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/LIMFAD.git
cd LIMFAD
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

## Example Output

The project generates:

* Model accuracy results
* Feature importance analysis
* Confusion matrix heatmaps
* Correlation matrix visualizations
* Predictions for new Instagram accounts

---

## Future Improvements

* Add Deep Learning models
* Deploy as a web application
* Real-time Instagram profile analysis
* Improve dataset size and diversity
* Hyperparameter optimization

---

## Learning Outcomes

This project helped in understanding:

* End-to-end machine learning workflow
* Data preprocessing techniques
* Feature engineering
* Model evaluation
* Data visualization
* Classification algorithms

---

## Author

Manish Kumar

---

## License

This project is open-source and available under the MIT License.
