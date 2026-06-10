# AWS FinOps

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This section establishes the AWS-specific implementation framework for the FinOps Operating System.

The objective is to provide practical guidance for managing, governing, optimizing, forecasting, allocating, and reporting AWS cloud costs while aligning technology investments with business objectives.

This section translates the governance, allocation, budgeting, forecasting, and KPI frameworks defined elsewhere in the FinOps Operating System into AWS-specific implementation practices.

The guidance contained within this section aligns with FinOps Foundation principles, AWS Well-Architected Framework Cost Optimization guidance, and enterprise cloud financial management best practices.

---

# Scope

This section applies to:

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
* Amazon SageMaker
* Amazon Bedrock
* Amazon OpenSearch Service
* Shared Platform Services
* Enterprise AWS Environments

---

# AWS FinOps Objectives

The AWS FinOps operating model is designed to achieve the following objectives.

## Cost Visibility

Provide stakeholders with accurate and timely visibility into AWS spending and consumption.

Examples include:

* Service-level cost reporting
* Account-level reporting
* Business unit reporting
* Product reporting
* Application reporting

---

## Financial Accountability

Establish ownership of AWS resources and spending.

Examples include:

* Cost allocation
* Resource ownership
* Showback
* Chargeback
* Business accountability

---

## Cost Optimization

Continuously improve efficiency while maintaining required performance, reliability, and business outcomes.

Examples include:

* Rightsizing
* Storage optimization
* Database optimization
* Commitment optimization
* Container optimization

---

## Financial Planning

Support budgeting, forecasting, commitment planning, and variance management.

Examples include:

* Budget development
* Demand forecasting
* Savings Plan planning
* Forecast reviews

---

## Governance and Control

Establish policies, standards, guardrails, and accountability mechanisms that support sustainable AWS growth.

Examples include:

* Tagging standards
* Resource ownership requirements
* Cost governance controls
* Budget controls
* Policy enforcement

---

# AWS FinOps Operating Model

The AWS FinOps lifecycle follows a continuous improvement model.

```text
Inform
   │
   ▼
Optimize
   │
   ▼
Operate
   │
   ▼
Measure
   │
   ▼
Improve
```

This lifecycle should be embedded into engineering, finance, platform, and product operating cadences.

---

# AWS FinOps Capability Areas

The AWS domain is organized into the following capability areas.

## AWS Organizations Strategy

Establishes multi-account governance, account structures, billing models, and ownership alignment.

Topics include:

* Organizational Units
* Account Strategy
* Billing Structures
* Shared Services
* Account Ownership

Document:

* aws-organizations-strategy.md

---

## AWS Cost Management

Establishes visibility into AWS spending and consumption.

Topics include:

* Cost Explorer
* Cost and Usage Reports
* Cost Categories
* Billing Analysis
* Spend Reporting

Document:

* aws-cost-management-framework.md

---

## AWS Tagging and Allocation

Defines AWS-specific implementation of allocation and ownership standards.

Topics include:

* Cost Allocation Tags
* Tag Governance
* Business Mapping
* Shared Cost Allocation
* Allocation Reporting

Document:

* aws-tagging-and-allocation.md

---

## AWS Commitment Management

Provides governance and operational guidance for AWS commitment programs.

Topics include:

* Savings Plans
* Reserved Instances
* Coverage Management
* Utilization Management
* Commitment Planning

Document:

* aws-commitment-management.md

---

## AWS Cost Optimization

Establishes optimization practices across AWS services.

Topics include:

* Rightsizing
* Storage Optimization
* Database Optimization
* Resource Cleanup
* Cost Efficiency Reviews

Document:

* aws-cost-optimization-framework.md

---

## AWS Reporting and Analytics

Provides reporting architecture and analytics guidance.

Topics include:

* Cost Reporting
* Executive Dashboards
* Engineering Dashboards
* CUR Analytics
* QuickSight Reporting

Document:

* aws-reporting-and-analytics.md

---

## AWS Governance

Establishes AWS-specific governance controls and operational guardrails.

Topics include:

* Policies
* Controls
* Standards
* Exception Management
* Compliance Monitoring

Document:

* aws-governance-framework.md

---

## AWS AI FinOps

Provides governance and optimization guidance for AWS AI services.

Topics include:

* Amazon Bedrock
* Amazon SageMaker
* GPU Consumption
* Model Economics
* AI Unit Economics

Document:

* aws-ai-finops.md

---

## AWS Service Optimization

Provides service-specific optimization guidance.

Topics include:

* EC2
* EBS
* S3
* RDS
* Aurora
* DynamoDB
* Redshift
* EKS
* ECS
* Lambda
* OpenSearch

Document:

* aws-service-optimization-guide.md

---

# AWS Native FinOps Services

The following AWS services support FinOps activities.

## Cost Visibility

* AWS Cost Explorer
* AWS Cost and Usage Reports (CUR)
* AWS Billing Console
* AWS Cost Categories

---

## Governance

* AWS Organizations
* AWS Budgets
* AWS Resource Groups
* AWS Tag Policies
* AWS Service Control Policies

---

## Optimization

* AWS Cost Optimization Hub
* AWS Compute Optimizer
* AWS Trusted Advisor

---

## Analytics

* Amazon Athena
* AWS Glue
* Amazon QuickSight

---

## Monitoring

* Amazon CloudWatch
* AWS Cost Anomaly Detection

---

# Roles and Responsibilities

| Function           | Responsibility                      |
| ------------------ | ----------------------------------- |
| Finance            | Financial governance                |
| FinOps             | AWS cost management and reporting   |
| Engineering        | Resource ownership and optimization |
| Platform Teams     | Shared service management           |
| Product Teams      | Business accountability             |
| Cloud Architecture | Platform standards and design       |
| Leadership         | Strategic oversight                 |

---

# Success Measures

Successful AWS FinOps adoption should result in:

* Improved cost visibility
* Increased allocation coverage
* Improved forecast accuracy
* Improved commitment utilization
* Reduced waste
* Improved optimization execution
* Increased ownership accountability
* Improved business alignment

Success should be measured through the KPI framework defined within this repository.

---

# Related Documents

* FinOps Charter
* Operating Model
* Governance Framework
* Cost Accountability Model
* Allocation Framework
* Budget Framework
* Forecasting Framework
* KPI Dictionary
* Executive KPIs
* Engineering KPIs
* Unit Economics KPIs

---

# Documents in This Section

* aws-organizations-strategy.md
* aws-cost-management-framework.md
* aws-tagging-and-allocation.md
* aws-commitment-management.md
* aws-cost-optimization-framework.md
* aws-reporting-and-analytics.md
* aws-governance-framework.md
* aws-ai-finops.md
* aws-service-optimization-guide.md

This section provides the AWS implementation layer of the FinOps Operating System and should be used in conjunction with the governance, allocation, budgeting, forecasting, and KPI frameworks defined throughout the repository.
