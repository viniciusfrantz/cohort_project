# Customer Cohort Analysis

## What is a Cohort?  
A cohort is a group of people who share a common trait during a specific time period.  
It helps track and compare customer behavior over time, especially retention.

## Data Used  
I use the "UCI Online Retail Dataset," which has about 1 year of transaction data from a UK online store (2009-2010).  
There are around 525,000 rows.

## Business Question  
What are the behavioral patterns of customers when grouped by monthly cohorts?

## Objectives  
- Analyze customer behavior month by month.  
- Find trends in retention and engagement.  
- Help business understand customer lifecycle.

## What I Did  

### Data Wrangling  
- Standardized column names.  
- Converted invoice dates to datetime.  
- Removed duplicates and missing customer IDs.  
- Dropped rows with negative quantity or price.  
- Non-product stock codes (like adjustments, postage, test products) were excluded to keep only relevant sales data.
- Data types were corrected: customer_id and invoice converted to integer.
- Noted that some stock codes have multiple descriptions, which is an area for further cleaning.

### Exploratory Data Analysis (EDA)  
- Performed thorough data cleaning and preprocessing to ensure data quality.  
- Created new features to capture customer behavior and transaction patterns.  
- Counted transactions per month and analyzed purchase distribution by country.  
- Calculated average revenue per customer.  
- Conducted cohort analysis to examine customer retention and behavior over time.

### Tools  
- Python (Pandas, Numpy, Matplotlib, Seaborn) for data processing.  
- Tableau for visualization 


### Results
- The analysis revealed clear customer retention patterns and monthly behaviors that can help improve marketing and sales strategies.
- The first cohort has the highest retantion rate.
- There are some impórtant customers that are inactive and can be important to understand or mnake specific campaigns

### Tableau Dashboard
You can explore the interactive dashboard with all the visualizations here:
[Tableau Dashboard: Customer Cohort Analysis](https://public.tableau.com/app/profile/vinicius.giacomini.frantz/viz/Cohort_analysis_17480910712760/Painel1)
