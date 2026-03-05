# IRS 2022 Tax Data Analysis – Power BI Project

## Project Overview
This project presents an in-depth analytical exploration of the IRS 2022 (SOI) dataset using Power BI. The objective was to transform raw federal tax return data into an interactive analytical environment capable of revealing income distribution patterns, tax burden dynamics, compliance behavior, tax credit utilization, and geographic tax intelligence across the United States.

The project integrates advanced data modeling, DAX measures, and multi-page interactive dashboards to analyze how income, tax liability, and taxpayer behavior vary across states, income brackets, and filing categories.
Through a combination of descriptive analytics, distribution modeling, and policy-oriented metrics, it transforms raw IRS statistical datasets into interactive analytical dashboards that reveal:

- Income and AGI distribution patterns
- Filing status trends
- Tax liability dynamics across income brackets
- Geographic distribution of taxpayers
- Tax credit utilization and compliance patterns
- State-level economic activity indicators

The analysis is structured into four thematic dashboards, each designed to examine a different dimension of the federal tax landscape.

The objective is to demonstrate data analysis, tax policy interpretation, and business intelligence storytelling using publicly available government data.

## Project Objectives
The project was designed to answer several key analytical questions:
- How is income distributed across AGI brackets and states?
- How does effective tax burden vary across income levels?
- Which states contribute most to federal tax revenue?
- What are the structural sources of income across different income tiers?
- How prevalent are business income, capital gains, and other income types?
- What patterns exist in filing behavior and compliance outcomes?

## Project Benefits
- Provides data-driven support system to Tax Policy decision makers.
- Helps businesses identify best labor market.
- Helps applicants identify high employment hubs and manage income expectations.

## Data Source
The dataset used in this analysis is from the United Stste Internal Revenue Service 2022 Tax data.

Source: https://www.irs.gov/statistics/soi-tax-stats-state-data-fy-2022

A total of 165 variables and 166,132 records were analysed. Sample variables used include:<br>
N1	  - Total number of tax returns<br>
A00100	  - Total Adjusted Gross Income (AGI)<br>
A04800	  - Total taxable income <br>
A10300	 - Total income tax liability <br>
A00200 -	  Wage income <br>
A00900	-  Business income (Schedule C) <br>
A01000	 - Capital gains <br>
A01750	 - Pension income <br>
A02500	 - Social security income, etc.

All monetary values are reported in thousands of dollars as per IRS SOI conventions.

## Dashboard Architecture
The Power BI report is organized into four analytical dashboards, each addressing a distinct dimension of tax system analysis.

## 1. Federal Tax Landscape
This dashboard provides a macro-level overview of the U.S. tax system.

