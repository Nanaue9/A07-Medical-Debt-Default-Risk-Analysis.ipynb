# A07-Medical-Debt-Default-Risk-Analysis.ipynb

Problem Definition & Data Source

Problem Definition:

The primary objective of this project is to analyze and understand the factors contributing to medical debt in the United States. By examining data from 2011 to 2023 at county, state, and national levels, we aim to identify key demographic and financial determinants that influence the likelihood of medical debt defaults. Specifically, the project focuses on:
	•	Identifying the most significant financial and demographic factors associated with higher medical debt.
	•	Assessing the impact of hospital market concentration, closures, and mergers on medical debt levels.
	•	Evaluating the role of insurance coverage, income levels, and racial disparities in contributing to medical debt.
	•	Comparing trends from previous years to identify shifts in the dynamics of medical debt.
	•	Forecasting future trends in medical debt to inform policy and strategic decision-making.

Data Source:

The analysis leverages comprehensive datasets from multiple reputable sources to ensure a robust and multifaceted understanding of medical debt trends:
	•	Urban Institute Credit Bureau Panel: Provides detailed information on medical debt in collections, covering over 5 million consumers annually from 2011 to 2019 and over 10 million consumers annually from 2020 to 2023.
	•	American Hospital Association Annual Survey Database: Supplies data on hospital market concentration, closures, and mergers.
	•	CMS Provider of Services File: Offers insights into hospital closures and mergers.
	•	American Community Survey (ACS): Delivers demographic and income data, including uninsured rates, disability prevalence, and household income figures.
	•	U.S. Census Bureau: Complements ACS data with additional demographic information.

These datasets are integrated and analyzed using BigQuery to facilitate comprehensive multivariate analyses, enabling the identification of patterns and correlations that drive medical debt trends.
https://datacatalog.urban.org/dataset/changing-medical-debt-landscape-united-states

Motivation and Summary

Motivation:

Medical debt poses a significant financial burden on individuals and communities, affecting both personal well-being and the stability of healthcare providers and financial institutions. Understanding the underlying factors that contribute to medical debt is crucial for developing effective policies and strategies to alleviate this burden. This project seeks to provide actionable insights by analyzing extensive data on medical debt, insurance coverage, income levels, and healthcare market dynamics. The findings aim to inform policymakers, healthcare providers, and individuals, enabling them to make informed decisions that promote financial stability and equitable access to healthcare.

Summary:

In this project, we conducted an extensive analysis of medical debt in the United States from 2011 to 2023, utilizing data from the Urban Institute, American Hospital Association, CMS Provider File, and American Community Survey. Our analysis encompasses several key areas:
	1.	Medical Debt Trends:
	•	Identified a strong correlation between uninsured rates and higher medical debt levels.
	•	Observed a negative correlation between household income and medical debt, with lower-income counties experiencing higher debt burdens.
	2.	Income and Racial Disparities:
	•	Found that counties with a majority of residents identifying as people of color have significantly higher medical debt shares compared to majority white counties across all income segments.
	•	Highlighted that middle and high-income uninsured individuals face higher median medical debt compared to their insured counterparts.
	3.	Healthcare Market Concentration:
	•	Determined that higher hospital market concentration (higher HHI) is associated with increased medical debt, suggesting that reduced competition may lead to higher healthcare costs.
	4.	Regional Differences:
	•	Noted substantial regional disparities, with Western states exhibiting higher medical debt rates and uninsured populations compared to Northeastern and Midwestern states.
	5.	Future Projections and Recommendations:
	•	Forecasted trends indicating the need for expanded health insurance coverage and economic support for low-income households.
	•	Proposed strategies to address racial disparities and promote healthcare market competition to mitigate medical debt.

Our findings provide a comprehensive understanding of the multifaceted nature of medical debt, emphasizing the importance of targeted policy interventions to reduce financial burdens and promote equitable healthcare access.

Collaborators

Yanxu(Adam) Yang, Yucheng He, Jacob Rose, Kayla Candice Huang, Sanjal Atul Desai, Victoria Carlsten

By systematically addressing the complexities of medical debt through data-driven analysis, this project aims to contribute valuable insights that can shape future healthcare policies and financial support mechanisms, ultimately fostering a more equitable and financially secure healthcare environment for all Americans.
