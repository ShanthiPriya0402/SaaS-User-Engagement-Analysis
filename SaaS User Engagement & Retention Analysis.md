# 📊 SaaS User Engagement & Retention Analysis

An end-to-end data analytics project for a freemium SaaS product to uncover churn drivers, identify key user segments, and deliver actionable insights via a Tableau dashboard.

---

## 🔍 Problem Statement

Understand how users interact with a SaaS platform:
- Who upgrades?
- Who churns?
- What engagement patterns matter?
- Can we identify user segments using clustering?

---

## 📁 Dataset

- **File:** `saas_user_data.csv`
- ~10,000 rows of simulated SaaS user data
- Features: login frequency, session time, upgrade status, churn flag, and feature usage.

---

## 🛠️ Tools & Technologies

| Tool        | Purpose                        |
|-------------|--------------------------------|
| Python 🐍   | Data cleaning, EDA, clustering |
| Pandas      | Data manipulation              |
| Seaborn     | Data visualization             |
| Scikit-Learn| KMeans clustering              |
| Tableau 📊  | Dashboard + storytelling        |
| Jupyter     | Notebook environment           |

---

## 📊 Project Workflow

1. **Data Cleaning**
   - Handled nulls, date formats, created new columns like `days_to_upgrade`
2. **Exploratory Data Analysis**
   - Churn analysis
   - Upgrade behavior
   - Feature usage patterns
3. **User Segmentation**
   - Rule-based segments (Free, Upgraded, Churned)
   - KMeans clustering (behavioral clusters)
4. **Data Visualization (Tableau)**
   - Churn pie chart
   - Funnel analysis
   - Upgrade trend line chart
   - Cluster breakdown

---

## 📌 Key Insights

- 📉 Churn rate ~25.8%; linked to low login frequency and feature usage
- 🚀 Upgraded users show higher engagement before conversion
- 📊 Cluster 1 users (power users) have high feature usage and longer retention
- ⚠️ At-risk users identified for proactive engagement

---

## 📷 Dashboard Preview

![Churn Overview](assets/churn_pie_chart.png)
![User Segments](assets/segments_bar.png)

📌 Built in **Tableau** — filters by segment, churn status, upgrade, etc.

---

## 💾 Files in This Repository

| File                             | Description                                      |
|----------------------------------|--------------------------------------------------|
| `SaaS_Analysis_Notebook.ipynb`   | Full Python analysis notebook                   |
| `saas_user_data_final.csv`       | Cleaned version of dataset                      |
| `Tableau_Dashboard.twbx`         | Packaged Tableau dashboard                      |
| `README.md`                      | Project summary and insights                    |
| `assets/`                        | Folder for dashboard screenshots                |
| `requirements.txt`               | Python library list (optional)                  |

---

## 🧠 Business Recommendations

- 🔁 Improve onboarding for users with low first-week activity
- 📬 Send upgrade nudges after 5+ sessions
- 🎯 Use power users as brand advocates
- ⚠️ Proactively engage Cluster 3 (at-risk) with personalized help

---

## 🙌 Author

**Shanthi Priya**  
*Aspiring Data Analyst | Passionate about Product Analytics*  
[GitHub](https://github.com/ShanthiPriya0402) | [LinkedIn]https://www.linkedin.com/in/shanthi-priya-nirmalan/)

---
