# Showback Framework

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the framework for providing visibility into cloud costs, consumption, and financial accountability through showback reporting.

The objective of showback is to increase cost awareness, improve decision-making, establish accountability, and prepare the organization for more advanced FinOps practices without requiring financial cost transfers.

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
* Corporate IT Workloads
* Enterprise Cloud Services

---

# Guiding Principles

## Visibility Before Accountability

Teams must have access to accurate and timely cost information before they can be expected to manage cloud spending effectively.

---

## Transparency Builds Trust

Showback reports should clearly communicate costs, consumption patterns, allocation methodologies, and ownership structures.

---

## Consistency Matters

Reporting methodologies should remain consistent to support trend analysis, forecasting, budgeting, and optimization activities.

---

## Business Context Is Essential

Cloud costs should be presented alongside ownership and business context to support informed decision-making.

---

## Showback Is Not Chargeback

Showback provides financial visibility and accountability without transferring costs between business units or cost centers.

---

## Shared Costs Must Be Visible

Consumers should understand both direct costs and allocated shared costs associated with the services they consume.

---

# Definition of Showback

Showback is the process of reporting cloud costs and consumption to accountable stakeholders without creating internal financial transactions.

The objective is to provide transparency into:

* Cloud spending
* Resource consumption
* Cost ownership
* Shared cost allocation
* Optimization opportunities
* Budget performance
* Forecast performance

---

# Showback Objectives

The showback model should enable organizations to:

* Increase cost awareness
* Improve ownership accountability
* Support budgeting activities
* Improve forecasting accuracy
* Encourage optimization behaviors
* Support governance processes
* Establish a foundation for chargeback

---

# Showback Hierarchy

Showback reporting should align with the organizational ownership structure.

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
Environment
    │
Resource Owner
```

Reporting structures should remain consistent across cloud providers whenever possible.

---

# Showback Cost Categories

## Direct Costs

Direct costs represent cloud services that can be assigned directly to a consuming owner.

Examples:

* Compute services
* Databases
* Storage services
* AI services
* Dedicated Kubernetes clusters

---

## Shared Costs

Shared costs support multiple consumers and require allocation methodologies.

Examples:

* Shared Kubernetes platforms
* Enterprise networking
* Security services
* Monitoring platforms
* Identity services

Shared cost allocations should be included in showback reports.

---

## Enterprise Costs

Enterprise costs support organization-wide cloud capabilities.

Examples:

* FinOps tooling
* Governance platforms
* Enterprise support contracts
* Shared observability services

Organizations should determine whether these costs are included in showback reporting.

---

# Showback Reporting Components

## Cost Visibility

Reports should provide visibility into:

* Monthly spend
* Historical trends
* Cost drivers
* Service-level spend
* Business unit spend
* Product spend
* Application spend

---

## Consumption Visibility

Where available, showback should include:

* Compute utilization
* Storage utilization
* Network consumption
* Kubernetes utilization
* GPU utilization
* AI consumption metrics

---

## Ownership Visibility

Reports should clearly identify:

* Business owner
* Product owner
* Application owner
* Platform owner
* Cost center owner

---

## Shared Cost Visibility

Reports should identify:

* Shared service costs
* Allocation methodologies
* Consumer allocations
* Platform ownership

---

# Showback Audience

| Stakeholder       | Purpose                        |
| ----------------- | ------------------------------ |
| Executives        | Strategic visibility           |
| Finance           | Budget and forecast management |
| FinOps            | Governance and optimization    |
| Product Teams     | Cost accountability            |
| Engineering Teams | Consumption management         |
| Platform Teams    | Shared service management      |

---

# Showback Reporting Cadence

| Report Type          | Frequency |
| -------------------- | --------- |
| Cost Reports         | Monthly   |
| Optimization Reports | Monthly   |
| Forecast Reviews     | Monthly   |
| Executive Reports    | Quarterly |
| Budget Reviews       | Quarterly |
| Strategic Reviews    | Annual    |

Organizations may adopt more frequent reporting where operationally appropriate.

---

# Showback Metrics

Common showback metrics include:

* Total cloud spend
* Cost by business unit
* Cost by application
* Cost by environment
* Shared cost allocation
* Unit cost metrics
* Forecast variance
* Budget variance
* Optimization opportunity value
* Unallocated spend

Metric definitions should align with the KPI Dictionary.

---

# Showback Process

## Step 1: Cost Collection

Collect cloud billing and consumption data from approved sources.

---

## Step 2: Ownership Validation

Validate ownership metadata and allocation mappings.

---

## Step 3: Shared Cost Allocation

Apply approved allocation methodologies to shared services.

---

## Step 4: Report Generation

Generate showback reports using approved reporting standards.

---

## Step 5: Stakeholder Review

Review results with business, finance, and technology stakeholders.

---

## Step 6: Optimization Identification

Identify opportunities to improve efficiency and reduce waste.

---

## Step 7: Governance Review

Review reporting effectiveness and allocation accuracy.

---

# Roles and Responsibilities

| Function       | Responsibility                    |
| -------------- | --------------------------------- |
| FinOps         | Showback reporting and governance |
| Finance        | Financial alignment               |
| Engineering    | Resource ownership validation     |
| Product Teams  | Cost review and accountability    |
| Platform Teams | Shared service reporting          |
| Leadership     | Strategic oversight               |

---

# Governance Requirements

Showback methodologies should be:

* Documented
* Consistent
* Auditable
* Repeatable
* Transparent

Changes to reporting structures, ownership models, or allocation methodologies should be reviewed through established governance processes.

---

# Transition to Chargeback

Organizations considering chargeback should demonstrate:

* Stable ownership models
* Reliable allocation methodologies
* Consistent reporting processes
* Stakeholder acceptance
* Governance maturity

Showback is commonly used as an intermediate step before implementing formal chargeback models.

---

# Success Measures

An effective showback framework should result in:

* Increased cost visibility
* Improved accountability
* Better budgeting accuracy
* Improved forecasting quality
* Greater optimization participation
* Reduced unallocated spend
* Improved business alignment

---

# Related Documents

* allocation-framework.md
* shared-cost-allocation.md
* chargeback-framework.md
* tagging-standards.md
* cost-accountability-model.md
* governance-framework.md
* finops-raci.md
* kpi-dictionary.md
