# Cost Allocation Framework

| Attribute | Value |
|------------|---------|
| Owner | FinOps Team |
| Version | 1.0 |
| Status | Active |
| Last Updated | YYYY-MM-DD |
| Review Cycle | Annual |

---

# Purpose

This document establishes the framework for allocating cloud costs across business units, products, applications, environments, and shared services.

The objective is to provide a consistent and transparent approach for assigning cloud costs to accountable owners, improving cost visibility, supporting financial decision-making, and enabling showback and chargeback practices.

This framework aligns with FinOps Foundation principles of accountability, collaboration, visibility, and business value realization.

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
* SaaS and Platform Services

---

# Guiding Principles

## Accountability Through Allocation

Cloud costs should be allocated to the teams, products, or business units responsible for consuming cloud resources.

---

## Visibility Enables Better Decisions

Allocation should provide stakeholders with clear visibility into the cost of the services they consume.

---

## Consistency Matters

Allocation methodologies should remain consistent over time to support trend analysis, budgeting, forecasting, and financial reporting.

---

## Accuracy Over Complexity

Allocation methods should balance precision with operational simplicity.

Organizations should avoid overly complex allocation models that are difficult to understand or maintain.

---

## Shared Costs Require Transparency

Shared platform and infrastructure costs should be allocated using documented and approved methodologies.

---

## Allocation Supports Business Value

The purpose of allocation is to improve decision-making and accountability, not simply to redistribute costs.

---

# Cost Allocation Hierarchy

Cloud costs should be allocated using a structured ownership hierarchy.

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

Organizations may adapt the hierarchy based on operating model requirements while maintaining consistency across reporting processes.

---

# Cost Categories

## Direct Costs

Direct costs are associated with a single consuming entity and can be assigned without additional calculations.

Examples:

* Dedicated compute resources
* Application databases
* Dedicated storage services
* AI workloads
* Dedicated Kubernetes clusters

Direct costs should be assigned to the responsible owner whenever possible.

---

## Shared Costs

Shared costs support multiple consumers and require allocation methodologies.

Examples:

* Shared Kubernetes platforms
* Central networking
* Security platforms
* Monitoring services
* Identity services
* Shared data platforms

Shared cost allocation methods should be documented and reviewed periodically.

---

## Enterprise Costs

Enterprise costs support organization-wide capabilities.

Examples:

* FinOps tooling
* Governance platforms
* Enterprise support contracts
* Shared observability platforms

Organizations may choose to allocate these costs or retain them as centrally managed expenses.

---

# Allocation Methods

## Consumption-Based Allocation

Costs are allocated according to measured resource consumption.

Examples:

* CPU usage
* Memory consumption
* Storage utilization
* Network traffic
* GPU utilization
* API requests

This method should be preferred when reliable consumption data exists.

---

## Fixed Percentage Allocation

Costs are distributed according to predefined allocation percentages.

Examples:

* Shared management services
* Enterprise support costs
* Governance tooling

Percentages should be reviewed regularly.

---

## Business Driver Allocation

Costs are allocated using business metrics that correlate with resource usage.

Examples:

* Active users
* Transactions
* Revenue contribution
* Customer count
* Application instances

This method may be appropriate when technical consumption metrics are unavailable.

---

## Equal Distribution Allocation

Costs are distributed evenly among participating entities.

This method should only be used when more accurate allocation methods are not practical.

---

# Allocation Ownership Model

| Function | Responsibility |
|------------|---------------------------|
| FinOps | Allocation standards and reporting |
| Finance | Financial alignment and reporting |
| Engineering | Resource ownership validation |
| Product Teams | Business ownership validation |
| Platform Teams | Shared service allocation support |
| Leadership | Allocation policy approval |

---

# Allocation Requirements

Every cloud resource should be associated with the following ownership attributes where technically feasible.

| Attribute | Description |
|------------|--------------------------------|
| Business Unit | Organizational owner |
| Application | Consuming application |
| Product | Business product or service |
| Environment | Production, Development, Test |
| Cost Center | Financial ownership |
| Resource Owner | Responsible team |

Allocation requirements should be supported through tagging, metadata, account structures, or alternative ownership mechanisms.

---

# Unallocated Cost Management

Unallocated costs should be actively monitored and reviewed.

Common causes include:

* Missing ownership metadata
* Incomplete tagging
* Shared resources without allocation rules
* Newly deployed resources
* Unsupported services

Unallocated costs should be treated as governance exceptions and reviewed through established FinOps processes.

---

# Allocation Review Process

Allocation methodologies should be reviewed periodically.

Review activities should include:

* Allocation accuracy validation
* Shared cost methodology review
* Ownership verification
* Reporting effectiveness assessment
* Business alignment review
* Emerging service evaluation

Changes should be documented and approved through the FinOps governance process.

---

# Success Measures

An effective allocation framework should result in:

* Increased cost visibility
* Improved ownership clarity
* Reduced unallocated spend
* Better budgeting accuracy
* Improved forecasting quality
* Greater optimization accountability
* Improved business alignment

---

# Related Documents

* cost-accountability-model.md
* tagging-standards.md
* shared-cost-allocation.md
* showback-framework.md
* chargeback-framework.md
* governance-framework.md
* finops-raci.md
