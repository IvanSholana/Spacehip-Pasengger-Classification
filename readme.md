# Spaceship Passenger Classification 🚀

## 📌 Project Overview
This project aims to classify spaceship passengers based on various factors to predict whether they were transported to another dimension due to an anomaly. The dataset contains information about passengers, including their spending habits, travel class, and personal attributes.

## ❓ Problem Statement
In the year 2912, Spaceship Titanic suffered a catastrophic accident while traveling through Alpha Centauri, resulting in many passengers being transported to an unknown dimension. This project seeks to identify key factors influencing this transportation and develop a predictive model to classify passengers accordingly.

## 🔍 Data Science Workflow
### 1️⃣ Data Understanding
- The dataset includes passenger details such as age, home planet, cryosleep status, travel destination, and expenditure on various spaceship facilities.
- Exploratory Data Analysis (EDA) was conducted to identify patterns and relationships among features.

### 2️⃣ Data Preprocessing
- **Handling Missing Values**: Missing data was imputed using techniques such as forward fill, backward fill, and multiple imputations.
- **Feature Engineering**: Created new features, including passenger group ID, total spending, and age categories.
- **Encoding Categorical Data**: Applied Label Encoding and One-Hot Encoding.
- **Feature Scaling**: Used MinMaxScaler to standardize numerical features.

### 3️⃣ Model Development
- **Algorithm Used**: Implemented **CatBoostClassifier**, optimized for categorical data.
- **Hyperparameter Tuning**: Used **GridSearchCV** for optimization.
- **Evaluation Metrics**: Achieved **83% accuracy**, with balanced precision and recall.

## 📊 Results & Insights
- The model effectively predicts passenger transportation with **83% accuracy**.
- Important factors include **CryoSleep status, age, and spending behavior**.
- The model can be further optimized for real-world space travel risk assessment.

## 📂 Project Structure
```
📂 spaceship-classification
│-- 📄 spaceship_classification.ipynb  # Jupyter Notebook with implementation
│-- 📄 train.csv  # Training dataset
│-- 📄 test.csv  # Test dataset
│-- 📄 submission.csv  # Predictions for test dataset
│-- 📄 README.md  # Project documentation
```

## ⚙️ How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/spaceship-classification.git
   ```
2. Navigate to the project directory:
   ```sh
   cd spaceship-classification
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook or Python script to preprocess data and train the model.
5. Evaluate model performance using test data.

## 🛠 Dependencies
- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Seaborn
- Matplotlib
- CatBoost

## 🤝 Contributing
Contributions are welcome! Feel free to fork this repository, submit issues, or make pull requests.

## 📬 Contact
For any inquiries, reach out via [GitHub Issues](https://github.com/yourusername/spaceship-classification/issues).

---
**Author:** [Your Name]  
**Date:** March 2025