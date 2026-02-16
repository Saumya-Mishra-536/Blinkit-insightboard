Blinkit Business Analytics Project

Customer Insights | Feedback Analysis | Inventory Optimization

Project Overview

This project focuses on analyzing key operational and customer data from Blinkit to generate actionable business insights. The analysis is divided into three major domains: Customer Data, Customer Feedback, and Inventory Management.

The objective of this project is to understand customer behavior, evaluate service quality, and monitor inventory efficiency. By cleaning, validating, and analyzing structured datasets, this project demonstrates how raw operational data can be transformed into meaningful performance indicators and decision-support insights.

1. Customer Analytics

The customer dataset contains demographic and transactional summary information for registered users. This data helps in understanding purchasing behavior, customer segmentation, and revenue contribution.

Dataset Description

Each customer record includes identification details, contact information, geographic information, registration date, customer segment classification, total orders placed, and average order value.

Key Business Metrics

Total Revenue (calculated as total_orders × avg_order_value)

Revenue contribution by customer segment

Customer distribution by segment

Average order value by segment

Top customers by revenue

Customer acquisition trend based on registration date

Business Purpose

This analysis helps identify high-value customers, inactive users, and growth opportunities across regions. Segment-level insights support targeted marketing strategies and retention planning.

2. Customer Feedback Analysis

The feedback dataset captures customer ratings, written feedback, feedback category, and sentiment classification. This dataset is used to measure customer satisfaction and identify operational pain points.

Rating and Sentiment Structure

Ratings are mapped as follows:
1 – Bad
2 – Average
3 – Neutral
4 – Very Good
5 – Excellent

For reporting purposes, ratings are grouped into sentiment buckets:

Positive (4–5)

Neutral (3)

Negative (1–2)

Key Insights Generated

Overall customer satisfaction percentage

Sentiment distribution

Category-wise complaint analysis (Delivery, App Experience, Product Quality, Customer Service)

Identification of recurring issues

Feedback trends over time

Business Purpose

This analysis helps identify service gaps, monitor product quality issues, and improve operational efficiency. Sentiment tracking enables management to take corrective actions based on customer voice.

3. Inventory and Damage Analysis

The inventory dataset tracks stock received and damaged stock quantities for products. This analysis supports operational quality control and loss reduction.

Key Metric

Damage Percentage = (damaged_stock / stock_received) × 100

Validation rules ensure that damaged stock does not exceed received stock.

Insights Derived

Overall damage rate

Product-level damage tracking

Identification of high-loss inventory

Operational efficiency measurement

Business Purpose

Monitoring damage percentage helps reduce wastage, improve supplier quality control, and optimize logistics handling processes.

Data Cleaning and Validation Performed

Standardized text fields to proper case

Cleaned address formatting and removed line breaks

Split phone number into country code and mobile number

Validated phone number structure

Standardized sentiment classification based on rating

Flagged invalid inventory records

Created derived metrics such as Revenue and Damage %

Dashboard Structure

The final dashboard is structured into the following sections:

KPI Overview

Total Customers

Total Revenue

Total Orders

Average Order Value

Customer Satisfaction Rate

Overall Damage Percentage

Customer Analytics

Segment performance

Revenue by segment

Top customers

Feedback Insights

Sentiment distribution

Category-wise issues

Monthly feedback trends

Inventory Analysis

Damage percentage trends

High damage products

Stock vs damaged comparison

Conclusion

This project demonstrates the complete lifecycle of business data analysis — from cleaning and validation to KPI development and insight generation. By integrating customer behavior analysis, sentiment tracking, and inventory monitoring, the project provides a comprehensive operational overview that can support data-driven decision-making in an e-commerce environment.
