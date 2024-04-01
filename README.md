# Analysis-of-Community-Housing-Availability-and-Distribution-in-Toronto-Project-Overview


## Project Overview
This project explores a critical question impacting urban communities: **"Is there sufficient community housing in Toronto, and is it appropriately distributed across neighbourhoods?"** Through comprehensive analysis and visualization, we reveal significant disparities in the availability of community housing across various areas of Toronto. Notably, neighbourhoods such as O'Connor-Parkview and Newtonbrook West stand out due to their inadequate community housing provisions. These areas, among others identified, exhibit a concerning combination of high composite benchmarks and low median household incomes. Our study leverages the capabilities of **ArcGIS Online** to conduct this analysis.

## Methodology
The investigation into Toronto's community housing landscape involved several key steps, utilizing data sourced from the City of Toronto's open datasets. The process is outlined below:

# Data Acquisition: 
We began by downloading the following datasets from the City of Toronto's open data portal and adding the "TREB Current Statistics" layer from ArcGIS Online:
* [Neighbourhoods](https://github.com/Beh-naz/Analysis-of-Community-Housing-Availability-and-Distribution-in-Toronto-Project-Overview/blob/main/Neighbourhoods_-_4326.zip).
* [Community Housing Data](https://github.com/Beh-naz/Analysis-of-Community-Housing-Availability-and-Distribution-in-Toronto-Project-Overview/blob/main/Community%20Housing%20Data%20-%204326.zip).
  
Source: City of Toronto Open Data

* "TREB Current Statistics" in ArcGIS Online.

Source: Toronto Regional Real Estate Board

# Data Preparation: 
The datasets underwent initial preprocessing, which included renaming various fields for clarity and consistency.

# Layer Creation and Enhancement:

* Saved the processed data as layers, each assigned with a descriptive name, summary, and relevant tags for ease of identification and access.
* Added the "TREB Current Statistics" layer from ArcGIS Online.
* Developed new layers representing the sum of median household incomes across neighbourhoods to identify economic disparities.
* Created layers to visualize the average composite benchmark in each neighbourhood, highlighting areas with potential housing stress.
* Generated layers summarizing the distribution of community housing units across neighbourhoods, revealing the extent of community housing availability.
  
# Data Analysis:

* Employed the "Manage Data" feature in the ArcGIS Online Analysis tab to integrate layers combining composite benchmark and median household income data.
* Conducted a stacked analysis of these layers to identify neighborhoods with the most critical need for additional community housing, based on composite benchmarks and household income levels.

# Findings
Our analysis illuminated stark contrasts in the distribution and adequacy of community housing across Toronto. Neighbourhoods like O'Connor-Parkview and Newtonbrook West were identified as areas with a significant shortage of community housing. This situation is exacerbated by the juxtaposition of high living costs (as indicated by composite benchmarks) against the backdrop of low median household incomes, highlighting a pressing need for targeted housing interventions in these and similar neighbourhoods.

# Visualizations
Find some of the important layers in the [Visualizations](https://github.com/Beh-naz/Analysis-of-Community-Housing-Availability-and-Distribution-in-Toronto-Project-Overview/tree/main/Visualizations) file.

# Tools Used
ArcGIS Online: This cloud-based mapping and analysis solution was instrumental in performing spatial analysis, creating informative visualizations, and sharing our findings on the distribution of community housing in Toronto.
