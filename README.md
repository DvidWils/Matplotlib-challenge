# Pymaceuticals Tumor Volume Study

This project analyzes the performance of various medications on the volume of tumors in mice diagnosed with squamous cell carcinoma, a commonly occurring form of skin cancer.
The primary objective was to evaluate the performance of Pymaceuticals' Capomulin drug, compared to other medication.
---

## Objectives

- Clean and merge dataset
- Generate descriptive statistics for each drug regimen
- Visualize the data using bar, pie, line, scatter, and box plots
- Identify outliers using interquartile ranges (IQR)
- Analyze trends in tumor progression and treatment outcomes
- Assess the correlation between mouse weight and tumor volume for Capomulin
---

## Dataset

- `Mouse_metadata.csv`: Mouse demographic and treatment info
- `Study_results.csv`: Tumor volume measurements collected
---

## Key Findings

Capomulin and Ramicane had lower final tumor volumes shown by the box plots and summary statistics. This indicates that they were most effective in reducing tumor size.
+ Capomulin's Mean = 40.67 mm3 & Median = 41.56 mm3
+ Ramicane's Mean = 40.22 mm3 & Median = 40.67 mm3

Capomulin and Ramicane had very similar effectiveness; They had comparable medians and IQRs, which indiacates a similar level of effectiveness and treatment performance.
+ Capomulin's IQR: 37.69 to 45.00
+ Ramicane's IQR: 36.58 to 45.00

The summary statistics showed Ketapril and Zoniferol having some of the highest average tumor volumes suggesting they were among the least effective treatments.
+ Ketapril's Mean = 55.24 mm3, Median = 53.70 mm3
+ Zoniferol's Mean = 53.23 mm3, Median = 51.82 mm3
---

## Tools

- Python (Pandas, Matplotlib, SciPy)
---

## Resources

Relied on in class activites and examples from the instructor.
ChatGPT was used for conceptual support and to clarify data analysis and visualization techniques.
