**What software did you use to create your data visualization?**

This visualization was created using Python, primarily using GeoPandas and Matplotlib. Python was selected because it supports reproducible, script-based workflows. I followed the outline provided through the data visualization library for my chosen visualization (https://python-graph-gallery.com/choropleth-map-geopandas-python/), including the use of GeoPandas python package. This package enables integration of spatial boundary files with tabular open data, which allowed me to emphasize geographic patterns across Toronto wards as my visualization of choice.

**Who is your intended audience?**

The intended audience includes Toronto residents, planners, and policy-oriented audiences interested in how public library infrastructure is distributed spatially across the city. Unlike the Excel visualization, this figure is designed to emphasize spatial patterns rather than precise numeric comparison, providing a high-level view of geographic distribution.

**What information or message are you trying to convey with your visualization?**

The goal of this visualization is to show spatial variation in total Toronto Public Library square footage across wards, highlighting geographic clustering of higher and lower levels of infrastructure. I intentionally chose to map total square footage rather than per-branch averages, to allow visualization of overall infrastructure concentration within wards. Grouping wards into quintiles allows the map to show relative spatial patterns rather than being dominated by a small number of exceptionally large reference libraries. This is more meaningful for spatial interpretation than normalized metrics. Although numeric tables allow for exact comparison, presenting it as spatial visualizations reduce this burden by embedding data directly in place, supporting more immediate recognition of patterns, clustering, and gaps across wards. Furthermore, it allows viewers to connect data to lived experience which is important for public facing resources and services. 

**What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?**

Design choices were guided by appropriateness and perceptual effectiveness. A choropleth map was chosen to align with ward-level data and support detection of regional patterns. To address the skewed distribution of square footage, wards were grouped into quintiles, enabling comparison without extreme values overwhelming the scale. A colour-blind–friendly sequential palette (viridis) was used to display ordered differences, and ward boundaries were outlined to maintain geographic clarity. Labels were limited to reference libraries, which were highlighted with point annotations to provide context while minimizing visual clutter.

**How did you ensure that your data visualization is reproducible?**

This visualization is reproducible. All data sources, cleaning, merging of spatial boundaries, categorization into quintiles, and plotting steps are contained within a Python script and posted in a public GitHub repository (https://github.com/sumitraybardhan/visualization/tree/assignment-three/02_activities/assignments/Assignment_3). Given the same input data and boundary files, the figure can be regenerated or modified programmatically. I wanted to contrast this with the Excel visualization for my own learning journey to demonstrate how different tools support different levels of reproducibility.

**How did you ensure that your data visualization is accessible?**

Accessibility was addressed through the use of the viridis colour palette, a uniform sequential scale that supports interpretation for viewers with colour vision deficiencies. Also colour was used to encode ordered categories rather than precise values, and the legend explicitly defines these categories to avoid reliance on colour alone. Grouping wards into quintiles further reduces reliance on fine colour discrimination, supporting interpretability for a broad, non-technical audience.

**Who are the individuals and communities who might be impacted by your visualization?**

This visualization may impact Toronto communities, advocacy groups, and municipal planners by revealing spatial inequities in public library infrastructure. The goal of presenting the infrastructure concentration geographically, is so that the map can inform discussion about equity, access, and future investment.

**How did you choose which features of your chosen dataset to include or exclude from your visualization?**

Only total library square footage by ward was included, as this measure best represents the overall scale of infrastructure available within geographic areas. Per-branch averages were excluded from the map because normalization can obscure spatial patterns and exaggerate values in wards with few branches. Furthermore, because the underlying data processing and visualization workflow is reproducible, this map provides a foundation for more detailed, layered analyses. Additional variables—such as library service offerings, neighbourhood-level socioeconomic indicators, or measures of access and demand—could be integrated in future work to explore how library infrastructure aligns with community need.

**What ‘underwater labour’ contributed to your final data visualization product?**

Similar to the Excel visualization, “Underwater labour” contributed to the final visualization. Similarly, maintaining the City of Toronto’s Open Data Portal, including data collection, curation, documentation, and regular updates are essential to allow for accurate data visualization.