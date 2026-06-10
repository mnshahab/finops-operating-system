# AWS Commitment Management Framework

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the framework for planning, purchasing, managing, optimizing, and governing AWS commitment-based discount programs.

The objective is to maximize cost efficiency while balancing financial risk, workload flexibility, business growth, and operational requirements.

This framework provides AWS-specific guidance for managing Savings Plans, Reserved Instances, Capacity Reservations, and long-term AWS consumption commitments.

---

# Scope

This framework applies to:

* AWS Organizations
* AWS Accounts
* Amazon EC2
* Amazon RDS
* Amazon Aurora
* Amazon Redshift
* Amazon OpenSearch Service
* Amazon ElastiCache
* AWS Lambda
* Amazon EKS
* Amazon ECS
* AWS Fargate
* AWS Savings Plans
* AWS Reserved Instances
* AWS Capacity Reservations

---

# Guiding Principles

## Commitments Should Follow Demand

Commitments should be based on predictable workload demand rather than discount opportunities alone.

---

## Flexibility Has Value

The lowest cost option is not always the best option.

Organizations should balance commitment coverage with business agility.

---

## Coverage and Utilization Must Be Managed Together

High coverage with poor utilization creates waste.

Effective commitment programs require continuous monitoring of both metrics.

---

## Commitments Are Financial Investments

All commitment decisions should be supported by business cases, forecasting analysis, and governance approvals.

---

## Optimization Is Continuous

Commitment portfolios should evolve as workloads, architecture, and business requirements change.

---

# AWS Commitment Objectives

The AWS commitment management process should enable organizations to:

* Reduce AWS spending
* Improve forecast accuracy
* Improve budget predictability
* Maximize commitment utilization
* Minimize commitment waste
* Improve cloud investment decisions
* Support enterprise financial planning
* Improve optimization maturity

---

# AWS Commitment Portfolio

AWS provides several commitment mechanisms.

## Savings Plans

AWS Savings Plans provide flexible discounts in exchange for a committed hourly spend.

Types include:

* Compute Savings Plans
* EC2 Instance Savings Plans
* SageMaker Savings Plans

Savings Plans are generally the preferred commitment model due to flexibility and broad coverage.

---

## Reserved Instances

Reserved Instances provide discounted pricing for specific AWS services.

Examples include:

* Amazon RDS
* Amazon Redshift
* Amazon ElastiCache
* Amazon OpenSearch

Reserved Instances may provide additional savings for stable workloads.

---

## Capacity Reservations

Capacity Reservations provide guaranteed infrastructure availability.

Examples include:

* EC2 Capacity Reservations
* Zonal Reservations
* Dedicated Capacity Requirements

Capacity Reservations should be evaluated separately from cost optimization initiatives.

---

## Enterprise Commitments

Examples include:

* Strategic AWS Agreements
* Enterprise Discount Programs
* Contractual Consumption Commitments

These commitments should be integrated into financial planning processes.

---

# Commitment Lifecycle

```text
Workload Analysis
        │
        ▼
Demand Forecasting
        │
        ▼
Coverage Modeling
        │
        ▼
Business Case Review
        │
        ▼
Approval Process
        │
        ▼
Purchase Execution
        │
        ▼
Monitoring
        │
        ▼
Optimization
```

The commitment lifecycle should be incorporated into regular FinOps operating cadences.

---

# Commitment Planning Process

## Step 1: Analyze Historical Consumption

Evaluate historical AWS usage patterns.

Areas of analysis include:

* EC2 consumption
* Database consumption
* Kubernetes consumption
* Serverless consumption
* AI workload consumption

---

## Step 2: Forecast Future Demand

Forecast future cloud consumption using:

* Historical trends
* Business growth assumptions
* Product roadmaps
* Technology initiatives
* AI adoption plans

---

## Step 3: Identify Eligible Workloads

Determine workloads suitable for commitment coverage.

Examples:

* Production applications
* Core databases
* Shared platforms
* Stable Kubernetes environments
* AI inference environments

---

## Step 4: Model Coverage Scenarios

Evaluate multiple commitment strategies.

Examples:

* Conservative
* Balanced
* Aggressive

---

## Step 5: Review Risks

Assess financial and operational risks.

Examples:

* Overcommitment
* Underutilization
* Architectural changes
* Product retirement
* Migration initiatives

---

