# 🧠 Personality Type Prediction (Ensemble Learning)

## 📋 Project Overview
This project is a Machine Learning application designed to predict whether an individual is an **Introvert** or an **Extrovert**. It analyzes behavioral data such as time spent alone, frequency of social attendance, and energy levels after socializing.

## 🚀 Key Features
- **Data Preprocessing:** Automated cleaning, handling missing values with median/mode, and outlier clipping.
- **Ensemble Model:** Combines the strengths of **Random Forest** and **Gradient Boosting** using a `VotingClassifier` (Soft Voting).
- **Optimization:** Hyperparameter tuning implemented via `RandomizedSearchCV`.
- **Evaluation:** Full performance report including Accuracy, Precision, Recall, and Confusion Matrix.

## 🛠️ Technologies Used
- Python 3.x
- Pandas & Numpy (Data Manipulation)
- Scikit-Learn (Machine Learning)
- Matplotlib & Seaborn (Data Visualization)

## 📊 Results
The model achieves a robust accuracy of **98%+** (approx.) by leveraging ensemble techniques to reduce variance and bias.

## ⚙️ How to use
1. Clone the repository.
2. Install dependencies: `pip install -r requirements.txt`
3. Run the script: `python personality_model.py`
