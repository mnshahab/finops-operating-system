# AWS Organizations Strategy

| Attribute    | Value                               |
| ------------ | ----------------------------------- |
| Owner        | Cloud Platform Team and FinOps Team |
| Version      | 1.0                                 |
| Status       | Active                              |
| Last Updated | YYYY-MM-DD                          |
| Review Cycle | Annual                              |

---

# Purpose

This document establishes the strategy for designing, governing, and operating AWS Organizations within the enterprise.

The objective is to create a scalable, secure, and financially accountable AWS operating model that supports business growth, cloud governance, financial management, workload isolation, and operational efficiency.

AWS Organizations serves as the foundational structure upon which allocation, governance, security, reporting, budgeting, forecasting, and optimization capabilities are built.

---

# Scope

This strategy applies to:

* AWS Organizations
* Organizational Units (OUs)
* AWS Accounts
* Consolidated Billing
* Shared Services
* Platform Services
* Production Environments
* Non-Production Environments
* Multi-Business Unit Environments
* Multi-Account AWS Deployments

---

# Guiding Principles

## Accounts Are Governance Boundaries

AWS accounts should be used as primary governance, security, operational, and financial boundaries.

---

## Ownership Must Be Clear

Every AWS account should have a designated business owner and technical owner.

---

## Standardization Enables Scale

Organizational structures should remain consistent across business units and workloads.

---

## Financial Accountability Starts With Structure

AWS Organizations should support accurate cost allocation, showback, chargeback, forecasting, and reporting.

---

## Shared Services Should Be Intentional

Shared services should be centrally managed and allocated through defined cost allocation methodologies.

---

# AWS Organizations Objectives

The AWS Organizations strategy should enable organizations to:

* Improve financial accountability
* Support cost allocation
* Improve security governance
* Improve operational consistency
* Support workload isolation
* Simplify reporting
* Improve scalability
* Enable multi-account management

---

# AWS Organizations Operating Model

```text
AWS Organization
        │
        ▼
Organizational Units
        │
        ▼
AWS Accounts
        │
        ▼
Applications and Workloads
```

The AWS Organization should align with business ownership and governance requirements.

---

# Organizational Unit Strategy

Organizational Units (OUs) should group accounts based on governance, ownership, and operational requirements.

Recommended top-level structure:

```text
Root
│
├── Infrastructure
├── Shared Services
├── Production
├── NonProduction
├── Sandbox
├── Security
└── Suspended
```

Organizations may adapt structures based on business requirements.

---

# Infrastructure OU

Purpose:

Provide centralized infrastructure services.

Examples:

* Networking
* DNS
* Identity Services
* Connectivity Services

Characteristics:

* Centrally managed
* Restricted access
* Shared service support

---

# Shared Services OU

Purpose:

Host services consumed across multiple business units.

Examples:

* Monitoring Platforms
* Logging Platforms
* FinOps Platforms
* CI/CD Platforms
* Container Platforms

Characteristics:

* Shared ownership model
* Allocation required
* Centralized governance

---

# Production OU

Purpose:

Host customer-facing and business-critical production workloads.

Characteristics:

* Highest governance requirements
* Budget ownership required
* Enhanced monitoring
* Commitment planning participation

---

# NonProduction OU

Purpose:

Host development, testing, QA, and staging environments.

Characteristics:

* Cost optimization focus
* Scheduling controls
* Lifecycle governance

---

# Sandbox OU

Purpose:

Support experimentation and innovation.

Characteristics:

* Spending controls
* Automated expiration policies
* Limited lifecycle expectations

---

# Security OU

Purpose:

Host security and compliance services.

Examples:

* Audit Accounts
* Logging Accounts
* Security Tooling

Characteristics:

* Restricted access
* Enhanced governance
* Enterprise visibility

---

# Suspended OU

Purpose:

Retain inactive accounts while preserving historical records.

Characteristics:

* Restricted access
* Minimal activity
* Governance oversight

---

# AWS Account Strategy

AWS accounts should be created to support governance, accountability, and operational requirements.

Accounts should not be created solely for technical convenience.

---

# Recommended Account Types

## Shared Services Accounts

Examples:

* Networking
* Logging
* Monitoring
* Platform Services

---

## Platform Accounts

Examples:

