# Unit Economics KPIs

| Attribute    | Value                                        |
| ------------ | -------------------------------------------- |
| Owner        | Product Leadership, Finance, and FinOps Team |
| Version      | 1.0                                          |
| Status       | Active                                       |
| Last Updated | YYYY-MM-DD                                   |
| Review Cycle | Annual                                       |

---

# Purpose

This document defines the unit economics Key Performance Indicators (KPIs) used to measure the relationship between cloud spending and business outcomes.

The objective is to help organizations understand how cloud investments support products, services, customers, and revenue-generating activities. Unit economics KPIs provide a business-oriented view of cloud consumption and enable leaders to evaluate efficiency, profitability, scalability, and value realization.

These KPIs align with FinOps Foundation principles of accountability, visibility, collaboration, and business value realization.

---

# Scope

This document applies to:

* AWS
* Microsoft Azure
* Google Cloud Platform
* Kubernetes Platforms
* AI and Machine Learning Workloads
* SaaS Products
* Digital Products
* Customer-Facing Applications
* Shared Platforms
* Enterprise Cloud Services

---

# Unit Economics Principles

## Cloud Costs Should Be Connected to Business Outcomes

Organizations should understand the relationship between cloud spending and the value delivered to customers, users, products, and business operations.

---

## Metrics Must Be Actionable

Unit economics KPIs should support strategic planning, pricing decisions, product investment decisions, and optimization efforts.

---

## Consistency Is Critical

Metric definitions should remain consistent across reporting periods to support trend analysis and decision-making.

---

## Business Context Matters

Cloud cost metrics should be evaluated alongside growth, revenue, customer adoption, and operational performance.

---

## No Single KPI Tells the Whole Story

Unit economics should be evaluated through multiple related metrics rather than relying on a single indicator.

---

# Unit Economics KPI Categories

The KPI framework is organized into four categories.

## Customer Economics

Measures cloud cost relative to customers and customer growth.

---

## Product Economics

Measures cloud cost relative to products and services.

---

## Transaction Economics

Measures cloud cost relative to business transactions and usage activity.

---

## AI and Platform Economics

Measures cloud cost associated with platform services, AI services, and shared technology capabilities.

---

# Customer Economics KPIs

## Cost per Customer

Measures cloud spending associated with each customer.

### Purpose

Evaluate customer-level efficiency and scalability.

### Calculation

```text
Total Cloud Spend ÷ Total Customers
```

### Reporting Frequency

Monthly

### KPI Owner

Product Leadership and Finance

---

## Cost per Active Customer

Measures cloud spending associated with active customers.

### Purpose

Provide a more accurate view of customer consumption patterns.

### Calculation

```text
Total Cloud Spend ÷ Active Customers
```

### Reporting Frequency

Monthly

### KPI Owner

Product Teams

---

## Cloud Spend per Customer Segment

Measures cloud cost across different customer groups.

### Purpose

Support pricing, profitability, and growth decisions.

### Examples

* Enterprise Customers
* Mid-Market Customers
* Small Business Customers
* Consumer Customers

### Reporting Frequency

Monthly or Quarterly

### KPI Owner

Product Leadership

---

# Product Economics KPIs

## Cost per Product

Measures cloud spending associated with individual products or services.

### Purpose

Improve product-level financial visibility.

### Calculation

```text
Product Cloud Spend
```

### Reporting Frequency

Monthly

### KPI Owner

Product Leadership

---

## Product Gross Margin Impact

Measures the influence of cloud costs on product profitability.

### Purpose

Support product investment and pricing decisions.

### Calculation

```text
Product Revenue - Cloud Costs
```

### Reporting Frequency

Monthly or Quarterly

### KPI Owner

Finance

---

## Cloud Spend as a Percentage of Product Revenue

Measures cloud spending relative to product revenue.

### Purpose

Evaluate product efficiency and scalability.

### Calculation

```text
Cloud Spend ÷ Product Revenue
```

### Reporting Frequency

Monthly

### KPI Owner

Finance and Product Leadership

---

# Transaction Economics KPIs

## Cost per Transaction

Measures cloud spending associated with business transactions.

### Purpose

Evaluate operational efficiency.

### Calculation

```text
Cloud Spend ÷ Transaction Volume
```

