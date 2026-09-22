# Exploratory Data Analysis (EDA) Report

## 1. Introduction

This EDA report analyzes an AI Jobs dataset using Microsoft Excel.

The objective is to understand job-market patterns across job titles, salaries, experience levels, employment types, locations, education requirements, industries, and remote-work arrangements.

---

## 2. Dataset Overview

- Total Records: 15,000
- Total Columns: 26
- Missing Values: None in the cleaned dataset
- Salary Range: $32,519 – $399,095
- Average Salary: Approximately $115,349
- Median Salary: Approximately $99,705

The dataset contains information about AI-related job opportunities, companies, salaries, experience requirements, education requirements, locations, industries, and work arrangements.

---

## 3. Data Structure

The dataset contains fields covering:

- Job information
- Salary information
- Experience level
- Employment type
- Company location
- Company size
- Employee residence
- Remote-work ratio
- Required skills
- Education requirements
- Years of experience
- Industry
- Posting dates
- Application deadlines
- Company information

Additional derived fields were created for analysis, including:

- Remote Work Type
- Salary Band
- Posting Year
- Posting Month
- Month Name
- Quarter
- Day Name

---

## 4. Data Cleaning

The cleaned dataset was prepared before analysis.

The cleaning process included:

- Reviewing the dataset structure
- Checking for missing values
- Standardizing fields for analysis
- Creating derived analytical columns
- Preparing date-related fields
- Creating salary bands
- Categorizing remote-work arrangements

After cleaning, the dataset contained 15,000 records with no missing values.

---

## 5. Exploratory Analysis

### 5.1 Job Analysis

The dataset contains a variety of AI-related job roles.

The most frequently occurring job titles include:

- Machine Learning Researcher
- AI Software Engineer
- Autonomous Systems Engineer
- Machine Learning Engineer
- AI Architect
- Head of AI
- NLP Engineer
- Robotics Engineer
- Data Analyst
- AI Research Scientist

---

### 5.2 Salary Analysis

Salary analysis shows considerable variation across AI-related roles.

Key statistics:

- Average Salary: Approximately $115,349
- Median Salary: Approximately $99,705
- Minimum Salary: $32,519
- Maximum Salary: $399,095

Salary bands were also created to support easier comparison between lower-, medium-, and higher-salary jobs.

---

### 5.3 Experience-Level Analysis

The dataset contains four experience categories:

| Experience Level | Job Records |
|---|---:|
| MI | 3,781 |
| EX | 3,760 |
| SE | 3,741 |
| EN | 3,718 |

The distribution is relatively balanced across the four experience categories.

---

### 5.4 Location Analysis

The dataset includes job opportunities across multiple countries.

Countries with high job-record counts include:

- Germany
- Denmark
- Canada
- France
- Austria
- Singapore
- China
- India
- Sweden
- Israel

Germany has the highest number of records in the dataset with 814 job records.

---

### 5.5 Employment Type Analysis

The dataset contains four employment types:

| Employment Type | Job Records |
|---|---:|
| FT | 3,812 |
| FL | 3,758 |
| CT | 3,721 |
| PT | 3,709 |

The distribution is relatively balanced across employment types.

---

### 5.6 Remote Work Analysis

Remote-work arrangements are categorized into:

| Work Type | Job Records |
|---|---:|
| Onsite | 5,075 |
| Hybrid | 5,005 |
| Remote | 4,920 |

Onsite roles have the highest record count, followed closely by hybrid and remote roles.

---

### 5.7 Education Analysis

The dataset contains four education categories:

| Education Requirement | Job Records |
|---|---:|
| Bachelor | 3,789 |
| Associate | 3,785 |
| Master | 3,748 |
| PhD | 3,678 |

The distribution is relatively balanced across the education categories.

---

### 5.8 Industry Analysis

The dataset covers multiple industries.

Industries with high job-record counts include:

- Retail
- Media
- Automotive
- Consulting
- Technology
- Real Estate
- Government
- Transportation
- Telecommunications
- Healthcare

Retail has the highest number of records among the listed industries, with 1,063 job records.

---

### 5.9 Company Size Analysis

Company sizes are distributed almost evenly:

| Company Size | Job Records |
|---|---:|
| Small | 5,007 |
| Large | 4,998 |
| Medium | 4,995 |

This provides a balanced basis for comparing job and salary patterns across company sizes.

---

### 5.10 Salary Band Analysis

The dataset contains three salary bands:

| Salary Band | Job Records |
|---|---:|
| Low | 7,532 |
| Medium | 5,985 |
| High | 1,483 |

The Low salary band contains the largest number of records.

---

### 5.11 Job Posting Trend

The dataset contains job postings from 2024 and 2025.

| Posting Year | Job Records |
|---|---:|
| 2024 | 11,332 |
| 2025 | 3,668 |

The dataset therefore contains more records from 2024 than 2025.

---

## 6. Pivot Table Analysis

Pivot Tables were used to summarize and compare important dimensions of the dataset.

The analysis includes comparisons involving:

- Job titles
- Salary
- Experience level
- Employment type
- Company location
- Company size
- Education
- Industry
- Remote-work type
- Posting periods

Pivot Tables helped convert the detailed dataset into summarized information that could be used for charts and dashboard reporting.

---

## 7. Data Visualization

Charts were created to communicate the analysis visually.

The visualization section includes charts related to:

- Job distribution
- Salary patterns
- Experience levels
- Employment types
- Locations
- Industries
- Remote-work arrangements
- Other analytical dimensions

These visualizations were incorporated into the Excel reporting workflow.

---

## 8. Key Findings

The EDA highlights several characteristics of the dataset:

1. The dataset contains 15,000 AI-related job records.
2. Average salary is approximately $115,349.
3. Salary varies considerably across the dataset.
4. Experience-level categories have relatively balanced distributions.
5. Employment types are also relatively evenly distributed.
6. Onsite and hybrid roles slightly outnumber remote roles.
7. Company sizes are almost evenly represented.
8. Retail has the highest record count among the major industries shown.
9. Germany has the highest job-record count among the listed countries.
10. The dataset contains substantially more 2024 postings than 2025 postings.

---

## 9. Conclusion

This EDA demonstrates how raw AI job data can be transformed into structured analytical information using Microsoft Excel.

The workflow combines data cleaning, derived fields, Pivot Tables, charts, and dashboard reporting to make a large dataset easier to understand and interpret.

The resulting analysis provides a structured view of AI job-market characteristics across salary, experience, employment type, location, education, industry, company size, and remote-work arrangements.