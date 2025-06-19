# 🌍 Global AI Job Market Salary Trends (2025)

This project explores global trends in AI job salaries using a synthetic dataset of 15,000 job postings. Through data cleaning, EDA, clustering, and ML modeling, we uncover insights about salary trends, skills, company locations, education, and remote work.

## 📊 Project Highlights

- Cleaned and standardized salary data in USD
- Explored salary patterns by:
  - Job title
  - Country
  - Education
  - Experience
  - Industry
  - Company size
- Identified top-paying roles and in-demand skills
- Applied K-Means clustering to group jobs
- Built a linear regression model to predict salaries
- Classified industries based on required skills
- Analyzed remote vs. local job salary gaps
- Visualized trends over time using Matplotlib & Seaborn

## 📁 Dataset

The dataset includes the following fields:

- `job_title`, `salary_usd`, `experience_level`, `remote_ratio`, `required_skills`, `industry`, `education_required`, etc.
- Standardized salaries using exchange rates for `EUR`, `GBP`, and `USD`

## 📌 Tools & Libraries

- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn
- TF-IDF, KMeans, Logistic Regression

## 🤖 Machine Learning

- **Unsupervised**: KMeans for job role clustering
- **Supervised**: 
  - Linear Regression for salary prediction
  - Logistic Regression to predict industry from skillset

## 🔍 Key Insights

- 💰 Switzerland had the highest average salary
- 🧠 Python remains the most in-demand skill
- 🧑‍🎓 Education level didn't significantly impact salary
- 🌐 Fully remote roles are common in the US and Canada
- 📈 Shorter application deadlines were **not** correlated with higher salaries
- 📊 Clustering showed patterns by experience and salary

## 📉 Challenges

- Industry prediction using only skills had limited accuracy (~7%)
- Some columns had low impact or inconsistent values
- Dataset may not reflect real-world hiring dynamics

## 🚀 How to Run

1. Clone the repo
2. Install dependencies:

```bash
pip install -r requirements.txt
