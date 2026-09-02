# 📊 Real-Time Job Analytics Portal

## 📌 Project Overview

The **Real-Time Job Analytics Portal** is an interactive data visualization project developed using **Tableau** to analyze and explore job-market data.

The project was developed as part of my data analytics learning and internship work. It combines the concepts and applications covered during the training phase with the assigned internship tasks into a single integrated Tableau workbook.

The portal provides interactive visualizations that help analyze job opportunities based on factors such as:

- Work Type
- Job Title
- Company
- Salary
- Company Size
- Experience
- Qualification
- Preference
- Country
- Job Portal
- Location

The objective of the project is to transform raw job-posting data into meaningful and interactive visual insights.

---

## 🎯 Project Objectives

The major objectives of this project are:

- Analyze job-market trends using real-world job-posting data.
- Understand relationships between different job attributes.
- Create interactive Tableau visualizations.
- Apply filters and conditions to extract meaningful subsets of data.
- Analyze salary distributions and company hiring patterns.
- Compare job opportunities across countries.
- Visualize geographic job-posting data using maps.
- Develop an interactive portal to present the completed analysis.
- Apply data visualization and analytical concepts learned during training to practical internship tasks.

---

## 🛠️ Tools & Technologies

- **Tableau Desktop / Tableau Public** – Data visualization and dashboard development
- **Microsoft Excel / CSV** – Dataset handling and preparation
- **GitHub** – Project documentation and source-code hosting
- **HTML / CSS** – Web portal implementation
- **GitHub Pages** – Website deployment

---

## 📂 Project Structure

The project consists of training applications and internship tasks integrated into a single Tableau workbook.

### Training Phase

During the training phase, multiple worksheets and a dashboard were developed to understand the dataset and Tableau visualization concepts.

The training work covered different analytical views and visualization techniques before moving to the internship-specific tasks.

### Internship Phase

The internship phase consisted of multiple analytical visualization tasks. All completed tasks were maintained within the same Tableau workbook to keep the project integrated with the training applications.

---

# 📊 Internship Tasks

## Task 1 — Preference vs Work Type

### Visualization
**Bar Chart**

### Objective
Analyze the relationship between **Preference** and **Work Type** for internship opportunities.

### Conditions Applied

- Work Type = `Intern`
- Company Size < `50,000`
- Salary > `$9,000`
- Results sorted in descending order based on count

### Purpose

This visualization shows how different preferences are distributed across available internship opportunities.

---

## Task 2 — Company Size vs Company Name

### Visualization
**Scatter Plot**

### Conditions Applied

- Company Size < `50,000`
- Job Title = `Mechanical Engineer`
- Experience > `5 years`
- Salary > `$50,000`
- Work Type = `Full-Time` or `Part-Time`
- Preference = `Male`
- Asian countries included
- Countries starting with `I` excluded
- Job Portal = `Idealist`
- Company Name contains at least two vowels

### Additional Requirement

The visualization was configured to be visible only between:

**3:00 PM and 5:00 PM IST**

### Purpose

This visualization examines the relationship between company size and companies offering Mechanical Engineer positions under the specified conditions.

---

## Task 3 — Work Type Salary Distribution

### Visualization
**Box-and-Whisker Plot**

### Conditions Applied

- Work Type = `Intern`
- Latitude < `10`
- Company Size < `50,000`
- Salary > `$8,000`
- Job Title contains a single word
- Job Title length < `10 characters`
- Experience is an even number
- Posting Date between `2021` and `2023`
- Contact Person's name contains at least one `e`

### Additional Requirement

The visualization was configured to be visible only between:

**3:00 PM and 5:00 PM IST**

### Purpose

The visualization analyzes the salary distribution and spread for internship opportunities satisfying the specified conditions.

---

## Task 4 — India vs Germany Job Comparison

### Visualization
**Stacked Bar Chart**

### Countries

- India
- Germany

### Conditions Applied

- Qualification = `B.Tech`
- Work Type = `Full-Time`
- Experience > `2 years`
- Job Role includes:
  - Data Scientist
  - Art Teacher
  - Aerospace Engineer
- Salary > `$10,000`
- Job Portal = `Indeed`
- Company Name length > `8 characters`
- Location is not empty

### Purpose

This visualization compares job-posting trends between India and Germany and highlights differences in job availability under the specified conditions.

---

## Task 5 — Top 10 Companies

### Visualization
**Treemap**

### Conditions Applied

- Role = `Data Engineer`
- Job Title = `Data Scientist`
- Asian countries excluded
- Countries starting with `C` excluded
- Company Size >= `10,000`
- Qualification = `B.Tech`
- Preference = `Female`
- Job Portal = `LinkedIn`
- Posting Date between `01/01/2023` and `06/01/2023`
- Contact Person's name ends with a vowel

### Additional Requirement

The visualization was configured to be visible only between:

**3:00 PM and 5:00 PM IST**

### Purpose

The treemap identifies the top 10 companies based on the filtered job-posting data.

---

## Task 6 — Qualification Drilldown Map

### Visualization
**Geographic Map**

### Conditions Applied

- Countries located in Africa
- Qualification:
  - B.Tech
  - M.Tech
  - PhD
- Work Type = `Full-Time`
- Job Title starts with `D`
- Preference = `Male`
- Company Size > `80,000`
- Salary > `$20,000`
- Contact Person's name starts with `A`
- Job Portal = `Indeed`

### Geographic Fields

- Latitude
- Longitude

### Additional Requirement

The visualization includes drilldown functionality to allow users to explore individual job locations.

The visualization was configured to be visible only between:

**3:00 PM and 6:00 PM IST**

### Purpose

This map provides a geographic view of job postings matching the specified qualification, company, salary, and role conditions.

---

# 🧩 Integrated Tableau Workbook

All training applications and internship tasks were developed and maintained within a **single Tableau workbook**.

This approach keeps the project connected to the concepts and applications completed during the training phase rather than treating the internship tasks as an unrelated standalone project.

The workbook contains:

- Training worksheets
- Training dashboard
- Internship task worksheets
- Internship task dashboard/views
- Interactive filters and calculated fields
- Geographic visualizations
- Time-based visibility conditions
- Final portal/dashboard components

---

# 🌐 Real-Time Job Analytics Portal

The completed Tableau analysis is presented through a web-based portal.

The portal provides an accessible interface for viewing the Tableau visualizations online.

### Portal Flow

```text
Real-Time Job Analytics Portal
            │
            ├── Training Analysis
            │       └── Training Dashboard
            │
            └── Internship Analysis
                    └── Internship Tasks
                            ├── Task 1
                            ├── Task 2
                            ├── Task 3
                            ├── Task 4
                            ├── Task 5
                            └── Task 6
