# SQL-Email-Campaign-Analysis

## Table of Contents
- [1. Introduction](#1-introduction)
- [2. Objectives](#2-objectives)
- [3. Key Metrics](#3-key-metrics)
- [4. Data Model](#4-data-model)
- [5. Lessons Learned](#5-lessons-learned)

## 1. Introduction

Email campaigns play a pivotal role in modern marketing strategies. Analyzing their effectiveness is essential for optimizing marketing spend and enhancing customer engagement. This project delves into the impact of various email campaigns by comparing control and target groups. By analyzing data from these campaigns, we aim to extract actionable insights to refine future marketing strategies.

## 2. Objectives

The primary goal of this analysis is to evaluate the effectiveness of email campaigns by leveraging various key performance indicators (KPIs). This evaluation helps determine which campaigns are most effective in achieving marketing goals and improving customer engagement. The specific objectives are:

- **Measure Campaign Effectiveness**: Evaluate how well email campaigns drive desired actions, such as purchases.
- **Gauge Customer Reaction**: Understand how customers respond to campaigns by monitoring engagement and dissatisfaction metrics.
- **Financial Impact Assessment**: Analyze the revenue generated from email campaigns to understand their financial contribution.
- **Long-term Engagement Analysis**: Assess how email campaigns influence customer retention and loyalty over time.
- **Performance Comparison**: Compare the performance of different email campaigns to identify best practices and areas for improvement.

## 3. Key Metrics

To comprehensively assess email campaign performance, the following key metrics are analyzed:

- **Conversion Rate**: Indicates the percentage of recipients who made a purchase after receiving the email.
- **Unsubscribe Rate**: Shows the percentage of recipients who opted out of receiving future emails.
- **Open Rate**: Measures the percentage of recipients who opened the email.
- **Click Rate**: Represents the percentage of recipients who clicked on links within the email.
- **Daily Average Revenue per Active Client**: Calculates the average revenue generated per active client each day.
- **Daily Average Revenue per Contributed Client**: Determines the average revenue per client who completed a transaction on a given day.
- **Day 10/30 Retention Rate**: Measures the percentage of clients retained 10 or 30 days after the email campaign.
- **Churn Rate**: Reflects the percentage of clients who ceased engagement with the campaign.
- **% Rate Lift**: Evaluates the improvement in performance metrics between the target and control groups.
- **Customer Lifetime Value (CLV)**: Estimates the total revenue a customer is expected to generate throughout their relationship with the business.


## 4. Data Model

The analysis is based on a **Snowflake Schema** data model, which is critical for organizing and managing campaign data efficiently. The schema includes:

- **Email Campaign**: Contains details of campaigns, such as names, start dates, and client actions.
- **Activity**: Logs interactions like email opens, clicks, and purchases.
- **Transaction**: Records transaction details, including amounts and client IDs.

## 5. Lessons Learned

This analysis provided several key insights into email campaign effectiveness:

- **Critical Role of Data Modeling**: Effective data modeling is essential for accurate analysis. A well-structured data model ensures that data is correctly organized and relationships are properly defined. Without proper data modeling, the analysis can produce misleading or incorrect results, impacting decision-making.
- **Importance of Retention and Churn Rates**: These metrics are vital for understanding the long-term success of campaigns.
- **Need for Cross-Departmental Collaboration**: Defining relevant indicators and timeframes requires input from various departments to ensure comprehensive evaluation.

The project underscores the importance of accurate data modeling in deriving meaningful insights and optimizing email marketing strategies.
