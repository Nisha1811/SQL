🔍 Top Skills & Salaries for Data Analysts – SQL Project
# Introduction
This project explores the landscape of Data Analyst job postings using SQL to extract insights on salaries, required skills, and in-demand tools. It aims to guide aspiring analysts in identifying which technologies and proficiencies to prioritize for career growth and financial success.

# 📊 Data Background
The dataset includes job postings related to Data Analyst roles, covering:

Job titles and locations
Company information
Salary details
Required skills per job posting
These were sourced from a structured database with tables like job_postings_fact, skills_dim, company_dim, and others that provide rich metadata on job market trends.

# 🎯 Project Goals
Identify the top-paying Data Analyst jobs
Determine the skills associated with these high-paying roles
Find the most in-demand skills in the job market
Evaluate which skills offer the highest salary return
Highlight optimal skills that are both in-demand and high-paying

# 🛠️ Tools & Technologies
SQL – Main query language for data extraction and transformation
DBMS – Queries are designed to be executed in PostgreSQL-like environments
GitHub – For version control and collaboration
Jupyter/Notebooks (optional) – For visualizing and discussing results

# 📈 The Analysis
Top Paying Jobs
Extracted the top 10 highest-paying Data Analyst jobs with remote options.
1_top_paying_jobs.sql
🔍 Filters:

Job Title = "Data Analyst"
Location = "Anywhere"
Ordered by salary

Top Paying Jobs with Skills
Combined the top-paying jobs with their required skills.
2_top_paying_jobs_skill.sql
💡 Insight: Tools like SQL, Python, R, Tableau, Azure, AWS are common.

Most In-Demand Skills
Identified the top 5 most requested skills in remote job listings.
3_top_demanded_Skills.sql
📌 Top 5 Skills by Demand:

SQL
Excel
Python
Tableau
Power BI

Top Paying Skills
Evaluated average salaries associated with each skill.
4_top_paying_jobs.sql
💰 Highest-paying skills include:

PySpark
Bitbucket
Couchbase
Pandas
GitLab
Databricks

Optimal Skills (High Demand + High Pay)
Combined demand and salary to find the best skills to learn.
5_optimal_skills.sql
✅ Optimal Skills:

Python
R
Tableau
Snowflake
Azure
AWS
Oracle

# 🧱 Database Setup (Assumed Schema)
While the raw data and schema aren't included, the following key tables were used:
job_postings_fact: Main fact table containing job data
company_dim: Contains company information
skills_dim: Skill names with IDs
skills_job_dim: Bridge table linking jobs with skills
You can simulate this environment using PostgreSQL or any SQL-compatible DBMS with appropriately mocked data.

# 📚 What I Learned
How to write complex SQL queries using CTE, JOIN, GROUP BY, HAVING, and ORDER BY
How to analyze job market data using SQL
How to extract actionable insights for career planning
Importance of cloud tools and data visualization platforms in today’s analytics job market

✅ Conclusion
This SQL project sheds light on the Data Analyst job market, helping professionals and students understand which skills are valuable and why. By merging salary insights with demand statistics, we get a clearer picture of what skills drive both employability and income. This kind of analysis is crucial for guiding learning paths and staying competitive in the evolving data industry.