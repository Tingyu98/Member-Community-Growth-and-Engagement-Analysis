# Member-Community-Growth-and-Engagement-Analysis

## Overview
This project leverages data-driven insights to help a nonprofit organization increase engagement within its community programs. By analyzing demographic, financial, and participation data (2001–2024), the study identifies trends affecting cultural communities and young adult involvement. Advanced modeling, visualization, and spatial analysis were applied to support strategic planning, optimize resource allocation, and strengthen outreach strategies. In total, the analysis covered 300K+ records spanning 20 years of community, financial, and participation data.

## Goal
* Understand the growth, decline, and participation of cultural communities and young adults.
* Evaluate the impact of language-specific services and structural changes on engagement.
* Forecast community participation trends to guide long-term strategic planning.
* Provide actionable recommendations for inclusive and sustainable programs.

## Methodology
* Data Sources – Organizational records (household counts, program participation, finances), plus U.S. Census demographic data.
* Data Preparation 
  * Built a Python ETL pipeline to collect, clean, and analyze 300K+ demographic, financial, and event records from 15 fragmented Excel files.  
  * Integrated data into a unified SQLite database, reducing manual processing from weeks to hours.  
  * Handled missing values, normalized participation metrics, and structured datasets for modeling.
* Modeling Techniques
  * ARIMA – Forecast household counts through 2027.
  * PCA + K-Means – Identify demographic & cultural clusters.
  * Lasso & OLS Regression – Analyze variables influencing young adult engagement.
  * T-Tests – Compare impacts of language-specific services and structural transitions.
* Visualization 
  * Built plots in Python (matplotlib, seaborn) to highlight time-series trends and cluster patterns.
  * Designed an interactive Power BI dashboard to visualize participation and demographic trends across 10 years.
* Tools
  * Python (pandas, scikit-learn, statsmodels)
  * SQLite for database management
  * ArcGIS for spatial analysis
  * Google Colab for model prototyping and workflow sharing

## Results & Insights
* Forecasting – Households projected to decline by ~5,633 between 2024–2027 (~4.45% drop).
* Cultural Communities – Programs offering Spanish (+7.5%) and Vietnamese (+27.7%) services grew, while overall registrations declined (-6.7%).
* Young Adults – 29% of participants are aged 18–39; engagement was higher in some regions (33%) compared to others (26%). Revenue, baptisms, and Hispanic/Latino counts positively correlated with young adult participation. An interactive Power BI dashboard further uncovered a 20% registration gap in young adult participation, and this finding was presented to the strategic planning team to drive new initiatives.
* Language & Cultural Services – Non-English programs show significantly higher participation, though not necessarily higher financial outcomes.
* Structural Changes – Communities transitioning from “mission” to “independent unit” saw stronger engagement and higher activity.
* Clustering Insights – PCA revealed two dominant components:
  * PC1: racial & marital diversity (African American, White Non-Hispanic, single/divorced).
  * PC2: cultural diversity (Caribbean, Filipino, Southeast Asian, Middle Eastern).
    → Distinct clusters highlight need for tailored outreach strategies.

## Recommendation
* Language Alignment – Introduce Spanish-language services in communities with high Hispanic populations to bridge the engagement gap.
* Resource Rebalancing – Shift services from overserved to underserved regions for greater community reach.
* Empower Young Adults – Create programs, events, and leadership roles where young adult presence is growing.
* Counter Decline Proactively – Address projected 1% annual decline through digital outreach, regional hubs, and strategic partnerships.
* Invest in Cultural Epicenters – Strengthen high-engagement communities with language-specific staff, events, and outreach.