### Examples

* Orders
* Payments
* API Calls
* Claims
* Reservations

### Reporting Frequency

Monthly

### KPI Owner

Product Teams

---

## Cost per API Request

Measures cloud spending associated with API consumption.

### Purpose

Evaluate platform efficiency.

### Calculation

```text
Cloud Spend ÷ API Requests
```

### Reporting Frequency

Monthly

### KPI Owner

Platform Teams

---

## Cost per Workload

Measures cloud spending associated with a workload or service.

### Purpose

Support workload optimization and platform management.

### Calculation

```text
Cloud Spend ÷ Workloads
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering and Product Teams

---

# AI and Platform Economics KPIs

## Cost per AI Inference

Measures cloud spending associated with AI inference requests.

### Purpose

Evaluate AI service efficiency and scalability.

### Calculation

```text
AI Cloud Spend ÷ Inference Requests
```

### Reporting Frequency

Monthly

### KPI Owner

AI Platform Teams

---

## Cost per Model Training Run

Measures cloud spending associated with model training activities.

### Purpose

Improve visibility into AI development costs.

### Calculation

```text
Training Spend ÷ Training Runs
```

### Reporting Frequency

Monthly

### KPI Owner

AI Platform Teams

---

## Cost per GPU Hour

Measures cloud spending associated with GPU consumption.

### Purpose

Evaluate AI infrastructure efficiency.

### Calculation

```text
GPU Spend ÷ GPU Hours Consumed
```

### Reporting Frequency

Monthly

### KPI Owner

AI Platform Teams

---

## Cost per Kubernetes Workload

Measures cloud spending associated with workloads deployed on Kubernetes platforms.

### Purpose

Evaluate platform efficiency and workload economics.

### Calculation

```text
Kubernetes Spend ÷ Workloads
```

### Reporting Frequency

Monthly

### KPI Owner

Platform Teams

---

# Shared Service Economics KPIs

## Cost per Platform User

Measures shared platform costs relative to platform consumers.

### Purpose

Evaluate efficiency of shared services.

### Calculation

```text
Platform Spend ÷ Platform Users
```

### Reporting Frequency

Monthly

### KPI Owner

Platform Owners

---

## Cost per Environment

Measures cloud spending associated with supported environments.

### Purpose

Improve visibility into development, testing, and production costs.

### Calculation

```text
Cloud Spend ÷ Environments
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

# KPI Review Process

Unit economics reviews should evaluate:

* Customer growth trends
* Product profitability trends
* Transaction efficiency trends
* Platform efficiency trends
* AI consumption trends
* Business value realization
* Pricing model effectiveness

Reviews should be incorporated into regular product, financial, and FinOps operating cadences.

---

# Reporting Requirements

Unit economics reporting should provide visibility into:

* Customer economics
* Product economics
* Transaction economics
* Platform economics
* AI economics
* Revenue alignment
* Cost efficiency trends
* Business value realization

Reports should support product leaders, finance teams, executives, and FinOps practitioners.

---

# Roles and Responsibilities

| Function             | Responsibility                |
| -------------------- | ----------------------------- |
| Product Leadership   | Product performance oversight |
| Finance              | Financial analysis            |
| FinOps               | Cost analysis and reporting   |
| Engineering          | Workload cost visibility      |
| Platform Teams       | Platform economics reporting  |
| AI Teams             | AI economics reporting        |
| Executive Leadership | Strategic decision-making     |

---

# Governance Requirements

Unit economics KPI definitions should:

* Use approved business definitions.
* Align with financial reporting standards.
* Remain consistent across reporting periods.
* Be reviewed periodically.
* Support strategic decision-making.

Changes should be reviewed through established governance processes.

---

# Success Measures

An effective unit economics KPI framework should result in:

* Improved product profitability visibility
* Better pricing decisions
* Increased financial transparency
* Improved business alignment
* Better investment decisions
* Improved platform efficiency
* Stronger AI cost visibility
* Greater value realization from cloud investments

---

# Related Documents

* README.md
* kpi-dictionary.md
* executive-kpis.md
* engineering-kpis.md
* allocation-framework.md
* budget-framework.md
* forecasting-framework.md
* commitment-planning.md
* unit-economics-framework.md
* executive-reporting-framework.md

