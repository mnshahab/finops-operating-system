# Tagging Standards

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | YYYY-MM-DD  |
| Review Cycle | Annual      |

---

# Purpose

This document establishes the standards for resource tagging and ownership metadata across cloud environments.

The objective is to support cost allocation, accountability, budgeting, forecasting, optimization, governance, automation, security, operational management, and reporting through consistent resource classification.

This standard aligns with FinOps Foundation principles of visibility, accountability, and business value realization.

---

# Scope

This standard applies to:

* AWS
* Microsoft Azure
* Google Cloud Platform
* Kubernetes Platforms
* AI and Machine Learning Workloads
* Platform Services
* Shared Services
* Infrastructure Services
* Application Workloads

---

# Guiding Principles

## Ownership Is Mandatory

Every cloud resource should have a clearly identifiable owner.

---

## Business Context Matters

Resources should be associated with the business capabilities, products, applications, and teams they support.

---

## Standardization Improves Accuracy

Consistent tagging standards improve reporting quality, allocation accuracy, and governance effectiveness.

---

## Tags Support Multiple Functions

Tagging supports:

* Cost allocation
* Showback
* Chargeback
* Budgeting
* Forecasting
* Optimization
* Security
* Operations
* Automation
* Compliance

---

## Automation Should Be Preferred

Tagging enforcement should be automated whenever possible through cloud-native controls and governance tooling.

---

# Tagging Objectives

The tagging model should enable organizations to:

* Identify resource ownership
* Allocate cloud costs accurately
* Support financial accountability
* Improve reporting quality
* Enable automation
* Improve governance visibility
* Support operational management
* Improve optimization activities

---

# Required Tagging Standard

The following tags should be considered mandatory for all supported resources where technically feasible.

| Tag Name     | Purpose                               |
| ------------ | ------------------------------------- |
| Application  | Identifies the application or service |
| Owner        | Responsible team or owner             |
| BusinessUnit | Organizational ownership              |
| CostCenter   | Financial ownership                   |
| Environment  | Resource lifecycle classification     |
|              |                                       |

Product | Business product or service |

---

# Environment Values

Approved environment values should include:

| Value            | Description                          |
| ---------------- | ------------------------------------ |
| Production       | Customer-facing production workloads |
| NonProduction    | Shared non-production environments   |
| Development      | Development environments             |
| Test             | Testing environments                 |
| QA               | Quality assurance environments       |
| Sandbox          | Experimental environments            |
| DisasterRecovery | Recovery environments                |

Organizations may extend values based on operational requirements.

---

# Optional Tags

Organizations may implement additional tags to support operational, governance, and reporting requirements.

Examples include:

| Tag Name           | Purpose                    |
| ------------------ | -------------------------- |
| Project            | Project ownership          |
| Department         | Organizational reporting   |
| DataClassification | Security classification    |
| ServiceTier        | Criticality classification |
| Platform           | Platform ownership         |
| Compliance         | Regulatory requirements    |
| Lifecycle          | Resource lifecycle stage   |
| ManagedBy          | Automation ownership       |

---

# Tag Naming Standards

Tag names should:

* Use consistent naming conventions
* Avoid abbreviations where possible
* Be easy to understand
* Remain stable over time
* Align with reporting requirements

Recommended examples:

```text
Application
Owner
BusinessUnit
CostCenter
Environment
Product
```

Avoid inconsistent naming patterns such as:

```text
app
application_name
owner-name
dept
cc
env
```

---

# Tag Value Standards

Tag values should:

* Use approved reference values
* Follow consistent formatting
* Avoid special characters when possible
* Be reviewed periodically
* Align with enterprise master data where available

Examples:

```text
BusinessUnit = Finance
BusinessUnit = Marketing
BusinessUnit = ProductEngineering

Environment = Production
Environment = Development
Environment = Test
```

---

# Resource Ownership Requirements

Every resource should be traceable to an accountable owner.

Minimum ownership attributes include:

| Attribute    | Requirement |
| ------------ | ----------- |
| Owner        | Required    |
| Application  | Required    |
| BusinessUnit | Required    |
| CostCenter   | Required    |
| Environment  | Required    |

Resources without ownership should be treated as governance exceptions.

---

# Shared Services Tagging

Shared services should include ownership metadata even when costs are allocated across multiple consumers.

Examples:

* Kubernetes Platforms
* Security Platforms
* Monitoring Platforms
* Networking Platforms
* Data Platforms
* AI Platforms

Shared service tags should identify:

* Platform owner
* Service owner
* Allocation owner

---

# Kubernetes Tagging Considerations

Kubernetes environments often require metadata beyond traditional cloud tags.

Examples include:

* Namespace ownership
* Cluster ownership
* Team ownership
* Application ownership
* Environment ownership

Organizations should integrate Kubernetes metadata into allocation and reporting processes.

---

# AI Workload Tagging Considerations

AI workloads often require additional ownership visibility.

Examples include:

* Model owner
* Business sponsor
* AI platform owner
* Use case classification
* Cost center ownership

AI-related metadata should support allocation, reporting, governance, and optimization activities.

---

# Tag Compliance Monitoring

Organizations should monitor:

* Tag coverage
* Missing tags
* Invalid values
* Orphaned resources
* Untagged spend
* Ownership exceptions

Compliance reporting should be reviewed regularly through FinOps governance processes.

---

# Tagging Enforcement

Enforcement methods may include:

* Cloud-native policies
* Infrastructure as Code validation
* CI/CD controls
* Automated remediation
* Resource deployment guardrails

Organizations should prioritize preventive controls over manual remediation.

---

# Exception Management

Exceptions should be documented when:

* Services do not support tagging
* Technical limitations exist
* Third-party services prevent compliance
* Temporary exemptions are approved

All exceptions should have documented ownership and review dates.

---

# Governance Requirements

Tagging standards should be reviewed periodically to ensure continued alignment with:

* Organizational structures
* Reporting requirements
* Allocation models
* Cloud platform capabilities
* Regulatory requirements

Changes should be approved through the FinOps governance process.

---

# Success Measures

An effective tagging standard should result in:

* Improved allocation accuracy
* Reduced unallocated spend
* Increased ownership visibility
* Better reporting quality
* Improved forecasting accuracy
* Enhanced governance visibility
* Greater automation effectiveness

---

# Related Documents

* allocation-framework.md
* shared-cost-allocation.md
* showback-framework.md
* chargeback-framework.md
* cost-accountability-model.md
* governance-framework.md
* finops-raci.md
* budget-framework.md
* kpi-dictionary.md
