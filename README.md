# 🎓 HireScore

**Predicting Student Placement Success and Salary Outcomes using Machine Learning**

---

## 🧭 About the Project

**HireScore** is a machine learning project that analyzes the academic and extracurricular profiles of engineering students to predict:
- ✅ **Placement status** (placed or not)
- 💰 **Expected salary** (CTC in LPA)

This project was created as a milestone application of my learning from the **MIT 6.036: Introduction to Machine Learning** course, up to **Week 5 (Regression)**. The goal was not only to build something practically useful, but to deeply understand the ML workflow — from feature engineering and data preprocessing to model building and evaluation.

> 🧠 *This was my first complete end-to-end ML project — a hands-on, applied extension of what I learned in 6.036.*

---

## 🔍 Problem Statement

Engineering students often wonder:
- *Will I get placed?*
- *What kind of salary offer can I expect?*

With increasing competition and uncertainty in campus placements, this project uses data to give students a sense of what factors influence outcomes, and what might be realistically expected.

---

## 📊 Dataset

- **Source**: [Kaggle – Engineering Student Journey](https://www.kaggle.com/datasets/rakeshkapilavai/engineering-student-journey)
- **Records**: ~2000 students from various engineering branches
- **Features include**:
  - Semester-wise GPA (Sem1–Sem8)
  - Attendance %
  - Technical skills (count)
  - Club involvement (count)
  - Backlogs
  - Internship experience
  - Branch (CSE, ECE, IT, etc.)
  - Placement outcome and salary (CTC)

---

## 🧠 Models Used

### 🟩 Classification – Will the student be placed?
- Logistic Regression
- Random Forest Classifier

### 🟦 Regression – If placed, what salary (CTC) will they receive?
- Linear Regression
- Random Forest Regressor

---

## 📌 Features Used for Modeling

| Category       | Features Used                                                   |
|----------------|------------------------------------------------------------------|
| **Academic**   | Average GPA, Sem6 GPA, GPA Trend, Backlogs                      |
| **Behavioral** | Attendance (%), Skill Count, Club Count                         |
| **Profile**    | Branch (one-hot encoded), Internship Done (Yes/No)              |

📉 Categorical data was one-hot encoded  
⚖️ Continuous features were standardized  
🏷 Labels were encoded as 0/1 for classification and numeric for regression  

---

## 📈 Key Learnings

- 📦 Hands-on implementation of concepts from Weeks 1–5 of MIT 6.036
- 🧹 Extensive data cleaning, feature engineering, and preprocessing
- 🔍 Learned the importance of model selection (RF > Logistic in this case)
- 📊 Visualized feature importance to interpret model decisions
- 🚧 Faced and overcame challenges with noisy data and low signal-to-noise ratio in regression

---

## 🙌 Acknowledgements

- 📘 MIT 6.036: *Introduction to Machine Learning* — for the concepts & intuition
- 📊 Dataset by Rakesh Kapilavayi on Kaggle
- 🤝 Open-source Python ML stack: `pandas`, `scikit-learn`, `matplotlib`, `gradio`

---

> 🔖 **This was my first serious dive into applied ML** — not just learning algorithms, but using them to tell a story and solve a real-world problem. Onward and upward 🚀
