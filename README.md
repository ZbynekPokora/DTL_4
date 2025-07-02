# Uncovering trends in Czech Healthcare Data with LLM tools

Overview
This project will use cutting-edge LLM tools to explore one of the largest healthcare movement datasets in the Czech Republic. The dataset consists of origin-destination (O-D) records of patient visits across the country between 2010 and 2022, totaling approximately 100 million visits across various healthcare groups (e.g., emergency, preventive, and specialized care).

The primary goal is twofold:
Descriptive Exploration of Spatio-Temporal Trends
Use LLMs to interactively query and summarize patterns in healthcare utilization across time and geography. This includes analyzing how different types of care were accessed over time, how demand fluctuated during crises (e.g., COVID-19), and how different regions varied in care-seeking behavior.


Network-Based Modeling and Analysis
 Model the healthcare system as a dynamic, weighted network of patient flows between regions. Use graph-based methods to uncover community structures, regional dependencies, and temporal changes in connectivity between healthcare providers and districts.


Data: UZIS healthcare data
The data directory contains two files:
“UZIS.zip”: containing the origin-destination aggregated numbers of healthcare visits, grouped across healthcare categories and on monthly aggregation.
“Lau1-current-iz.shp.zip”: shapefiles of origin/destination regions present in the data.
