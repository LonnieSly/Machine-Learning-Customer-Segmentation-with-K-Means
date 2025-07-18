Project: Data-Driven Optimization for a Food Delivery Service
This repository documents a comprehensive data analysis of a food delivery service. The project leverages customer order history to uncover actionable insights into customer behavior, operational efficiency, and menu popularity. The goal is to transform raw data into a strategic asset that can drive business growth, enhance customer satisfaction, and optimize marketing efforts.
1. The Challenge: A Problem of Untapped Data
SITUATION: A food delivery company possesses a wealth of customer and order data but lacks the deep insights needed to make strategic, data-informed decisions. The current approach to marketing, operations, and partner relations is reactive and generalized, leading to inefficient resource allocation and missed opportunities in a highly competitive market.
TASK: The primary objective is to analyze the available data to answer critical business questions: Who are our most valuable customers? What are their preferences? Where are the bottlenecks in our service? The mission is to create a clear, evidence-based roadmap for improving the service from multiple angles—customer engagement, operational speed, and partner strategy.
2. Our Solution: An Investigative Data Analysis Framework
PROBLEM SOLUTION: To address this challenge, we conducted a thorough exploratory data analysis (EDA). By visualizing key performance indicators and segmenting the customer base, we can move from abstract numbers to concrete, actionable intelligence. This project translates complex datasets into a clear narrative about the business's strengths, weaknesses, and opportunities, enabling a shift towards a proactive and targeted strategy.
3. The Investigation: Uncovering Actionable Insights (The STAR Method in Action)
Action 1: Segmenting the Customer Base
To understand who uses the service, we first analyzed the distribution of customers across different predefined segments.
Result 1: Identifying Key Customer Personas
The analysis reveals that the customer base is not monolithic. The visual shows that our customers are divided into four main groups: Loyal, New, Regular, and Occasional.
Key Insight: While "Regular" customers form the largest group, "Loyal" customers, though fewer in number, are critical to sustained success. This segmentation provides the foundation for creating targeted communication and retention strategies.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/segment-count.png)
Action 2: Analyzing Spending Habits and Value
We then investigated the spending patterns across the platform to identify where the most value is generated.
Result 2: The Link Between Ordering and Spending
The scatter plot demonstrates a clear relationship between the number of orders a customer places and their average spend.
Key Insight: There is a positive correlation between order frequency and average spend. Customers who order more frequently also tend to spend more per order, highlighting the immense value of fostering customer loyalty.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/orders_vs_avg_spend.png)
This is further supported by the platform-wide average spend.
Key Insight: With a platform-wide average spend of $24.58, we have a vital benchmark to measure the effectiveness of future marketing campaigns aimed at increasing order value.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/average_spend.png)
Action 3: Assessing Menu Popularity and Operational Performance
Finally, we analyzed product performance and service efficiency to pinpoint areas for optimization.
Result 3: Dominant Cuisines and Delivery Speed
The bar chart leaves no doubt about customer preferences.
Key Insight: American cuisine is the undisputed favorite, dramatically outperforming all other categories. This indicates a massive opportunity for targeted promotions, menu expansions, and strategic partnerships with America cuisine restaurants.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/top_cuisine.png)
On the operational front, delivery time is a cornerstone of customer satisfaction.
Key Insight: The average delivery time currently stands at 24 minutes. This metric is a critical KPI for measuring operational efficiency and should be continuously monitored to maintain a competitive edge.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/avg_del_time.png)
4. Strategic Recommendations
This data-driven investigation leads to several clear, actionable recommendations:
For Marketing:
Develop a Loyalty Program: Create an exclusive rewards program for the "Loyal" customer segment to maximize retention and lifetime value.
Targeted Campaigns: Design campaigns to convert "Regular" customers into "Loyal" ones by encouraging higher frequency and spend.
Promote the Winner: Heavily feature American cuisine in all marketing channels, from email newsletters to in-app banners.
For Business Development:
Strengthen Partnerships: Deepen relationships with top-performing American cuisine restaurants.
Expand the Menu: Actively seek out new, high-quality American restaurants to add to the platform to meet the clear market demand.
For Operations:
Maintain Speed: Use the 24-minute average delivery time as a core performance benchmark for all operational teams.
Investigate Variance: Analyze delivery times by location, time of day, and restaurant to identify and address any sources of delay.
5. How to Replicate This Analysis
This analysis was conducted using Python in a Google Colaboratory environment. All data and code are available in this repository.
Clone the repository:
Generated bash
git clone https://github.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means.git
Use code with caution.
Bash
Explore the data and code:
The dataset is available in the repository.
The complete analysis, from data cleaning to visualization, can be viewed and run in the provided Google Colab notebook:
View the Notebook Here
Tools Used
Python
Pandas for data manipulation and analysis.
Matplotlib & Seaborn for data visualization.
Google Colaboratory for the interactive development environment.
