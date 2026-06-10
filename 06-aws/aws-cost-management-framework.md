# AWS Cost Management Framework

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the framework for managing AWS cost visibility, reporting, allocation, analysis, forecasting, and financial accountability.

The objective is to provide a structured approach for collecting, analyzing, governing, and communicating AWS cost and usage data to support informed decision-making and effective cloud financial management.

This framework aligns with FinOps Foundation principles of visibility, accountability, collaboration, and business value realization.

---

# Scope

This framework applies to:

* AWS Organizations
* AWS Accounts
* Amazon EC2
* Amazon EBS
* Amazon S3
* Amazon RDS
* Amazon Aurora
* Amazon DynamoDB
* Amazon Redshift
* Amazon EKS
* Amazon ECS
* AWS Lambda
* Amazon OpenSearch Service
* Amazon Bedrock
* Amazon SageMaker
* Shared Platform Services

---

# Guiding Principles

## Visibility Before Optimization

Organizations must establish visibility into spending and usage before optimization efforts can be effective.

---

## Data Must Be Trusted

Financial decisions should be based on accurate, validated, and governed AWS cost data.

---

## Accountability Requires Ownership

AWS costs should be associated with accountable business units, products, applications, and teams.

---

## Reporting Should Support Decisions

Cost reporting should focus on enabling business, financial, and technical decision-making.

---

## Cost Management Is Continuous

AWS cost management should be embedded into ongoing operational and governance processes.

---

# AWS Cost Management Objectives

The AWS cost management process should enable organizations to:

* Improve cost visibility
* Improve allocation accuracy
* Support budgeting and forecasting
* Enable financial accountability
* Improve optimization effectiveness
* Support commitment planning
* Improve executive reporting
* Enable business value analysis

---

# AWS Cost Management Architecture

The AWS cost management model consists of five primary layers.

```text
AWS Billing Data
        │
        ▼
Cost Collection
        │
        ▼
Cost Processing
        │
        ▼
Allocation and Analysis
        │
        ▼
Reporting and Insights
```

Each layer should be governed through established FinOps processes.

---

# AWS Cost Data Sources

## AWS Billing Console

Provides high-level visibility into AWS spending.

Typical use cases:

* Invoice review
* Billing validation
* Executive summaries

---

## AWS Cost Explorer

Provides interactive cost analysis capabilities.

Typical use cases:

* Spend analysis
* Trend analysis
* Service analysis
* Cost allocation analysis

---

## AWS Cost and Usage Report (CUR)

Provides the authoritative AWS billing dataset.

Typical use cases:

* Detailed reporting
* Cost allocation
* Showback
* Chargeback
* Advanced analytics

CUR should be considered the primary source for enterprise AWS cost analytics.

---

## AWS Cost Categories

Provides business-focused cost classification.

Typical use cases:

* Business unit reporting
* Product reporting
* Cost ownership
* Executive reporting

Cost Categories should align with allocation and governance frameworks.

---

## AWS Cost Anomaly Detection

Provides automated identification of unusual spending patterns.

Typical use cases:

* Cost monitoring
* Spend investigations
* Operational alerts

---

# Cost Data Processing Framework

## Data Collection

Collect AWS billing and usage data from approved sources.

Examples:

* CUR
* Cost Explorer
* AWS Billing APIs
* Cost Categories

---

## Data Validation

Validate:

* Billing completeness
* Cost accuracy
* Allocation mappings
* Cost category assignments

---

## Data Enrichment

Enhance AWS cost data using:

* Tags
* Cost Categories
* CMDB mappings
* Business ownership mappings
* Product ownership mappings

---

## Data Governance

Maintain:

* Data quality standards
* Access controls
* Ownership definitions
* Reporting standards

---

# AWS Cost Allocation Framework

AWS costs should be mapped to business ownership structures.

Recommended hierarchy:

```text
AWS Organization
        │
AWS Account
        │
Business Unit
        │
Product
        │
Application
        │
Environment
```

Allocation should align with the Cost Allocation Framework.

---

