Project: Unlocking Customer Value Through K-Means Segmentation
This repository documents a data-driven approach to customer segmentation for a retail business. By moving beyond a one-size-fits-all marketing strategy, this project aims to provide actionable insights to drive personalized marketing campaigns, enhance customer engagement, and optimize marketing spend.
1. The Challenge: A Problem of Impersonal Marketing
SITUATION: A retail company possesses a diverse customer base. However, their current marketing strategy is generic, failing to resonate with specific customer needs and preferences. This leads to inefficient allocation of the marketing budget and low return on investment, as engagement remains low.
TASK: The primary objective is to transform the company's marketing approach from broad and impersonal to targeted and effective. This requires a deep understanding of the customer base by identifying distinct groups or "segments" and profiling their unique characteristics and behaviors. The challenge is not just to group customers, but to create meaningful segments that can inform actionable business strategies.[1]
2. Our Solution: A Data-Driven Segmentation Strategy
PROBLEM SOLUTION: To address this challenge, we employed a machine learning methodology. Specifically, this project utilizes the K-Means clustering algorithm, an unsupervised learning technique, to segment customers based on their annual income and spending score.[2] This data-driven approach allows us to uncover natural groupings within the data, providing an objective foundation for targeted marketing.[3]
The project follows a structured workflow:
Exploratory Data Analysis (EDA): To understand the underlying patterns and distributions within the customer data.[4]
Model Building: To determine the optimal number of customer segments and apply the K-Means algorithm.[5]
Cluster Analysis & Visualization: To profile the resulting segments and translate data into actionable business intelligence.[6]
3. The Investigation: Uncovering Customer Insights (The STAR Method in Action)
Action 1: Exploratory Data Analysis (EDA)
Before segmentation, we performed a thorough exploratory data analysis to understand the demographic and behavioral characteristics of the customers.
Distribution of Annual Income:
The income distribution shows a concentration of customers in the lower to middle-income brackets, with fewer customers in the high-income range.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/Annual%20Income%20(k%24).png)
Age Distribution:
The customer base is fairly evenly distributed across different age groups, with a notable peak in the early thirties.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/Age.png)
Spending Score Insights:
The "Spending Score" is a metric assigned to customers based on their purchasing behavior. The distribution indicates that a significant portion of customers have a moderate spending score.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/Spending%20Score%20(1-100).png)
Action 2: Determining the Optimal Number of Segments
A critical step in K-Means clustering is selecting the right number of clusters (k). Choosing a k that is too low can result in overly broad segments, while a k that is too high can create segments that are too granular and not practically useful.
To make an informed decision, we used the Elbow Method. This technique involves running the K-Means algorithm for a range of k values and calculating the Within-Cluster Sum of Squares (WCSS) for each. The "elbow" of the resulting graph represents the point of diminishing returns, indicating the optimal value for k.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/The%20Elbow%20Method.png)
As seen in the plot, the "elbow" is clearly visible at k=5. This suggests that segmenting the customers into five distinct groups is the most effective choice.
Action 3: Building the Segmentation Model
With the optimal number of clusters identified, we trained the K-Means model on the customer dataset, focusing on Annual Income and Spending Score as the key features for segmentation. The algorithm successfully partitioned the customers into five distinct, non-overlapping groups.
4. The Result: Meet Your Customer Segments
RESULT: The analysis successfully identified five distinct customer segments, each with a unique behavioral and financial profile. This provides a clear roadmap for creating highly targeted marketing campaigns.
![alt text](https://raw.githubusercontent.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means/main/Clusters%20of%20customers.png)
The Five Customer Personas:
Cluster 0: The Careful Spenders
Profile: This group has a high income but a low spending score.
Interpretation: These customers are cautious with their money. They have the financial capacity but are selective about their purchases.
Cluster 1: The Standard Customer
Profile: Characterized by moderate income and moderate spending habits.
Interpretation: This is the largest and most average segment of the customer base.
Cluster 2: The Target Audience
Profile: This highly valuable segment boasts a high income and a high spending score.
Interpretation: These are the ideal customers—affluent and willing to spend. They are prime candidates for premium products and loyalty programs.
Cluster 3: The On-a-Budget Shoppers
Profile: This group has a low income and a low spending score.
Interpretation: These are budget-conscious shoppers who are likely motivated by sales and discounts.
Cluster 4: The Careless Spenders
Profile: These customers have a low income but a high spending score.
Interpretation: This group may consist of younger customers or those who are highly influenced by trends, spending beyond their means. They are likely responsive to impulse buys and trendy product promotions.
5. Strategic Recommendations
These data-driven personas allow for the development of targeted and effective marketing strategies:
For the "Target Audience":
Strategy: Implement exclusive loyalty programs, offer early access to new collections, and create personalized high-value offers.
Goal: Maximize lifetime value and foster brand advocacy.
For the "Careful Spenders":
Strategy: Target them with marketing that highlights product quality, durability, and value for money. Limited-time offers on premium items may also be effective.
Goal: Encourage them to convert their high income into higher spending.
For the "Standard Customer":
Strategy: Maintain engagement through general brand marketing, seasonal promotions, and popular product highlights.
Goal: Nurture loyalty and gradually move them into higher-spending segments.
For the "Careless Spenders":
Strategy: Utilize social media marketing, trend alerts, and promotions on fast-moving consumer goods.
Goal: Capitalize on their tendency for impulse purchases.
For the "On-a-Budget Shoppers":
Strategy: Focus on value-based marketing, including discounts, bundle deals, and clearance sales.
Goal: Drive volume and maintain their business through affordability.
6. Technical Details
How to Replicate This Analysis
To replicate this analysis, follow these steps:
Clone the repository:
Generated bash
git clone https://github.com/LonnieSly/Machine-Learning-Customer-Segmentation-with-K-Means.git
Use code with caution.
Bash
Navigate to the project directory:
Generated bash
cd Machine-Learning-Customer-Segmentation-with-K-Means
Use code with caution.
Bash
Install the required dependencies:
Generated bash
pip install -r requirements.txt
Use code with caution.
Bash
Run the analysis:
Open and run the K-Means-Customer-Segmentation.ipynb notebook in a Jupyter environment.
Tools and Libraries
Python
Pandas: For data manipulation and analysis.
NumPy: For numerical operations.
Scikit-learn: For implementing the K-Means clustering algorithm.
Matplotlib & Seaborn: For data visualization.
Jupyter Notebook: For interactive analysis and reporting.
Dataset
The project uses the "NYC Restaurants Data - Food Ordering and Delivery" which is included in the repository (import kagglehub

# Download latest version
path = kagglehub.dataset_download("ahsan81/food-ordering-and-delivery-app-dataset")

print("Path to dataset files:", path)).
