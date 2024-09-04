Sgcarmart Data Science Project

Project Overview: Analyzing the Used Car Market in Singapore

Objective:
In an effort to explore the used luxury sedan car market and identify affordable yet reliable options, a comprehensive data analysis was undertaken. 
Given the dynamic nature of the used car market in Singapore, no readily available datasets were found online. 
Consequently, data was scraped directly from sgcarmart.



Methodology:

Data Acquisition:
To scrape data from sgcarmart.com, a leading online marketplace for used cars in Singapore, the BeautifulSoup library (BS4) was employed for web-scraping due to its speed and reliability. 
The first 10000 car listings were targeted, and information was collected as of September 03, 2024.

The extracted information included the following:
Car Listing URL 'LISTING_URL', 
Car Brand and Model 'BRAND', 
Price 'PRICE', 
Depreciation Value Yearly 'DEPRE_VALUE_PER_YEAR', 
Registered Date 'REG_DATE', 
Mileage in KM 'MILEAGE_KM', 
Year of Manufacture 'MANUFACTURED_YEAR', 
Road Tax Yearly 'ROAD_TAX_PER_YEAR', 
Automatic or Manual Tranmission 'TRANSMISSION', 
Deregistration Value as of Web Scraping DTD 'DEREG_VALUE_FROM_SCRAPE_DATE', 
Web Scraping DTD 'SCRAPE_DATE', 
Open Market Value (OMV) 'OMV', 
Additional Registration Fee (ARF) 'ARF', 
Certificate of Entitlement (COE) from Web Scraping DTD 'COE_FROM_SCRAPE_DATE', 
Number of Days till COE Expires 'DAYS_OF_COE_LEFT', 
Engine Capacity in CC 'ENGINE_CAPACITY_CC', 
Car Curb Weight in KG 'CURB_WEIGHT_KG', 
Number of Past Owners 'NO_OF_OWNERS', 
Vehicle Type 'VEHICLE_TYPE'

This data was subsequently stored in a CSV file named sgcarmart_used_cars_prices.csv.



Data Cleaning and Preparation:

The raw data contained numerous null values, duplicated rows, and inconsistencies in data types. 
A thorough cleaning process was conducted to address these issues. 
Feature engineering was then applied to create new columns that would be beneficial for the analysis. 
The cleaned data was saved in a new CSV file named cleaned_cars.csv.



This structured approach ensures that the data is reliable and ready for further analysis to provide insights into the pricing and availability of various car brands in the used car market.
