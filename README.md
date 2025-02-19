# House Depot Sales For The Year 2023
---

### Table of Contents

- [Project Overview](#project_overview)
- [Data Sources](#data_sources)
- [Data Preperation](#data_preperation)
- [Exploratory Data Analysis](#exporatory_data_analysis)
- [Data Analysis](#data_analysis)
- [Results](#results)
- [Recommendations](#recommendations)
- [Limitations](#limitations)



### Project Overview
---

This Project provides a comprehensive analysis of House Depot's 2023 sales data. Utilizing data cleaning and manipulation techniques, we look to identify sales trends and insights to provide the busisness with increased sales knowledge for future decision-making.

![Dashboard 1-3](https://github.com/user-attachments/assets/e93747eb-c696-43f4-a308-32ce5e121337)



### Data Sources

Sales Data: Raw sales data for 2023 was extracted from House Depot's internal database and was then cleaned and transformed in preparation for analysis.

### Tools Used

  - Google Sheets
    - [Downnload Here](https://github.com/BrandonDuenas/House-Depot-Sales-2023/blob/main/Yearly%20HD%20-%20Sheet1.csv)

  - Tableau Public
    - [Download Here](https://public.tableau.com/views/YearlysalesHouseDepot/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

### Data Preperation 

For the data preparation and processing I completed the following:
  1. I first compiled all of the data onto a new spreadsheet to avoid modifing the original spreadsheet provided by Company.
  2. Then I made all of the data uniform by changing everything to the same: font, font size, alighnment, and borders.
  3. The raw data was then meticulously cleaned and processed to calculate the necessary totals.
  4. Finally, the data was then transferred to Tableau Public for  data visualization and analysis.

### Exploratory Data Analysis

After meeting with the company owners we sought to answer the following questions:
  -  What was the total revenue from all products sold?
  -  What was the total cost of all products?
  -  What was the total revenue from warrenties sold?
  -  What were the total fees paid to Squarespace?
  -  What was the total loss due to damaged products?
  -  What was the total Profit?
  -  What was the average time products spent in inventory?
    
### Data Analysis

For the data analysis, I used various formulas to calculate totals, including:
``` Google Sheets
=SUM(cell_range)
```
``` Google Sheets
 =SUMIF(range, criteria, [sum_range])
```
``` Google Sheets
=average(cell_range)
```
``` Google Sheets
=DATEDIF(start_date, end_date, unit)
```

### Results
  - The total revenue from products sold was $263,443
  - The total cost of goods was $145,176
  - The total revenue from warrenties sold was $2,930
  - The total fees paid to Squarespace were $3,397
  - The total loss due to damaged products was $20,361
  - The total amount of profit was $136,547
  - The average time products spent in inventory was 47 days.

### Recommendations

Through the analysis of House Depots sales data from 2023. Somee key areas for growth were identified includeding warrenty sales, product cost optomization, and finding an avenue to profit off damaged products recieved.

  - For warrenty sales I recommeded to: provide more warrenty knowledge, highlight peace of mind the warrenty provides, focus on the fincial protection the warrenty provides, show testimonials from customers that have purchased the warrenty, and provide deal bundles at point of purhcase.
  - For Product Cost Optimization I recommeded to analyze bids to get the best prices on productcs. They can do this by relecting on the Tableau Dashboard and analyzing past bids.
  - To Maximize on profits we came up with a couple of options to deal with damaged products including: selling products to local rage rooms, and parting out components that still work for online resale.

By following these stragies House Depot will enhance profits and buisness growth for the years to come.

### Limitations

There were some limmitations to the sales data including incomplete or missing values. Those Values were removed or highlighted to provide unskewed results.

