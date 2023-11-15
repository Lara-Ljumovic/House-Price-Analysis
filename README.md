# Wake County - House Sale Price Analysis
Data analysis project assessing all sale prices of all houses sold in Wake County (from Jan. 1958 to Oct. 2023) and exploring what contributing factors affect the price most.

## Objective
Research triangle Park (RTP) is the largest Research Park in US where research, technology, education and health care are consistently growing industries. Wake county with county seat of Raleigh, the capitol of North Carolina, and cities and towns are constantly expanding and house sare becoming bigger and more expensive. We wanted to explore what are the main factors that drive hiigher prices and does location really matters.

## Data
Data includes all real estate in Wake county and it represents administrative data for determining amount of property tax. We used only data about single family houses, they were over 300,000 of them, and about a dozen of features that could be contributing factors affecting sale prices. [Real estate data](https://www.wake.gov/departments-government/tax-administration/data-files-statistics-and-reports/real-estate-property-data-files) we used was downloaded on 10/29/2023.
 
We also used [Code Description](https://s3.us-west-1.amazonaws.com/wakegov.com.if-us-west-1/s3fs-public/documents/2020-10/CodeDescriptions.pdf) file, found on the same webpage, to change codes for some house features into descriptions.

For plotting all zip codes in Wake county in **Python** we used [GeoJSON](https://data-ral.opendata.arcgis.com/datasets/Wake::zip-codes/explore) file.

## Tools and project deliverables
For this project I used **Python** and this libraries
 * *pandas* and *numpy* for data analysis
 * *matplotlib*, *seaborn* and *skipy* for data visualizations and *folium* for geographic visualizations
 * *sklearn* for supervised and unsupervised machine learning (we performed regression and clustering)
 * public version of *statsmodels* for handling statistical models for analysis of time-series data

[Final presentation](https://public.tableau.com/app/profile/lara.ljumovic/viz/Wake_County_House_Sale_Price_Analysis/SALEPRICEANALYSIS) was prepared in **Tableau**.

