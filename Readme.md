# Retail Analysis

### Problem Statement
- It is a critical requirement for business to understand the value derived from a customer. RFM is a method used for analyzing customer value.
- Customer segmentation is the practice of segregating the customer base into groups of individuals based on some common characteristics such as age, gender, interests, and spending habits
 - Perform customer segmentation using RFM analysis. The resulting segments can be ordered from most valuable (highest recency, frequency, and value) to least valuable (lowest recency, frequency, and value)


##### Steps Performed
**Data Cleaning**
- Check for missing data and formulate an apt strategy to treat them
- Remove duplicate data records.
- Perform descriptive analytics on the given data

**Data Transformation**
Perform cohort analysis (a cohort is a group of subjects that share a defining characteristic). Observe how a cohort behaves across time and compare it to other cohorts **(Customer Monthly Retention )**
- Create month cohorts and analyze active customers for each cohort
- Analyze the retention rate of customers

**Data Modelling**
1. Build a RFM (Recency Frequency Monetary) model. Recency means the number of days since a customer made the last purchase. Frequency is the number of purchase in a given period. It could be 3 months, 6 months or 1 year. Monetary is the total amount of money a customer spent in that given period. Therefore, big spenders will be differentiated among other customers such as MVP (Minimum Viable Product) or VIP.
2. Calculate RFM metrics.
3. Build RFM Segments. Give recency, frequency, and monetary scores individually by dividing them into quartiles
    - Combine three ratings to get a RFM segment (as strings).
    - Get the RFM score by adding up the three ratings
    - Analyze the RFM segments by summarizing them and comment on the findings
    
**Data Modelling**
Create clusters using k-means clustering algorithm
- Prepare the data for the algorithm. If the data is asymmetrically distributed, manage the skewness with appropriate transformation. Standardize the data.
- Decide the optimum number of clusters to be formed.
- Analyze these clusters and comment on the results.