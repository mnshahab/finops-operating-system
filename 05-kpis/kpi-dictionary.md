# FinOps KPI Dictionary

## Purpose

This document provides standardized FinOps Key Performance Indicators (KPIs) used to measure financial accountability, optimization effectiveness, forecasting accuracy, and technology value across cloud, AI, SaaS, Kubernetes, and data platforms.

A common KPI framework helps Engineering, Finance, Product, and Leadership teams make decisions using the same definitions and measurements.

---

# KPI Categories

1. Visibility and Allocation
2. Financial Management
3. Optimization
4. Commitment Management
5. Unit Economics
6. AI FinOps
7. Operational Excellence

---

# Visibility and Allocation KPIs

## Allocation Coverage

### Definition

Percentage of technology spend assigned to a known owner, application, business unit, product, or cost center.

### Formula

```text
Allocated Spend ÷ Total Spend × 100
```

### Target

```text
95%+
```

### Why It Matters

Organizations cannot manage costs effectively without ownership.

---

## Tagged Resource Coverage

### Definition

Percentage of resources containing required business and ownership metadata.

### Formula

```text
Tagged Resources ÷ Total Resources × 100
```

### Target

```text
90%+
```

---

# Financial Management KPIs

## Budget Variance

### Definition

Difference between actual spend and approved budget.

### Formula

```text
(Actual Spend - Budget) ÷ Budget × 100
```

### Target

```text
Within ±5%
```

---

## Forecast Accuracy

### Definition

Measures how accurately future spending is predicted.

### Formula

```text
1 - (|Forecast - Actual| ÷ Actual)
```

### Target

```text
95%+
```

### Why It Matters

Accurate forecasts improve planning and reduce surprises.

---

# Optimization KPIs

## Waste Percentage

### Definition

Percentage of spend identified as avoidable or unused.

### Examples

* Idle compute
* Unattached storage
* Overprovisioned resources
* Unused snapshots
* Unused load balancers

### Formula

```text
Waste Spend ÷ Total Spend × 100
```

### Target

```text
Less than 10%
```

---

## Savings Realized

### Definition

Verified reduction in spend resulting from optimization actions.

### Formula

```text
Baseline Cost - Optimized Cost
```

### Target

Continuous improvement

---

## Optimization Backlog Completion

### Definition

Percentage of approved optimization opportunities completed.

### Formula

```text
Completed Items ÷ Total Backlog Items × 100
```

### Target

```text
80%+
```

---

# Commitment Management KPIs

## Savings Plan Coverage

### Definition

Percentage of eligible compute spend covered by Savings Plans.

### Formula

```text
Covered Spend ÷ Eligible Spend × 100
```

### Target

Organization specific

Typical range:

```text
70% - 95%
```

---

## Savings Plan Utilization

### Definition

Percentage of purchased Savings Plan commitment consumed.

### Formula

```text
Consumed Commitment ÷ Purchased Commitment × 100
```

### Target

```text
95%+
```

---

## Reserved Instance Utilization

### Definition

Percentage of reserved capacity actively used.

### Formula

```text
Consumed RI Hours ÷ Purchased RI Hours × 100
```

### Target

```text
95%+
```

---

# Unit Economics KPIs

## Cost per Customer

### Definition

Technology spend divided by active customers.

### Formula

```text
Total Technology Cost ÷ Active Customers
```

### Why It Matters

Helps evaluate scalability and business growth.

---

## Cost per Transaction

### Definition

Technology spend divided by completed business transactions.

### Formula

```text
Total Technology Cost ÷ Total Transactions
```

---

## Cost per Application

### Definition

Total cost associated with a specific application or service.

### Formula

```text
Application Spend ÷ Number of Applications
```

---

# Kubernetes FinOps KPIs

## Cluster Utilization

### Definition

Percentage of allocated cluster resources actively consumed.

### Formula

```text
Used Capacity ÷ Available Capacity × 100
```

### Target

Organization specific

---

## Idle Capacity Percentage

### Definition

Percentage of provisioned capacity not used.

### Formula

```text
Idle Capacity ÷ Total Capacity × 100
```

### Target

As low as practical

---

# AI FinOps KPIs

## Cost per Inference

### Definition

Average cost to process a single inference request.

### Formula

```text
Inference Spend ÷ Number of Inference Requests
```

---

## Cost per Token

### Definition

Average cost per token processed.

### Formula

```text
Model Cost ÷ Total Tokens Processed
```

---

## GPU Utilization

### Definition

Percentage of allocated GPU capacity actively consumed.

### Formula

```text
Used GPU Capacity ÷ Allocated GPU Capacity × 100
```

### Target

```text
70%+
```

---

## AI Cost Variance

### Definition

Difference between expected AI spend and actual AI spend.

### Formula

```text
(Actual AI Spend - Forecast AI Spend) ÷ Forecast AI Spend × 100
```

---

# Operational Excellence KPIs

## Anomaly Resolution Time

### Definition

Average time required to investigate and resolve cost anomalies.

### Formula

```text
Total Resolution Time ÷ Number of Incidents
```

### Target

```text
Less than 5 business days
```

---

## Reporting Timeliness

### Definition

Percentage of reports delivered on schedule.

### Formula

```text
Reports Delivered On Time ÷ Total Reports × 100
```

### Target

```text
100%
```

---

# Executive Dashboard KPIs

The following KPIs should appear in executive reporting:

* Total Spend
* Budget Variance
* Forecast Accuracy
* Allocation Coverage
* Savings Realized
* Waste Percentage
* Commitment Coverage
* Commitment Utilization
* Cost per Customer
* Cost per Transaction
* AI Cost per Inference

---

# KPI Review Process

KPIs should be reviewed:

| Audience             | Frequency |
| -------------------- | --------- |
| Engineering Teams    | Weekly    |
| FinOps Team          | Weekly    |
| Finance Teams        | Monthly   |
| Executive Leadership | Monthly   |
| Steering Committee   | Quarterly |

---

# Document Information

| Item             | Value          |
| ---------------- | -------------- |
| Document         | KPI Dictionary |
| Version          | 1.0            |
| Status           | Active         |
| Owner            | FinOps Team    |
| Review Frequency | Quarterly      |
| Last Updated     | 2026           |
