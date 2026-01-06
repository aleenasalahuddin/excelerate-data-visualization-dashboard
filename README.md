End-to-End Data Visualization & BI Dashboard (SQL + Looker Studio)
📌 Project Overview

This project focuses on transforming fragmented, multi-source operational data into a unified, decision-ready analytics system. Using SQL-based ETL, data cleaning, and structured metric mapping, six independent datasets were consolidated into a single Master Table and visualized through an interactive Google Looker Studio dashboard.

The objective was not only to visualize data, but to establish a reliable source of truth that supports performance monitoring, trend analysis, and data-driven decision-making.

🎯 Problem Statement

Prior to this project, data existed across six separate datasets with:

No centralized structure or Master Table

Inconsistent formats (dates, text casing, numeric values)

Missing values, duplicates, and indirect relationships

No standardized KPIs or metrics

Limited accessibility for non-technical stakeholders

As a result, answering even basic business questions required manual effort and ad-hoc analysis.

🛠️ Solution Approach

The project followed a structured analytics workflow:

Data Familiarization

Reviewed schema, column meanings, and data quality issues

Identified potential join keys and relationships

ETL & Master Table Creation

Extracted relevant fields from all six datasets

Applied SQL-based transformations in PostgreSQL

Merged datasets into a clean, consistent Master Table

Data Cleaning & Transformation

Standardized date and text formats

Handled missing values and duplicates

Applied business rules and transformation logic

Metric Mapping & Schema Design

Defined KPIs, metrics, and dimensions

Mapped dashboard metrics to Master Table columns

Created a comprehensive data dictionary

Dashboard Design & UX Validation

Designed an annotated dashboard wireframe

Built an interactive dashboard in Google Looker Studio

Conducted UX testing and refined layout based on feedback

🧱 Datasets Used

The project integrates six datasets:

Learner Data

Opportunity Data

Learner Opportunity Mapping

Cohort Data

Cognito (Authentication/User Metadata)

Marketing Campaign Performance Data

Each dataset contributes a specific layer of information (user attributes, engagement, campaigns, opportunities, or timelines) to the final Master Table.

📊 Dashboard Overview
<img width="2840" height="1307" alt="image" src="https://github.com/user-attachments/assets/68abb500-749e-4ec5-a1cd-d441c926ce33" />
<img width="2918" height="1466" alt="image" src="https://github.com/user-attachments/assets/0306e794-bd69-4415-bdd1-073ca5a6543f" />


🔗 Live Dashboard: https://lookerstudio.google.com/s/vN0corTx10g

🚀 Tools & Technologies

PostgreSQL — Data storage, ETL, and transformations

SQL — Joins, cleaning, aggregation, validation

Excel — Mapping tables, data review, validation

Google Looker Studio — Dashboard development

Google Sheets — Collaborative documentation

