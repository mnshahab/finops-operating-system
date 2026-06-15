# AWS Tagging and Allocation Framework

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the AWS-specific framework for resource tagging, cost allocation, ownership attribution, showback, chargeback, and financial accountability.

The objective is to ensure AWS costs can be accurately allocated to business units, products, applications, environments, and accountable owners while supporting reporting, budgeting, forecasting, optimization, and governance processes.

This framework extends the enterprise Cost Allocation Framework and provides AWS implementation guidance.

---

# Scope

This framework applies to:

* AWS Organizations
* AWS Accounts
* Amazon EC2
* Amazon EBS
* Amazon S3
* Amazon EFS
* Amazon FSx
* Amazon RDS
* Amazon Aurora
* Amazon DynamoDB
* Amazon Redshift
* Amazon OpenSearch Service
* Amazon EKS
* Amazon ECS
* AWS Lambda
* Amazon SageMaker
* Amazon Bedrock
* Shared Services Platforms

---

# Guiding Principles

## Every Dollar Should Have an Owner

AWS costs should be allocated to an accountable owner whenever technically feasible.

---

## Allocation Must Support Business Decisions

Cost allocation should enable accountability, forecasting, budgeting, optimization, and business value analysis.

---

## Tagging Supports Allocation

Tags are a key component of allocation, but not the only mechanism.

AWS accounts, Cost Categories, and allocation rules should also be leveraged.

---

## Shared Costs Must Be Allocated Transparently

Shared service costs should follow documented allocation methodologies.

---

## Allocation Accuracy Improves Over Time

Organizations should continuously improve allocation coverage and reporting quality.

---

# Objectives

The AWS tagging and allocation framework should enable organizations to:

* Improve allocation accuracy
* Increase financial accountability
* Improve reporting quality
* Support showback
* Support chargeback
* Improve forecasting
* Improve budgeting
* Support optimization initiatives

---

# AWS Allocation Hierarchy

Recommended allocation structure:

```text id="f3d9wr"
AWS Organization
        │
Business Unit
        │
Product
        │
Application
        │
Environment
        │
Resource
```

Allocation structures should align with enterprise accountability models.

---

# Allocation Methods

AWS cost allocation should use multiple allocation mechanisms.

## Account-Based Allocation

Accounts represent the highest level of allocation.

Best suited for:

* Business Units
* Products
* Platforms
* Shared Services

Advantages:

* High accuracy
* Simple implementation
* Native AWS reporting support

---

## Tag-Based Allocation

Tags provide resource-level ownership visibility.

Best suited for:

* Applications
* Products
* Environments
* Teams

Advantages:

* Granular visibility
* Flexible reporting
* Enhanced accountability

---

## Cost Category Allocation

AWS Cost Categories provide business-focused groupings.

Best suited for:

* Executive reporting
* Business reporting
* Product reporting
* Chargeback reporting

Advantages:

* Consistent business views
* Simplified reporting

---

## Shared Cost Allocation

Used when multiple consumers share common services.

Examples:

* Kubernetes Platforms
* Logging Platforms
* Monitoring Platforms
* Networking Services
* AI Platforms

Shared allocation methodologies should be documented and approved.

---

# AWS Tagging Strategy

Tagging should support:

* Ownership
* Allocation
* Governance
* Automation
* Reporting

Tags should follow enterprise tagging standards.

---

# Required Tags

The following tags should be considered mandatory whenever supported by AWS services.

| Tag          | Purpose                    |
| ------------ | -------------------------- |
| BusinessUnit | Organizational ownership   |
| CostCenter   | Financial ownership        |
| Application  | Application ownership      |
| Product      | Product ownership          |
| Environment  | Environment classification |
| Owner        | Accountable owner          |

---

# Environment Standards

Recommended values:

| Value            | Description                             |
| ---------------- | --------------------------------------- |
| Production       | Customer-facing production environments |
| NonProduction    | Shared non-production environments      |
| Development      | Development environments                |
| Test             | Testing environments                    |
| QA               | Quality assurance environments          |
| Sandbox          | Experimental environments               |
| DisasterRecovery | Recovery environments                   |

Organizations may extend values as required.

---

# AWS Cost Allocation Tags

AWS Cost Allocation Tags should be activated centrally.

Tag activation should follow governance procedures.

Examples:

* BusinessUnit
* CostCenter
* Application
* Product
* Owner

Only approved tags should be activated for financial reporting.

