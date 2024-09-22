# **Customer Lifetime Value Prediction using Machine Learning**

## **Overview**
Customer Lifetime Value (CLV) is a crucial metric for businesses, representing the total revenue expected from a customer throughout their relationship with the company. Understanding CLV helps organizations allocate resources effectively, tailor marketing strategies, and enhance customer retention efforts. This project aims to predict customer segments based on their lifetime value using historical transaction data, enabling businesses to make informed decisions.

## **Project Goals**
- **Identify customer segments** based on predicted LTV.
- **Develop a machine learning model** to classify customers into low, mid, and high LTV groups.
- **Visualize insights** from the data to aid in business strategy formulation.

## **Dataset** [(Link)](https://www.kaggle.com/datasets/sergeymedvedev/customer_segmentation)
The dataset used for this project comprises transaction data from a retail company, including customer IDs, purchase dates, quantities, and unit prices. Key features include:
- **Recency:** Time since last purchase.
- **Frequency:** Number of purchases.
- **Monetary Value:** Total spent by the customer.
  

## **Project Structure**
- **Data Preprocessing:**
  - Data cleaning and preparation.
  - Feature engineering to derive metrics like Recency, Frequency, and Revenue.
  
- **Exploratory Data Analysis (EDA):**
  - Visualizations to understand the distribution of customer LTV.
  - Correlation analysis to identify key features influencing LTV.

- **Clustering:**
  - Implementation of K-means clustering to segment customers into LTV groups.
  - Identification of characteristics for each segment.

- **Machine Learning Model:**
  - Multiclass classification using XGBoost to predict LTV segments.
  - Model evaluation using accuracy, precision, recall, and F1-score.

## **Methodology**
1. **Data Cleaning:** Remove duplicates and outliers to ensure data quality.
2. **Feature Engineering:** Convert categorical variables into numerical format and create new features relevant for the model.
3. **Clustering Analysis:** Use K-means to create LTV segments, helping visualize customer groups.
4. **Model Training:** Train an XGBoost classifier to predict customer segments based on engineered features.
5. **Model Evaluation:** Assess the model's performance using metrics such as accuracy, precision, recall, and F1-score.

## **Results**
- Achieved an accuracy of 90% on the test set.
- Identified precision and recall metrics for each LTV segment, indicating areas for model improvement:
  - **Cluster 0:** High precision and recall (Good performance).
  - **Cluster 1:** Moderate performance, needs improvement.
  - **Cluster 2:** Low detection rate, requires further enhancement.

## **Future Work**
- **Feature Expansion:** Incorporate additional features to improve model performance.
- **Hyperparameter Tuning:** Experiment with different model parameters for optimization.
- **Alternative Models:** Explore other machine learning algorithms for potential better accuracy.
- **Additional Data:** Integrate more data for improved model robustness.

## **Conclusion**
This project demonstrates the application of machine learning to classify customers based on their lifetime value. The insights derived can significantly influence business strategies, enabling targeted marketing and improved customer relationships.

## **Contact**
Email - vsc312@gmail.com
[LinkedIn](www.linkedin.com/in/vardhan-choudhary)
