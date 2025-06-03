# Wine Quality Classification

This project uses machine learning models to predict wine quality based on physicochemical tests. The dataset comes from the UCI Machine Learning Repository.

## 📊 Dataset

- **Source**: [UCI Wine Quality Dataset](https://archive.ics.uci.edu/ml/datasets/Wine+Quality)
- Contains data on red and white wine variants
- Features include pH, alcohol content, residual sugar, and more

## 🚀 Project Goals

1. Build baseline models using:
   - Decision Tree Classifier
   - Random Forest Classifier
2. Evaluate models using:
   - Accuracy
   - Precision, Recall, F1 Score
   - Average Precision Score
3. Tune hyperparameters using `GridSearchCV`

## 🔍 Key Findings

- The **Random Forest Classifier** outperformed the Decision Tree on most metrics.
- Despite slightly lower recall, Random Forest had:
  - Higher precision
  - Better F1 score
  - Superior average precision score

## 🛠️ Requirements

To install dependencies:

pip install -r requirements.txt

## 📃 License

This project is for educational purposes only.
