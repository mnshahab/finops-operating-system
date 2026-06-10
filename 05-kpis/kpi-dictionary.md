# KPI Dictionary

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document serves as the authoritative source for all Key Performance Indicator (KPI) definitions used throughout the FinOps Operating System.

The objective is to establish standardized metric definitions, calculation methodologies, ownership models, reporting frequencies, and data requirements to ensure consistency across financial reporting, executive dashboards, operational reviews, optimization programs, and governance activities.

This KPI Dictionary aligns with FinOps Foundation principles of visibility, accountability, collaboration, and business value realization.

---

# Scope

This dictionary applies to:

* AWS
* Microsoft Azure
* Google Cloud Platform
* Kubernetes Platforms
* AI and Machine Learning Workloads
* Shared Services Platforms
* Product Teams
* Corporate IT Workloads
* Enterprise Cloud Services

---

# KPI Classification Framework

KPIs are organized into the following categories:

| Category          | Purpose                                            |
| ----------------- | -------------------------------------------------- |
| Financial         | Financial performance and accountability           |
| Governance        | Ownership, allocation, and compliance              |
| Forecasting       | Planning and predictability                        |
| Optimization      | Efficiency and waste reduction                     |
| Engineering       | Resource utilization and operational effectiveness |
| Unit Economics    | Business value and product efficiency              |
| AI FinOps         | AI workload efficiency and economics               |
| Kubernetes FinOps | Container platform efficiency                      |

---

# Financial KPIs

## Total Cloud Spend

| Attribute | Value                           |
| --------- | ------------------------------- |
| Category  | Financial                       |
| Owner     | Finance and FinOps              |
| Frequency | Monthly                         |
| Purpose   | Measure total cloud expenditure |

### Calculation

```text
Sum of Cloud Costs
```

### Data Sources

* Cloud Billing Data
* Cost Management Platforms
* Financial Reporting Systems

---

## Cloud Spend Growth Rate

| Attribute | Value                         |
| --------- | ----------------------------- |
| Category  | Financial                     |
| Owner     | Finance and FinOps            |
| Frequency | Monthly                       |
| Purpose   | Measure cloud spending growth |

### Calculation

```text
(Current Spend - Previous Spend)
÷ Previous Spend
```

---

## Cloud Spend as Percentage of Revenue

| Attribute | Value                                      |
| --------- | ------------------------------------------ |
| Category  | Financial                                  |
| Owner     | Finance                                    |
| Frequency | Monthly or Quarterly                       |
| Purpose   | Measure cloud spending relative to revenue |

### Calculation

```text
Cloud Spend ÷ Revenue
```

---

# Governance KPIs

## Allocation Coverage

| Attribute | Value                                                       |
| --------- | ----------------------------------------------------------- |
| Category  | Governance                                                  |
| Owner     | FinOps                                                      |
| Frequency | Monthly                                                     |
| Purpose   | Measure percentage of spend allocated to accountable owners |

### Calculation

```text
Allocated Spend ÷ Total Spend
```

---

## Resource Ownership Coverage

| Attribute | Value                        |
| --------- | ---------------------------- |
| Category  | Governance                   |
| Owner     | Engineering and FinOps       |
| Frequency | Monthly                      |
| Purpose   | Measure ownership visibility |

### Calculation

```text
Owned Resources ÷ Total Resources
```

---

## Tag Compliance Rate

| Attribute | Value                                     |
| --------- | ----------------------------------------- |
| Category  | Governance                                |
| Owner     | Engineering                               |
| Frequency | Monthly                                   |
| Purpose   | Measure compliance with tagging standards |

### Calculation

```text
Compliant Resources ÷ Total Resources
```

---

## Unallocated Spend

| Attribute | Value                                       |
| --------- | ------------------------------------------- |
| Category  | Governance                                  |
| Owner     | FinOps                                      |
| Frequency | Monthly                                     |
| Purpose   | Measure spend without accountable ownership |

### Calculation

```text
Total Spend - Allocated Spend
```

---

# Forecasting KPIs

