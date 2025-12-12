# STAT540 Project 2 – Data Wrangling with dplyr and tidyr  
**Author:** Shantal Ewell  
**Date:** `r Sys.Date()`  

---

## Project Overview

This project was completed as part of STAT540 and focuses on demonstrating proficiency in **data wrangling**, **table manipulation**, and **tidy data principles** in R.  
The main objective is to analyze traffic stop data in Mississippi and combine it with U.S. Census demographic information to explore patterns related to race, age, county, and policing behavior.

The project uses real-world datasets:

- **MS_trafficstops_bw_age.csv** — over 211K traffic stop records from 2013–2016  
- **MS_acs2015_bw.csv** — county-level population demographics for Black and White residents  

The motivation for this project is to apply practical tidyverse techniques used in real data analysis, including:

- Filtering and selecting columns  
- Grouped summaries  
- Mutating new variables  
- Joining datasets  
- Pivoting between long and wide formats  
- Using the pipe operator (`%>%`) to build clean workflows  

This project shows how data wrangling supports insights into racial disparities, policing patterns, and demographic context across Mississippi counties.

---

## Project Goals

1. Demonstrate correct use of **dplyr** functions: `select`, `filter`, `mutate`, `summarize`, `group_by`, `count`, and joins.  
2. Apply the **pipe operator** to build readable and efficient workflows.  
3. Work with **wide vs. long data formats** using `pivot_wider()` and `pivot_longer()`.  
4. Download, import, and clean raw datasets using tidy principles.  
5. Produce a fully reproducible R Markdown report.

---



