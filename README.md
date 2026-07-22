# HR-Analysis-Dashboard
Power BI HR Analytics Dashboard analyzing employee attrition &amp; demographics. Features key KPIs (total count, attrition rate, active staff, avg age) alongside visual breakdowns by department, education, age, gender, and job satisfaction. Designed to help HR teams identify retention risks and make data-driven workforce decisions.


# 📊 HR Analytics Dashboard: Workforce Demographics & Attrition Insights

## 1. Project Title / Headline
**People Analytics: Interactive HR Attrition & Workforce Satisfaction Dashboard**  
A dynamic, interactive Power BI report built to analyze employee attrition patterns, workplace satisfaction, and demographic drivers across organizational tiers.

---

## 2. Short Description / Purpose
The HR Analytics Dashboard is a visually engaging and analytical Power BI report designed to help HR leaders and executive management identify the key drivers of employee turnover. By analyzing workforce metrics such as department-wise attrition, job satisfaction scores, education backgrounds, and age-gender demographics, this tool empowers organizations to implement data-driven employee retention strategies.

---

## 3. Tech Stack
The dashboard was built using the following tools and technologies:

* 📊 **Power BI Desktop** – Main data visualization platform used for report creation and visual design.
* 📁 **Power Query** – Data cleaning, transformation, and custom column profiling (e.g., age band grouping).
* 🧠 **DAX (Data Analysis Expressions)** – Used for calculated measures (Attrition Rate %, Active Employee count, Average Age).
* 🎨 **Data Modeling** – Built relational model and cross-filtering functionality across demographic and job role dimensions.
* 📁 **File Format** – `.pbix` for dashboard development and `.png` for repository preview.

---

## 4. Data Source
**Source:** `HR_Analytics_Data.csv` (Employee Records Dataset)

The dataset contains employee background and performance metrics including `Overall Employee Count`, `Attrition`, `Department`, `Job Role`, `Job Satisfaction Rating`, `Education Field`, `Age Band`, and `Gender`.

---

## 5. Features / Highlights

### 🎯 Business Problem
High employee turnover leads to increased recruitment costs, loss of institutional knowledge, and reduced productivity. Without centralized analytics, HR teams struggle to pinpoint whether turnover is driven by satisfaction levels, specific job roles, or demographic factors.

### 💡 Goal of the Dashboard
To provide an interactive, single-page executive overview that highlights high-risk attrition groups, evaluates job satisfaction across roles, and isolates actionable workforce trends.

### 📊 Key Insights & Metrics Analyzed
* **Primary KPIs:** Overall Employee Count (572), Total Attrition (99), Attrition Rate (17%), Active Employees (473), and Average Employee Age (36.48 years).
* **Department-wise Attrition:** Identifies that **R&D** accounts for the highest share of turnover (56.57%), followed by **Sales** (39.39%) and **HR** (4.04%).
* **Job Satisfaction Heatmap:** Cross-tabulates satisfaction ratings (rated 1 to 4) across roles—highlighting lower satisfaction clusters in *Laboratory Technicians*, *Sales Executives*, and *Research Scientists*.
* **Education Field Breakdown:** Measures attrition by academic background, showing highest attrition among employees with *Life Sciences* (37) and *Medical* (25)
*
 ## 6. Screenshot
Shows how the dashboard looks like.

    degrees.
* **Demographics & Gender Analysis:** Segmented age bands (Under 25 to Over 55) showing gender distribution and age-wise attrition percentages to pinpoint career stage drop-offs.