## Forecast Accuracy

| Attribute | Value                          |
| --------- | ------------------------------ |
| Category  | Forecasting                    |
| Owner     | Finance and FinOps             |
| Frequency | Monthly                        |
| Purpose   | Measure forecast effectiveness |

### Calculation

```text
1 - (|Actual - Forecast|
÷ Forecast)
```

---

## Budget Variance

| Attribute | Value                                   |
| --------- | --------------------------------------- |
| Category  | Forecasting                             |
| Owner     | Finance                                 |
| Frequency | Monthly                                 |
| Purpose   | Measure deviation from approved budgets |

### Calculation

```text
Actual Spend - Budget
```

---

## Forecast Variance

| Attribute | Value                           |
| --------- | ------------------------------- |
| Category  | Forecasting                     |
| Owner     | Finance and FinOps              |
| Frequency | Monthly                         |
| Purpose   | Measure deviation from forecast |

### Calculation

```text
Actual Spend - Forecast
```

---

# Optimization KPIs

## Optimization Opportunity Value

| Attribute | Value                                         |
| --------- | --------------------------------------------- |
| Category  | Optimization                                  |
| Owner     | FinOps                                        |
| Frequency | Monthly                                       |
| Purpose   | Measure identified optimization opportunities |

### Calculation

```text
Sum of Approved Opportunities
```

---

## Optimization Realization Rate

| Attribute | Value                                        |
| --------- | -------------------------------------------- |
| Category  | Optimization                                 |
| Owner     | Engineering and FinOps                       |
| Frequency | Monthly                                      |
| Purpose   | Measure optimization execution effectiveness |

### Calculation

```text
Implemented Actions
÷ Approved Actions
```

---

## Commitment Utilization

| Attribute | Value                                      |
| --------- | ------------------------------------------ |
| Category  | Optimization                               |
| Owner     | FinOps                                     |
| Frequency | Monthly                                    |
| Purpose   | Measure effective use of cloud commitments |

### Calculation

```text
Consumed Commitment
÷ Purchased Commitment
```

---

## Commitment Coverage

| Attribute | Value                                    |
| --------- | ---------------------------------------- |
| Category  | Optimization                             |
| Owner     | FinOps                                   |
| Frequency | Monthly                                  |
| Purpose   | Measure workload coverage by commitments |

### Calculation

```text
Eligible Spend Covered
÷ Eligible Spend
```

---

# Engineering KPIs

## Compute Utilization

| Attribute | Value                      |
| --------- | -------------------------- |
| Category  | Engineering                |
| Owner     | Engineering Teams          |
| Frequency | Monthly                    |
| Purpose   | Measure compute efficiency |

### Calculation

```text
Consumed Capacity
÷ Provisioned Capacity
```

---

## Storage Utilization

| Attribute | Value                      |
| --------- | -------------------------- |
| Category  | Engineering                |
| Owner     | Engineering Teams          |
| Frequency | Monthly                    |
| Purpose   | Measure storage efficiency |

### Calculation

```text
Used Storage
÷ Allocated Storage
```

---

## Rightsizing Adoption Rate

| Attribute | Value                                                 |
| --------- | ----------------------------------------------------- |
| Category  | Engineering                                           |
| Owner     | Engineering Teams                                     |
| Frequency | Monthly                                               |
| Purpose   | Measure implementation of rightsizing recommendations |

### Calculation

```text
Implemented Rightsizing Actions
÷ Approved Rightsizing Actions
```

---

## Resource Cleanup Rate

| Attribute | Value                               |
| --------- | ----------------------------------- |
| Category  | Engineering                         |
| Owner     | Engineering Teams                   |
| Frequency | Monthly                             |
| Purpose   | Measure removal of unused resources |

### Calculation

```text
Removed Resources
÷ Identified Resources
```

---

# Unit Economics KPIs

## Cost per Customer

| Attribute | Value                                      |
| --------- | ------------------------------------------ |
| Category  | Unit Economics                             |
| Owner     | Product Leadership                         |
| Frequency | Monthly                                    |
| Purpose   | Measure cloud cost efficiency per customer |

