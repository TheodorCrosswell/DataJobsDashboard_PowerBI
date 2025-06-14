# Data Jobs Analysis - Power BI Dashboard

This interactive Power BI dashboard provides a comprehensive overview of the data jobs market, analyzing over 400,000 job postings. The report allows users to explore high-level trends and drill down into specific job titles for granular insights into salaries, benefits, and global distribution.

![Data Jobs Dashboard](https://github.com/TheodorCrosswell/DataJobsDashboard_PowerBI/blob/c12bbc4ff5982da2b91a422809a2156828cdd312/images/Data_Jobs_Dashboard-images-0.jpg)
![Data Jobs Dashboard](https://github.com/TheodorCrosswell/DataJobsDashboard_PowerBI/blob/1adbd5c1c08311abe96c44ab3243ab859cdecf93/images/Data_Jobs_Dashboard-images-1.jpg)
---

## 🚀 Key Features

*   **At-a-Glance KPIs:** Immediately understand the state of the data jobs market with key metrics for total job count, average star rating, and median salaries.
*   **Time Series Analysis:** Track the volume of data job postings over time with a monthly trend line.
*   **Job Title Comparison:** Compare job titles by volume and salary using interactive charts and tables.
*   **Dynamic Filtering:** Filter the entire dashboard by a specific `Job Title` to focus the analysis.
*   **Drill-Through Capability:** Go from a high-level overview to a detailed report for a specific job title (e.g., Business Analyst) with a single click.
*   **Geographic Job Distribution:** Visualize the global concentration of job opportunities on an interactive map.
*   **Benefit & Requirement Analysis:** Instantly see statistics on remote work options, degree requirements, and health insurance offerings for specific roles.

---

## 📊 Dashboard Pages

The report consists of two main pages: the main dashboard for a general overview and a drill-through page for a detailed look at a specific role.

### 1. Main Dashboard Overview

This page serves as the central hub for analyzing the overall data jobs landscape.

![Data Jobs Dashboard](https://github.com/TheodorCrosswell/DataJobsDashboard_PowerBI/blob/c12bbc4ff5982da2b91a422809a2156828cdd312/images/Data_Jobs_Dashboard_1.gif)


**Visuals on this page include:**
*   **KPI Cards:** Total Job Count (406K), Star Rating, Median Yearly Salary ($113K), and Median Hourly Salary ($50).
*   **How many data jobs per month?:** A line chart illustrating the trend of job postings from January to October 2024.
*   **How many data jobs?:** A bar chart ranking job titles by the number of available positions, with Data Engineer, Data Analyst, and Data Scientist as the top roles.
*   **Hourly vs Yearly Salary:** A scatter plot showing the correlation between median hourly and yearly salaries for different job titles.
*   **Job Details Table:** A filterable matrix providing specific salary and job count numbers for each role.
---

### Using the Drill-Through Button

For quick navigation, use the dedicated drill-through button located in the top-right corner of the main dashboard.

1.  **Select a Job Title:** First, click on a single job title in any of the visuals (e.g., click the "Data Engineer" bar in the "How many data jobs?" chart).
2.  **Activate the Button:** Notice how the drill-through button updates, now reading "Drill Through To Data Engineer".
3.  **Click to Navigate:** Click this button to be instantly taken to the detailed report page for that specific role.

![Drill-Through Button Demo GIF](https://github.com/TheodorCrosswell/DataJobsDashboard_PowerBI/blob/1adbd5c1c08311abe96c44ab3243ab859cdecf93/images/Data_Jobs_Dashboard_2.gif)
---

### 2. Job Title Drill-Through Page

This page provides a deep dive into a single job title, in this case, **Business Analyst**. It is accessed by right-clicking a job title in a chart or using the drill-through button.

![Data Jobs Dashboard](https://github.com/TheodorCrosswell/DataJobsDashboard_PowerBI/blob/c12bbc4ff5982da2b91a422809a2156828cdd312/images/Data_Jobs_Dashboard_3.gif)

**Visuals on this page include:**
*   **Salary Gauges:** Visual gauges showing the median yearly and hourly salaries against the overall range for the role.
*   **Jobs Globally:** An interactive map showing the geographic density of Business Analyst jobs around the world.
*   **Benefit & Perk Donuts:** Donut charts breaking down the percentage of jobs that offer Work From Home, have No Degree requirements, and include Health Insurance.
*   **Job Platform:** A bar chart showing which job platforms (e.g., LinkedIn, Indeed) have the most listings for the role.
*   **Job Schedule Type:** A chart highlighting the employment type, dominated by Full-time positions.

---

## 🛠️ How to Use the Dashboard

1.  **Get the Big Picture:** Start on the main dashboard to see the summary KPIs and overall trends.
2.  **Filter by Role:** Use the **Job Title** dropdown menu at the top to filter all visuals on the main page for a specific role you are interested in.
3.  **Drill Down for Details:** To explore a role in-depth, **right-click** on a bar in the "How many data jobs?" chart (or a row in the table) and select **Drill Through**.
4.  **Navigate Back:** Once on the drill-through page, use the **back arrow** in the top-left corner to return to the main dashboard.
5.  **Hover for Info:** Hover your mouse over any data point on any chart to reveal a tooltip with more specific information.

---

## 💾 Data Source

The dashboard is built using a sample dataset of over 400,000 data job postings. The dataset contains information such as:
*   Job Title
*   Company Name
*   Location (City, Country)
*   Median Salary (Yearly and Hourly)
*   Job Posting Date
*   Job Platform/Source
*   Job Benefits (Work From Home, Health Insurance)
*   Educational Requirements
---

## 💻 Tools Used

*   **Power BI Desktop:** For data modeling, analysis, and visualization.
*   **Snipping Tool**: For capturing demonstration video.
*   **ClipChamp**: For editing and producing demonstration GIFs.
