# CLEANING & ANALYSING SALES DATA TO AID DECISION MAKING 
 
This 'csv' document is extracted for a clean and analyze sales performance of an e-commerce business using Excel. By leveraging historical sales data, the project aims to identify trends, key performance metrics, and areas for improvement, ultimately helping the business and organization make data-driven decisions to optimize revenue, marketing strategies, product offerings and also gain a deeper understanding of the company's performance .
## Table of content 
- [Project Overview](#project-overview)
- [Focus and Objectives](#focus-and-objectives)
- [Data Soures](#data-sources)
- [Tools](#tools)
- [Data Cleaning And Analysis Workflow](#data-cleaning-and-analysis-workflow)
- [Data Analysis](#data-analysis)
- [Results And Findings](#results-and-findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Reference](#references)



## Project Overview
 This 'csv' document is extracted for a clean and analyze sales performance of an e-commerce business using Excel. By leveraging historical sales data, the project aims to identify trends, key performance metrics, and areas for improvement, ultimately helping the business and organization make data-driven decisions to optimize revenue, marketing strategies, product offerings and also gain a deeper understanding of the company's performance .


### Focus and Objectives:
Understand customer purchase behavior.
Identify high-performing products and categories.
Analyze sales trends across different regions and time periods.
Provide recommendations for business optimization.
### Data Sources

The data used in this project is the "sales_data.csv" file derived through web scrapping from an authorised link. The dataset includes the following KPI

Order ID: Unique identifier 
- Customer ID: Unique identifier for each customer.
- Product: Name purchased product.
- Quantity: Number of products purchased in an order.
- Price: Price of each product.
- Order Date: Date of purchase.
- Shipping Cost: cost of shipping order goods.
- Location : Region where the order was placed from  e.t.c.
These dataset has been cleaned and prepared for analysis, with missing values handled appropriately.....


### Tools 

- Excel : | for data cleaning, manipulation and roburst for use
    - [Download here](https://microsoft.com)
- Pivot table : Main analytical tool for summerization
- Pivot Chart : for visualization

### Data Cleaning And Analysis Workflow
Data Cleaning: In the initial sales dataset I performed the following tasks
1. Data loading & Visual Exploration:  this is where I carried out my observations to demisify the problems
2. Datat Cleaning: I cleaned up to handle noises and missing values, remove duplicate entries, and formatting inconsistencies.
3. Data Modeling: I carried out relationship between worksheet for further analysis 
4. Exploratory Data Analysis (EDA): Visualizations and statistical summaries are generated to understand the dataset
5. Data Analysis : (Pivot Table)
6.  Visualization & Reporting: The results of the analysis are visualized using plots and charts to make insights actionable. (Pivot Chart) 

## Data Analysis

``` XLOOKUP, error trapping and IF conditional Statement
=XLOOKUP(AV5,age[Column1],age[Column2],,-1)
=IFERROR(VLOOKUP(B7, ReturnedItems,2,0), "Delivered")
=IF(Z15 <12.84, "Low Cost", IF(Z15>12.84, "High Cost",IF(Z15 = 12.84, "Average Cost")))
```

### Results And Findings

Brief analysis of results are summerised as follows:

1. I realised that in the product categories, investing in Technology has more Profitability compared to other products.
2.   I realised that in a well populated city as Ontairo Canada this technology sells better compared to other region based on high volume of population
3.   Most profitable age-band is between the average age of people who has family compare to other age group.
4.   I found out the best performing team with good managerial skills
5.   i was able to analyse each team, region, product and manager by their activities for evaluation, to know where needs to be adjusted e.t.c.

## Recommendations

Based on my analysis, i recommended the following actions to further improve sales for the company.

- Invest more in publication and awareness in the populated regions that have less sales in recent time.
- Invest in markerting and promotions during sales seasons to maximise revenue
- Implemetation of real time tracking devices for deliveries
- customer review and referral should attract strategic benefit and strategic marketing.
   
## Limitations

- During my clean-up, i removed "Null Values" from sensitie fields that would have affected the visualization of my result
- I also remove all noises that came along with the dataset,
- replacing missing values could be more tasking when replacing them for result accuracy.

## References
1. Google
2. geeksforgeeks [https://www.geeksforgeeks.org]
3. w3schools [https://www.w3schools.com]











 
