# 🧠 Adolescent Depression Prediction using Machine Learning

> **Final Project – Advanced Analysis with Power BI and Python**  
> Universidad Privada Boliviana · Diploma: Managerial Analytics for Decision-Making with Power BI and Python

---

## 📋 Project Information

| Field | Detail |
|---|---|
| **Student** | Nicolás Rivera |
| **Instructor** | Ariel López |
| **Course** | Advanced Analysis with Power BI and Python |
| **Date** | May 24, 2026 |

---

## 📌 Description

This project applies **Machine Learning** techniques to predict potential cases of depression in adolescents, based on variables related to digital habits, social media usage, sleep quality, and stress levels.

Adolescent mental health has become a growing concern, driven by increased social media use, academic stress, and unhealthy digital habits. Through exploratory analysis and the construction of a **Random Forest** classification model, patterns are identified that allow the prediction of possible depression cases.

---

## 🎯 Objectives

### General Objective
Develop a predictive model capable of identifying potential cases of adolescent depression using variables related to digital habits and social behavior.

### Specific Objectives
- Perform exploratory analysis of the dataset.
- Identify variables related to depression.
- Build a predictive model using Random Forest.
- Evaluate the model's performance.
- Propose recommendations based on the results obtained.

---

## 📁 Repository Structure

```
📦 adolescent-depression-prediction
 ┣ 📓 trabajo_final_modulo_nicolas_rivera.ipynb   # Main notebook
 ┣ 📊 Teen_Mental_Health_Dataset.csv              # Required dataset
 ┣ 📄 requirements.txt                            # Project dependencies
 ┗ 📄 README.md                                   # Project documentation
```

> ⚠️ **Important:** The `Teen_Mental_Health_Dataset.csv` file must be in the same folder as the `.ipynb` file to run the notebook correctly.

---

## 📥 Dataset

The dataset used in this project was obtained from Kaggle:

🔗 [Social Media Impact on Teen Mental Health – Kaggle](https://www.kaggle.com/datasets/algozee/teenager-menthal-healy)

> Download the file `Teen_Mental_Health_Dataset.csv` and place it in the root folder of the repository before running the notebook.

---

## 🔧 Technologies & Libraries

| Library | Purpose |
|---|---|
| `pandas` | Data manipulation and analysis |
| `numpy` | Numerical operations |
| `matplotlib` | Data visualization |
| `seaborn` | Advanced statistical visualization |
| `scikit-learn` | Predictive modeling and evaluation |

---

## 🚀 Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/your-username/adolescent-depression-prediction.git
cd adolescent-depression-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the notebook
```bash
jupyter notebook trabajo_final_modulo_nicolas_rivera.ipynb
```

---

## 🔬 Methodology

The analysis follows this workflow:

```
Load Dataset
      ↓
Initial Exploration (info, describe, null values)
      ↓
Data Cleaning (dropna, drop_duplicates)
      ↓
Exploratory Data Analysis (distribution, boxplots)
      ↓
Variable Encoding (LabelEncoder)
      ↓
Correlation Heatmap
      ↓
Train / Test Split (80% / 20%)
      ↓
Training: Random Forest Classifier
      ↓
Evaluation (accuracy, confusion matrix, classification report)
      ↓
Feature Importance Analysis
```

---

## 📊 Key Results

### Model Performance
- **Algorithm:** Random Forest Classifier
- **Accuracy:** `97.92%`
- **Data split:** 80% training / 20% testing

### Most Influential Variables
Based on the model's feature importance analysis, the variables with the highest predictive power are:

1. 🔴 **Anxiety level** — strongest correlation with depression
2. 🔶 **Stress level** — strongly associated with positive cases
3. 📱 **Daily social media hours** — higher usage in depressed adolescents
4. 😴 **Sleep hours** — fewer hours in adolescents with depression

### Exploratory Analysis Findings
- Adolescents **with depression** tend to have **higher daily social media usage**.
- Adolescents **with depression** show **fewer sleep hours**.
- **Anxiety and stress levels** are considerably higher in positive cases.

---

## 💡 Conclusions

The analysis confirmed that the factors most associated with adolescent depression are **anxiety level**, **stress**, and **excessive social media use**. The Random Forest model achieved a satisfactory accuracy of **97.92%**, proving to be an effective tool for early identification of at-risk cases.

---

## 📢 Recommendations

Based on the results obtained:

- 🧑‍⚕️ Implement **preventive psychological support programs** in educational institutions.
- 💤 Promote **healthy sleep habits** among adolescents.
- 📵 Encourage **responsible social media use**.
- 📣 Develop **mental health awareness campaigns** in schools and universities.
- 🔍 Early detection of **high anxiety and stress levels**.

---

## 📄 License

This project was developed for academic purposes as part of the Managerial Analytics Diploma at **Universidad Privada Boliviana**.

---

*Developed by **Nicolas Rivera** · 2026*
