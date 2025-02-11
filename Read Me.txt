Insurance Claim Analysis
Project Overview
This project focuses on analyzing auto insurance claims data to detect fraud patterns, understand geographical trends, and gain insights into the most significant factors affecting claims. The analysis includes data cleaning, machine learning techniques, and data visualization to identify key business impacts.

Files & Structure
File Name -->	Description
Auto_claims.csv -->	The original raw dataset containing insurance claims.
Data_Cleaning.ipynb -->	Jupyter Notebook detailing the data cleaning process, including handling missing values, removing duplicates, and preparing the dataset for analysis.
Prepared_data.csv -->	The cleaned dataset after preprocessing, which was used for further analysis and visualization.
ClaimAnalysis.twb -->	Tableau workbook containing dashboards and visualizations based on the cleaned data.
General Claim analysis.pdf -->	A report summarizing key insights from the analysis.

Key Steps in Analysis
    1 Data Cleaning & Preparation
        ◦ Processed missing values and removed irrelevant data.
        ◦ Ensured data integrity by filtering out unnecessary records.
        ◦ Generated Prepared_data.csv after preprocessing.
        ◦ 		
    2 Machine Learning Insights
        ◦ Applied ML techniques to identify major factors affecting claim outcomes.
        ◦ Determined which variables significantly impact different claim types.
        ◦ Discarded non-impacting features from further analysis.
        ◦ 		
    3 Data Visualization with Tableau
        ◦ Created dashboards to explore claim distributions, fraud detection, and geographical trends.
        ◦ Focused on Property, Injury, and Vehicle claims, with Vehicle claims being the most frequent.
        ◦ 		
    4 Key Findings
        ◦ Certain variables significantly affect claim results, while others do not.
        ◦ Fraud hotspots and patterns were identified based on claim types and locations.
        ◦ Vehicle claims are far more common than property claims in the dataset.

Usage & How to Explore
    1. Data Cleaning & Preprocessing
        ◦ Open Data_Cleaning.ipynb to see the full pipeline.
        ◦ 		
    2. Machine Learning Analysis
        ◦ Run models to explore feature importance in claim outcomes. 
        		
    3.  Tableau Dashboards 
 		
        ◦ Open ClaimAnalysis.twb to explore interactive visualizations.
         		
    4. Final Report
        ◦ Read General Claim Analysis.pdf for summarized insights.

Next Steps
    • Further refinement of ML models to improve fraud detection.
    • Additional analysis on underrepresented claim types.
    • Expansion to other insurance fraud cases.