# Cost Visibility Framework

AWS reporting should support multiple stakeholder groups.

## Executive Reporting

Focus areas:

* Cloud spend trends
* Budget performance
* Forecast performance
* Commitment performance

---

## Finance Reporting

Focus areas:

* Cost allocation
* Budget management
* Forecasting
* Variance analysis

---

## Engineering Reporting

Focus areas:

* Resource utilization
* Optimization opportunities
* Platform efficiency
* Service-level spend

---

## Product Reporting

Focus areas:

* Product costs
* Unit economics
* Customer economics
* Business value metrics

---

# AWS Cost Analysis Framework

Analysis should occur across multiple dimensions.

## Service Analysis

Examples:

* EC2
* S3
* RDS
* EKS
* OpenSearch
* Bedrock

---

## Account Analysis

Examples:

* Production Accounts
* Development Accounts
* Shared Service Accounts

---

## Business Analysis

Examples:

* Business Units
* Products
* Applications
* Cost Centers

---

## Trend Analysis

Examples:

* Monthly trends
* Quarterly trends
* Growth analysis
* Seasonal analysis

---

# AWS Budget Management

AWS Budgets should support:

* Cost budgets
* Usage budgets
* Commitment budgets
* Forecast budgets

Budget ownership should align with governance frameworks.

---

# AWS Forecasting Support

Forecasting should leverage:

* Historical AWS consumption
* Business demand signals
* Growth projections
* Product roadmaps
* AI adoption forecasts

Forecasts should be reviewed regularly through FinOps operating cadences.

---

# AWS Cost Optimization Support

Cost management data should support identification of:

* Rightsizing opportunities
* Storage optimization opportunities
* Commitment opportunities
* Resource cleanup opportunities
* Platform optimization opportunities

Insights should be incorporated into optimization workflows.

---

# AWS Reporting Architecture

Recommended reporting architecture:

```text
CUR
 │
 ▼
Amazon S3
 │
 ▼
AWS Glue
 │
 ▼
Amazon Athena
 │
 ▼
Amazon QuickSight
```

Organizations may integrate third-party reporting platforms where appropriate.

---

# AWS Cost Management KPIs

Recommended KPIs include:

* Total Cloud Spend
* Cloud Spend Growth Rate
* Allocation Coverage
* Forecast Accuracy
* Budget Variance
* Forecast Variance
* Commitment Coverage
* Commitment Utilization
* Optimization Opportunity Value
* Unallocated Spend

Definitions should align with the KPI Dictionary.

---

# Roles and Responsibilities

| Function       | Responsibility                |
| -------------- | ----------------------------- |
| FinOps         | Cost management and reporting |
| Finance        | Financial governance          |
| Engineering    | Resource ownership            |
| Platform Teams | Shared service accountability |
| Product Teams  | Business ownership            |
| Leadership     | Strategic oversight           |

---

# Reporting Requirements

AWS cost reporting should provide visibility into:

* Service-level spend
* Account-level spend
* Business unit spend
* Product spend
* Shared services
* Forecast performance
* Budget performance
* Optimization opportunities
* Commitment performance

Reports should be tailored to stakeholder needs while maintaining consistent definitions.

---

# Governance Requirements

AWS cost management should be governed through established FinOps processes.

Governance activities should include:

* Cost reviews
* Budget reviews
* Forecast reviews
* Allocation reviews
* Optimization reviews
* Executive reporting

Changes to reporting methodologies should be documented and approved.

---

# Success Measures

An effective AWS cost management practice should result in:

* Improved cost visibility
* Increased allocation accuracy
* Better forecast accuracy
* Improved budgeting effectiveness
* Increased optimization participation
* Improved financial accountability
* Better executive decision-making

---

# Related Documents

* aws-organizations-strategy.md
* aws-tagging-and-allocation.md
* aws-commitment-management.md
* aws-reporting-and-analytics.md
* aws-governance-framework.md
* allocation-framework.md
* budget-framework.md
* forecasting-framework.md
* kpi-dictionary.md
* executive-kpis.md
