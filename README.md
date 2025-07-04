# DSA-Project Documentation
This is my data analysis portfolio building. This is me putting on here my project documentation as I have learnt quite a lot.
## Project Topic-Kultra Mega Store sales analysis
### Project overview
The Kultra mega store Data analysis helped us generate answers to crucial questions needed to aid the business operations and from the analysis, we have madeour inferences 
####Tools used
- MS excel- for updating table
- SQL server (for Query and analysis)
- Drive for saving
### Data cleaning and  preparation 
We loaded the data on the device to use for analysis and on the Excel sheet updated missing data before finally loading it into the SQL
###Exploratory Data Analysis (EDA)
Involved the exploring of the data to answer our project questions about the data. And we had this;
###Strategic Business Advice Based on Sales Insights
#####Strengthening Presence in the West Region

The West region accounts for the highest total sales among all regions, making it a critical market for the company. This strong performance suggests a loyal and active customer base, which should not be taken for granted.

Recommendation:
- Reinforce marketing efforts and logistics support in the West.
- Prioritize customer satisfaction and feedback from this region.
- Invest in deeper market intelligence to understand consumer behavior and potential competitors in the West.
#####Dominance of Technology Products
- Technology is the top-selling product category company-wide, with significant traction especially in the West. This points to a robust demand for tech-related items.
Recommendation:
- Keep the technology product line strong with continuous improvement based on customer feedback.
- Monitor trends to ensure products remain relevant and competitive.
- Analyze competitors’ tech offerings in this region to stay ahead.
#####Most Frequently Used Shipping Mode
- Regular Air
This suggests it’s the preferred mode for speed and reliability in delivering.
#####Costliest Shipping Mode Overall:
- Delivery Truck
Despite not being the most used  it racks up the highest total shipping costs across all categories — something the company should keep an eye on, especially if cost optimization is important.
###Data Analysis
[download](https://1drv.ms/w/c/e7999c5408a92e2a/EenhHqKch69EupqVCVtY-IYBWjZtsl4BXEM7bWUEtRVePg?e=IBSaVQ)
SALES (Top product category)*

•	Technology | 5984248.182

*Query;

Select Top 1 product_category, sum (sales) 

AS TotalSales

From kmsP_TABLE

GROUP BY product_category

Order by TotalSales desc

 2) Top 3 regions by Sale

•	West | 3597549.2755

•	Ontario | 3063212.4795

•	Prairie | 2837304.6015

*Query;

Select top 3 Region, sum (sales)

As TotalSales

From kmsP_table

GROUP BY Region

Order By TotalSales DESC



2b) Bottom 3 regions  by sale

•	Nunavut | 116376.4835

•	Northwest Territories | 800847.3295

•	Yukon | 975867.371

*Query;

Select top 3 Region, sum (sales)

As TotalSales

From kmsP_table

GROUP BY Region

Order By TotalSales ASC

