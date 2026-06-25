# Movie-Genre-Classifcation-Codsoft-Intership

## Overview

This project was developed as part of the CODSOFT Machine Learning Internship (Task 1). The goal is to build a machine learning model capable of predicting a movie's genre based on its plot description.

The project applies Natural Language Processing (NLP) techniques to transform textual movie descriptions into numerical features using TF-IDF Vectorization. A Logistic Regression classifier is then trained on these features to perform genre classification.

Repository Link:
https://github.com/piyushranjan07/Movie-Genre-Classifcation-Codsoft-Intership

---

## Problem Statement

Movie databases contain thousands of movies with textual descriptions. Manually categorizing these movies into genres can be time-consuming. The objective of this project is to automate genre prediction using machine learning techniques.

---

## Dataset

The dataset contains:

* Movie ID
* Movie Title
* Genre
* Movie Description

Files used:

* `train_data.txt` – Training dataset containing movie descriptions and genres
* `test_data.txt` – Test dataset containing movie descriptions
* `test_data_solution.txt` – Actual genres used for evaluation

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn

---

## Machine Learning Pipeline

### 1. Data Loading

The dataset files are loaded into Pandas DataFrames for analysis and model training.

### 2. Data Exploration

Basic exploration is performed to understand:

* Dataset dimensions
* Genre distribution
* Missing values

### 3. Feature Engineering

Movie descriptions are converted into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency).

### 4. Model Training

A Logistic Regression classifier is trained on the transformed text data.

### 5. Prediction

The trained model predicts genres for unseen movie descriptions.

### 6. Evaluation

The model performance is evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## Project Structure

```text
Movie-Genre-Classifcation-Codsoft-Intership/
│
├── Movie_Genre_Classification.ipynb
├── README.md
├── requirements.txt
└── screenshots/
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/piyushranjan07/Movie-Genre-Classifcation-Codsoft-Intership.git
```

Move to the project directory:

```bash
cd Movie-Genre-Classifcation-Codsoft-Intership
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

---

## How to Run

1. Open the notebook in Google Colab or Jupyter Notebook.
2. Upload the dataset ZIP file (`archive.zip`).
3. Run all cells sequentially.
4. The notebook will:

   * Load and preprocess the data
   * Convert text using TF-IDF
   * Train the Logistic Regression model
   * Evaluate performance
   * Predict genres for new movie descriptions

---

## Sample Prediction

Input:

```text
A superhero fights dangerous villains to save the world.
```

Predicted Output:

```text
Action
```

---

## Results

The model successfully classifies movie genres using textual plot descriptions.

Evaluation metrics used:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## Learning Outcomes

Through this project, the following concepts were explored:

* Natural Language Processing (NLP)
* Text Vectorization using TF-IDF
* Machine Learning Classification
* Logistic Regression
* Model Evaluation Techniques
* Data Preprocessing and Analysis

---

## Author

Piyush Ranjan

CODSOFT Machine Learning Internship

GitHub: https://github.com/piyushranjan07

---

### Internship

CODSOFT Machine Learning Internship

#MachineLearning #CustomerChurnPrediction #Python #RandomForest #CODSOFT

