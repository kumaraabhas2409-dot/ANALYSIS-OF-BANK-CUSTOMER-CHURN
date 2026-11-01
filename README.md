ACE OF SPADES — CSV Matrix 2.0

This repository showcases the Python-based case study developed by Team Ace of Spades for CSV Matrix 2.0. The project focuses on understanding bank customer churn through data analysis, customer segmentation, and visualization to help financial institutions strengthen customer retention and enhance overall customer satisfaction.

Project Overview

ABC Bank was experiencing an increasing rate of customer attrition, with customers discontinuing their banking relationships or switching to competing institutions.

The primary goal of this project was to investigate the factors contributing to customer churn, identify vulnerable customer segments, and develop data-driven strategies to improve customer retention.

The study includes:

Calculation and evaluation of the overall customer churn rate.
Analysis of churn trends across different customer tenure groups.
Examination of churn patterns based on age, gender, and geographical location.
Customer segmentation using credit scores and account balances.
Identification and assessment of potentially high-risk customers.
Correlation analysis to understand the relationship between customer attributes and churn.
Estimation of Customer Lifetime Value (CLV) and development of retention-focused insights.
Team Members
Aabhas Kumar — 2023UGMM017
Aditya Raj Tewary — 2023UGMM006
Filza Ahsan — 2023UGMM028
Tools and Technologies

The project utilized the following tools and technologies for data processing, analysis, and visualization:

Python – Primary programming language for analysis.
NumPy – Numerical computations and data operations.
Pandas – Data cleaning, manipulation, and analysis.
Matplotlib – Graphical representation of analytical findings.
Seaborn – Statistical data visualization.
Google Colab – Cloud-based development and execution environment.
Microsoft Excel – Data inspection and spreadsheet analysis.
Google Sheets – Collaborative data handling and review.
Problem Statement

ABC Bank aimed to understand the underlying reasons behind its increasing customer attrition and determine effective ways to retain valuable customers.

The available dataset contained information about customer demographics, banking activities, account characteristics, and engagement indicators. By examining these attributes, we aimed to uncover meaningful churn patterns, recognize customer segments with higher attrition risks, and translate the findings into practical business recommendations.

Key Areas of Analysis
1. Overall Churn Rate and Customer Tenure

We began by determining the bank's overall customer churn percentage and examining how attrition differed across various tenure categories.

The findings suggested that customer churn did not increase or decrease consistently with tenure. Both recently acquired customers and customers with longer banking relationships demonstrated noticeable attrition patterns, highlighting the importance of retention strategies throughout the customer lifecycle.

2. Demographic Analysis of Customer Churn

We investigated customer attrition across three major demographic dimensions:

Age groups
Gender
Geographical regions

The analysis revealed several important observations:

Customers between 50 and 60 years of age demonstrated a comparatively higher likelihood of leaving the bank.
Female customers exhibited a higher churn tendency.
Customers residing in Germany recorded the highest churn tendency among the geographical groups examined.

These findings suggest that demographic characteristics and regional differences should be considered when designing customer retention initiatives.

3. Customer Segmentation

To better understand the bank's customer base, we grouped customers according to:

Credit score ranges.
Account balance categories.
Geographical regions.

This segmentation approach helped us examine differences in customer value, identify potentially vulnerable groups, and understand how account balances were distributed across various customer categories.

4. Identification of At-Risk Customers

We applied selected risk-based filtering conditions to identify customers who demonstrated characteristics associated with a greater possibility of attrition.

The resulting subset provided an opportunity to examine high-risk customers more closely, including their demographic characteristics and regional distribution.

This approach helped highlight the importance of identifying vulnerable customers early so that targeted retention measures could be implemented.

5. Correlation Analysis

We performed correlation analysis to investigate the relationships between customer churn and important banking attributes, including:

Customer tenure.
Age.
Estimated salary.
Account balance.
Credit score.
Number of banking products.

The results indicated that age had the strongest positive correlation with customer churn, while account balance demonstrated a comparatively smaller positive association.

The remaining variables showed weaker relationships with churn, suggesting that customer attrition is influenced by multiple factors rather than a single characteristic.

6. Customer Lifetime Value (CLV) Estimation

We estimated Customer Lifetime Value for customers who had not churned to understand their potential long-term contribution to the bank.

The analysis explored:

Revenue contribution across different geographical regions.
CLV distribution across credit score categories.
Differences in CLV among age groups and geographical segments.

This assessment helped identify valuable customer segments, understand regional revenue contributions, and recognize the importance of retaining customers with greater long-term business potential.

Key Business Insights and Recommendations

Based on the analysis, we identified the following strategic insights:

Prioritize older customers: Develop targeted engagement and retention initiatives for customers within higher-risk age groups.
Focus on high-risk geographical regions: Strengthen customer experience and retention efforts in regions demonstrating higher churn, particularly Germany.
Adopt personalized engagement strategies: Customize communication and relationship-building initiatives according to customer demographics and regional preferences.
Use credit scores for effective segmentation: Although credit scores were not strong standalone indicators of CLV, they remained useful for categorizing customers.
Prioritize valuable customers: Allocate retention resources strategically by considering both customer attrition risk and long-term business value.
Encourage proactive retention: Use customer data to recognize potential churn patterns and intervene before customers decide to leave.
How to Run the Project

Follow these steps to explore and reproduce the analysis:

Open the project notebook or Python script using Google Colab or Jupyter Notebook.
Import and load the dataset used for the customer churn study.
Execute the data preprocessing and exploratory data analysis sections.
Run the visualization, segmentation, correlation, and CLV estimation procedures.
Examine the generated charts, analytical results, and business recommendations.
Competition Background

This project was created as part of CSV Matrix 2.0, where Team Ace of Spades presented a data-driven approach to understanding banking customer churn.

Through Python-based exploratory data analysis, customer segmentation, and visualization, the team aimed to transform raw customer information into meaningful business insights and actionable customer retention strategies.

Developed by Team Ace of Spades
CSV Matrix 2.0
