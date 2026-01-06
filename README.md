# Data Jobs Dashboard w/ Power BI

This project is the outcome of my participation in a comprehensive Power BI course delivered by [Luke Barousse](https://github.com/lukebarousse) and published on [YouTube](https://www.youtube.com/watch?v=FwjaHCVNBWA&t=12118s) .
The course provided a practical, hands-on approach to building real-world business intelligence solutions using Power BI.

## Introduction

This interactive dashboard was designed for **Job Seekers, Job Transitioners, and Job Swappers** to solve a common problem: information about the data job market is scattered and hard to grasp. Using a real-world dataset of 2024 data science job postings (including titles, salaries, schedule type and locations).

The goal is to provide a clear, navigable view of job demand, salaries, required skills, locations, and employment characteristics across data-related roles.

The analysis is structured across three interactive report pages, each designed with a specific analytical purpose:
a *general market overview*, a *comparative analysis between data job titles*, and a detailed *drill-through view for individual job titles*.


### Dashboard File
You can find the file for the dashboard here: [`Data_Jobs_Dashboard.pbix`](Data_Jobs_Dashboard.pbix).

---

## Skill Showcased

This project was a journey through key Power BI features. Here's a look at what we mastered:

- **⚙️ Power Query (ETL & Data Transformation)**:
Data cleaning, shaping, type handling, and feature engineering.

- **🔗 Data Modeling**:
Table relationships and Star Schema design principles.

- **🧮 DAX Measures (Implicit & Explicit)**:
KPI creation and custom calculations using functions such as
CALCULATE, context modifiers, and standard aggregations.

- **📊 Data Visualization**:
Core visuals including Bar, Column, Line, and Area charts,
as well as KPI cards and detailed tables.

- **🗺️ Geospatial Analysis**:
Map visuals for analyzing global job distribution.

- **🎛️ Dynamic & Parameter-Driven Analysis**:
Field and numeric parameters to enable what-if scenarios
and dynamically controlled visuals.

- **🖱️ Interactive Reporting**:
Slicers, advanced cross-filtering, buttons, bookmarks,
and drill-through navigation.

- **🎨 Dashboard Design & UX**:
Single-page optimization, layout clarity, and visual storytelling.

---

## Dashboard Pages Overview

### Page 1: Data Jobs Dashboard

![Data Jobs Dashboard](/img/Dashboard_page1.png)

This page provides a general overview of the data job market and summarizes the most relevant aggregate metrics.

Key elements:

- KPI cards showing total job count, average number of skills per job, median yearly salary, and median hourly salary
- A bar chart ranking the most requested skills, with the option to switch between job percentage and absolute job count
- A time series chart displaying job postings over time, with a toggle between job count and median salary
- A world map illustrating the geographic distribution of data jobs
- A donut chart showing the breakdown of job types (full-time, contractor, temporary)

This page is intended to answer the question: *“What does the data job market look like overall?”*

### Page 2: Data Jobs Comparison

![Data Jobs Comparison](/img/Dashboard_page2.png)

This page focuses on comparing different data job titles in terms of skills, salaries and demand.

Key elements:

- A scatter plot showing the relationship between median yearly salary and skill count for each job title
- A stacked bar chart breaking down skill types per job role
- A detailed table including job count, skill count, salary rating, and job trend indicators
- A horizontal bar chart ranking the top-paying data jobs, with a toggle between yearly and hourly salary
- A country slicer to filter the analysis geographically
- Drill-through functionality to access role-specific details

This page answers the question: *“How do different data title compare to each other?”*


### Page 3: Job Title Drill Through

![Job Title Drill Through](/img/Dashboard_page3.png)

This page provides a deep dive into a single job title, accessed via drill-through from the comparison dashboard.

Key elements:
- Gauge visuals for median yearly and median hourly salary
- Donut charts showing the percentage of job postings that mention: no degree requirement, smart working and health insurance
- A world map displaying the geographic distribution of the selected role
- A bar chart ranking the most requested skills for that job title
- A bar chart showing which platforms host the most job postings
- A donut chart illustrating the employment type distribution

This page answers the question: *“What are the concrete characteristics of this specific data title?”*

---

## Conclusion
The Data Jobs Dashboard brings together market-level trends and role-specific insights to provide a clear and structured view of the 2024 data job landscape.

Beyond its analytical value for end users, this project also proved valuable to the author, to understand demand, compensation and skill requirements across data-related roles, while improve Power BI and data analysis skills.