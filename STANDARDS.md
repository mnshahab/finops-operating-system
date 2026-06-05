# FinOps OS Standards

## Purpose

This document defines the standards, conventions, and quality requirements for all content published within the FinOps OS repository.

The objective is to ensure consistency, maintainability, and professional quality across all artifacts.

---

# Core Principles

All content within FinOps OS should be:

* Practical
* Vendor neutral where possible
* Business focused
* Engineering friendly
* Actionable
* Measurable
* Repeatable
* Scalable

---

# Repository Standards

## Folder Naming

Use numeric prefixes to control navigation order.

Example:

```text
01-strategy
02-governance
03-cost-allocation
04-budgeting-forecasting
05-kpis
06-aws
07-azure
08-gcp
09-kubernetes
10-ai-finops
11-templates
12-dashboard-library
13-optimization-playbooks
```

---

## File Naming

Use lowercase characters.

Use hyphens instead of spaces.

Examples:

```text
finops-charter.md
operating-model.md
governance-framework.md
kpi-dictionary.md
aws-playbook.md
```

Do not use:

```text
FinOps Charter.docx
Operating_Model.md
My File.md
```

---

# Markdown Standards

## Heading Structure

Every document should follow a consistent hierarchy.

```markdown
# Document Title

## Purpose

## Scope

## Objectives

## Roles and Responsibilities

## Process

## KPIs

## Deliverables

## Review Cycle
```

---

## Lists

Use bullet points for readability.

Example:

```markdown
- Improve cost visibility
- Increase accountability
- Reduce waste
- Optimize commitments
```

---

## Tables

Use tables for structured information.

Example:

| KPI               | Description              |
| ----------------- | ------------------------ |
| Coverage          | Savings Plan coverage    |
| Utilization       | Resource utilization     |
| Forecast Accuracy | Budget forecast variance |

---

# Required Metadata

Every major document should begin with:

```markdown
# Document Name

| Attribute | Value |
|-----------|---------|
| Owner | FinOps Team |
| Version | 1.0 |
| Status | Draft |
| Last Updated | YYYY-MM-DD |
| Review Cycle | Quarterly |
```

---

# Standard Document Template

Every governance, process, framework, or strategy document should contain the following sections.

## 1. Purpose

Explain why the document exists.

---

## 2. Scope

Define what is included.

Define what is excluded.

---

## 3. Objectives

Describe expected outcomes.

Example:

* Improve accountability
* Improve forecasting accuracy
* Reduce cloud waste

---

## 4. Roles and Responsibilities

Include a RACI matrix where appropriate.

Example:

| Activity     | FinOps | Engineering | Finance |
| ------------ | ------ | ----------- | ------- |
| Budgeting    | A      | C           | R       |
| Optimization | R      | A           | I       |

---

## 5. Process

Document step-by-step activities.

Example:

1. Collect cost data.
2. Analyze trends.
3. Identify opportunities.
4. Assign actions.
5. Measure results.

---

## 6. KPIs

Include measurable outcomes.

Example:

* Forecast Accuracy
* Commitment Coverage
* Commitment Utilization
* Unit Cost
* Cost per Customer

---

## 7. Deliverables

Define expected outputs.

Example:

* Monthly Report
* Executive Dashboard
* Optimization Backlog
* Forecast Package

---

## 8. Review Cycle

Document review frequency.

Example:

* Monthly
* Quarterly
* Semi-Annual
* Annual

---

# Cloud Standards

## AWS

All AWS content should reference:

* AWS Organizations
* Cost Explorer
* CUR 2.0
* Savings Plans
* Reserved Instances
* Compute Optimizer
* Trusted Advisor

---

## Azure

All Azure content should reference:

* Management Groups
* Subscriptions
* Azure Cost Management
* Reservations
* Savings Plans
* Azure Advisor

---

## GCP

All GCP content should reference:

* Billing Accounts
* Projects
* BigQuery Billing Export
* Committed Use Discounts
* Recommender

---

# KPI Standards

Every KPI must include:

| Field            | Requirement |
| ---------------- | ----------- |
| KPI Name         | Required    |
| Definition       | Required    |
| Formula          | Required    |
| Data Source      | Required    |
| Owner            | Required    |
| Review Frequency | Required    |
| Target           | Required    |

---

# Dashboard Standards

Every dashboard should contain:

## Executive View

* Spend
* Budget
* Forecast
* Savings
* Risks

## Operational View

* Resource Utilization
* Optimization Opportunities
* Tag Compliance
* Commitment Coverage

---

# Optimization Standards

Every optimization recommendation must include:

| Field             | Requirement |
| ----------------- | ----------- |
| Recommendation    | Required    |
| Business Impact   | Required    |
| Estimated Savings | Required    |
| Effort Level      | Required    |
| Risk Level        | Required    |
| Owner             | Required    |

---

# AI FinOps Standards

AI-related content should include:

* GPU Utilization
* Training Cost Tracking
* Inference Cost Tracking
* Token Consumption
* Model Cost Attribution
* Unit Economics
* Cost per Inference
* Cost per Model

---

# Kubernetes FinOps Standards

Kubernetes content should include:

* Namespace Allocation
* Cluster Allocation
* Node Utilization
* Pod Utilization
* Rightsizing
* Shared Cost Allocation

---

# Quality Checklist

Before publishing any artifact verify:

* Structure follows repository standards
* Metadata is present
* KPIs are measurable
* Ownership is defined
* Content is technically accurate
* Examples are included
* Review cycle is documented
* Formatting is consistent

---

# Version Control

Major updates should be recorded in DECISIONS.md.

All contributors should update version numbers when significant changes are made.

---

## Document Ownership

Owner: FinOps OS Community

Version: 1.0

Review Cycle: Quarterly