---

# AWS Cost Categories Strategy

Cost Categories should support executive and financial reporting.

Recommended categories include:

## Business Unit

Examples:

* Finance
* Marketing
* Product Engineering
* Operations

---

## Product

Examples:

* SaaS Products
* Customer Applications
* Shared Platforms

---

## Environment

Examples:

* Production
* Development
* Test

---

## Shared Services

Examples:

* Kubernetes
* Security
* Networking
* Monitoring

---

# Shared Cost Allocation Framework

Certain AWS costs cannot be directly assigned to a single consumer.

Examples include:

* Transit Gateway
* Shared VPCs
* Shared Kubernetes Clusters
* Logging Platforms
* Monitoring Platforms

Allocation methods may include:

* Equal distribution
* Consumption-based allocation
* Resource-based allocation
* Business unit allocation

Methods should be documented and reviewed periodically.

---

# Kubernetes Allocation

Amazon EKS environments often require allocation beyond AWS tags.

Allocation should incorporate:

* Namespace ownership
* Team ownership
* Cluster ownership
* Workload ownership

Organizations should integrate Kubernetes allocation data into AWS reporting processes.

---

# AI Allocation

AI workloads often require additional allocation dimensions.

Examples include:

* Model ownership
* AI use case
* Business sponsor
* Product ownership

Recommended AI tags:

| Tag          | Purpose              |
| ------------ | -------------------- |
| ModelName    | Model identification |
| ModelType    | Model classification |
| AIUseCase    | Business purpose     |
| BusinessUnit | Ownership            |
| Product      | Product ownership    |

AI allocation should support unit economics and business value analysis.

---

# Showback Framework

Showback reports should provide visibility into:

* Business Unit spend
* Product spend
* Application spend
* Shared service costs
* Forecast performance
* Budget performance

Showback should encourage accountability without financial transfer mechanisms.

---

# Chargeback Framework

Chargeback reports should support:

* Internal billing
* Financial accountability
* Budget ownership
* Cost recovery

Chargeback calculations should be transparent and documented.

---

# Allocation Reporting

Allocation reporting should provide visibility into:

* Allocated spend
* Unallocated spend
* Shared service allocations
* Allocation coverage
* Cost ownership

Reports should support executive, financial, and operational stakeholders.

---

# Allocation Governance

Allocation governance should include:

* Tag reviews
* Allocation reviews
* Cost Category reviews
* Shared service allocation reviews
* Ownership validation

Reviews should occur on a regular basis.

---

# Tag Compliance Monitoring

Organizations should monitor:

* Missing tags
* Invalid values
* Ownership gaps
* Allocation exceptions

Compliance reporting should be incorporated into governance reviews.

---

# AWS Native Allocation Services

The following AWS services support allocation and reporting.

## AWS Cost Allocation Tags

Provides:

* Resource-level allocation
* Ownership visibility

---

## AWS Cost Categories

Provides:

* Business-focused reporting
* Executive reporting structures

---

## AWS Cost and Usage Report

Provides:

* Detailed allocation analytics
* Cost reporting

---

## AWS Organizations

Provides:

* Account-based allocation
* Consolidated billing

---

# Allocation KPIs

Recommended KPIs include:

* Allocation Coverage
* Unallocated Spend
* Resource Ownership Coverage
* Tag Compliance Rate
* Shared Cost Allocation Accuracy
* Chargeback Accuracy

Definitions should align with the KPI Dictionary.

---

# Roles and Responsibilities

| Function       | Responsibility                      |
| -------------- | ----------------------------------- |
| FinOps         | Allocation governance and reporting |
| Finance        | Financial oversight                 |
| Engineering    | Resource ownership                  |
| Platform Teams | Shared service allocation support   |
| Product Teams  | Business ownership validation       |
| Leadership     | Accountability oversight            |

---

# Success Measures

An effective AWS tagging and allocation framework should result in:

* Increased allocation coverage
* Improved accountability
* Better reporting quality
* Improved forecasting accuracy
* Better budgeting outcomes
* Improved optimization visibility
* Reduced unallocated spend

---

# Related Documents

* allocation-framework.md
* showback-framework.md
* chargeback-framework.md
* tagging-standards.md
* aws-organizations-strategy.md
* aws-cost-management-framework.md
* aws-governance-framework.md
* budget-framework.md
* forecasting-framework.md
* kpi-dictionary.md
