# Chicago Social Deprivation Index

## Overview

Welcome to the Chicago Social Deprivation Index project! In this lab, we present a social deprivation index developed using data from Chicago, Illinois. This index aims to provide insights into the social and economic conditions in different areas of Chicago, with a focus on socioeconomic status indicators.

## Social Deprivation Indicators

The Chicago Social Deprivation Index includes the following five social-economic status indicators:

1. **Education**: Measures the level of education in each area.
2. **Unemployment**: Indicates the unemployment rate.
3. **Income**: Reflects average household income.
4. **Built**: Represents the condition of housing and infrastructure.
5. **Rent**: Evaluates the affordability of housing.

For all indicators except income, higher values correspond to a higher risk of social deprivation. In the case of income, higher values indicate greater access to resources and opportunities.

## Methodology

To create the index, we followed these steps:

1. **Normalization**: We normalized the values of each indicator using the max-min method, scaling them to a range of 0 to 1.

2. **Aggregation**: We aggregated these normalized values and calculated the average for each census tract in Chicago.

3. **Final Normalization**: We normalized the averaged index again using the max-min method, resulting in the final social deprivation index for each census tract.

## Choropleth Plot

We visualized the results of the social deprivation index using a choropleth plot. In this plot, darker shades represent higher levels of social deprivation. The analysis revealed that socially deprived regions are concentrated in the south and western parts of Chicago. We speculate that factors such as proximity to Lake Michigan, downtown areas, and family composition may contribute to these patterns.

## Future Directions

While this index provides valuable insights, further exploration is encouraged. Possible areas of interest include:

- **Health**: Examining health-related variables to understand their correlation with social deprivation.
- **Access to Amenities**: Investigating access to amenities like parks, libraries, recreation centers, and grocery stores.
- **Comparative Studies**: Comparing the results of this index with similar indices in different regions for a broader perspective.

## Utilization

This Chicago Social Deprivation Index can serve as a valuable tool for policymakers, community leaders, and researchers. It helps identify areas in need of targeted interventions and resources and facilitates the study of social deprivation's impact on various outcomes.
