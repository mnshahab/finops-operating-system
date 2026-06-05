# Showback and Chargeback Framework

## Purpose

This framework establishes a standardized approach for allocating, reporting, and recovering technology costs across business units, applications, products, and teams.

The goal is to create transparency, accountability, and informed decision-making while ensuring technology investments are aligned with business objectives.

---

# Overview

Organizations cannot effectively manage technology costs without ownership.

Showback and chargeback provide visibility into who consumes technology resources and how those costs impact the business.

## Showback

Showback reports technology costs to consumers without financial transfer.

Business units receive visibility into their consumption and spending but are not directly charged.

### Benefits

* Builds cost awareness
* Encourages accountability
* Improves transparency
* Simplifies adoption

---

## Chargeback

Chargeback allocates technology costs directly to consuming business units, departments, products, or cost centers.

### Benefits

* Creates financial accountability
* Improves budgeting accuracy
* Encourages cost optimization
* Aligns consumption with business value

---

# Framework Objectives

## Visibility

Provide clear visibility into technology consumption and spend.

### Success Measures

* Allocation coverage above 95%
* Consistent reporting
* Business unit ownership

---

## Accountability

Assign ownership for technology consumption.

### Success Measures

* Named cost owners
* Product ownership
* Business accountability

---

## Financial Management

Support budgeting, forecasting, and planning activities.

### Success Measures

* Improved forecast accuracy
* Reduced budget variance
* Better investment decisions

---

# Allocation Hierarchy

Technology costs should be allocated using the following priority order.

| Priority | Allocation Method          |
| -------- | -------------------------- |
| 1        | Direct Resource Tagging    |
| 2        | Application Ownership      |
| 3        | Product Ownership          |
| 4        | Business Unit Mapping      |
| 5        | Shared Service Allocation  |
| 6        | Enterprise Allocation Pool |

---

# Cost Categories

## Direct Costs

Costs directly attributable to a team, application, or business unit.

Examples:

* Compute
* Storage
* Databases
* AI Services
* Dedicated Kubernetes Clusters

Allocation Method:

Direct assignment.

---

## Shared Costs

Costs supporting multiple teams or business units.

Examples:

* Networking
* Security Platforms
* Shared Kubernetes Platforms
* Monitoring Solutions
* Shared Data Platforms

Allocation Method:

Consumption-based allocation whenever possible.

---

## Enterprise Costs

Costs benefiting the entire organization.

Examples:

* Enterprise Agreements
* Shared Licenses
* Central Governance Platforms

Allocation Method:

Defined corporate allocation methodology.

---

# Required Metadata Standards

Every workload should include the following metadata.

| Field         | Required    |
| ------------- | ----------- |
| Application   | Yes         |
| Business Unit | Yes         |
| Cost Center   | Yes         |
| Owner         | Yes         |
| Environment   | Yes         |
| Product       | Recommended |
| Project       | Recommended |

---

# Recommended Allocation Models

## Direct Allocation

Used when ownership is known.

Formula:

```text
Resource Cost = Assigned Directly To Owner
```

Preferred approach.

---

## Consumption-Based Allocation

Used for shared services.

Formula:

```text
Business Unit Usage ÷ Total Usage × Shared Cost
```

Examples:

* Storage consumption
* CPU usage
* Memory usage
* Network traffic
* API requests

---

## Equal Distribution

Used when consumption metrics are unavailable.

Formula:

```text
Shared Cost ÷ Number Of Participants
```

Use only as a temporary solution.

---

## Revenue-Based Allocation

Used when business value is closely linked to revenue generation.

Formula:

```text
Business Unit Revenue ÷ Total Revenue × Shared Cost
```

---

# Shared Service Allocation Examples

## Shared Kubernetes Platform

Possible allocation drivers:

* CPU requests
* CPU usage
* Memory requests
* Memory usage
* Namespace ownership

---

## Shared Data Platform

Possible allocation drivers:

* Storage consumed
* Query volume
* Processing hours
* Data transferred

---

## Shared AI Platform

Possible allocation drivers:

* Token consumption
* Inference requests
* GPU usage
* Model usage

---

# Showback Reporting

Recommended reporting dimensions:

* Business Unit
* Product
* Application
* Environment
* Cloud Provider
* Team
* Cost Center

### Monthly Report Content

* Current Spend
* Previous Spend
* Budget
* Forecast
* Variance
* Top Cost Drivers
* Optimization Opportunities

---

# Chargeback Reporting

Chargeback reports should include:

* Allocated Costs
* Shared Service Costs
* Enterprise Allocations
* Total Charges
* Cost Trends
* Forecasted Charges

---

# Allocation Coverage KPI

## Definition

Percentage of spend assigned to an owner.

### Formula

```text
Allocated Spend ÷ Total Spend × 100
```

### Target

```text
95%+
```

---

# Governance Process

## Monthly

* Review allocation coverage
* Validate ownership
* Review shared service allocations
* Review new workloads

---

## Quarterly

* Review allocation methodology
* Review chargeback accuracy
* Review business alignment
* Update allocation drivers

---

# Common Challenges

## Missing Ownership

Solution:

Enforce ownership requirements during provisioning.

---

## Shared Resource Complexity

Solution:

Use measurable consumption metrics whenever possible.

---

## Inconsistent Metadata

Solution:

Implement governance policies and validation controls.

---

## Allocation Disputes

Solution:

Document allocation rules and review them regularly with stakeholders.

---

# Maturity Model

| Level | Description                                                  |
| ----- | ------------------------------------------------------------ |
| Crawl | Basic showback with limited ownership                        |
| Walk  | Standardized showback with shared cost allocation            |
| Run   | Full chargeback with business accountability and forecasting |

---

# Success Criteria

The framework is successful when:

* Allocation coverage exceeds 95%
* Business units understand their costs
* Forecast accuracy improves
* Shared costs are transparent
* Technology spending supports business objectives

---

# Document Information

| Item             | Value                             |
| ---------------- | --------------------------------- |
| Document         | Showback and Chargeback Framework |
| Version          | 1.0                               |
| Status           | Active                            |
| Owner            | FinOps Team                       |
| Review Frequency | Quarterly                         |
| Last Updated     | 2026                              |
