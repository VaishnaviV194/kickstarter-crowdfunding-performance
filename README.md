# 🚀 Kickstarter Campaign Performance

A business intelligence project that explores Kickstarter crowdfunding campaigns using **Excel, SQL, and Power BI** to identify the factors influencing campaign success, funding trends, backer engagement, and category performance.


## 🗂️ Project Overview

This project examines **365,892 Kickstarter campaigns** launched between **2009 and 2019** across **22 countries** to identify the factors that contribute to successful crowdfunding campaigns. The analysis focuses on campaign outcomes, funding patterns, category performance, and geographic trends to support data-driven decision-making.

---

## 🎯 Business Problem

With thousands of crowdfunding campaigns launched every year, understanding what drives campaign success is critical. Only **38.35% of Kickstarter projects succeed**, highlighting the need to identify the factors that influence funding outcomes, including goal amount, category, country, and campaign duration.

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| **Excel** | Data preparation, calendar table creation, data modeling |
| **SQL (MySQL)** | Business analysis and query-based insights |
| **Power BI + DAX** | Interactive dashboard, KPI measures, and data visualization |

---

## 📁 Dataset

- **Source:** Kickstarter Crowdfunding Dataset
- **Projects:** 365,892
- **Period:** 2009 – 2019
- **Countries:** 22
- **Tables:** Projects, Category, Creator, Location, Calendar

---

## 🔄 Project Workflow

**Raw Dataset** (365,892 Records | 4 Related Tables)

⬇️

**Data Preparation (Excel)**
- Converted date fields into readable format
- Built a Calendar Table with 9 date attributes
- Created a relational data model
- Converted goal amounts to USD using static exchange rates

⬇️

**Business Analysis (SQL)**
- Performed business queries to analyze campaign performance

⬇️

**Interactive Dashboard (Power BI + DAX)**
- Built KPI measures and interactive visualizations

⬇️

**Business Insights & Recommendations**

---

## 📅 Calendar Table

<img width="1352" height="696" alt="Screenshot 2026-07-05 202139" src="https://github.com/user-attachments/assets/180b1cb2-81e7-49f5-a66f-5c7c710c94c2" />

## 🔗 Data Model

<img width="1728" height="783" alt="Screenshot 2026-07-05 202257" src="https://github.com/user-attachments/assets/67b6f8f9-f89d-4c35-9eca-1f96ca3e53db" />

---

## 📊 Dashboard Features

- KPI Cards — Success Rate, Amount Raised, Average Campaign Duration, and Total Backers
- Projects by Category
- Projects by Outcome
- Success Rate by Goal Range
- Top Projects by Amount Raised
- Top Projects by Backers
- Success Rate by Year
- Success Rate by Category
- Projects by Country
- Success Rate by Quarter
- Interactive Filters (Year, Quarter, Month)

---

## 🗄️ SQL Analysis

SQL was used to retrieve, aggregate, filter, and analyze crowdfunding campaign data to identify success patterns, category performance, funding trends, geographic distribution, and project outcomes. The insights generated through SQL formed the foundation for the Power BI dashboard and business recommendations.

---

## 💡 Key Insights

- Only **38.35%** of Kickstarter projects succeed, while the majority fail or are canceled.
- Successful campaigns raised over **$4.28 billion** during the analysis period.
- More than **39.96 million backers** supported successful campaigns globally.
- Successful campaigns run for an average of **31.90 days**.
- The **United States** accounts for **278,524 projects**, representing over **76%** of all campaigns.
- **Product Design** is the most popular category with **22,277 projects**.
- **Chiptune** has the highest category success rate at **76.32%**.
- Projects with funding goals **below $5,000** achieve the highest success rate (**47.27%**).
- Projects with funding goals **above $100,000** have a success rate of only **6.28%**.
- Campaign success peaked in **2018 (59.36%)** before declining sharply in **2019 (17.18%)**.

---

## 📌 Business Recommendations

- Set realistic funding goals, as campaigns below **$5,000** are significantly more likely to succeed than high-value campaigns.
- Prioritize high-performing categories such as **Chiptune, Residential,** and **Anthology** when planning new campaigns.
- Aim for campaign durations of approximately **30 days**, aligning with the average successful project.
- Focus marketing efforts on the **United States**, which contributes the largest share of projects and backers.
- Plan campaign launches during periods of higher engagement, particularly **Q3**, which records the highest project volume.
- Consider breaking large funding goals into smaller phased campaigns to improve success rates.
- Investigate the factors that contributed to the **2018 success peak** to replicate effective campaign strategies.

---

## 👩‍💻 Author

**Vaishnavi V**

Aspiring Data Analyst
