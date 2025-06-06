## Portfolio

---

### Project #1

[Optimizing Nursing Home Distribution and Quality Using Medicare/Medicaid Enrollment and Population Trends](/nursing_home_project.md)

This project was completed as part of a graduate-level technical report in health informatics. The objective was to evaluate and improve the distribution and quality of nursing homes across the United States using publicly available healthcare and demographic data.

We sourced our data from CMS’s Chronic Conditions Data Warehouse and the Medicare Monthly Enrollment datasets. The analysis integrated geographic, enrollment, and quality rating data to identify underserved areas, evaluate staffing and quality measures, and propose strategies for improving long-term care.

**Key questions we explored:**
- Does region (Midwest, South, East, and West) correlate with higher rates of Medicare/Medicaid enrollment and the distribution of nursing homes?
- What quality measures do nursing homes perform well in, and where is there room for improvement?
- Which states have a higher older population (65+) where more nursing homes would be beneficial?

**What we did:**
- Conducted correlation and geographic trend analysis by U.S. region  
- Filtered and cleaned large datasets to focus on metrics like staffing, certified beds, and quality measures  
- Built visualizations to highlight discrepancies in access and performance  
- Evaluated areas for potential new nursing home development based on need and population trends

**Skills used:** Python (Pandas), data cleaning, exploratory data analysis (EDA), geographic trend analysis, public health data interpretation, and data visualization (e.g., maps, charts).

This work aims to support healthcare administrators, policymakers, and community planners in making data-driven decisions to ensure better long-term care access and equity.

Sample visualizations:

<img src="images/Business Question 2 Picture 1.png?raw=true"/>
<img src="images/Business Question 2 Picture 2.png?raw=true"/>
<img src="images/Business Question 2 Picture 3.png?raw=true"/>

---

### Project #2

[Improving Prescription Alert Efficiency Through Data-Driven EHR Analysis](/alert_efficiency_project)

This project was developed as part of a graduate-level assignment focused on information systems and data-driven decision-making in healthcare. The goal was to evaluate how clinical alerts function within Electronic Health Record (EHR) systems and propose improvements to reduce inefficiencies in prescription-related notifications.

Using a de-identified dataset of provider encounters, alerts, actions, and medication orders, I examined alert frequency, response times, and prescription changes to assess whether current alert systems were effectively supporting clinical workflows.

**Key questions we explored:**
- What are the number of encounters and alerts handled per provider?
- What are the most common alert reasons and medications involved?
- How quickly do providers respond to alerts, and does that vary by role?
- What percentage of alerts result in an actual change to medication?
- How is provider action distributed across different types of alerts?

**What we did:**
- Created a relational database structure with five normalized tables (alerts, encounters, providers, actions, and medications)
- Cleaned and reduced the dataset by removing redundant and null-heavy columns (e.g., override reason, duplicate provider IDs)
- Joined key tables to compute metrics such as alert frequency, response time, and change rates
- Used SQL to perform detailed aggregations and visual breakdowns of provider behavior and alert effectiveness
- Identified potential inefficiencies in alert design that could be addressed with smarter EHR alert logic

**Skills used:** SQL (PostgreSQL), database normalization, ERD design, data cleaning, relational joins, aggregation queries, and healthcare data interpretation.

This work was part of a proposal to improve hospital EHR systems, aiming to reduce alert fatigue and enhance decision-making by tailoring alerts to be more actionable and timely.

---

## Project #3  
**Segmenting U.S. Healthcare Facilities with K-Means and UMAP to Identify Operational Trends**
[Improving Prescription Alert Efficiency Through Data-Driven EHR Analysis](/alert_efficiency_project)

This project was completed as part of a graduate-level data science course in health systems. The goal was to uncover meaningful patterns in U.S. hospital operations using clustering techniques, with a focus on charges, staffing, and inpatient vs. outpatient capacity.

Using publicly available data from the Centers for Medicare & Medicaid Services (CMS), we analyzed hospital-level metrics to explore how facilities vary in resource allocation and cost structures. The outcome was a set of interpretable clusters that offer insights into operational variation across the U.S. healthcare system.

### Key questions we explored:
- Can U.S. hospitals be grouped by operational similarities (e.g., charges, staffing, bed availability)?
- Do geographic or service-type patterns emerge across these clusters?
- What defines facilities with high inpatient costs vs. outpatient-oriented care?

### What we did:
- Cleaned and preprocessed CMS hospital data by removing null-heavy and duplicate fields
- Standardized key operational metrics such as total charges, outpatient services, and staffing
- Performed K-means clustering to segment hospitals into groups based on selected features
- Used UMAP (Uniform Manifold Approximation and Projection) to reduce dimensionality for visualization
- Interpreted cluster profiles to identify meaningful operational differences

### Skills used:
**R**, `kmeans`, `umap`, `dplyr`, `ggplot2`, data wrangling, unsupervised learning, dimensionality reduction, healthcare systems analysis

### Why it matters:
This project demonstrates how machine learning techniques like clustering and dimensionality reduction can support more data-informed health policy and operational planning. By understanding the different types of hospitals that exist across the U.S., decision-makers can more effectively allocate resources, benchmark performance, and target interventions where they’re most needed.

### Category Name 2

- [Project 1 Title](http://example.com/)
- [Project 2 Title](http://example.com/)
- [Project 3 Title](http://example.com/)
- [Project 4 Title](http://example.com/)
- [Project 5 Title](http://example.com/)

---




---
<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
