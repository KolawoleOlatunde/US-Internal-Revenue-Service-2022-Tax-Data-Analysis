# IRS 2022 Tax Data Analysis – Power BI Project

## Project Overview
This project presents an in-depth analytical exploration of the IRS 2022 (SOI) dataset using Power BI. The objective was to transform raw federal tax return data into an interactive analytical environment capable of revealing income distribution patterns, tax burden dynamics, compliance behavior, tax credit utilization, and geographic tax intelligence across the United States.

The project integrates advanced data modeling, DAX measures, and multi-page interactive dashboards to analyze how income, tax liability, and taxpayer behavior vary across states, income brackets, and filing categories.
Through a combination of descriptive analytics, distribution modeling, and policy-oriented metrics, it transforms raw IRS statistical datasets into interactive analytical dashboards that reveal:

•	Income and AGI distribution patterns
<br>•	Filing status trends
<br>•	Tax liability dynamics across income brackets
<br>•	Geographic distribution of taxpayers
<br>•	Tax credit utilization and compliance patterns
<br>•	State-level economic activity indicators

The analysis is structured into four thematic dashboards, each designed to examine a different dimension of the federal tax landscape.

The objective is to demonstrate data analysis, tax policy interpretation, and business intelligence storytelling using publicly available government data.

## Project Objectives
The project was designed to answer several key analytical questions:
<br>•	How is income distributed across AGI brackets and states?
<br>•	How does effective tax burden vary across income levels?
<br>•	Which states contribute most to federal tax revenue?
<br>•	What are the structural sources of income across different income tiers?
<br>•	How prevalent are business income, capital gains, and other income types?
<br>•	What patterns exist in filing behavior and compliance outcomes?

## Project Benefits
•	Provides data-driven support system to Tax Policy decision makers.
<br>•	Helps businesses identify best labor market.
<br>•	Helps applicants identify high employment hubs and manage income expectations.

## Data Source
The dataset used in this analysis is from the IRS Statistics of Income (SOI) Program.
Source: https://www.irs.gov/statistics/soi-tax-stats-individual-income-tax-statistics
IRS SOI Individual Income Tax Statistics – Tax Year 2022

Key variables used include:<br>
<b>Variable	Description </b> <br>
N1	      Total number of tax returns<br>
A00100	  Total Adjusted Gross Income (AGI)<br>
A04800	  Total taxable income <br>
A10300	  Total income tax liability <br>
A00200	  Wage income <br>
A00900	  Business income (Schedule C) <br>
A01000	  Capital gains <br>
A01750	  Pension income <br>
A02500	  Social security income
<br>
All monetary values are reported in thousands of dollars as per IRS SOI conventions.

## Dashboard Architecture
The Power BI report is organized into four analytical dashboards, each addressing a distinct dimension of tax system analysis.

## 1. Federal Tax Landscape
https://github.com/KolawoleOlatunde/US-Internal-Revenue-Service-2022-Tax-Data-Analysis/blob/main/FTL.jpg

This dashboard provides a macro-level overview of the U.S. tax system.

<b>Key Metrics</b>
<br>•	Total Returns Filed
<br>•	Total Adjusted Gross Income
<br>•	Total Taxable Income
<br>•	Total Federal Tax Liability
<br>•	Compliance Rate

<b>Visualizations</b>
<br>•	Non-wage income composition across major states
<br>•	Filing method adoption (electronic vs agent-prepared returns)
<br>•	Filing status distribution
<br>•	Geographic distribution of taxpayers
<br>•	State-level compliance and filing volumes

<b>Purpose</b>
<br>To establish a high-level snapshot of federal tax activity and taxpayer distribution across the United States.

## 2. Income & AGI Dynamics
This dashboard focuses on income distribution and tax burden across income brackets.

<b>Key Visualizations</b>
<br>•	Effective tax rate across AGI brackets
<br>•	Average taxable income by AGI bracket
<br>•	Filing status distribution across income tiers
<br>•	Income composition matrix (wages, business income, capital gains, pensions, social security)
<br>•	State-level income vs effective tax rate scatter analysis
<br>•	AGI decomposition tree by state and income tier

<b>Analytical Value</b><br>
This section reveals how income structure and tax burden change as income increases, highlighting the progressive nature of the U.S. tax system.

## 3. Tax Revenue & Income Dynamics
This dashboard examines economic income sources and wealth concentration patterns.

<b>Key Analyses</b>
<br>•	Capital gains vs business income concentration by state
<br>•	Wage income concentration in major employment states
<br>•	Volume of investors and business income returns
<br>•	Prevalence of Alternative Minimum Tax (AMT)
<br>•	Geographic concentration of wealth-based income

<b>Key Insight Areas</b>
<br>•	States acting as investment and business income hubs
<br>•	Structural drivers of high-income tax bases
<br>•	Relationship between wealth income and federal tax contribution

## 4. Policy Advisor – Income & Credit Dynamics
This dashboard simulates a policy-focused perspective of the federal tax system.

<b>Core Metrics</b>
<br>•	Average tax paid per return
<br>•	Tax credits distribution
<br>•	Refund dependency ratios
<br>•	Tax gap exposure by state
<br>•	State-level AGI vs tax paid relationships

<b>Visualizations</b>
<br>•	Credit distribution across income brackets
<br>•	Refund dependency curves
<br>•	Tax compliance and tax gap analysis
<br>•	Income vs tax paid scatter modeling

<b>Purpose</b><br>
This section translates raw tax data into policy-relevant insights on taxpayer behavior, credits, and compliance risks.

## Analytical Techniques Used
The project involved several analytical and modeling techniques including:

<b>Data Preparation</b>
<br>•	Power Query transformations
<br>•	Data cleaning and normalization
<br>•	Star schema data modeling

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
