# Boston Crime Insights using Tableau
  
**Tableau Public**: Boston-Crime-Insights-Published-Link

**By**: Krish Patel  
**Date**: April 10, 2025

---

## Overview

This project is a comprehensive Tableau dashboard exploring crime trends in Boston from 2015 to 2025. The primary aim is to assess the state of public safety in Boston using real, publicly available crime data. The project utilizes official crime records from the City of Boston and presents interactive visuals for detailed temporal, geographical, and categorical crime analysis.

The dataset includes incident-level records covering various offense types, locations, and timestamps. The dashboard enables users to explore patterns over time, by location, and by crime category through intuitive, interactive visuals.

### Key Features:
- **10-Year Crime Trends**: Line and bar charts show total crime trends and year-wise breakdowns by category.
- **Category Breakdown**: Visuals include bar charts, treemaps, and pie charts summarizing the most common types of crimes.
- **Street-Level Analysis**: Identifies high-crime streets and shows top 10 locations per crime type.
- **Crime Timing**: Users can explore when crimes occur (by hour, weekday, and month).
- **Geographical Distribution**: Dynamic map visualizes density of crime incidents across Boston neighborhoods.
- **Fully Interactive Filters**: Allows filtering by year, category, street, and time, including custom date ranges.

---

## Objectives

- To identify long-term trends and changes in crime patterns across time and location.
- To assess the current state of crime in Boston using official public data.
- To provide an accessible and interactive tool for exploring Boston’s crime data in depth.
- To enable data-driven validation of public safety narratives and examine whether claims about improvements in crime rates align with reported data.

---

## Methodology

- **Data Collection**: Crime incident data from 2015 to early 2025 was collected from the City of Boston’s open data portal.
- **Data Integration**: Multiple CSV files were unioned in Tableau to create a consolidated 10-year dataset.
- **Data Cleaning**: Field types were standardized (e.g., date/time, text categories) for accurate visualization and filtering.
- **Crime Categorization**: A calculated field grouped similar offenses into broader categories (e.g., Assault, Theft).
- **Feature Engineering**: Fields like year, month, weekday, hour, and street were extracted for multidimensional analysis.
- **Visualization Development**: Charts (bar, line, pie, treemap, map) were created to reflect different crime perspectives.
- **Dashboard Assembly**: The visualizations were combined into themed dashboards and then into a comprehensive Tableau story.

---

## Conclusion

The Boston Crime Insights Dashboard delivers an interactive and transparent view of crime trends across Boston from 2015–2025. By leveraging open government data and transforming it into categorized, filterable insights, the dashboard allows users to explore patterns over time, across neighborhoods, and by crime type. It also supports data-driven discussions on whether crime has improved or worsened over the past decade.

---

## Future Work

- Integrate predictive analytics for crime forecasting.
- Add demographic overlays for spatial insights.
- Embed real-time crime feeds for current data analysis.

---

## Skills Demonstrated

- Data Cleaning & Union in Tableau  
- Calculated Field Creation for Category Grouping  
- Dashboard Design and Interactivity Setup  
- Storytelling with Tableau  
- Public Data Utilization & Visualization

---

## Sources

- **Boston Crime Data**: [Boston Open Data Portal](https://data.boston.gov/dataset/crime-incident-reports-august-2015-to-date-source-new-system)
