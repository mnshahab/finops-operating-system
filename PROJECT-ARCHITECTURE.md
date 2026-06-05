# Project Architecture

## Purpose

This document defines the structure, standards, and relationships used throughout the FinOps OS repository. It ensures consistency, scalability, and maintainability across all artifacts.

---

## Repository Structure

```text
/
├── 01-strategy
├── 02-governance
├── 03-cost-allocation
├── 04-budgeting-forecasting
├── 05-kpis
├── 06-aws
├── 07-azure
├── 08-gcp
├── 09-kubernetes
├── 10-ai-finops
├── 11-templates
├── 12-dashboard-library
├── 13-optimization-playbooks
├── PROJECT-VISION.md
├── PROJECT-ARCHITECTURE.md
├── PROJECT-BACKLOG.md
├── STANDARDS.md
└── DECISIONS.md
```

---

## Folder Descriptions

### 01-Strategy

Contains foundational strategy and planning documents.

Artifacts:

* FinOps Charter
* Operating Model
* FinOps Vision
* FinOps Roadmap
* Organizational Structure

### 02-Governance

Defines governance, accountability, policies, and controls.

Artifacts:

* Governance Framework
* RACI Matrix
* Policy Library
* Standards
* Compliance Controls

### 03-Cost-Allocation

Defines allocation methodologies and ownership models.

Artifacts:

* Allocation Strategy
* Showback Model
* Chargeback Model
* Tagging Standards
* Cost Ownership Matrix

### 04-Budgeting-Forecasting

Supports financial planning and forecasting activities.

Artifacts:

* Budget Templates
* Forecast Models
* Variance Analysis
* Planning Calendar

### 05-KPIs

Central repository for metrics and measurement standards.

Artifacts:

* KPI Dictionary
* KPI Catalog
* Unit Economics Library
* Executive Metrics

### 06-AWS

AWS-specific governance, reporting, and optimization content.

Artifacts:

* AWS Standards
* AWS Dashboards
* AWS Optimization Guides
* AWS Governance Controls

### 07-Azure

Azure-specific governance, reporting, and optimization content.

Artifacts:

* Azure Standards
* Azure Dashboards
* Azure Optimization Guides
* Azure Governance Controls

### 08-GCP

Google Cloud-specific governance, reporting, and optimization content.

Artifacts:

* GCP Standards
* GCP Dashboards
* GCP Optimization Guides
* GCP Governance Controls

### 09-Kubernetes

Kubernetes and container cost management practices.

Artifacts:

* Namespace Standards
* Cost Allocation Models
* Optimization Frameworks
* Chargeback Guidance

### 10-AI-FinOps

Cost governance and optimization for AI workloads.

Artifacts:

* AI Governance Framework
* AI Cost Models
* GPU Optimization Guides
* AI KPI Catalog

### 11-Templates

Reusable templates and standard forms.

Artifacts:

* Business Cases
* Intake Forms
* Review Templates
* Reporting Templates

### 12-Dashboard-Library

Central catalog of reporting assets.

Artifacts:

* Executive Dashboards
* Operational Dashboards
* KPI Dashboards
* Unit Economics Dashboards

### 13-Optimization-Playbooks

Step-by-step optimization procedures.

Artifacts:

* AWS Playbook
* Azure Playbook
* GCP Playbook
* Kubernetes Playbook
* AI Optimization Playbook

---

## Relationships

The repository follows a layered architecture.

```text
Strategy
    ↓
Governance
    ↓
Cost Allocation
    ↓
Budgeting & Forecasting
    ↓
KPIs & Reporting
    ↓
Cloud Platforms
    ↓
Optimization Playbooks
```

Dependencies:

* Governance supports all domains.
* Cost Allocation feeds Budgeting and Forecasting.
* Budgeting feeds KPI reporting.
* KPI reporting feeds Executive Dashboards.
* Cloud-specific standards inherit Governance requirements.
* Optimization Playbooks support all cloud domains.

---

## Naming Standards

### Files

Use lowercase letters and hyphens.

Examples:

* finops-charter.md
* operating-model.md
* governance-framework.md
* kpi-dictionary.md

### Folders

Use numeric prefixes to maintain navigation order.

Examples:

* 01-strategy
* 02-governance
* 03-cost-allocation

### Templates

Use the suffix "-template".

Examples:

* business-case-template.xlsx
* forecast-template.xlsx

### Dashboards

Use cloud and audience naming.

Examples:

* aws-executive-dashboard
* azure-cost-optimization-dashboard
* ai-finops-dashboard

---

## Required Artifacts

Every major domain should contain:

* README.md
* Process Documentation
* Governance Guidance
* KPI Definitions
* Templates
* Example Reports
* Optimization Guidance

---

## Design Principles

* Cloud agnostic where possible
* Native tooling first
* FinOps Foundation aligned
* Automation preferred over manual processes
* Executive visibility and accountability
* Data-driven decision making
* Continuous optimization
* Scalable multi-cloud support

---

## Versioning

Major updates should be documented in DECISIONS.md.

All artifacts should include:

* Author
* Version
* Last Updated Date
* Review Cycle
* Owner
