# Real-Estate-Investment-Case-Study
I used Python to wrangle and analyze several datasets for my real estate investment case study. I then created a Tableau Story that communicates my analysis process and my results.

## Objective
![image](https://github.com/DawnChism/Real-Estate-Investment-Case-Study/blob/main/Gold%20White%20Modern%20Professional%20Luxury%20Real%20Estate%20Logo-1.png)

Real estate investors are interested in purchasing homes that will maximize the return on their invesment.

This case study looks at the median home listing price across the United States by zip code.

The goal is to determine the most affordable zip codes that offer the largest return on investment.

Several analytical approaches were utilized to aid investors to quickly narrow down their search from 33,791 zip codes in the United States to a few dozen depending on budget and return criteria.

## Key Question
● What Zip codes have the lowest median list price but the highest return year over year?

## Data
● RDC_Inventory_Core_Metrics_Zip_History - The data set contained 2,681,926 rows and 40 columns of data which included information on month_date_yyyymm, postal_code, zip_name, median_listing_price, active_listing_, median_days_on_market, new_listing_count, price_increased_count, price_reduced_count, pending_listing_count, median_listing_price_per_square_foot, median_square_feet, average_listing_price, total_listing_count, pending_ratio, and a quality_flag to indicate values that are outside their typical range. All numerical columns also had corresponding columns that contained the % to prior month, and % to the prior year. 

● USZipcodes_compressed - shape file that contained multippolygon data for every zip code in the united states.

## Tools
The data was analyzed using Python and the following libraries:

● Pandas: for data analysis

● Numpy: for mathematical equations

● Seaborn: for data visualizations

● Matplotlib: for data visualizations

● Matplotlib.pyplot: for data visualizations

● Folium: for geospatial data visualization

● json: for geospatial data visualization

● geojson: for geospatial data visualization

● sklearn: for machine learning and statistical modeling

● pylab: for data visualizations

● statsmodels.api: .api imports the public access version of statsmodels

● warnings: to handle warnings

## Tableau Story
Tableau Story was created in Tableau Public and may be viewed in the attached [Tableau Storyboard](https://public.tableau.com/app/profile/dawn.chism/viz/RealEstateInvestmentCaseStudy_17104345666230/RealEstatePriceAnalysis#1).

## Folders
The project files are divided between the following folders:

● 01 Project Management: Project Brief & Data Dictionary.

● 02 Data: Separated into two subfolders Original and Prepared Data. These contain the original data frames and the data frames after they have been cleaned and prepared for analysis respectively. (Data files not uploaded to GitHub due to size.)

● 03 Scripts: The Jupyter notebooks containing the coding for the analysis.

## Resources
● https://www.realtor.com/research/data/

● https://www.census.gov/programs-surveys/geography/guidance/geo-areas/zctas.html
