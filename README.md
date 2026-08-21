Geographic Access to Cardiac Care

Outcomes Across the Southern U.S.

Nashville Software School, DA17 Capstone Project

 Overview

This project looks at whether where someone lives affects their cardiac care outcomes. It covers 1,318 counties across 13 Southern states: Alabama, Arkansas, Florida, Georgia, Kentucky, Louisiana, Mississippi, North Carolina, South Carolina, Tennessee, Texas, Virginia, and West Virginia.

The project uses four public datasets to answer three questions:

1. Does a county's cardiac care shortage status predict its readmission outcomes?
2. Do income, insurance coverage, or rurality predict readmission outcomes?
3. Are there high shortage counties that outperform expectations, and if so, why?

My Motivation

This project started with a personal experience. A family friend had a cardiac event in a rural area with limited hospital access nearby. That night raised a question about how location affects the chance of getting timely, effective cardiac care.

County level data on emergency response times is not tracked nationally, so this project uses 30 day hospital readmission rates as the closest available measure of ongoing care quality after diagnosis.

Key Findings

Almost 9 in 10 counties with no cardiac readmission data on file are majority rural. This means the counties most likely to lack access are also the counties we have the least ability to measure.

Cardiac care shortage status alone did not reliably predict readmission outcomes.

Income and rurality showed only a small relationship with readmission outcomes, too small to act on by themselves.

33 counties with high shortage status still ranked in the top tier for readmission performance. These counties are not only rural. Some sit near major cities and some are far from any metro area.

 Data Sources

HRSA Health Professional Shortage Areas (HPSA). County level cardiac and primary care shortage designations. Source: data.hrsa.gov/data/download

HRSA Medically Underserved Areas and Populations (MUA/P). County level designations for underserved areas. Source: data.hrsa.gov/data/download

CMS Hospital Readmissions Reduction Program. 30-day hospital-level cardiac readmission rates. Source: data.cms.gov

County Health Rankings (Robert Wood Johnson Foundation). Income, insurance coverage, and rurality by county. Source: countyhealthrankings.org

 Tools and Technologies

Python. Used for data cleaning, merging, and exploratory analysis.

Power BI. Used to build an interactive county level dashboard.

 Repository Structure

data/raw
Original downloaded files, unchanged.

data/cleaned
Cleaned and merged county level datasets used for analysis.

notebooks
The Jupyter notebook containing the full analysis, from raw data to final findings.

dashboard
The Power BI file 


presentation
A PDF copy of the capstone presentation slides.


 Getting Started

1. Clone the repository.


2. Install the required Python packages.

   pip install -r requirements.txt

3. Open notebooks/Amber_Gaines_Cardiac_Capstone.ipynb in Jupyter Notebook or JupyterLab. Run the cells in order. The notebook walks through raw data import, cleaning, merging, and analysis for each dataset, in sequence.

4. Open dashboard/cardiac_access_dashboard.pbix in Power BI Desktop to view the interactive dashboard. Power BI Desktop is free and available from Microsoft.

 Data Privacy

All data used in this project is public and reported at the county level. No patient level or individually identifiable information appears anywhere in the raw data, the notebook, or the dashboard.

 Author

Amber Gaines

Registered Cardiac Sonographer (RCS), CCI

SAFe SSM, SAFe POPM

Nashville Software School, DA17
