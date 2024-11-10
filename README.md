# 📊 Text Mining Product Reviews

This project performs text mining on Indonesian product reviews to classify sentiments and emotions using machine learning models. Through NLP and feature engineering, the analysis provides insights into customer feedback, enabling better understanding and decision-making.

## 📁 Project Structure

- **Text_Mining_Classification.ipynb** 📓: The primary Jupyter notebook for data loading, preprocessing, model training, and evaluation.
- **Text_Mining_Final_Report.pdf** 📄: The final report documenting methodology, results, and analysis.

## 🧩 Project Overview

In the age of e-commerce, understanding customer reviews is essential for businesses. This project uses NLP and machine learning to classify product reviews into sentiments (positive, negative) and specific emotions (happiness, sadness, anger, etc.). By uncovering customer emotions, it provides actionable insights for improving products and customer satisfaction.

## ⭐ Key Features

- **Data Preprocessing**:
  - **Tokenization and Normalization** 📝: Converts raw text to lower case, removes punctuation, and tokenizes Indonesian text.
  - **Stop Word Removal** 🛑: Uses Indonesian stop words to clean and refine text for improved model accuracy.
  - **Feature Engineering** 📐: TF-IDF is used to vectorize text for model training.

- **Classification Models**:
  - **Support Vector Machine (SVM)** 🧠: Provides high accuracy for emotion classification.
  - **Decision Tree and Random Forest** 🌳: Used for interpretability and ensemble learning.
  - **Performance Metrics** 📊: Evaluated using accuracy, precision, recall, and F1-score.

- **Hyperparameter Tuning**:
  - **Grid Search with Cross-Validation** 🔄: Optimizes model performance by tuning parameters like C (SVM) and max_depth (Decision Tree).

## ⚙️ Requirements

Install required libraries before running the notebook:
```bash
pip install -r requirements.txt
