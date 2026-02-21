# fintech-cost-optimization-case-study
End-to-end cost and margin analysis of credit card payments in a B2B fintech platform, combining transaction data, processor invoices, and BI dashboards to improve unit economics.

💳 Credit Card Payments Cost Optimization

Domain: FinTech | B2B Payments | Financial Analytics
Role: Data Analyst / BI Analyst
Status: Completed
Impact: ~$43,000 monthly cost savings

📌 Overview

This project focused on analyzing the profitability of credit card payment features offered by a B2B payments platform. Although the platform charged customers a standard processing fee, a detailed cost analysis revealed that the feature was operating at a loss due to high processor and network fees.

The objective was to identify cost leakages, understand root causes, and recommend data-driven strategies to improve unit economics.

🏢 Business Context

Platform type: B2B Payments Platform

Payment method analyzed: Credit Card Payments

Monthly transaction volume: $9M+

Customer processing fee: 2.9% per transaction

Card processors involved:

National Processing

TabaPay

Card Networks (including AmEx)

❓ Problem Statement

Despite strong transaction volumes and standard pricing, leadership suspected that the credit card payment feature might be negatively impacting profitability.

Key questions:

Is the credit card payment feature profitable?

Where are the major cost drivers?

What actions can reduce processing costs without hurting user experience?

🗂️ Data Sources

MySQL Database

Transaction-level payment data

Processor routing and fee details

Monthly Processor Invoices

Provided as PDF files

Converted to structured Excel data

AI Assistance

Claude AI used to extract, normalize, and categorize invoice line items

🛠️ Tools & Technologies

SQL (MySQL)

Power BI

Python

Databricks

Excel

Claude AI (for invoice parsing)

🔍 Methodology

Extracted and aggregated transaction data from MySQL to calculate:

Total volume

Fees collected from customers

Net revenue by card type and processor

Parsed monthly processor invoices and categorized:

Interchange fees

Network fees

Processor-specific charges

Built a cost vs revenue model to evaluate:

Net margin by processor

Loss-making transaction routes

Conducted root cause analysis to identify:

High-cost card types

Inefficient routing

Fee structure issues

Researched industry best practices and processor agreements to identify feasible cost-optimization strategies.

📊 Key Findings

The credit card payment feature was operating at a net loss, despite a 2.9% customer fee.

Interchange and network fees were significantly higher for certain transaction routes.

American Express transactions were particularly expensive under the existing setup.

Fee recovery directly from credit cards increased downstream processing costs.

💡 Recommendations

Implement Level 3 Data Passing
Reduce interchange fees for eligible B2B transactions.

Direct AmEx Processing Agreement
Leverage high transaction volume to negotiate a direct deal with American Express.

Change Fee Collection Method
Shift fee recovery from credit cards to customer wallet or bank account to reduce processing overhead.

🚀 Impact

Estimated $43,000+ monthly cost savings

Improved unit economics for credit card payments

Enabled leadership to make informed decisions on pricing, routing, and processor negotiations

Strengthened long-term sustainability of the payment feature

📈 Stakeholders

Product & Engineering

Finance & Operations

Leadership & Strategy Teams

🧠 Key Learnings

High transaction volume does not guarantee profitability.

Detailed cost modeling is critical in fintech products.

Small routing and fee-structure changes can have large financial impact.

Combining structured data with unstructured invoice data unlocks deeper insights.

🔒 Notes

Due to confidentiality, no production data or code is shared. This case study focuses on the analytical approach, decision-making process, and business impact.
