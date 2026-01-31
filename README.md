## StatisticsProject

This repository contains a Jupyter notebook file, to analyze customer behavior using statistical and mathematical tools in Python, to identify factors affecting customer retention and churn.

Dataset used: "customer_behavior.csv"

# Dataset Description:
Assume a dataset with the following columns:
    1. CustomerID
    2. Gender
    3. Region
    4. PurchaseAmount
    5. ProductCategory
    6. Churn (Yes/No)
    7. CampaignGroup (A/B)

 Notebook file contains the answers the following questions:

    1. What is the average, median, and mode of PurchaseAmount?
        - Uses the mean(), median() and mode() functions.
    2. Are there any outliers in the PurchaseAmount data?
        - Uses the IQR method to identify if there is any outliers.
    3. Is there any skewness or kurtosis in the PurchaseAmount distribution?
        - Uses the skew and kurtosis method of scipy.stats.
    4. Is there a significant difference in spending between male and female customers?
        - Performs statistical independent two-sample t-test.
    5. Is there a relationship between ProductCategory and customer churn?
        - Performs chi-square test
    6. Does PurchaseAmount vary significantly across different regions?
        - Performs one-way ANOVA test.
    7. Which email campaign (A or B) performed better in terms of average PurchaseAmount?
        - Performs the independent two-sample t-test
    8. Can we assume PurchaseAmount follows a normal distribution?
        - Visualizes using the histplot.
    9. What insights can we gain by applying the Central Limit Theorem?
        - Normal Distribution of Means with Central Limit Theorem using histplot.
    10.What is the 95% confidence interval for the average PurchaseAmount?
        - Identifies the 95% Confidence Interval for average PurchaseAmount.