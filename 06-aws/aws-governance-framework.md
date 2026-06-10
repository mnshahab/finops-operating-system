# AWS Governance Framework

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the governance framework for managing AWS financial accountability, cost controls, resource ownership, compliance, and operational oversight.

The objective is to ensure AWS resources are deployed, managed, and optimized in a manner that aligns with business objectives, financial targets, security requirements, and organizational policies.

This framework provides AWS-specific governance guidance that supports the broader FinOps Operating System.

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
* Shared Services
* Platform Services

---

# Guiding Principles

## Accountability Must Be Clear

Every AWS resource should have a clearly identified owner responsible for cost, operational management, and business outcomes.

---

## Governance Should Enable Business Value

Governance should provide controls and visibility while supporting innovation, agility, and business growth.

---

## Prevention Is Better Than Correction

Organizations should implement preventive controls wherever possible rather than relying solely on reactive remediation.

---

## Financial Accountability Is Shared

Finance, FinOps, Engineering, Product, Platform, and Leadership teams all contribute to effective cloud governance.

---

## Governance Must Be Measurable

Governance effectiveness should be evaluated using defined KPIs, compliance reporting, and continuous improvement processes.

---

# AWS Governance Objectives

The governance framework should enable organizations to:

* Improve financial accountability
* Increase cost visibility
* Improve allocation accuracy
* Strengthen resource ownership
* Improve forecasting accuracy
* Support optimization programs
* Reduce governance risks
* Enable sustainable AWS growth

---

# AWS Governance Operating Model

```text
Policies
    │
    ▼
Standards
    │
    ▼
Controls
    │
    ▼
Monitoring
    │
    ▼
Reporting
    │
    ▼
Continuous Improvement
```

Governance activities should be integrated into operational and financial management processes.

---

# Governance Domains

## Financial Governance

Focuses on cloud spending oversight and accountability.

Areas include:

* Budget management
* Forecast reviews
* Cost allocation
* Chargeback
* Showback
* Commitment governance

---

## Resource Governance

Focuses on resource ownership and lifecycle management.

Areas include:

* Resource ownership
* Resource provisioning
* Resource retirement
* Environment governance

---

## Operational Governance

Focuses on sustainable cloud operations.

Areas include:

* Capacity planning
* Optimization management
* Shared service management
* Platform management

---

## Compliance Governance

Focuses on adherence to organizational standards.

Areas include:

* Tag compliance
* Cost allocation compliance
* Resource ownership compliance
* Policy compliance

---

# AWS Organizations Governance

AWS Organizations should serve as the foundation of governance.

Key areas include:

* Organizational Unit structure
* Account management
* Consolidated billing
* Account ownership
* Shared services strategy

Governance structures should align with business accountability models.

---

# AWS Account Governance

Each AWS account should have:

* Account owner
* Business owner
* Cost center assignment
* Budget ownership
* Operational support model

Account ownership should be documented and reviewed regularly.

---

# Resource Ownership Governance

All AWS resources should be associated with accountable owners.

Minimum ownership requirements should include:

| Attribute     | Requirement |
| ------------- | ----------- |
| Business Unit | Required    |
| Application   | Required    |
| Cost Center   | Required    |
| Environment   | Required    |
| Owner         | Required    |

Resources without ownership should be treated as governance exceptions.

---

# Tagging Governance

Tagging standards should align with enterprise allocation requirements.

Mandatory tags should support:

* Cost allocation
* Ownership visibility
* Reporting
* Automation
* Governance

Tag compliance should be monitored continuously.

---

# Cost Allocation Governance

Cost allocation should align with the organizational accountability model.

Allocation governance should include:

* Cost Categories
* Tag-based allocation
* Shared service allocation
* Showback reporting
* Chargeback reporting

Allocation coverage should be reviewed monthly.

---

# Budget Governance

Budget governance should establish financial accountability and spending controls.

Requirements include:

* Budget ownership
* Budget reviews
* Budget alerts
* Variance reviews
* Corrective action planning

Budgets should be reviewed as part of monthly FinOps operating cadences.

---

# Forecast Governance

Forecast governance should ensure financial predictability.

Requirements include:

* Forecast ownership
* Forecast review processes
* Assumption validation
* Variance analysis
* Executive reporting

Forecast accuracy should be monitored regularly.

---

# Commitment Governance

Commitment decisions should follow formal governance processes.

Requirements include:

* Coverage reviews
* Utilization reviews
* Risk assessments
* Purchase approvals
* Renewal planning

Significant commitment purchases should require documented approvals.

---

# Optimization Governance

Optimization activities should follow structured governance processes.

Requirements include:

* Opportunity identification
* Prioritization
* Savings validation
* Backlog management
* Benefit realization tracking

Optimization outcomes should be reported regularly.

---

# AWS Native Governance Controls

## AWS Organizations

Provides:

* Organizational structure
* Consolidated billing
* Centralized governance

---

## Service Control Policies (SCPs)

Provides:

* Preventive controls
* Service restrictions
* Governance enforcement

---

## AWS Tag Policies

Provides:

* Tag standardization
* Compliance enforcement
* Metadata governance

---

## AWS Budgets

Provides:

* Budget monitoring
* Financial alerts
* Cost controls

---

## AWS Cost Anomaly Detection

Provides:

* Spend monitoring
* Anomaly detection
* Early warning alerts

---

# Governance Reviews

Organizations should establish formal governance reviews.

## Monthly Reviews

Examples:

* Spend reviews
* Budget reviews
* Forecast reviews
* Optimization reviews

---

## Quarterly Reviews

Examples:

* Commitment reviews
* Governance assessments
* KPI reviews
* Executive reporting

---

## Annual Reviews

Examples:

* Policy reviews
* Standards reviews
* Governance maturity assessments

---

# Governance KPIs

Recommended KPIs include:

* Allocation Coverage
* Resource Ownership Coverage
* Tag Compliance Rate
* Forecast Accuracy
* Budget Variance
* Commitment Utilization
* Commitment Coverage
* Optimization Realization Rate
* Unallocated Spend

Definitions should align with the KPI Dictionary.

---

# Exception Management

Governance exceptions should be documented and approved.

Exception records should include:

* Description
* Business justification
* Risk assessment
* Owner
* Expiration date
* Review requirements

Exceptions should be reviewed regularly.

---

# Roles and Responsibilities

| Function       | Responsibility                    |
| -------------- | --------------------------------- |
| Finance        | Financial governance              |
| FinOps         | Cost governance and reporting     |
| Engineering    | Resource ownership and compliance |
| Platform Teams | Shared service governance         |
| Product Teams  | Business accountability           |
| Security Teams | Security governance alignment     |
| Leadership     | Strategic oversight               |

---

# Reporting Requirements

Governance reporting should include:

* Compliance metrics
* Allocation metrics
* Budget performance
* Forecast performance
* Commitment performance
* Optimization performance
* Exception reporting
* Governance trends

Reports should support operational, financial, and executive audiences.

---

# Success Measures

An effective AWS governance framework should result in:

* Improved accountability
* Increased allocation accuracy
* Better forecasting accuracy
* Improved compliance
* Increased optimization adoption
* Better financial visibility
* Reduced governance risk
* Sustainable AWS growth

---

# Related Documents

* aws-organizations-strategy.md
* aws-cost-management-framework.md
* aws-tagging-and-allocation.md
* aws-commitment-management.md
* aws-cost-optimization-framework.md
* aws-reporting-and-analytics.md
* allocation-framework.md
* governance-framework.md
* budget-framework.md
* kpi-dictionary.md