### Calculation

```text
Cloud Spend ÷ Customers
```

---

## Cost per Active Customer

| Attribute | Value                                             |
| --------- | ------------------------------------------------- |
| Category  | Unit Economics                                    |
| Owner     | Product Leadership                                |
| Frequency | Monthly                                           |
| Purpose   | Measure cloud cost efficiency per active customer |

### Calculation

```text
Cloud Spend ÷ Active Customers
```

---

## Cost per Transaction

| Attribute | Value                          |
| --------- | ------------------------------ |
| Category  | Unit Economics                 |
| Owner     | Product Teams                  |
| Frequency | Monthly                        |
| Purpose   | Measure operational efficiency |

### Calculation

```text
Cloud Spend ÷ Transactions
```

---

## Cost per User

| Attribute | Value                             |
| --------- | --------------------------------- |
| Category  | Unit Economics                    |
| Owner     | Product Teams                     |
| Frequency | Monthly                           |
| Purpose   | Measure cloud efficiency per user |

### Calculation

```text
Cloud Spend ÷ Users
```

---

# AI FinOps KPIs

## Cost per AI Inference

| Attribute | Value                          |
| --------- | ------------------------------ |
| Category  | AI FinOps                      |
| Owner     | AI Platform Team               |
| Frequency | Monthly                        |
| Purpose   | Measure AI inference economics |

### Calculation

```text
AI Spend ÷ Inference Requests
```

---

## Cost per Training Run

| Attribute | Value                            |
| --------- | -------------------------------- |
| Category  | AI FinOps                        |
| Owner     | AI Platform Team                 |
| Frequency | Monthly                          |
| Purpose   | Measure training cost efficiency |

### Calculation

```text
Training Spend ÷ Training Runs
```

---

## Cost per GPU Hour

| Attribute | Value                 |
| --------- | --------------------- |
| Category  | AI FinOps             |
| Owner     | AI Platform Team      |
| Frequency | Monthly               |
| Purpose   | Measure GPU economics |

### Calculation

```text
GPU Spend ÷ GPU Hours
```

---

# Kubernetes FinOps KPIs

## Kubernetes Resource Efficiency

| Attribute | Value                                     |
| --------- | ----------------------------------------- |
| Category  | Kubernetes FinOps                         |
| Owner     | Platform Team                             |
| Frequency | Monthly                                   |
| Purpose   | Measure Kubernetes utilization efficiency |

### Calculation

```text
Consumed Resources
÷ Allocated Resources
```

---

## Cost per Kubernetes Workload

| Attribute | Value                      |
| --------- | -------------------------- |
| Category  | Kubernetes FinOps          |
| Owner     | Platform Team              |
| Frequency | Monthly                    |
| Purpose   | Measure workload economics |

### Calculation

```text
Kubernetes Spend ÷ Workloads
```

---

## Node Utilization

| Attribute | Value                   |
| --------- | ----------------------- |
| Category  | Kubernetes FinOps       |
| Owner     | Platform Team           |
| Frequency | Monthly                 |
| Purpose   | Measure node efficiency |

### Calculation

```text
Consumed Node Capacity
÷ Available Node Capacity
```

---

# KPI Governance

All KPI definitions should:

* Maintain consistent calculation methodologies.
* Use approved data sources.
* Align with governance standards.
* Support executive and operational reporting.
* Be reviewed periodically.

Changes should be approved through the FinOps governance process.

---

# KPI Review Process

KPI definitions should be reviewed:

| Review Activity       | Frequency |
| --------------------- | --------- |
| KPI Validation        | Quarterly |
| Data Quality Review   | Quarterly |
| KPI Definition Review | Annual    |
| Governance Review     | Annual    |

---

# Related Documents

* README.md
* executive-kpis.md
* engineering-kpis.md
* unit-economics-kpis.md
* governance-framework.md
* allocation-framework.md
* budget-framework.md
* forecasting-framework.md
* executive-reporting-framework.md
