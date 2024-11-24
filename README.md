Aviation Risk Assessment Dashboard

Overview

This repository contains the resources, data, and analysis for creating a comprehensive Aviation Risk Assessment Dashboard. As part of the company's expansion into aviation, this project evaluates historical aviation incident data to guide the acquisition of safe and low-risk aircraft for commercial and private operations. The dashboard provides actionable insights into risk factors and trends, enabling data-driven decision-making that aligns with safety and operational goals.
Business Understanding
Problem Statement

Our company is venturing into the aviation industry to operate commercial and private aircraft. However, there is limited knowledge about the risks associated with different aircraft models. This project aims to address this challenge by analyzing historical aviation data to identify the safest aircraft for our fleet and minimize operational risks.
Executive Summary

This project evaluates historical aviation incident data to identify low-risk aircraft types that meet the company’s goals for safety and profitability. By analyzing variables such as incident frequency, injury rates, weather conditions, and damage severity, we aim to recommend aircraft models that reduce risks and ensure passenger safety.
Objectives

Identify Low-Risk Aircraft: Analyze historical data to determine aircraft models with minimal incidents, injuries, and damages.
Understand Risk Factors: Investigate variables like weather conditions, flight purpose, and damage severity that influence aviation risks.
Provide Actionable Insights: Develop data-driven recommendations for acquiring safe aircraft based on risk assessments.

Research Questions

1.Which aircraft models have the lowest incident rates and injury severities?

2.How do weather conditions (e.g., VMC, IMC) affect the frequency and severity of aviation incidents?

3.What is the distribution of risk scores across different aircraft types, and which factors contribute most to higher scores?

4.How have aviation incident trends evolved over time, particularly for business and commercial flights?

5.What patterns emerge from incidents across countries, and how do they inform regional safety standards?

Success Criteria

1.Data Quality and Handling: Effectively manage missing values and extract meaningful insights from the dataset.

2.Risk Assessment Framework: Develop a reliable risk scoring model that integrates factors such as incidents, injuries, and damages.

3.Actionable Recommendations: Present clear, data-driven recommendations for aircraft acquisition that align with safety and operational objectives.

Features of the Dashboard

1.Aviation Risk Compass: A user-friendly, interactive Tableau dashboard that visualizes risk factors for different aircraft models, weather conditions, and regions.

2.Risk Scoring Model: Comprehensive scoring framework for evaluating safety risks based on multiple variables.

3.Actionable Insights: Clear recommendations for fleet acquisition and operational safety improvements.

4.Here is the link to the Dashboard 

https://public.tableau.com/views/AviationRiskCompass/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

Repository Structure

    ├── data/                # Raw and processed datasets
    ├── notebooks/           # Jupyter notebooks for data analysis and model development
    ├── dashboard/           # Tableau files and screenshots of the dashboard
    ├── scripts/             # Python scripts for data cleaning and processing
    ├── visuals/             # Exported charts and visualizations
    ├── README.md            # Overview of the project (this file)

Getting Started
Prerequisites

    Python 3.9+: For data processing and analysis.
    Tableau: For dashboard creation and visualization.
    Libraries: Install dependencies from requirements.txt:

    pip install -r requirements.txt

Running the Analysis

    Load the dataset into the data/ directory.
    Run the data processing scripts in scripts/ to clean and preprocess the data.
    Open the Jupyter notebooks in notebooks/ to explore the data and calculate risk scores.
    Use Tableau files in dashboard/ to visualize insights and build the dashboard.

Future Enhancements

    Expand the risk model to incorporate real-time aviation data.
    Develop predictive analytics to forecast future risks.
    Integrate automated reporting for decision-makers.
