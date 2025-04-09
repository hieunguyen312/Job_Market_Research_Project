# 📊 Job Market Research Project

A data-driven exploration of the U.S. job market using job postings from LinkedIn and Indeed (2023–2024), enriched with salary normalization, industry classification, and geographic insights.

---

## 🚧 Work in Progress

🔗 [**View the current interactive HTML report**](https://htmlpreview.github.io/?https://github.com/hieunguyen312/Job_Market_Research_Project/blob/main/Job_Market_Project.html)

---

## 📌 Project Overview

This project explores patterns and insights from job posting data across the United States. By analyzing listings from LinkedIn and Indeed, the report aims to help job seekers, employers, and policy makers better understand:

- 🧠 In-demand skills and industries
- 🌎 Regional differences in job opportunities and salaries
- 💰 Normalized salary trends across different currencies and pay periods
- 🏢 Shifts in hiring trends, especially in the tech sector
- 🗓️ Temporal patterns in job availability

---

## 📁 Key Features

- Cleaned and processed thousands of job listings using R
- Handled duplicate and inconsistent entries with care
- Normalized salary data to annual USD equivalent
- Converted and visualized time data from UNIX timestamps
- Mapped job counts geographically across U.S. states
- Analyzed job industries using natural language processing (NLP)
- Connected education trends with job market demands

---

## 📊 Technologies Used

- **R** (Data wrangling and visualization)
- **RMarkdown** (Report generation)
- **Libraries**:  
  `tidyverse`, `readr`, `scales`, `tidytext`, `maps`, `ggthemes`, `readxl`

---

## 📚 Datasets

- [📂 LinkedIn Job Postings (Kaggle)](https://www.kaggle.com/datasets/arshkon/linkedin-job-postings/data)  
- [📈 U.S. Job Openings Index (FRED)](https://fred.stlouisfed.org/series/IHLIDXUS)
- [📂 1.3M LinkedIn Job Posting](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024/data)
- [💻 U.S. Tech Job Openings Index (FRED)](https://fred.stlouisfed.org/series/IHLIDXUSTPSOFTDEVE)  
- 📎 Additional `.csv` and `.xlsx` files included in the repository

---

## 🚀 How to Run This Project

### 🔧 Prerequisites

- R and RStudio (latest version recommended)
- R Packages:
  ```r
  install.packages(c("tidyverse", "readr", "scales", "tidytext", "maps", "ggthemes", "readxl"))