## Step 6: Obtain Approvals

Follow established governance and approval processes.

---

## Step 7: Execute and Monitor

Purchase commitments and monitor ongoing performance.

---

# Savings Plan Strategy

## Coverage Prioritization

Organizations should prioritize:

1. Stable Production Workloads
2. Shared Platform Services
3. Container Platforms
4. Serverless Workloads
5. AI Inference Workloads

Coverage strategies should align with workload predictability.

---

## Term Selection

Common options include:

* One-Year Term
* Three-Year Term

Selection should consider:

* Business growth
* Technology roadmaps
* Risk tolerance
* Financial objectives

---

## Payment Options

Options include:

* No Upfront
* Partial Upfront
* All Upfront

Selection should align with financial planning objectives.

---

# Reserved Instance Strategy

Reserved Instances are appropriate when:

* Workloads are highly stable.
* Service-specific commitments provide meaningful benefits.
* Flexibility requirements are limited.
* Long-term usage patterns are predictable.

Reserved Instance purchases should be reviewed regularly.

---

# Commitment Coverage Management

Coverage measures the percentage of eligible AWS spend protected by commitments.

### Calculation

```text
Eligible Spend Covered
÷ Eligible Spend
```

Coverage should be monitored by:

* AWS Organization
* Business Unit
* Product
* Shared Platform
* Service

---

# Commitment Utilization Management

Utilization measures how effectively purchased commitments are consumed.

### Calculation

```text
Consumed Commitment
÷ Purchased Commitment
```

Low utilization should trigger investigation and corrective action.

---

# AWS Service Coverage Strategy

## Compute Services

Examples:

* EC2
* EKS Worker Nodes
* ECS
* Fargate
* Lambda

Primary commitment vehicle:

* Savings Plans

---

## Database Services

Examples:

* RDS
* Aurora
* Redshift
* ElastiCache

Primary commitment vehicle:

* Reserved Instances

---

## AI Services

Examples:

* SageMaker
* GPU Workloads
* Inference Services

Primary commitment vehicle:

* Savings Plans

---

# AI Commitment Planning

AI workloads require specialized evaluation.

Areas of focus include:

* GPU demand forecasts
* Training workloads
* Inference workloads
* Model adoption trends
* Accelerator utilization

AI commitments should be reviewed more frequently than traditional workloads.

---

# Commitment Risk Management

Common risks include:

* Overcommitment
* Underutilization
* Technology modernization
* Cloud migration
* Product retirement
* Demand volatility
* Organizational change

Risks should be documented and reviewed regularly.

---

# AWS Commitment KPIs

Recommended KPIs include:

* Commitment Coverage
* Commitment Utilization
* Commitment Waste
* Savings Realization
* Forecast Accuracy
* Budget Variance
* Coverage by Business Unit
* Coverage by Service

Definitions should align with the KPI Dictionary.

---

# Roles and Responsibilities

| Function       | Responsibility                    |
| -------------- | --------------------------------- |
| FinOps         | Commitment strategy and reporting |
| Finance        | Financial governance              |
| Engineering    | Workload planning                 |
| Platform Teams | Shared service planning           |
| Product Teams  | Demand forecasting                |
| Leadership     | Approval and oversight            |

---

# Reporting Requirements

Commitment reporting should include:

* Savings Plan inventory
* Reserved Instance inventory
* Coverage metrics
* Utilization metrics
* Expiration schedules
* Savings realization
* Financial risk indicators
* Optimization opportunities

Reports should support operational, financial, and executive stakeholders.

---

# Governance Requirements

Commitment management should be governed through established FinOps processes.

Governance activities should include:

* Commitment reviews
* Purchase approvals
* Utilization reviews
* Coverage reviews
* Renewal planning
* Executive reporting

Material commitment decisions should follow documented approval procedures.

---

# Success Measures

An effective AWS commitment management program should result in:

* Improved commitment utilization
* Improved coverage alignment
* Reduced commitment waste
* Better forecast accuracy
* Increased cost efficiency
* Reduced financial risk
* Improved planning maturity

---

# Related Documents

* aws-cost-management-framework.md
* aws-cost-optimization-framework.md
* aws-reporting-and-analytics.md
* aws-governance-framework.md
* budget-framework.md
* forecasting-framework.md
* commitment-planning.md
* variance-management.md
* kpi-dictionary.md
* executive-kpis.md
