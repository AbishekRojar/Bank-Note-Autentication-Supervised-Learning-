# 💸Bank-Note-Autentication-Supervised-Learning-
This project demonstrates how to classify bank notes as **genuine** or **fake** using supervised learning models—including Decision Tree, Random Forest, XGBoost, and Logistic Regression. The workflow includes data cleaning, feature engineering, handling class imbalance, model training, evaluation, and visualization.

---

## 🗂️ Project Structure
├── BankNoteAuthentication.csv # Dataset containing features from banknotes

├── bank_note_auth.py # Python script for data processing, model training, and visualization

└── README.md # Project documentation


---

## 🧰 Tech Stack & Libraries Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

---

## 📊 Project Workflow

### 1. Data Loading & Preprocessing

- Load bank note data from `BankNoteAuthentication.csv`.
- Visualize the first few records to understand the data.
- Detect and remove outliers using the Z-score method.

### 2. Exploratory Data Analysis

- Explore data features: **variance**, **skewness**, **curtosis**, **entropy**.
- Visualize distribution and outliers with boxplots.
- Analyze class distribution.

### 3. Handling Class Imbalance

- Upsample the minority (fake note) class to balance the dataset.

### 4. Feature Engineering

- Select features and target label for the ML models.

### 5. Model Training

- Split data into training and testing sets.
- Train multiple models:
  - **Decision Tree Classifier**
  - **Random Forest Classifier**
  - **XGBoost Classifier**
  - **Logistic Regression**

### 6. Model Evaluation

- Evaluate model performance on the test set.
- Metrics: **Accuracy Score**
- Compare results across models.

### 7. Visualization

- Visualize the correlation matrix and class distributions.
- Optionally, plot confusion matrices or ROC curves for deeper insights.

---


---

## 📈 Results (Example Metrics)

| Model                  | Accuracy      |
|------------------------|--------------|
| Decision Tree          | 97.0%        |
| Random Forest          | 99.0%        |
| XGBoost                | 99.5%        |
| Logistic Regression    | 98.5%        |

*Fill in the actual metrics after running the code on your data!*

---

## 🚀 How to Run

1. Clone the repository:
git clone https://github.com/yourusername/bank-note-authentication.git
cd bank-note-authentication




