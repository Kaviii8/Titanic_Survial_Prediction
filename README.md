# 🚢 Titanic Survival Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Jupyter Notebook](https://img.shields.io/badge/Notebook-Jupyter-orange.svg)](https://jupyter.org/)

Predicting who survived the Titanic disaster using machine learning techniques. This project explores the classic **Titanic dataset** and applies **Logistic Regression** and **Decision Tree** classifiers to determine survival probabilities.

---

## 📌 Project Overview

The sinking of the Titanic is one of the most well-known maritime tragedies. This project aims to build predictive models using passenger data such as age, ticket class, and gender.

### 🔧 Steps in `titanic-saviours.ipynb`:

* 🔍 **Data Loading & EDA**
* 🧼 **Data Preprocessing**:

  * Handle missing values (e.g., `Age`, `Cabin`, `Embarked`)
  * Encode categorical features (e.g., `Sex` → `Le_Sex`)
  * Drop irrelevant columns
* ✂️ **Feature Selection**: Use `Pclass`, `Age`, `Fare`, `Le_Sex`
* 📊 **Model Training**:

  * Logistic Regression
  * Decision Tree Classifier
* 🧪 **Evaluation**:

  * Confusion matrix
  * Accuracy scores
* 📈 **Visualization**:

  * Plots using `matplotlib` and `seaborn`

---

## 🧾 Dataset

* **File**: `titanic.csv`
* **Source**: [Kaggle Titanic Dataset](https://www.kaggle.com/c/titanic/data)
* **Records**: 891 passengers
* **Target Variable**: `Survived` (0 = No, 1 = Yes)

### 🎯 Key Features Used:

| Feature  | Description                                 |
| -------- | ------------------------------------------- |
| `Pclass` | Passenger class (1 = 1st, 2 = 2nd, 3 = 3rd) |
| `Age`    | Passenger's age in years                    |
| `Fare`   | Ticket fare                                 |
| `Le_Sex` | Encoded gender                              |

---

## 📁 File Structure

```bash
├── titanic-saviours.ipynb     # Main notebook
├── titanic.csv                # Titanic dataset
└── README.md                  # Project documentation
```

---

## 🛠️ Technologies Used

* **Language**: Python 3.x
* **Libraries**:

  * `pandas`, `numpy` – Data manipulation
  * `matplotlib`, `seaborn` – Visualizations
  * `scikit-learn` – Machine learning:

    * `train_test_split`, `LabelEncoder`
    * `LogisticRegression`, `DecisionTreeClassifier`
    * `confusion_matrix`, etc.
  * `jupyterlab` / `notebook` – Interactive coding

---

## ⚙️ Setup & Installation

### 🔽 Step 1: Clone the Repository

```bash
git clone https://github.com/Kaviii8/titanic_survival_prediction.git
cd titanic_survival_prediction
```

### 🧪 Step 2: Create and Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

### 📦 Step 3: Install Requirements

Create a `requirements.txt`:

```txt
pandas
matplotlib
numpy
seaborn
scikit-learn
jupyterlab
```

Then install:

```bash
pip install -r requirements.txt
```

---

## ▶️ How to Run

1. Make sure the environment is set up and dependencies installed.
2. Launch Jupyter:

   ```bash
   jupyter lab
   # or
   jupyter notebook
   ```
3. Open `titanic saviours.ipynb` and run the cells sequentially.

---

## 📊 Results & Performance

* Models trained: **Logistic Regression**, **Decision Tree**
* Metrics used: **Confusion Matrix**, **Accuracy**
* Features used: `Pclass`, `Age`, `Fare`, `Le_Sex`

---

## 🤝 Contributing

Have ideas or want to improve this project? Contributions are welcome!

1. Fork this repo
2. Create a new branch
3. Make your changes
4. Submit a pull request 🚀

---

## 📄 License

This project is licensed under the **MIT License**. Feel free to use and adapt the code.

---

