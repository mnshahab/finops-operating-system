# Commitment Planning Framework

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the framework for planning, purchasing, managing, and governing cloud financial commitments across the organization.

The objective is to maximize business value from cloud commitment programs while balancing cost optimization, operational flexibility, financial risk, and workload uncertainty.

This framework aligns with FinOps Foundation principles of visibility, accountability, collaboration, and business value realization.

---

# Scope

This framework applies to:

* AWS
* Microsoft Azure
* Google Cloud Platform
* Kubernetes Platforms
* AI and Machine Learning Workloads
* Shared Services Platforms
* Product Teams
* Enterprise Cloud Services
* Long-Term Cloud Consumption Commitments

---

# Guiding Principles

## Commitments Must Support Business Demand

Commitments should be based on expected workload requirements and business demand, not solely on discount opportunities.

---

## Financial Risk Must Be Managed

All commitments introduce financial obligations and should be evaluated against business, technical, and operational risks.

---

## Coverage Should Follow Predictability

Commitments are most effective when applied to stable and predictable workloads.

---

## Optimization Is Continuous

Commitment management should be reviewed regularly as workloads, architecture, and business requirements evolve.

---

## Collaboration Is Required

Commitment decisions should involve Finance, FinOps, Engineering, Product, and Platform stakeholders.

---

# Objectives

The commitment planning process should enable organizations to:

* Reduce cloud costs through commitment programs
* Improve financial predictability
* Increase commitment utilization
* Reduce commitment waste
* Support budgeting and forecasting
* Improve cloud investment decisions
* Balance flexibility and cost optimization

---

# Commitment Types

## AWS Commitments

Examples include:

* Savings Plans
* Reserved Instances
* Capacity Reservations
* Reserved Node Offerings
* Reserved Database Capacity

---

## Microsoft Azure Commitments

Examples include:

* Azure Reservations
* Savings Plans for Compute
* Reserved Capacity
* Dedicated Host Reservations

---

## Google Cloud Commitments

Examples include:

* Committed Use Discounts
* Resource-Based Commitments
* Capacity Reservations

---

## Enterprise Agreements

Examples include:

* Enterprise Consumption Agreements
* Strategic Cloud Commitments
* Multi-Year Consumption Agreements

---

# Commitment Planning Lifecycle

```text
Workload Analysis
        │
        ▼
Demand Forecasting
        │
        ▼
Commitment Modeling
        │
        ▼
Risk Assessment
        │
        ▼
Approval Process
        │
        ▼
Purchase Execution
        │
        ▼
Utilization Monitoring
        │
        ▼
Continuous Optimization
```

Commitment planning should be integrated into budgeting and forecasting processes.

---

# Commitment Candidate Identification

Workloads should be evaluated for commitment suitability.

Common candidates include:

* Production applications
* Long-running services
* Stable databases
* Core platform services
* Kubernetes worker nodes
* AI inference environments
* Enterprise shared services

Workloads with highly variable consumption may require different commitment strategies.

---

# Commitment Evaluation Criteria

Before acquiring commitments, organizations should evaluate:

* Historical consumption
* Forecasted demand
* Growth expectations
* Business criticality
* Architectural roadmap
* Migration plans
* Workload flexibility
* Contract terms

Commitments should align with both technical and financial objectives.

---

# Commitment Modeling

Commitment planning should include scenario analysis.

Common scenarios include:

## Conservative Strategy

Prioritizes flexibility and minimizes financial risk.

Characteristics:

* Lower commitment coverage
* Higher flexibility
* Lower risk of unused commitments

---

## Balanced Strategy

Balances flexibility and cost optimization.

Characteristics:

* Moderate commitment coverage
* Moderate risk profile
* Common enterprise approach

---

## Aggressive Strategy

Maximizes commitment coverage and discount potential.

Characteristics:

* Higher commitment coverage
* Greater savings potential
* Increased utilization risk

Organizations should select strategies based on business requirements and risk tolerance.

---

# Commitment Coverage Management

Coverage represents the percentage of eligible cloud consumption supported by commitments.

Coverage analysis should consider:

* Compute services
* Database services
* Container platforms
* AI workloads
* Shared services

Coverage should be monitored regularly to identify opportunities and risks.

---

# Commitment Utilization Management

Utilization measures how effectively purchased commitments are consumed.

Organizations should monitor:

* Utilization trends
* Underutilized commitments
* Expiring commitments
* Workload shifts
* New demand patterns

Low utilization should trigger investigation and corrective action.

---

# AI Commitment Planning

AI workloads may require specialized commitment strategies.

Considerations include:

* GPU consumption patterns
* Training workload variability
* Inference workload growth
* Model deployment strategies
* Capacity availability

Commitment decisions should reflect the unique characteristics of AI environments.

---

# Kubernetes Commitment Planning

Kubernetes environments often benefit from commitment optimization.

Areas of focus include:

* Worker node commitments
* Shared cluster capacity
* Platform services
* Persistent storage
* Supporting infrastructure

Commitment planning should align with cluster growth forecasts and platform roadmaps.

---

# Commitment Risk Management

Common commitment risks include:

* Overcommitment
* Underutilization
* Architectural changes
* Cloud migration initiatives
* Business demand changes
* Product retirement
* Technology modernization

Risks should be documented and reviewed regularly.

---

# Roles and Responsibilities

| Function       | Responsibility                          |
| -------------- | --------------------------------------- |
| Finance        | Financial governance                    |
| FinOps         | Commitment analysis and recommendations |
| Engineering    | Workload planning                       |
| Product Teams  | Demand forecasting                      |
| Platform Teams | Shared service planning                 |
| Leadership     | Approval and oversight                  |

Commitment ownership should be clearly defined for all major commitment programs.

---

# Review Cadence

| Review Type                | Frequency |
| -------------------------- | --------- |
| Utilization Review         | Monthly   |
| Coverage Review            | Monthly   |
| Forecast Review            | Monthly   |
| Commitment Strategy Review | Quarterly |
| Executive Review           | Quarterly |
| Portfolio Assessment       | Annual    |

Organizations may adopt additional review cycles based on commitment volume and complexity.

---

# Reporting Requirements

Commitment reporting should include:

* Commitment inventory
* Coverage metrics
* Utilization metrics
* Expiration schedules
* Financial impact
* Savings realization
* Risk indicators
* Optimization opportunities

Reports should support operational, financial, and executive decision-making.

---

# Governance Requirements

Commitment planning should be governed through established FinOps and financial management processes.

Governance activities should include:

* Strategy approval
* Commitment reviews
* Risk assessments
* Purchase approvals
* Renewal planning
* Executive reporting

Significant commitment decisions should follow documented approval procedures.

---

# Success Measures

An effective commitment planning practice should result in:

* Improved commitment utilization
* Improved coverage alignment
* Better forecast accuracy
* Reduced financial risk
* Increased cost efficiency
* Improved planning maturity
* Better business alignment

---

# Related Documents

* budget-framework.md
* forecasting-framework.md
* variance-management.md
* allocation-framework.md
* showback-framework.md
* chargeback-framework.md
* governance-framework.md
* cost-accountability-model.md
* kpi-dictionary.md
* executive-reporting-framework.md
