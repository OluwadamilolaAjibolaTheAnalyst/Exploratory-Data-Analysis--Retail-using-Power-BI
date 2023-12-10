
**Exploratory Data Analysis- Retail using Power BI**

**INTRODUCTION**

A retail exploratory data analysis (EDA) focuses on analysing and interpreting data within the retail industry to gain insights and make informed decisions. EDA involves examining various data points,such as sales, profit, customer information, product details, and market trends,to uncover patterns,relationships,and potential opportunities.

By conducting an EDA, retailers can better understand their business performance identify area for improvement, and optimise thier strategies. this analysis can help retailers answer important questions such as: which products are the most popular? what factor influence customer purchasing decisions? how can marketing efforts be better targeted? EDA serves as a foundation for data driven decision making and enables retailer to stay competitive in a rapidly evolving industry.

Through data visualisation techniques, such as charts and graphs, EDA preents complex information in visually understandable manner.this allows stakeholders to grasp key findings quickly and efficeintly,leading to more effective decision-making and actions. Additionally, exploratory data analysis can also reveal anomalies or outliers in the data, enabling retailers to detect fraudulent activities, optimize inventory managemet, and improve overall operational efficiency.



**Problem Statement: Retail Analysis**

The problem at hand is to analyse a retail data set for a company and develop a predictive model that can identify the weak and where they can make more profit.
The goal of this analysis is to understand the factors that contribute to the profit loss  and develop a model that can accurately predict profit loss. By identifying product category, subcategory that are at risk of high profit losses, the company can proactively take actions to retain them such as reducing the discount rate allocated for a certain category,improving customer services,or enhancig the value proposition of thier products and services.

The following tasks was completed in order to address this issues:

1. Data Preparation and Cleaning
2. Exploratory data analysis  and Data insights
3. Recommendations for improving profit
4. Data Visualization

**Data cleaning and Preparation**

1. I changed some of the datatype for all the numrical columns to numerical datatypes ( i.e Whole Number, Fixed decimal) depending on the column
2. I removed duplicate values from some of the columns
3. I removed spaces in some columns in the product tables using trim function in power query

**Exploratory Analysis**

* In total there are 794 Customer
* 4 product Category
* 15 Product Sub category
* 1863 products
* 1 Country
* 49 states

**Analysis**

**Profit by Shipment mode**

what 2 shipment mode have the most profit?

This analysis is to determine the shipment mode that's most profitable.the company should focus on using standard class and first class shipment mode because these 2 shipment mode accounted  for 76.23% of the overall profit with standard class having the highest profit rate at 55.1% and First class at 21.13%

**Profit by state**

Which state have the highest profit loss?

The company should be worried about texas, illinois and pennsylvania. With texas having the highest profit loss,followed by illinois and pennysylvania, the company can create a new customer awareness strategy in this cities. it is also ideal to do a customer survey to know customer preference, reasons why product in this cities are not generating profit.
 

******how much profit was lost?** ****

They lost 13,350.9255, which is responsible for 9% of the overall profit. 

What are the reason for the profit loss

Which product category and subcategory has the massive profit loss?

Furniture has the highest profit loss which is as a result of the high rate of  discount allocated to this specific category compare to other product category with the sub-category Table account for -9,431 usd profit loss,Bookcases account for -2,049.368 USD profit loss  as a result of the discount rate compare to other product subcategory


**Additional Insights**

﻿﻿
* ﻿﻿At $35,733.1172, California had the highest Sum of Profit and was 381.64% higher than Texas, which had the lowest Sum of Profit at ($12,687.6957).﻿﻿
  
﻿* Across all 13 State, Sum of Profit ranged from ($12,687.6957) to $35,733.1172.﻿﻿
* Sum of Sales and total Sum of Profit are positively correlated with each other.
*  Sum of Sales and Sum of Profit diverged the most when the Category was Technology, when Sum of Sales were $367,612.3626 higher than Sum of Profit.﻿﻿


**Recommendations**

1. Discount rate reduction: since furnture has a weak profit as a result of high discount
rate allocated to this specific category compare to other category, it is ideal
to reduce the allocated discount rate and scourt for other ways of promoting these specific products
in other to maintain its competitive sales


2. Optimize product offerings: Capitalize on the popularity on the best selling product
sub-category by ensuring thier availability and promoting them effectively, conduct market research and customer
surveys to identify customer preferences and introduce new products subcategory that aligns
with the customer needs.

3. Improve customer engagement: Enhance communication strategies across country that generate low profit through 
email,phone call and online interactions to deliver personalised and relevant services to customers.
Consider implementing personalised offer, rewards and proactie customer support to improve customer satisfaction and loyalty



﻿

