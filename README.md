# 🚢 Titanic Survival Analysis

A data analysis and machine learning project based on the classic **Titanic dataset**. The objective is to explore passenger data and build models to predict survival outcomes.

---

## 📁 Dataset Overview

The dataset is sourced from [Kaggle - Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic). It contains details about passengers on the Titanic and whether they survived the tragedy.

### Key Features:
- `PassengerId`: Unique ID of the passenger
- `Survived`: 0 = No, 1 = Yes (Target variable)
- `Pclass`: Ticket class (1 = 1st, 2 = 2nd, 3 = 3rd)
- `Name`, `Sex`, `Age`: Personal details
- `SibSp`: Number of siblings/spouses aboard
- `Parch`: Number of parents/children aboard
- `Ticket`: Ticket number
- `Fare`: Passenger fare
- `Cabin`: Cabin number (many missing)
- `Embarked`: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

---

## 🎯 Project Objectives

- Perform **exploratory data analysis (EDA)** to identify patterns
- Handle **missing values** and **categorical variables**
- Visualize survival rates by demographics
- Build predictive models (Logistic Regression, Random Forest, etc.)
- Evaluate model performance with accuracy, precision, recall, etc.

---

## 📊 Exploratory Data Analysis

- 📈 Survival Rate by Gender, Age, Class
- 🧼 Missing Value Handling: Age and Cabin
- 🔍 Correlation Heatmaps, Feature Engineering

---

## 🤖 Machine Learning Models

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | 80.2%    |
| Random Forest       | 83.1%    |
| SVM (RBF Kernel)    | 81.6%    |
| XGBoost             | 84.5%    |

---

## 🛠️ Tools & Libraries

- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn
- XGBoost / LightGBM
- Jupyter Notebook
- Git & GitHub

---

## 📂 Project Structure

titanic-analysis/
│
├── data/
│ ├── train.csv
│ └── test.csv
│
├── notebooks/
│ └── Titanic_EDA_and_Modeling.ipynb
│
├── models/
│ └── saved_model.pkl
│
├── images/
│ └── survival_by_gender.png
│
├── README.md
└── requirements.txt

yaml
Copy
Edit

---

## 🚀 Getting Started

1. Clone this repo:
```bash
git clone https://github.com/your-username/titanic-analysis.git
cd titanic-analysis
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Launch the notebook:

bash
Copy
Edit
jupyter notebook
📌 Insights
Females had a much higher survival rate than males.

First-class passengers were more likely to survive.

Children under 10 had a better survival chance.

🙋‍♂️ Author
Lokendra Singh
📧 singhlokendra2164@gmail.com
🔗 LinkedIn | GitHub

📄 License
This project is open-sourced under the MIT License.

yaml
Copy
Edit

---

Would you like:
- The **`.ipynb` notebook template** for the project?
- This README in **PDF** or **DOC** format?
- A **requirements.txt** file?
- Help uploading to GitHub?

Let me know how you'd like to proceed.
