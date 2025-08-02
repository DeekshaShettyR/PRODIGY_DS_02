
# 🚢 PRODIGY_DS_02 - Titanic Dataset EDA

This repository contains my submission for **Task 2** of the **Data Science Internship** at **Prodigy InfoTech**. The task focuses on performing **Exploratory Data Analysis (EDA)** on the Titanic dataset to derive insights related to passenger survival, age, gender, and class.

---

## 📌 Task Overview

**Objective:**  
Explore and analyze the Titanic dataset to uncover patterns and visualize key features affecting survival using Python and Tableau.

---

## 🧩 Dataset

The dataset used is the classic [Titanic dataset](https://www.kaggle.com/c/titanic/data) from Kaggle.

**Fields include:**

- `PassengerId`, `Survived`, `Pclass`, `Name`, `Sex`, `Age`, `SibSp`, `Parch`, `Ticket`, `Fare`, `Cabin`, `Embarked`

---

## 🧼 Data Cleaning Performed

- Filled missing values in `Age` using the **median**
- Filled missing values in `Embarked` using the **mode**
- Dropped `Cabin` due to excessive nulls
- Converted `Sex` and `Embarked` to numeric values (for EDA)
- Exported a cleaned version of the dataset: `titanic_cleaned.csv`

---

## 📊 Visualizations (Python)

### Created using Seaborn/Matplotlib:
1. **Survival Count**
2. **Survival by Gender**
3. **Survival by Passenger Class**
4. **Age Distribution**
5. **Age vs Survival**
6. **Correlation Heatmap**

📁 All charts saved in the [`charts/`](charts/) directory.

---

## 📈 Tableau Dashboard

**Tableau Visualizations:**
- Survival Count
- Survival by Gender
- Survival by Passenger Class
- Age Distribution (Histogram)
- Age vs Survival (Boxplot)

The dashboard includes interactive filters and annotations. Screenshots are saved in `charts/`.

---

## 📂 Files Included

| File/Folder              | Description                                  |
|--------------------------|----------------------------------------------|
| `task_2_titanic_eda.ipynb` | Jupyter Notebook for EDA                    |
| `titanic_cleaned.csv`    | Cleaned dataset used for Tableau             |
| `charts/`                | Folder with exported PNG images of charts    |
| `README.md`              | Project documentation                        |

---

## 📚 Tools Used

- **Python** (Pandas, Matplotlib, Seaborn)
- ** Google Colab**
- **Tableau Desktop**
- GitHub for version control

---

## 📌 Key Insights

- Females had a much higher survival rate compared to males.
- First-class passengers had better survival chances.
- Children had slightly higher survival rates.
- The dataset shows clear class and gender-based survival disparities.

---

## 📣 Internship Acknowledgement

This project is completed as part of the **#ProdigyInfoTech Data Science Internship**.  
Stay tuned for upcoming tasks!