* Kubernetes Platforms
* Data Platforms
* AI Platforms

---

## Application Accounts

Examples:

* Product Applications
* Customer Services
* Internal Applications

---

## Security Accounts

Examples:

* Audit
* Logging
* Security Operations

---

## Sandbox Accounts

Examples:

* Innovation
* Testing
* Proof of Concepts

---

# Account Ownership Model

Every AWS account should have:

| Ownership Type  | Requirement |
| --------------- | ----------- |
| Business Owner  | Required    |
| Technical Owner | Required    |
| Cost Center     | Required    |
| Business Unit   | Required    |
| Support Team    | Required    |

Ownership information should be maintained centrally.

---

# Financial Management Strategy

AWS Organizations should support:

* Consolidated billing
* Cost allocation
* Showback
* Chargeback
* Budgeting
* Forecasting
* Commitment management

Financial structures should align with organizational accountability models.

---

# Consolidated Billing Strategy

Consolidated billing should be used to:

* Aggregate AWS spend
* Improve visibility
* Enable commitment sharing
* Simplify reporting

Benefits include:

* Centralized billing management
* Savings Plan sharing
* Reserved Instance sharing
* Enterprise reporting

---

# Shared Service Cost Allocation

Shared service costs should be allocated using approved allocation methodologies.

Examples:

* Equal distribution
* Consumption-based allocation
* Resource-based allocation
* Business unit allocation

Allocation methodologies should be documented and reviewed periodically.

---

# Tagging and Metadata Strategy

AWS Organizations should support standardized tagging practices.

Required ownership metadata should include:

* BusinessUnit
* CostCenter
* Application
* Environment
* Owner

Tagging standards should align with enterprise allocation frameworks.

---

# Budget Strategy

Budgets should exist at multiple levels.

Examples:

* Organization budgets
* Business unit budgets
* Account budgets
* Product budgets

Budget ownership should align with financial accountability structures.

---

# Commitment Strategy

AWS Organizations should maximize enterprise commitment benefits.

Focus areas include:

* Savings Plans
* Reserved Instances
* Commitment sharing
* Coverage optimization
* Utilization optimization

Commitments should be managed centrally through the FinOps operating model.

---

# Governance Controls

AWS Organizations should leverage:

## Service Control Policies (SCPs)

Purpose:

Prevent non-compliant activities.

Examples:

* Region restrictions
* Service restrictions
* Cost control guardrails

---

## Tag Policies

Purpose:

Standardize resource metadata.

Examples:

* Required tags
* Standardized values
* Ownership enforcement

---

## AWS Budgets

Purpose:

Financial monitoring and alerts.

Examples:

* Account budgets
* Product budgets
* Business unit budgets

---

# AWS Organizations KPIs

Recommended KPIs include:

* Allocation Coverage
* Resource Ownership Coverage
* Tag Compliance Rate
* Budget Variance
* Forecast Accuracy
* Commitment Utilization
* Commitment Coverage
* Shared Service Allocation Accuracy

Definitions should align with the KPI Dictionary.

---

# Roles and Responsibilities

| Function            | Responsibility                   |
| ------------------- | -------------------------------- |
| Cloud Platform Team | AWS Organizations management     |
| FinOps Team         | Financial governance             |
| Finance             | Budget and forecasting oversight |
| Engineering Teams   | Account ownership                |
| Security Teams      | Governance controls              |
| Product Teams       | Business accountability          |
| Leadership          | Strategic oversight              |

---

# Reporting Requirements

AWS Organizations reporting should provide visibility into:

* Account spend
* OU spend
* Shared services
* Allocation performance
* Budget performance
* Forecast performance
* Commitment performance
* Governance compliance

Reports should support operational and executive decision-making.

---

# Success Measures

An effective AWS Organizations strategy should result in:

* Improved financial accountability
* Better governance consistency
* Increased allocation accuracy
* Improved visibility
* Better forecasting accuracy
* Increased commitment effectiveness
* Scalable cloud operations
* Sustainable AWS growth

---

# Related Documents

* aws-cost-management-framework.md
* aws-tagging-and-allocation.md
* aws-governance-framework.md
* aws-commitment-management.md
* allocation-framework.md
* governance-framework.md
* budget-framework.md
* forecasting-framework.md
* kpi-dictionary.md
* cost-accountability-model.md


