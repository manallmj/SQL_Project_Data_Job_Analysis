# Introduction
Dive into the data job market! Focusing on data analyst roles, this project explores top paying jobs, in-demand skills, and where high market demand meets top-tier salary packages in data analytics. 

- SQL queries? Check them out here: [project_sql folder](/project_sql/)

# Background
Driven by a quest to navigate the data analyst job market more effectively, this project was born from a desire to pinpoint top-paid and in-demand skills, streamlining the search for optimal, lucrative career paths.

### The questions I wanted to answer through my SQL queries were:
1. What are the top paying data analyst jobs?
2. What skills are required for these top-paying jobs?
3. What skills are most in demand for data analysts?
4. Which skills are associated with higher salaries?
5. What are the most optimal skills to learn (high demand + high salary)?

# Tools I Used
* **SQL:** The standard data query language used to write complex aggregations, filter data subsets, and structure analytical answers.
* **PostgreSQL:** The database management system (DBMS) chosen to host the data warehouse and execute my SQL scripts efficiently.
* **VS Code:** My primary integrated development environment (IDE). I used it to write my SQL scripts, manage project files, and author this Markdown documentation.
* **Git & GitHub:** Used for local version control inside VS Code and hosting this repository to share my data-driven insights.

# The Analysis

### 1. Top-Paying Data Analyst Jobs
The initial analysis isolated the top 10 highest-paying remote Data Analyst positions. 
* **The Baseline:** Remote opportunities easily scale past **$184,000**, topping out at an extraordinary outlier of **$650,000** (Mantys).
* **Role Seniority:** True high-tier compensation relies heavily on organizational influence, highlighting titles like *Director of Analytics* (Meta - $336,500) and *Principal Data Analyst* (SmartAsset - $205,000).

### 2. Skills Required for Top-Paying Jobs
By joining our top 10 list with mapping tables, we extracted the micro-level skills requested by those specific elite employers:
* **Core Technical Stack:** Even at executive pay scales, **SQL** and **Python** remain completely non-negotiable across nearly every single top posting.
* **Big Data Ecosystems:** High-paying targets like AT&T and SmartAsset demand infrastructure tools such as **Snowflake**, **AWS**, **Azure**, and **PySpark**.
* **Enterprise Collaboration:** High-paying corporations tightly require workflow tools like **Jira**, **Confluence**, and **Bitbucket** to fit into Agile product teams.

### 3. Most In-Demand Skills for Data Analysts
Looking across the *entire* database rather than just elite salaries, the baseline market demand tells a very clear story of what you need to get hired:
| Skill | Entire Market Demand Count |
| :--- | :--- |
| **SQL** | 7,291 |
| **Excel** | 4,611 |
| **Python** | 4,330 |
| **Tableau** | 3,745 |
| **Power BI** | 2,609 |

### 4. Top Skills Based on Salary
When examining average salaries globally per skill, highly specialized, niche engineering tools claim the biggest paychecks:
* **Niche Infrastructure & AI Frameworks:** **SVN** ($400,000) and **Solidity** ($179,000) represent specialized software architecture gaps. Heavy engineering tools like **Couchbase** ($160,515), **DataRobot** ($155,486), and ML libraries like **Mxnet** ($149,000) dominate high-level pay scales.

### 5. Most Optimal Skills to Learn (High Demand + High Pay)
By intersecting high volume with high average payouts, we find the absolute sweet spot for a strategic career path:

| Skill | Total Remote Demand | Average Salary | Strategic Value |
| :--- | :--- | :--- | :--- |
| **SQL** | 398 | $96,435 | Core Foundation / Highest overall volume |
| **Python** | 236 | $101,512 | Advanced Scripting / Crosses the $100k mark |
| **Tableau** | 230 | $97,978 | Dominant Business Intelligence tool |
| **Snowflake** | 37 | $111,578 | Elite Cloud Data Warehousing |
| **Looker** | 49 | $103,855 | Premium BI / Modern Data Stack |

# What I Learned
* **The Volume vs. Value Dilemma:** The skills that appear most often in job postings (Excel, basic SQL) do not command the highest salaries. Conversely, the highest-paying skills (Solidity, Couchbase) are rarely requested.
* **Strategic Stacking:** To maximize earning potential while keeping job security high, an analyst should target skills with high baseline counts *and* six-figure averages, such as **Python**, **Snowflake**, and **Looker**.
* **Data Engineering Creep:** High-paying data analysis is steadily turning into data engineering. Top salaries require understanding data streaming (Kafka), cloud warehouses (BigQuery/Redshift), and script versioning (Git).

# Conclusions
To build an optimal career path as a remote Data Analyst, your educational roadmap should happen in phases:
1.  **Secure the Entry Gate:** Master **SQL**, **Excel**, and **Tableau** to capture the widest market demand safety net.
2.  **Break the Earning Ceiling:** Learn **Python** (alongside Pandas/NumPy) to shift from descriptive analysis to data engineering and predictive modeling.
3.  **Target Elite Ecosystems:** Specialize in cloud-native tools like **Snowflake** and cloud platforms (**AWS/Azure**) to qualify for high-paying enterprise teams.