# 🏥 Medical Insurance Cost Analysis | Day 3

## 📌 Project Overview

Welcome to **Day 3 of my Data Analysis Challenge!** 🚀

In this project, I analyzed a medical insurance cost dataset using Python to understand how different factors influence individual medical insurance charges.

The main goal was to explore the relationships between smoking status, age, BMI, region, and insurance costs while developing practical data analysis and visualization skills.

## 🎯 Project Objectives

- Understand the structure and characteristics of the dataset.
- Explore the distribution of medical insurance charges.
- Identify the major factors associated with higher insurance costs.
- Analyze relationships between numerical and categorical variables.
- Create meaningful visualizations to communicate findings.
- Practice the complete beginner-level data analysis workflow.

## 🛠️ Technologies Used

- **Python** — Programming language
- **Pandas** — Data manipulation and analysis
- **Seaborn** — Statistical data visualization
- **Matplotlib** — Charts and plots
- **JupyterLab** — Interactive development environment

## 📊 Dataset Features

The dataset contains information about individuals and their medical insurance costs.

Important features include:

| Feature | Description |
|---|---|
| `age` | Age of the individual |
| `sex` | Sex of the individual |
| `bmi` | Body Mass Index |
| `children` | Number of children covered by insurance |
| `smoker` | Smoking status |
| `region` | Residential region |
| `charges` | Individual medical insurance charges |

*Column names may vary depending on the dataset version.*

## 🔍 Key Questions

This analysis explores the following questions:

1. How does smoking status affect average medical insurance charges?
2. What is the relationship between age and insurance costs?
3. How does BMI relate to medical insurance charges?
4. Do insurance costs differ across regions?
5. How do smoking, age, and BMI together relate to higher insurance charges?

## 📈 Key Insights

### 1. Smoking Is the Strongest Cost Driver

Smokers have substantially higher average insurance charges than non-smokers in this dataset. Smoking status shows a particularly strong association with insurance costs.

### 2. Age Is Positively Associated with Charges

Older individuals generally have higher insurance charges, with an upward trend between age and cost.

### 3. BMI Also Matters

Higher BMI tends to be associated with higher insurance charges, particularly when combined with other risk factors.

### 4. Regional Differences Exist

Average insurance charges vary across regions, although these differences appear less pronounced than the differences associated with smoking status and age.

### 5. Risk Factors Can Compound

Individuals who smoke, are older, and have higher BMI tend to have the highest insurance charges in the dataset.

*These are exploratory findings from the dataset, not proof that any single factor causes higher charges.*

## 🧹 Data Analysis Workflow

The project follows these steps:

1. **Data Loading** — Import the dataset using Pandas.
2. **Data Exploration** — Inspect rows, columns, data types, and summary statistics.
3. **Data Quality Checks** — Check missing values and duplicate records.
4. **Data Analysis** — Compare insurance charges across different factors.
5. **Data Visualization** — Use charts to identify patterns and relationships.
6. **Insight Communication** — Summarize the most important findings.

## 📊 Visualizations

The analysis uses visualizations such as:

- Smoking status versus insurance charges.
- Age versus insurance charges.
- BMI versus insurance charges.
- Insurance charge distribution.
- Relationships between numerical variables.
- Comparisons across different regions.

## ⚙️ Installation and Setup

Follow these steps to run the project on your local machine.

### 1. Clone the Repository

```bash
git clone https://github.com/asifhas2/medical-insurance-cost-analysis-day3.git
```

### 2. Navigate to the Project Directory

```bash
cd medical-insurance-cost-analysis-day3
```

### 3. Install Python

Make sure Python 3 is installed on your system.

Check your Python version:

```bash
python --version
```

### 4. Install the Required Libraries

Install the libraries needed for data analysis and visualization:

```bash
pip install pandas seaborn matplotlib jupyterlab
```

### 5. Launch JupyterLab

Run the following command:

```bash
jupyter lab
```

JupyterLab will open in your browser. Open the project's `.ipynb` notebook to explore the code and analysis.

### 6. Load the Dataset

Make sure the medical insurance dataset is available in the correct project directory.

Example:

```python
import pandas as pd

df = pd.read_csv("insurance.csv")

df.head()

### 7. Run the Notebook

Execute the notebook cells in order to reproduce the data exploration, analysis, and visualizations.

**Requirements:**
- Python 3
- Pandas
- Seaborn
- Matplotlib
- JupyterLab

## 💡 What I Learned

Through this project, I practiced:

- Exploring a real-world healthcare dataset.
- Using Pandas for data analysis.
- Comparing numerical values across categories.
- Understanding correlations and distributions.
- Creating visualizations with Seaborn and Matplotlib.
- Translating analytical results into understandable insights.

## 🚀 Future Improvements

- Perform deeper statistical analysis of risk factors.
- Compare median and average insurance charges across groups.
- Investigate interactions between smoking, age, and BMI.
- Build a regression model to estimate insurance charges.
- Evaluate model performance using appropriate metrics.

## 👨‍💻 Project Summary

This beginner-level healthcare data analysis project demonstrates how Python can be used to explore medical insurance costs and identify patterns associated with higher charges.

It is part of my ongoing journey to improve my skills in **Python, Data Analysis, and Data Science** through hands-on projects.

## 👨‍🎓 Author

**Asif Hasan**  
Software Engineering Student  
Daffodil International University

## 📄 Disclaimer

This project is intended for educational purposes only. The findings describe associations observed in the dataset and should not be interpreted as medical advice or definitive evidence of causation.

---

⭐ If you find this project interesting, feel free to explore the analysis and share your feedback!
