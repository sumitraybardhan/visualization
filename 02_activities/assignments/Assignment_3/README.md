
**Toronto Public Library Data Visualization**
This repository contains data and visualizations created for a course assignment on data visualization. The project examines how Toronto Public Library (TPL) physical space is distributed across municipal wards, building on prior work by Ahmad (2024) that explored library infrastructure across the city, and extending it using ward-level spatial analysis and mapping.  Ahmad, H. (2024). Mapping Toronto’s Libraries: Are Libraries Distributed Equally Throughout the City? January 25, 2024. https://tellingstorieswithdata.com/inputs/pdfs/paper-1-2024-HadiAhmad.pdf

**Data**
All data are derived from the City of Toronto Open Data Portal. 
Source datasets 
• Library Branch General Information https://open.toronto.ca/dataset/library-branch-general-information/ 
• City Wards (Boundary Files) https://open.toronto.ca/dataset/city-wards/ 
Processed data 
• data/ toronto_library_sqft_by_ward.xlsx 
• Ward-level dataset containing total library square footage, branch counts, and calculated average square footage per branch (2023). 
Raw CSV and GeoJSON files from the Open Data Portal are also included to allow the analysis to be reproduced or extended.

**Visualizations**
•	Figure 1 (Excel): Average Toronto Public Library space per branch by ward (horizontal bar chart)
•	Figure 2 (Python): Choropleth map of library square footage by ward (quintiles)

**Reproducibility**
The Excel visualization was created using Microsoft Excel with documented aggregation steps.
The Python visualization was generated programmatically using Python, geopandas, and matplotlib, with the full analysis code available in this repository
able in this repository.