![image alt](https://github.com/KolawoleOlatunde/US-Internal-Revenue-Service-2022-Tax-Data-Analysis/blob/3bccc66aacef41d17348ed95a9f254030d65025f/FTL.jpg)

<b>Key Metrics</b>
- Total Returns Filed
- Total Adjusted Gross Income
- Total Taxable Income
- Total Federal Tax Liability
- Compliance Rate

<b>Visualizations</b>
- Non-wage income composition across major states
- Filing method adoption (electronic vs agent-prepared returns)
- Filing status distribution
- Geographic distribution of taxpayers
- State-level compliance and filing volumes

<b>Purpose</b>
<br>To establish a high-level snapshot of federal tax activity and taxpayer distribution across the United States.

## 2. Income & AGI Dynamics
This dashboard focuses on income distribution and tax burden across income brackets.

![image alt](https://github.com/KolawoleOlatunde/US-Internal-Revenue-Service-2022-Tax-Data-Analysis/blob/ef9bc856a2267db149b9178409359dc4c9ffd05b/IAD.jpg)

<b>Key Visualizations</b>
- Effective tax rate across AGI brackets
- Average taxable income by AGI bracket
- Filing status distribution across income tiers
- Income composition matrix (wages, business income, capital gains, pensions, social security)
- State-level income vs effective tax rate scatter analysis
- AGI decomposition tree by state and income tier

<b>Analytical Value</b><br>
This section reveals how income structure and tax burden change as income increases, highlighting the progressive nature of the U.S. tax system.

## 3. Tax Revenue & Income Dynamics
This dashboard examines economic income sources and wealth concentration patterns.

![image alt](https://github.com/KolawoleOlatunde/US-Internal-Revenue-Service-2022-Tax-Data-Analysis/blob/ef9bc856a2267db149b9178409359dc4c9ffd05b/TRID.jpg)

<b>Key Analyses</b>
- Capital gains vs business income concentration by state
- Wage income concentration in major employment states
- Volume of investors and business income returns
- Prevalence of Alternative Minimum Tax (AMT)
- Geographic concentration of wealth-based income

<b>Key Insight Areas</b>
- States acting as investment and business income hubs
- Structural drivers of high-income tax bases
- Relationship between wealth income and federal tax contribution

## 4. Policy Advisor – Income & Credit Dynamics
This dashboard simulates a policy-focused perspective of the federal tax system.

![image alt](https://github.com/KolawoleOlatunde/US-Internal-Revenue-Service-2022-Tax-Data-Analysis/blob/ef9bc856a2267db149b9178409359dc4c9ffd05b/PA.jpg)

<b>Core Metrics</b>
- Average tax paid per return
- Tax credits distribution
- Refund dependency ratios
- Tax gap exposure by state
- State-level AGI vs tax paid relationships

<b>Visualizations</b>
- Credit distribution across income brackets
- Refund dependency curves
- Tax compliance and tax gap analysis
- Income vs tax paid scatter modeling

<b>Purpose</b><br>
This section translates raw tax data into policy-relevant insights on taxpayer behavior, credits, and compliance risks.

## Analytical Techniques Used
The project involved several analytical and modeling techniques including:

<b>Data Preparation</b>
- Power Query transformations
- Data cleaning and normalization
- Star schema data modeling

<b>Advanced DAX Metrics</b>

Examples of calculated measures include:
<br>•	Effective Tax Rate
<br>•	Compliance Rate
<br>•	Refund Rate
<br>•	EITC Penetration
<br>•	Schedule C Prevalence
<br>•	Average AGI per Return
<br>•	Average Wage per Return
<br>•	Tax Credit Distribution Ratios

<b>Advanced Visual Analytics</b>
<br>•	Decomposition Trees
<br>•	Scatter Modeling
<br>•	Matrix Composition Analysis
<br>•	Geographic Mapping
<br>•	Bubble Charts
<br>•	Waterfall AGI distribution analysis

## Key Insights from the Analysis
<b>1. Income Concentration</b>:
High-income brackets account for a disproportionate share of total taxable income and federal tax liability.
<br><b>2. Geographic Tax Contribution</b>:
A small number of states – including California, Texas, Florida, and New York – dominate federal tax revenue contributions.
<br><b>3. Progressive Tax Structure</b>:
Effective tax rates increase with AGI brackets, demonstrating the progressive structure of the U.S. federal tax system.
<br><b>4. Income Source Diversification</b>:
Lower-income households rely heavily on wage income, while higher-income brackets increasingly derive income from capital gains and business income.
<br><b>5. Filing Behavior</b>:
Electronic filing dominates the filing landscape, indicating strong digital adoption within the tax system.
<br><b>6. Credit Dependence</b>:
Refund dependency declines sharply as income rises, highlighting the role of tax credits in supporting lower-income households.

## Skills Demonstrated
This project demonstrates practical expertise in:

•	Data analytics
<br>•	Financial and tax data interpretation
<br>•	Power BI dashboard design
<br>•	Advanced DAX modeling
<br>•	Public finance analysis
<br>•	Data storytelling
<br>•	Policy-oriented analytics

## Tools Used
•	Power BI
<br>•	Power Query
<br>•	DAX
<br>•	Microsoft Excel
<br>•	IRS SOI datasets

## Project Value

This analysis illustrates how public financial data can be transformed into decision-support tools for:
<br>•	policy analysis
<br>•	economic research
<br>•	tax compliance monitoring
<br>•	fiscal policy modeling
<br>•	public finance transparency
________________________________________
## Author
<b>Kolawole Olatunde</b>
<br>Tax Compliance & Data Analytics Specialist
<br>MSc Applied Artificial Intelligence & Data Analytics
