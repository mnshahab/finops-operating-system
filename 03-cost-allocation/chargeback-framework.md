# Chargeback Framework

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the framework for recovering cloud costs from the business units, products, applications, and teams responsible for consuming cloud resources.

The objective of chargeback is to align cloud spending with financial accountability, improve cost transparency, support budgeting and forecasting activities, and encourage responsible cloud consumption.

This framework aligns with FinOps Foundation principles of accountability, visibility, collaboration, and business value realization.

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
* Corporate IT Workloads
* Enterprise Support Services

---

# Guiding Principles

## Accountability Through Financial Ownership

Teams consuming cloud services should be financially accountable for the costs incurred.

---

## Transparency Before Chargeback

Chargeback should only be implemented after stakeholders have sufficient visibility into their cloud consumption through established reporting and showback processes.

---

## Consistency Across the Organization

Chargeback methodologies should be applied consistently across business units and reporting periods.

---

## Simplicity and Understandability

Chargeback calculations should be understandable by business, finance, and technology stakeholders.

---

## Fair Cost Distribution

Costs should be allocated using methodologies that reasonably reflect actual consumption and business ownership.

---

## Governance Driven

All chargeback methodologies should be approved and reviewed through established governance processes.

---

# Chargeback Model Overview

Chargeback transfers cloud costs from centralized cloud budgets to the business units, products, or applications responsible for consuming resources.

The model enables organizations to:

* Establish financial accountability
* Improve budgeting accuracy
* Encourage optimization behaviors
* Support product profitability analysis
* Improve investment decisions
* Align cloud spending with business outcomes

---

# Chargeback Hierarchy

Cloud costs should be assigned through a structured ownership hierarchy.

```text
Cloud Provider
    │
Account / Subscription / Project
    │
Business Unit
    │
Product or Service
    │
Application
    │
Cost Center
```

Organizations may adjust the hierarchy based on operating model requirements.

---

# Chargeback Cost Categories

## Direct Costs

Direct costs are assigned directly to a consuming owner.

Examples:

* Compute services
* Databases
* Storage services
* AI services
* Dedicated Kubernetes clusters
* Application-specific networking

Direct costs should be charged to the consuming business owner.

---

## Shared Costs

Shared costs support multiple consumers.

Examples:

* Shared Kubernetes platforms
* Central networking
* Security services
* Monitoring platforms
* Identity services
* Shared data platforms

Shared costs should be allocated using approved allocation methodologies.

---

## Enterprise Costs

Enterprise costs support organization-wide capabilities.

Examples:

* FinOps tooling
* Governance platforms
* Enterprise support agreements
* Enterprise observability platforms

Organizations may choose to recover these costs through chargeback or retain them as centrally funded services.

---

# Chargeback Methods

## Consumption-Based Chargeback

Costs are assigned according to actual resource consumption.

Examples:

* CPU utilization
* Memory usage
* Storage consumption
* Network traffic
* GPU utilization
* API requests

This method should be preferred whenever reliable consumption data exists.

---

## Fixed Allocation Chargeback

Costs are distributed according to predefined allocation percentages.

Examples:

* Shared management services
* Governance platforms
* Enterprise support services

Allocation percentages should be reviewed periodically.

---

## Business Driver Chargeback

Costs are allocated using business metrics that correlate with resource consumption.

Examples:

* Active users
* Customer count
* Revenue contribution
* Transactions processed

This method may be used when technical consumption metrics are unavailable.

---

# Chargeback Calculation Requirements

Chargeback calculations should be:

* Documented
* Repeatable
* Auditable
* Consistent
* Transparent

Calculation methodologies should be approved through governance processes and communicated to affected stakeholders.

---

# Roles and Responsibilities

| Function         | Responsibility                       |
| ---------------- | ------------------------------------ |
| Finance          | Financial processing and reporting   |
| FinOps           | Chargeback methodology and reporting |
| Engineering      | Resource ownership validation        |
| Product Teams    | Cost review and accountability       |
| Business Leaders | Budget ownership                     |
| Leadership       | Policy approval and oversight        |

---

# Chargeback Process

## Step 1: Resource Ownership Validation

Validate ownership attributes and allocation mappings.

---

## Step 2: Cost Collection

Collect cloud billing and consumption data from approved sources.

---

## Step 3: Cost Allocation

Apply approved allocation methodologies to direct and shared costs.

---

## Step 4: Chargeback Calculation

Calculate chargeback amounts by business unit, product, application, or cost center.

---

## Step 5: Financial Review

Validate chargeback results with Finance and FinOps stakeholders.

---

## Step 6: Reporting and Distribution

Distribute chargeback reports to accountable stakeholders.

---

## Step 7: Governance Review

Review methodology effectiveness and address disputes or exceptions.

---

# Chargeback Reporting Requirements

Chargeback reports should include:

* Total cloud spend
* Direct costs
* Shared costs
* Enterprise costs
* Allocation methodology references
* Historical trends
* Budget comparisons
* Forecast comparisons
* Variance analysis

Reports should be available to business, finance, engineering, and executive stakeholders.

---

# Chargeback Dispute Process

Organizations should establish a formal dispute process.

Disputes should include:

* Ownership validation
* Allocation review
* Methodology verification
* Financial validation
* Governance review

All approved adjustments should be documented.

---

# Governance Requirements

Chargeback methodologies should be reviewed periodically.

Review activities should include:

* Allocation accuracy
* Financial alignment
* Business alignment
* Shared cost methodologies
* Emerging technologies
* AI workload allocation models
* Kubernetes platform allocation models

Changes should be approved through the FinOps governance process.

---

# Success Measures

An effective chargeback framework should result in:

* Improved financial accountability
* Reduced unallocated spend
* Better budgeting accuracy
* Improved forecasting accuracy
* Increased optimization ownership
* Greater business visibility
* Improved cost transparency

---

# Related Documents

* allocation-framework.md
* shared-cost-allocation.md
* showback-framework.md
* tagging-standards.md
* cost-accountability-model.md
* governance-framework.md
* finops-raci.md
* kpi-dictionary.md
