# HealthFacilities.md
# Open Database of Health Facilities (ODHF) 

The Canadian Health Facilities Dashboard is an interactive Power BI tool utilizing the Open Database of Health Facilities (ODHF) from Statistics Canada, which contains approximately 9,000 records across all Canadian provinces and territories. The dashboard visualizes the distribution of hospitals, ambulatory care services, and nursing/residential care facilities, featuring geolocation and robust filtering by city, facility type, and region. Data cleaning and processing are done using Python (pandas, GeoPandas), while Power BI provides dynamic mapping and interactive analysis capabilities.

Key Dashboard Features
Facility distribution visualized by type and province/territory

Geographic maps for immediate spatial review of all facilities

Interactive filters for city, facility type, and region

Patterns and trends highlighting healthcare coverage and regional gaps

Dataset Details
Format: CSV

Version: 1.0 (April 2020)

Coverage: Nationwide (Canada)

Key Variables: Facility name, type, provider, address, city, province, latitude, longitude

Example Insights
Hospitals typically cluster in major urban centers, while ambulatory and nursing facilities are more spread out.

Some regions show significantly fewer facilities per capita, indicating coverage gaps and potential policy focus areas.

References
[ODHF Metadata – CSBP, Statistics Canada]

[ODHF Dataset CSV – Statistics Canada]
