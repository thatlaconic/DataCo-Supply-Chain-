# DataCo Supply Chain

## Table of Contents
- [Description of Dataset](#DescriptionofDataset)
- [Objectives](#Objectives)
- [Data Cleaning Using Excel](#DataCleaningUsingExcel)
- [Visualization Using Power BI](#VisualizationUsingPowerBI)
- [Analysis and Insights](#AnalysisandInsights)
- [Recommendation for Improvements](#RecommendationforImprovements)

## Description of Dataset
The dataset used was obtained from Kaggle and is from a company called “DataCo Global”. It contains supply chain operations from the year 2015 to the 1st quarter of 2018. 
The dataset includes 3 csv files.
1.	DataCoSupplyChainDataset – structured data that contains information in provisioning, production, sales and commercial distribution
2.	tokenized_access_logs – unstructured data that contains specific product details with ip and url
3.	DescriptionDataCoSupplyChain – contains category description

## Objectives
* Logistics KPIs such as order fill rate, on-time and late orders, and average shipping are tracked to enhance the delivery performance of supply chain logistics.
* Sales data is analyzed to determine the top-performing departments and categories.

## Data Cleaning Using Excel
*	Identified and removed irrelevant and redundant information from the dataset that are not needed for this analysis. 
* Fixed and standardized structural errors such as inconsistent naming discrepancies and mislabeled categories to ensure uniformity in data representation. Functions that were used are CONCAT( ), IF( ), TRIM( ) and filter option. 

## Visualization Using Power BI
*	Created an interactive supply chain dashboard with two pages that analyzes the logistics and sales aspect of the dataset provided by DataCo Global.
*	The dashboard can be filtered by the year, purchase country and market that allows the user to view specific area for trends and findings.

## Analysis and Insights
![](https://github.com/thatlaconic/DataCo-Supply-Chain-/blob/main/logistics.PNG)
* Between 2015 and Q1 2018, the order fill rate across all markets (Africa, Europe, LATAM, Pacific Asia, and USCA) was measured at 42.79%. When you explore more in the [dashboard](https://github.com/thatlaconic/DataCo-Supply-Chain-/blob/main/Supply%20Chain%20Dashboard%20for%20DataCo.pbix), filtering through the years, it shows that the fill rate have been consistent with 42-43% of fulfilled orders. This indicates that less than half of the total orders were fully fulfilled, highlighting a relatively poor performance compared to the industry benchmark of 85% to 95%, as stated by [Zeiger, Dan. (2022) in The Monthly Metric: Fill Rate](https://www.ismworld.org/supply-management-news-and-reports/news-publications/inside-supply-management-magazine/blog/2022/2022-07/the-monthly-metric-fill-rate/).
  
* This low performance likely leads to customer dissatisfaction, as expectations for order fulfillment are not met. Additionally, operational challenges, such as inventory mismanagement, inaccurate              demand forecasting, or supply chain disruptions, may be contributing to this issue.

*	The data also shows that over the past three years, late deliveries have consistently exceeded on-time deliveries, emphasizing inefficiencies in the shipping process.  On average, actual shipping days of 3.49 surpassed target shipping days of 2.93 as can be observed from the indicator. Furthermore, the presence of in-progress orders visible on the order status suggests that some orders remain unfulfilled or are stuck in the pipeline, further complicating the fulfillment process. Additionally, the shipping modes showed that the standard class is the primary contributor to late deliveries, accounting for the majority of late delivery counts across all markets.
  
![](https://github.com/thatlaconic/DataCo-Supply-Chain-/blob/main/sales.PNG)
*	The fanshop department outperformed the other five departments, contributing 49.92% of total sales in 2015, 50.32% in 2016, and 49.92% in 2017. Within this department, the fishing category achieved the highest sales with 18.76%, while CDs from the Discs Shop with 0.01% sales recorded the lowest through the years.

*	A low order fill rate significantly impacts sales by reducing revenue opportunities and damaging customer trust. When orders cannot be fulfilled completely, customers may cancel their purchases or turn to competitors, resulting in lost sales and market share. Loyal customers, may switch to competitors after repeated issues with incomplete or delayed orders, further reducing retention rates. Over time, the operational inefficiencies caused by low fill rates increase costs, forcing the company to raise product prices, which can deter customers and make the business less competitive.

## Recommendation for Improvements
*	The company should conduct a comprehensive audit of its shipping and logistics operations to identify bottlenecks and inefficiencies from the route of purchase country to the order country. 
*	Proactively communicating with customers about potential delays and providing realistic delivery timelines will help manage expectations and maintain trust.
*	Comparing regional performance can identify best practices that may be adopted across markets to improve overall efficiency. 
*	Adopting continuous improvement methodologies like Six Sigma can help the company iteratively refine its processes and achieve higher levels of operational excellence.


