Healthcare Operations & Financial Intelligence Dashboard

An end-to-end Healthcare Analytics solution built in Power BI, analyzing 28,000+ patient encounters to optimize hospital operational traffic, staff allocation and financial claim coverage.
 Executive Summary & Key Insights

This repository contains the complete analytical workflow, documentation and Power BI dashboard for hospital administrative operations and financial performance.
Highlights

    Ambulatory & Outpatient Traffic: Ambulatory and outpatient services account for nearly 70% of total hospital traffic across 28,000+ patient encounters.
    Financial Payer Coverage: Payer coverage averages 31% of total billed claim costs, highlighting key opportunities for revenue cycle management, claim audit workflows, and zero-coverage encounter reviews.
    Data Governance & Security: Strict PII minimization, standardized metrics and validated data quality procedures.

 Repository File Structure

    Health Operations.pbix: Main Power BI Desktop Report & Star-Schema Data Model
    Health dashboard.png: High-resolution visual export of the main dashboard
    Healthcare executive summary.docx: Executive briefing and operational recommendations
    Healthcare Report.docx: Data quality assessment & architecture documentation
    KPI Definition Sheet.docx: DAX formulas, business metrics, and validation rules
    README.md: Project overview & GitHub repository documentation

Key Performance Indicators (KPIs)
Metric	Business Definition & Focus Area
Total Encounters	Count of unique patient visits/encounters across all hospital units (28k+ records).
Outpatient Share %	Ratio of visits handled via Ambulatory/Outpatient care (~70% of volume).
Total Billed Costs	Aggregated gross claim amounts submitted across all encounters.
Payer Coverage %	Ratio of insurance coverage paid against total billed claim amounts (~31%).
Long Stays	Identification of inpatient length-of-stay exceeding clinical standard thresholds.
 Data Architecture & Star-Schema Design

The analytical engine relies on a Star-Schema model designed in Power BI:

    Fact Table: Fact_Encounters (Encounter records, claim costs, coverage amounts, duration)
    Dimension Tables: Dim_Patients (Anonymized profiles), Dim_Departments (Ambulatory/Outpatient/Inpatient), Dim_Payers (Insurance attributes), Dim_Date (Time-intelligence)

 How to Use & Deploy

    Open Health Operations.pbix in Power BI Desktop to inspect dashboard visuals and DAX metrics.
    Review Healthcare executive summary.docx for key business findings and strategic recommendations.
    Refer to Healthcare Report.docx and KPI Definition Sheet.docx for dataset specifications and data modeling details.
