# Insurance Risk & Claims Dashboard

## Project Overview

The Insurance Risk & Claims Dashboard is an interactive analytics dashboard built using Power BI to analyze insurance policies, claim amounts, and risk factors. The dashboard helps insurance companies understand policy distribution, claim trends, and customer demographics in order to improve risk management and decision-making.

## Objectives

• Analyze insurance policy distribution across different categories
• Monitor total claim amounts and claim frequency
• Understand customer demographics and risk profiles
• Identify trends in vehicle usage and insurance coverage
• Support data-driven decisions for insurance risk assessment

## Tools Used

• Power BI
• Power Query
• DAX (Data Analysis Expressions)
• Excel Dataset

## Dataset Description

The dataset contains insurance-related information including:

• Policy details
• Claim amount and claim frequency
• Customer demographics (age, gender, education)
• Vehicle information (car make, car year, car usage)
• Coverage zones (urban, rural, suburban)
• Driving behavior (kids driving indicator)

## Key Performance Indicators (KPIs)

The dashboard tracks the following key metrics:

• Total Policies
• Total Claim Amount
• Average Claim Frequency
• Average Claim Amount
• Policy distribution by gender

## Dashboard Features

### Policy Summary

Displays total number of insurance policies along with total claim amount and average claim statistics.

### Vehicle Analysis

Analyzes insurance policies based on:
• Car Make
• Car Usage
• Car Manufacturing Year

### Customer Demographics

Shows policy distribution by:
• Age Group
• Gender
• Education Level

### Geographic Coverage

Visualizes policy distribution across coverage zones such as:
• Urban
• Suburban
• Rural
• Highly Urban
• Highly Rural

### Risk Indicators

Analyzes potential risk factors such as the number of kids driving associated with policyholders.

### Education & Marital Status Analysis

Displays claim distribution based on education levels and marital status.

## Example DAX Measures

Total Claim Amount = SUM(Claims[Claim_Amount])

Average Claim Amount = AVERAGE(Claims[Claim_Amount])

Claim Frequency = AVERAGE(Claims[Claim_Frequency])

## Dashboard Preview

![Dashboard](https://github.com/beheradinesh8280/Insurance-Risk-Claims-Dashboard/blob/main/Screenshot.png)

## Business Value

This dashboard helps insurance companies:

• Understand claim patterns
• Identify high-risk customer segments
• Optimize policy pricing strategies
• Improve risk management
• Monitor insurance portfolio performance



Skills: Python, SQL, Power BI, Excel, Data Visualization
