**What software did you use to create your data visualization?**

This data visualization was created using Microsoft Excel (Microsoft Excel for Mac, version 16) as a data presentation tool. The underlying data aggregation was performed in Python, while Excel was used to calculate the derived metric of average square footage per library branch at the ward level and to produce the final horizontal bar chart. Excel was selected because it supports clear, static visualizations and allows transparent inspection by a broad, non-technical audience, making it well suited for presenting relative differences across wards.

**Who is your intended audience?**

The intended audience includes Toronto residents, community advocates, and municipal decision-makers interested in how public library infrastructure varies across wards. The visualization was designed to be interpretable without technical expertise, using clear labeling, a familiar chart structure, and straightforward comparisons to support accessibility for a non-specialist audience.

**What information or message are you trying to convey with your visualization?**

The goal of this visualization is to examine variation in average Toronto Public Library (TPL) space per branch across wards. As a frequent user of TPL branches with my young family, I was interested in better understanding how the scale of library facilities varies across the city. This work builds on prior analysis by Ahmad (2024), which examined library space using total square footage and branch counts. While total square footage highlights where infrastructure is concentrated, this visualization extends that framing by normalizing space by the number of branches in each ward. This approach highlights differences in typical branch size, which may better reflect the scale of facilities experienced by users. Wards containing major reference libraries are explicitly identified to contextualize extreme values. Ranking wards from lowest to highest average square footage per branch emphasizes relative comparisons that are less apparent when focusing on aggregate totals alone.

Reference: Ahmad, H. (2024). Mapping Toronto’s Libraries: Are Libraries Distributed Equally Throughout the City? January 25, 2024. https://tellingstorieswithdata.com/inputs/pdfs/paper-1-2024-HadiAhmad.pdf

**What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots?**

Perceptual accuracy was prioritized through the use of a horizontal bar chart, which presents values using length along a common baseline and supports accurate comparison across wards. Cognitive load was minimized by sorting wards by average square footage per branch and using a single, consistent colour, keeping attention focused on relative differences. The horizontal orientation accommodates long ward names without truncation. A limited call-out annotation was added to identify wards containing major reference libraries, providing contextual explanation without overstating differences.

**How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?**

Excel does not support fully reproducible workflows in the same way as code-based tools. To address this, reproducibility was supported through transparent documentation and data sharing. The aggregated Excel dataset was posted in a public GitHub repository (https://github.com/sumitraybardhan/visualization/tree/assignment-three/02_activities/assignments/Assignment_3
) and includes direct links to the original City of Toronto Open Data Portal datasets. While the figure cannot be regenerated automatically within Excel, another user could reproduce the visualization by following the documented aggregation steps and calculations using the same publicly available data. This limitation affects scalability and version control but does not undermine the interpretability or intended communicative purpose of the visualization.

**How did you ensure that your data visualization is accessible?**

Accessibility was addressed through a simple, high-contrast design and a familiar chart form. A single blue tone was used for the bars, which remains distinguishable for most forms of colour vision deficiency, and a dark outline was added to reinforce relative differences. Meaning is conveyed primarily through bar length, supported by clear axis labels and text rather than colour alone. The horizontal layout and readable font sizes further support interpretability.

**Who are the individuals and communities who might be impacted by your visualization?**

This visualization may be of interest to Toronto residents concerned with how public services are distributed, as well as community advocates and municipal planners involved in infrastructure planning. By making differences in library space visible at the ward level, the visualization can support informed discussion about the distribution of cultural and educational resources without implying conclusions about service quality.

**How did you choose which features of your chosen dataset to include or exclude from your visualization?**

The visualization focuses on average square footage per library branch at the ward level, calculated as total branch square footage divided by the number of branches. This measure provides a concise summary of the typical scale of facilities experienced by users while avoiding overemphasis on wards with a small number of exceptionally large branches. Other available variables—such as addresses, service offerings, and amenities —were excluded because they do not directly support this comparison. Limiting the visualization to a single derived metric helped preserve a clear, single-message chart. These additional variables remain available in the underlying dataset for complementary analyses.

**What ‘underwater labour’ contributed to your final data visualization product?**

“Underwater labour” supported the final visualization, including cleaning and aggregating raw open data, validating summary measures, and refining chart structure. This work also relies on the ongoing, largely invisible labour involved in maintaining the City of Toronto’s Open Data Portal, including data collection, curation, documentation, and regular updates. Although these efforts are not visible in the final figure, they are essential to ensuring the visualization is accurate, interpretable, and responsibly grounded in public data.