# ADM_PROJECT

# Stack Overflow Salary Prediction

This project aims to build a machine learning model that predicts a developer's salary based on features derived from the Stack Overflow Developer Survey dataset.

## 📌 Objective

To develop a machine learning model that predicts an individual's salary using data from the Stack Overflow Developer Survey. The goal is to understand which features (e.g., job title, education level, technologies used) contribute most significantly to salary and to build a regression model for accurate predictions.

## 📊 Dataset

- **Source**: [Stack Overflow Developer Survey](https://www.kaggle.com/datasets/stackoverflow/stack-overflow-2018-developer-survey?resource=download)
- The dataset includes information such as:
  - Job Role
  - Years of Experience
  - Education Level
  - Technologies Used
  - Country
  - Salary (`ConvertedSalary`)

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn (for visualization)
- Category Encoders (for encoding categorical data)

## 📈 Model Performance

- **Model Used**: Random Forest Regressor
- **R² Score**: ~60%
- **Key Features**: `YearsCodePro`, `Country`, `EdLevel`, `LanguageWorkedWith`

## 🔍 Insights

- Random Forest showed promising results for predicting salaries.
- Top predictive features include **professional coding experience**, **country**, and **education level**.
- R² score indicates a moderate fit, with room for improvement through hyperparameter tuning and feature engineering.

## 🚀 Future Work

- Develop a **GUI/Web app** for salary prediction.
- Explore **deep learning models** using **Keras** or **TensorFlow**.
- Improve performance with **hyperparameter tuning** and **feature selection**.
- Deploy the model using **Streamlit** or **Flask** for user interaction.


## 📦 Installation

1. Clone the repository:

```bash
git clone https://github.com/Rohit2303A510J0/ADM_PROJECT.git
cd salary-prediction
```

2. Install required packages

```bash
pip install -r requirements.txt
```

3. Run notebook:
```bash
jupyter notebook ADM_PROJECT/Salary_prediction.ipynb
```
