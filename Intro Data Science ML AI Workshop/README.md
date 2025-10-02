# Intro to Data Science & Machine Learning Workshop

Hosted by SFU Surge – PreHack Session

This workshop introduces beginners to core data science concepts, basic machine learning models, and hands-on demos they can extend for hackathon projects.

---

## ⚙️ Setup

Before the workshop, please ensure you have:

- [Anaconda](https://www.anaconda.com/download) installed (for Jupyter Notebook and console access).
- A [Kaggle account](https://www.kaggle.com/) created (to access datasets like Titanic).

---

## 🗓️ Agenda

- **Intro to Data Science** – Why does it matter?
- **Datasets, Types and Structure** – Understanding kinds of data
- **Data Cleaning and Preprocessing** – Making messy data usable
- **Exploratory Data Analysis (EDA)** – Finding insights through visualization
- **Machine Learning Basics** – Core ML concepts for hackathons
- **Demos** –
  - Random Forests (with Grid Search)
  - kNN (classification)
  - TF-IDF for text classification
  - Time series forecasting (Facebook Prophet)
  - _(Optional)_ CNNs, RNNs, GANs – brief discussion only

> Note: Math is kept light and conceptual. Each algorithm will be explained at a high level with practical demos on accessible datasets.

---

## 📊 Demos

### kNN Classification (Iris dataset)

- Workflow: EDA, scatter plots, histograms, train/test split, model training, evaluation.
- Shows interpretability and decision boundaries.

### Random Forests (Titanic dataset)

- Data cleaning: handle missing values, encode categorical variables, feature engineering.
- EDA with survival distributions and correlations.
- Baseline Linear Regression → Random Forest Classifier → GridSearchCV tuning.
- Export predictions for Kaggle.

### TF-IDF + Classifier (Text data)

- Convert raw text into numeric features with TF-IDF.
- Apply a classifier (Naive Bayes / Logistic Regression).
- Example: spam detection or sentiment classification.

### Time Series Forecasting (Facebook Prophet)

- Models trend, seasonality, and special events.
- Example: predicting daily registrations or traffic over time.

---

## 📘 Extra Resources

- [kNN Visual Demo – Stanford CS231n](http://vision.stanford.edu/teaching/cs231n-demos/knn/)
- [Kaggle Titanic Dataset](https://www.kaggle.com/competitions/titanic/data)

---

## 🙌 Credits

- Workshop organized by **SFU Surge**
- Slides and demos by Matt Wong
- Datasets: scikit-learn (Iris), Kaggle (Titanic)

---
