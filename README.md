# 📘 SDG 4: Quality Education — Student Performance Analysis Using Machine Learning

## 🌍 Overview

This project explores how **machine learning** and **data analysis** can contribute to achieving the **United Nations Sustainable Development Goal 4 (SDG 4)** — *“Ensure inclusive and equitable quality education and promote lifelong learning opportunities for all.”*

Using a dataset of over **6,600 student records**, the project investigates how academic, socioeconomic, and personal factors influence **student performance**. The goal is to uncover insights that can inform data-driven education policies, targeted interventions, and equitable learning opportunities.

---

## 🎯 Objectives

* **Identify** key factors influencing student exam performance.
* **Apply** machine learning models to predict outcomes based on multi-dimensional data.
* **Analyze** equity-related factors (income, gender, access to resources) to detect educational disparities.
* **Support** the achievement of **SDG 4** through evidence-based recommendations.

---

## 📊 Dataset Description

The dataset includes **20 variables** across several domains:

| Category                   | Features                                                                                   | Description                            |
| -------------------------- | ------------------------------------------------------------------------------------------ | -------------------------------------- |
| **Academic**               | `Hours_Studied`, `Attendance`, `Previous_Scores`, `Tutoring_Sessions`, `Teacher_Quality`   | Indicators of academic engagement      |
| **Personal**               | `Sleep_Hours`, `Motivation_Level`, `Physical_Activity`, `Learning_Disabilities`            | Well-being and learning conditions     |
| **Family & Socioeconomic** | `Parental_Involvement`, `Parental_Education_Level`, `Family_Income`, `Access_to_Resources` | Family background and support          |
| **School Environment**     | `School_Type`, `Peer_Influence`, `Distance_from_Home`, `Extracurricular_Activities`        | External influences and school context |
| **Demographics**           | `Gender`, `Internet_Access`                                                                | Background characteristics             |
| **Target Variable**        | `Exam_Score`                                                                               | Final exam performance score           |

📁 Dataset size: 6,607 rows × 20 columns
📈 Data types: 7 numeric, 13 categorical

---

## 🧠 Methodology

The analysis was conducted in a Jupyter Notebook: `SDG_4_quality_education.ipynb`.

### **Steps:**

1. **Data Cleaning & Preprocessing**

   * Handled missing values and inconsistent entries.
   * Encoded categorical variables using `LabelEncoder`.

2. **Exploratory Data Analysis (EDA)**

   * Visualized distributions, correlations, and variable importance.
   * Investigated relationships between academic, family, and environmental factors.

3. **Machine Learning Modeling**

   * Implemented regression models (Random Forest, Linear Regression).
   * Evaluated model performance using R² and RMSE metrics.
   * Extracted feature importance for interpretability.

4. **Interpretation & Policy Insights**

   * Mapped findings to relevant **SDG 4 targets** (4.1, 4.3, 4.5, 4.c).
   * Proposed interventions for quality and equitable education.

---

## 📈 Key Findings

| Theme                     | Finding                                                                         | Implication                                                      |
| ------------------------- | ------------------------------------------------------------------------------- | ---------------------------------------------------------------- |
| **Academic Effort**       | Study hours, attendance, and prior scores are top predictors of exam success.   | Encourage active learning and attendance programs.               |
| **Parental Influence**    | Parental involvement and education level positively correlate with performance. | Promote parent engagement initiatives.                           |
| **Socioeconomic Factors** | Low family income and limited access to resources lower scores.                 | Invest in equitable access to learning materials and technology. |
| **Teacher Quality**       | Higher teacher quality improves average exam scores.                            | Prioritize teacher training and evaluation systems.              |
| **Inclusivity**           | Learning disabilities and long travel distances negatively impact results.      | Support inclusive education and local school access.             |

---

## 🧩 Technologies Used

* **Languages:** Python
* **Libraries:**

  * Data Processing: `pandas`, `numpy`
  * Visualization: `matplotlib`, `seaborn`
  * Machine Learning: `scikit-learn`, `xgboost`
  * Model Explainability: `shap`, `lime`
* **Environment:** Jupyter Notebook
* **Version Control:** Git, GitHub

---

## 📂 Repository Structure

```
📦 SDG4_Quality_Education
├── 📜 README.md
├── 📓 SDG_4_quality_education.ipynb       # Main analysis notebook
├── 📊 data/
│   ├── student_performance.csv            # Dataset file
│   └── column_metadata.csv                # Column categories (Academic, Personal, etc.)
├── 📈 results/
│   ├── correlations_heatmap.png
│   ├── feature_importance.png
│   └── summary_statistics.csv
└── 🧠 models/
    ├── random_forest_model.pkl
    └── linear_regression_model.pkl
```

---

## 🔍 How to Run the Project

### **1. Clone the Repository**

```bash
git clone https://github.com/<your-username>/SDG4_Quality_Education.git
cd SDG4_Quality_Education
```

### **2. Install Dependencies**

```bash
pip install -r requirements.txt
```

### **3. Launch the Notebook**

```bash
jupyter notebook SDG_4_quality_education.ipynb
```

### **4. (Optional) Run in Google Colab**

Upload the notebook to [Google Colab](https://colab.research.google.com/) for cloud execution.

---

## 🌐 Alignment with SDG 4 Targets

| SDG 4 Target                      | Analytical Contribution                                      |
| --------------------------------- | ------------------------------------------------------------ |
| **4.1**: Ensure quality education | Identifies key predictors of student learning outcomes       |
| **4.3**: Equal access             | Highlights income and resource disparities                   |
| **4.5**: Eliminate inequalities   | Quantifies performance gaps by gender, income, and resources |
| **4.c**: Teacher quality          | Correlates teacher quality with learning achievement         |

---

## 🧾 Example Outputs

* **Feature Importance Chart:** shows most influential predictors of `Exam_Score`.
* **Equity Analysis:** visualizes disparities in performance across income levels.
* **Predictive Model:** forecasts exam performance for early intervention strategies.

---

## 🧭 Future Improvements

* Expand dataset with regional and longitudinal data.
* Integrate NLP for analyzing qualitative feedback from students and teachers.
* Build an **AI dashboard** for policy visualization.
* Use explainable AI (XAI) techniques to ensure fairness and transparency.

---

## 🤝 Contribution

Contributions are welcome!
To contribute:

1. Fork the repository
2. Create a new branch (`feature-branch-name`)
3. Commit changes with clear messages
4. Submit a Pull Request

---

# Core Libraries
pandas==2.2.2
numpy==1.26.4

# Visualization
matplotlib==3.9.2
seaborn==0.13.2

# Machine Learning
scikit-learn==1.5.2
xgboost==2.1.1

# Model Explainability (optional but recommended)
shap==0.46.0
lime==0.2.0.1

# Jupyter Environment
jupyter==1.1.1
notebook==7.2.2
ipykernel==6.29.5

# Utility Libraries
scipy==1.13.1
statsmodels==0.14.3


## 🧑‍💻 Author

**Rodah Chepkorir**
*Data Science for Sustainable Development Enthusiast*
📧 [[chepkorirrodah36@gmail.com]]
🌐 [LinkedIn / Portfolio / GitHub link]

---

## 📜 License

This project is licensed under the **MIT License** — feel free to use, modify, and share with attribution.

---
