# FinOps Organizational Structure

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD |
| Review Cycle | Annual      |

---

# Purpose

This document defines the organizational structure required to establish, operate, and mature a FinOps practice.

The objective is to create clear accountability for cloud financial management while enabling collaboration between Finance, Engineering, Product, Platform, Security, Procurement, and Executive leadership.

This structure aligns with FinOps Foundation principles of shared responsibility, business value realization, and continuous optimization.

---

# Scope

This document applies to:

* Public cloud environments
* Multi-cloud environments
* Kubernetes platforms
* AI and machine learning workloads
* Shared services environments
* Product and application teams
* Corporate IT workloads

---

# Organizational Principles

The FinOps operating model should be built upon the following principles:

## Shared Accountability

Cloud cost management is a shared responsibility across business, technology, and finance stakeholders.

No single team owns cloud spend independently.

---

## Federated Execution

Optimization activities should be performed by the teams responsible for consuming cloud resources.

The FinOps function provides governance, visibility, guidance, and reporting.

---

## Centralized Governance

Policies, standards, KPIs, reporting, and financial controls should be centrally governed.

---

## Business Alignment

Cloud spending decisions should be evaluated against business outcomes, customer value, and organizational objectives.

---

## Continuous Improvement

FinOps maturity should evolve through ongoing measurement, optimization, and stakeholder engagement.

---

# FinOps Organizational Model

The recommended model is a Centralized FinOps Team with Federated Stakeholder Ownership.

```text
Executive Sponsor
        │
        ▼
FinOps Steering Committee
        │
        ▼
FinOps Team
        │
 ┌──────┼──────┐
 ▼      ▼      ▼
Finance Engineering Product
        │
        ▼
Application & Platform Teams
```

---

# Key Roles

## Executive Sponsor

The Executive Sponsor provides strategic direction and organizational support for the FinOps practice.

Typical responsibilities include:

* Establishing organizational priorities
* Removing operational barriers
* Supporting governance decisions
* Reviewing business outcomes
* Championing FinOps adoption

Common executive sponsors include:

* CIO
* CTO
* CFO
* VP Technology
* VP Engineering

---

## FinOps Steering Committee

The FinOps Steering Committee provides cross-functional governance and decision-making.

Typical participants include:

* FinOps Leadership
* Finance Leadership
* Engineering Leadership
* Platform Leadership
* Product Leadership
* Procurement
* Security Representatives

Responsibilities include:

* Reviewing KPIs
* Approving policies
* Reviewing forecasts
* Prioritizing optimization initiatives
* Managing organizational risks

---

## FinOps Team

The FinOps Team serves as the central coordinating function.

Responsibilities include:

* Cost visibility
* Reporting and analytics
* KPI management
* Governance administration
* Forecasting support
* Cost allocation management
* Optimization program management
* Stakeholder enablement

The FinOps Team does not directly own application resources.

Optimization ownership remains with consuming teams.

---

## Finance

Finance partners with FinOps to ensure financial accountability and alignment.

Responsibilities include:

* Budget management
* Forecast validation
* Financial reporting
* Variance analysis
* Chargeback governance
* Financial planning support

---

## Engineering

Engineering teams are accountable for the efficient consumption of cloud resources.

Responsibilities include:

* Workload optimization
* Resource lifecycle management
* Rightsizing activities
* Cost-aware architecture decisions
* Remediation of identified opportunities

---

## Platform Teams

Platform teams manage shared infrastructure services.

Examples include:

* Cloud Platforms
* Kubernetes Platforms
* Data Platforms
* AI Platforms
* Shared Services

Responsibilities include:

* Shared cost management
* Platform efficiency
* Infrastructure standards
* Commitment management support

---

## Product Owners

Product teams provide business context and value measurement.

Responsibilities include:

* Business prioritization
* Unit economics participation
* Product profitability analysis
* Cloud consumption planning

---

## Procurement and Vendor Management

Responsibilities include:

* Contract negotiations
* Commitment management support
* Vendor relationship management
* Licensing reviews

---

# RACI Overview

| Activity            | FinOps | Finance | Engineering | Product | Executive |
| ------------------- | ------ | ------- | ----------- | ------- | --------- |
| Cost Visibility     | R      | C       | C           | I       | I         |
| Budgeting           | C      | A       | C           | C       | I         |
| Forecasting         | R      | A       | C           | C       | I         |
| Cost Allocation     | A      | C       | C           | I       | I         |
| Optimization        | C      | I       | A           | I       | I         |
| Governance          | R      | C       | C           | C       | A         |
| KPI Management      | A      | C       | C           | C       | I         |
| Executive Reporting | R      | C       | I           | I       | A         |

**R = Responsible**
**A = Accountable**
**C = Consulted**
**I = Informed**

---

# FinOps Council

Organizations should establish a recurring FinOps Council or Review Board.

Recommended agenda:

* KPI review
* Forecast review
* Budget variance review
* Optimization progress
* Commitment utilization review
* Risks and escalations
* New initiatives and workload planning

---

# Maturity Evolution

As FinOps maturity increases, responsibilities expand beyond cost visibility.

| Maturity Stage | Focus                                                   |
| -------------- | ------------------------------------------------------- |
| Crawl          | Visibility, allocation, accountability                  |
| Walk           | Forecasting, governance, optimization                   |
| Run            | Unit economics, automation, business value optimization |

---

# Success Measures

An effective organizational structure should enable:

* Clear accountability for cloud spend
* Accurate cost allocation
* Consistent forecasting processes
* Cross-functional decision making
* Sustainable optimization practices
* Business value measurement
* Continuous FinOps maturity improvement

---

# Related Documents

* finops-charter.md
* operating-model.md
* roadmap.md
* governance-framework.md
* finops-raci.md
