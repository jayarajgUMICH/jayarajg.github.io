# Optimizing Nursing Home Distribution and Quality  
**Analyzing Medicare/Medicaid Enrollment & Aging Population Trends**

## About the Project
As the U.S. population continues to age, the demand for long-term care grows. But are nursing homes being built in the areas that need them most?

In this project, we explored the relationship between Medicare/Medicaid enrollment, population demographics (65+), and nursing home distribution and quality. Using publicly available CMS data, we analyzed regional trends to identify where access to high-quality long-term care could be improved.

This was originally completed as part of a graduate-level course in health informatics, but it has real-world relevance for health policy, planning, and equity.

---

## Project Goals
- Find regions with high need but low access to nursing home care  
- Compare nursing home quality and staffing metrics across U.S. regions  
- Visualize enrollment and facility data to spot gaps and opportunities  
- Support data-informed decisions around long-term care investments  

---

## Key Questions We Asked
- Are some regions better served by nursing homes than others?
- Do areas with more Medicare/Medicaid enrollees also have more or better facilities?
- Where might new nursing homes have the biggest impact?
- How do staffing and quality ratings vary by state or region?

---

## Datasets Used

### CMS Provider Data  
Includes nursing home ratings, bed counts, staffing levels, and geographic data  
**Source:** [CMS Provider Dataset](https://data.cms.gov/provider-data/dataset/4pq5-n9py)

### Medicare/Medicaid Monthly Enrollment  
Includes enrollment counts by county, age group, and coverage type  
**Source:** [CMS Enrollment Dataset](https://data.cms.gov/summary-statistics-on-beneficiary-enrollment/medicare-and-medicaid-reports/medicare-monthly-enrollment/data)

---

## What We Did with the Data
- Replaced placeholder null values like `'*'` with proper `NaN`s
- Filtered to only the fields relevant to our analysis (ratings, location, etc.)
- Focused on people aged 65+ for our population analysis
- Merged datasets by state and county to align facilities with populations
- Grouped states into four major U.S. regions (West, South, Midwest, Northeast)

---

## How We Analyzed It
- Conducted descriptive analysis on ratings, bed counts, and staffing  
- Compared metrics across Medicare/Medicaid enrollment rates  
- Visualized geographic trends to identify areas of need  
- Focused on regional gaps, particularly in the Western U.S.  

You’ll find full code and visualizations in the `/notebooks` and `/visualizations` folders.

---

## Highlights from the Results
- Average overall quality rating: 2.86 / 5  
- Lowest average score: Staffing (2.68 / 5)  
- Highest average score: Quality Measures (3.5 / 5)  
- Western states showed the biggest mismatch between aging populations and available facilities  
- Several counties with high enrollment had few or no CMS-certified nursing homes

---

## Why This Matters
This kind of data analysis can help:
- Policymakers make better decisions about where to invest in long-term care
- Healthcare systems advocate for resources in underserved areas
- Communities plan for aging population needs before they become crises

---

## Ethical Considerations
- Identifiable facility data was excluded to protect privacy  
- No race-based analysis was performed to reduce demographic bias  
- Only CMS-certified homes were included, which limits completeness  
- All data sources were publicly available and ethically sourced

---

## Limitations
- Does not include private (non-CMS) nursing homes  
- County-level granularity only; more specific data could yield better insights  
- Benchmarking for quality scores was estimated at a midpoint of 2.5/5  
- Not all older communities require institutional care, which complicates assumptions

---

## Future Work
- Incorporate private facility data to get a fuller picture of coverage  
- Build predictive models for future geographic care gaps  
- Add other factors like income, access to transportation, or local health resources

---

## Team Contributions
- **Bowen Zheng** – data cleaning, geospatial analysis, methodology  
- **Gautham Jayaraj** – enrollment trends, visualizations, editing  
- **Jared Nelson** – quality metrics, narrative drafting, synthesis

---

## Contact
Interested in collaborating or have questions?

Email: gaujay7@gmail.com
LinkedIn: [linkedin.com/in/yourprofile](www.linkedin.com/in/gauthamjayaraj)  

---

## References
- [CMS Nursing Home Oversight](https://www.cms.gov/medicare/health-safety-standards/quality-safety-oversight-general-information/nursing-homes)  
- [Rural Health Information Hub](https://www.ruralhealthinfo.org/topics/healthcare-access)  
- [CMS Enrollment Data](https://data.cms.gov/summary-statistics-on-beneficiary-enrollment/medicare-and-medicaid-reports/medicare-monthly-enrollment/data)
