# fintech-cost-optimization-case-study
End-to-end cost and margin analysis of credit card payments in a B2B fintech platform, combining transaction data, processor invoices, and BI dashboards to improve unit economics.

# 💳 Credit Card Payments Cost Optimization

**Domain:** FinTech | B2B Payments | Financial Analytics  
**Role:** Data Analyst / BI Analyst  
**Status:** Completed  
**Impact:** ~$43,000 monthly cost savings  

---

## 📌 Overview

This project focuses on analyzing the **profitability of credit card payment features** offered by a B2B payments platform.  
Despite charging customers a standard processing fee, detailed cost analysis revealed that the feature was operating at a loss due to high processor and network fees.

The objective was to identify cost leakages, understand root causes, and recommend data-driven strategies to improve unit economics.

---

## 🏢 Business Context

- Platform type: **B2B Payments Platform**
- Payment method analyzed: **Credit Card Payments**
- Monthly transaction volume: **$9M+**
- Customer processing fee: **2.9% per transaction**
- Card processors involved:
  - National Processing
  - TabaPay
  - Card Networks (including American Express)

---

## ❓ Problem Statement

Leadership observed declining margins on credit card transactions and needed clarity on:

- Is the credit card payment feature profitable?
- What are the key cost drivers?
- Which actions can reduce processing costs without impacting customer experience?

---

## 🗂️ Data Sources

- **MySQL Database**
  - Transaction-level payment data
  - Processor routing and fee details
- **Monthly Processor Invoices**
  - Provided as PDF files
  - Converted into structured Excel data
- **AI Assistance**
  - Claude AI used to extract, normalize, and categorize invoice line items

---

## 🛠️ Tools & Technologies

- SQL (MySQL)
- Power BI
- Python
- Databricks
- Excel
- Claude AI (invoice parsing)

---

## 🔍 Methodology

1. Extracted and aggregated transaction data from MySQL to calculate:
   - Total transaction volume
   - Fees collected from customers
   - Net revenue by card type and processor

2. Parsed monthly processor invoices and categorized:
   - Interchange fees
   - Network fees
   - Processor-specific charges

3. Built a **cost vs revenue model** to evaluate:
   - Net margin by processor
   - Loss-making transaction routes

4. Conducted root cause analysis to identify:
   - High-cost card networks
   - Inefficient routing methods
   - Fee structure issues

5. Researched industry best practices and processor agreements to identify feasible cost-optimization strategies.

---

## 📊 Key Findings

- The credit card payment feature was operating at a **net loss**, despite charging a 2.9% processing fee.
- Interchange and network fees were the primary contributors to margin erosion.
- American Express transactions were significantly more expensive under the existing setup.
- Collecting processing fees directly from credit cards increased downstream processing costs.

---

## 💡 Recommendations

### 1️⃣ Implement Level 3 Data Passing
Reduce interchange fees for eligible B2B transactions by passing enhanced transaction data.

### 2️⃣ Direct American Express Processing
Leverage high transaction volume to negotiate a direct processing agreement with American Express.

### 3️⃣ Change Fee Collection Method
Shift processing fee recovery from credit cards to customer wallet or linked bank account to reduce additional processing overhead.

---

## 🚀 Impact

- Estimated **$43,000+ monthly cost savings**
- Improved unit economics for credit card payments
- Enabled leadership to make informed decisions on pricing, routing, and processor negotiations
- Improved long-term sustainability of the payment feature

---

## 📈 Stakeholders

- Product & Engineering Teams
- Finance & Operations Teams
- Leadership & Strategy Teams

---

## 🧠 Key Learnings

- High transaction volume does not guarantee profitability.
- Detailed cost modeling is critical in fintech products.
- Small routing and fee-structure changes can have significant financial impact.
- Combining structured transaction data with unstructured invoice data unlocks deeper insights.

---

## 🔒 Notes

Due to confidentiality, no production data or source code is shared.  
This repository focuses on the **analytical approach, methodology, and business impact** rather than implementation details.
