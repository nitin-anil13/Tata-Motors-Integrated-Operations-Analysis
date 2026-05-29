# Tata-Motors-Integrated-Operations-Analysis

**Business Problem**

Tata Motors manages large-scale manufacturing and logistics operations involving:

  1.Shipment Tracking
  2.Dealer Distribution
  3.Customer Management
  4.Payment Processing
  5.Employee Operations
  6.Supply Chain Monitoring

As operational data grows, manual reporting and fragmented systems reduce visibility into business performance and logistics efficiency.

This project builds a centralized analytics ecosystem to improve operational intelligence and automate reporting workflows.

**Project Objectives**
**SQL ETL Pipeline**
Design relational database schema
Load operational datasets into PostgreSQL
Clean and transform logistics data
Create analytical datasets

**Excel Exploratory Data Analysis**
Customer Analytics
Shipment Analysis
Payment Analysis
Logistics Efficiency Evaluation

**Power BI Dashboard**
Customer Insights
Shipment Operations Monitoring
Financial Health Dashboard

**GenAI Automation**
Daily Logistics Summary Generation
Shipment & Payment Issue Explanation System

**Technology Stack**
PostgreSQL
SQL
Microsoft Excel
Power BI
n8n
Groq Llama 3.3 70B
Postman

**Database Architecture**

The solution uses seven operational datasets:

Customer
Membership
Employee Details
Shipment Details
Payment Details
Shipment Status
Employee Shipment Mapping

The relational model supports shipment operations, customer management, payment tracking, and logistics analytics.

**Key Business Insights**
**Logistics Performance**
Domestic shipments average 117.98 days delivery time
International shipments average 96.26 days delivery time
Regional logistics bottlenecks identified

**Payment Analytics**
COD transactions average ₹49,578.86
Card payments average ₹45,039.89
Higher operational dependency on COD workflows

**Cargo Operations**
More than 60% shipments classified as Heavy Cargo
Increased transportation and warehousing complexity

**Customer Analytics**
Retail customers represent approximately 39% of total customers
Expired memberships indicate retention opportunities


**Power BI Dashboard Modules**

**Customer Insights Panel**
  1.Customer Segmentation
  2.Membership Analysis
  3.Revenue Contribution

**Shipment Operations Dashboard**
  1.Domestic vs International Logistics
  2.Delivery Performance
  3.Service Type Analysis

**Financial Health Monitor**
  1.Revenue Trends
  2.Payment Recovery
  3.Customer Revenue Contribution


**GenAI + n8n Automation**

**Automation 1: Daily Logistics Operations Summary**

Business Problem:

Operations managers cannot continuously monitor dashboards throughout the day.

Solution:

An automated workflow retrieves operational metrics and generates AI-powered daily summaries.

Workflow:

Cron Trigger

↓

SQL Metrics Extraction

↓

GenAI Analysis

↓

Email Report Generation


**Automation 2: Shipment & Payment Issue Explanation**

Business Problem:

Operations teams require immediate explanations for shipment delays and payment issues.

Solution:

An AI-powered workflow retrieves shipment, payment, and employee information and generates business-friendly operational explanations.

Workflow:

Webhook Input

↓

Shipment Lookup

↓

SQL Data Retrieval

↓

GenAI Reasoning

↓

Operational Explanation

Estimated Business Impact
Initiative	Expected Improvement
Predictive Maintenance	8%
Defect Reduction	5%
Inventory Optimization	4%
EV Expansion	6%
Supply Chain Optimization	3%
Estimated Profitability Improvement

26%

Authors
Nithin V Anil

**Project Outcome**

The project demonstrates how SQL ETL, Excel Analytics, Power BI Reporting, and GenAI Automation can be integrated into a unified manufacturing analytics ecosystem capable of improving logistics visibility, operational efficiency, and data-driven decision-making across Tata Motors' manufacturing and supply chain network.
