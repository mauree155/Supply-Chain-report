# Supply-Chain-Performance-Report
## Table of Contents
1. [Project background](project-background)
2. [Data Source](data-source)
3. [Tools](tools)
4. [Dashboard](dashboard)
5. [Analytical Process](analytical-process)
6. [key Insights](key-insights)
7. [Recommendations](recommendations)
8. [Conclusion](Conclusion)

### 1. Project background
This project analyzes the supply chain performance of a company selling a range of skincare, haircare, and cosmetics products. The company collects significant data on product sales, customer demographics, shipping costs, and supplier performance.
The objective of this analysis is to:
- Understand how different customer groups (including gender identities and unknown profiles) contribute to revenue and order quantities.
- Identify the top-performing products and suppliers.
- Evaluate shipping cost efficiencies by transportation modes.
By leveraging these insights, the company can make informed strategic decisions to optimize product offerings, streamline supplier relationships, and enhance customer satisfaction.

### 2. Data Source
The dataset, provided by Quantum Analytics during training, contains detailed transaction-level records of product sales and shipping activities. Key data points include:
- Product information: type, SKU, revenue, and quantity sold
- Customer demographics: gender, including an ‘Unknown’ category
- Supplier details: name and revenue contribution
- Shipping costs: transportation modes (road, air, rail, sea)
This dataset covers over 46,000 product sales, 4,922 order quantities, and total revenue of approximately $577,600. It spans skincare, haircare, and cosmetics product categories, providing a robust foundation for analysis.
<a href="https://github.com/mauree155/Supply-Chain-report/blob/main/supply%20chain%20dataset.xlsx">Access dataset</a>

### 3. Tools
The following tools  were used for this analysis:
- **Power BI:** For interactive dashboard creation and data visualization
- **Excel:** For initial data cleaning and preprocessing
### 4. Dashboard
The interactive Power BI dashboard developed for this project highlights key metrics and trends across several areas:
- Revenue and Order Quantity by Customer Demographics – Visualizes which customer segments (Female, Male, Non-binary, Unknown) are driving revenue and orders.
- Top Suppliers by Revenue – Displays top 10 suppliers based on revenue contribution.
- Top Products by Revenue – Highlights which products (by SKU) generate the highest revenue.
- Shipping Costs by Transportation Mode – Compares average shipping costs across Road, Air, Rail, and Sea.
- Product Type by Customer Demographics – Shows which product types are preferred by different customer groups.
- **Note:** The dashboard provides filters for product types, locations, routes, and SKUs, allowing stakeholders to drill down into specific areas of interest.

  ![supply chain dashboard](https://github.com/user-attachments/assets/673613c3-73ac-4a50-9bda-1e6551e0dbf7)

  
An interactive PowerBl dashboard can be downloaded <a href="https://app.powerbi.com/groups/me/reports/72fd70d1-5f68-4be5-9b48-db9de1fd29f9/ReportSection?experience=power-bi&clientSideAuth=0">Here</a>
 
 ### 5. Analytical Process
#### Data Cleaning & Preparation
- Standardized customer demographic labels (Female, Male, Non-binary, Unknown)
- Cleaned missing or inconsistent entries to ensure data integrity
- Verified supplier revenue data and shipping cost accuracy

#### Exploratory Data Analysis (EDA)
- Identified key revenue drivers and customer segment performance
- Analyzed supplier revenue contribution and shipping cost differences
- Investigated demographic and product-type ordering patterns
#### Dashboard Development
-  Designed a clear, visually appealing dashboard in Power BI
-  Added dynamic filtering to allow custom analysis by stakeholders

### 6. Key Insights
#### Executive Summary
Overview of Findings
Analysis of the 2022 supply chain data revealed notable patterns in revenue distribution, supplier dependence, shipping cost structures, and customer demographic trends. Although total revenue remained strong, there are opportunities to diversify the product portfolio, manage supplier risk, and improve data collection for better marketing strategies.

#### Revenue and Order Trends
- **Revenue Concentration**:
The dataset comprised over 46,000 product sales and $577,600 in revenue. Skincare products accounted for the highest revenue share at $216,000, followed by haircare and cosmetics. This revenue concentration in skincare highlights potential risk in product dependence.
- **Order Distribution:**
Order data showed similar concentration, with skincare orders accounting for nearly 40% of total order volume.
- **Supplier Contributions:**
Analysis revealed a significant reliance on a handful of suppliers. Supplier 1 alone generated over $157,000 in revenue, while the top five suppliers contributed the majority of total revenue. This underscores a potential vulnerability to disruptions from any single supplier.

#### Shipping Cost and Mode Analysis
- **Cost Differences by Mode:**
Shipping costs varied considerably by transportation mode. Road and Air transport had the highest average shipping costs, at $161 and $156, respectively, compared to lower-cost modes like Rail ($153) and Sea ($84). This suggests opportunities to optimize shipping strategies and reduce operational costs.
- **Demographic Segmentation:**
Female customers represented the largest customer segment, generating the majority of revenue and orders. Male and non-binary customers also contributed notably, though nearly 30% of revenue came from customers with ‘Unknown’ gender, highlighting a gap in customer data collection.

#### Product and Supplier Performance
- **Top Products:**
Revenue was highly concentrated among a few products, with the top three items—across skincare, haircare, and cosmetics accounting for over 70% of total revenue. This signals an opportunity to diversify product offerings and reduce dependence on a limited number of SKUs.
- **Supplier Risk Exposure:**
The reliance on top suppliers creates a potential risk to the supply chain if disruptions occur, as seen with Supplier 1’s dominance in revenue contributions.

### 7. Recommendations
Based on the uncovered insights, the following strategic recommendations have been developed:
- **Diversify the Product Portfolio:**
Reduce dependency on top product categories by introducing complementary products, particularly expanding into related beauty or wellness accessories, to provide upsell opportunities and stabilize revenue streams.
- **Mitigate Supplier Risk:**
Explore alternative suppliers and develop partnerships with smaller suppliers to reduce reliance on top contributors and improve supply chain resilience.
- **Optimize Shipping Costs**
Investigate opportunities to shift shipments from Road and Air to Rail and Sea where possible, as these modes offer substantial cost savings. Collaborate with logistics partners to balance cost and delivery speed based on product type and customer location.
- **Enhance Customer Data Collection:**
Develop strategies to reduce the ‘Unknown’ demographic share. Implement better data collection methods at checkout and through loyalty programs to enable more effective targeted marketing and personalized promotions.
- **Leverage the Power BI Dashboard:**
Use the interactive dashboard to continuously monitor supplier performance, product trends, and shipping costs. This will enable proactive decision-making and identification of new growth opportunities in the supply chain.

### 8. Conclusion
This comprehensive supply chain analysis uncovers actionable insights that can help streamline operations, reduce costs, and improve customer satisfaction. By implementing these recommendations and leveraging the Power BI dashboard, the company can build a more agile and resilient supply chain that supports long-term growth in the competitive beauty and personal care market.

