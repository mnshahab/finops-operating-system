# FinOps RACI Matrix

| Attribute    | Value       |
| ------------ | ----------- |
| Owner        | FinOps Team |
| Version      | 1.0         |
| Status       | Active      |
| Last Updated | 2026-06-08  |
| Review Cycle | Annual      |

---

# Purpose

This document defines the roles and responsibilities associated with FinOps activities across the organization.

The objective is to establish clear ownership, accountability, consultation, and communication for cloud financial management activities.

This RACI aligns with FinOps principles of collaboration, accountability, and business value optimization.

---

# Scope

This RACI applies to:

* AWS
* Microsoft Azure
* Google Cloud Platform
* Kubernetes Platforms
* AI and Machine Learning Platforms
* Shared Services
* Product Teams
* Corporate IT Workloads

---

# RACI Definitions

| Code | Definition                                     |
| ---- | ---------------------------------------------- |
| R    | Responsible for executing the activity         |
| A    | Accountable for the outcome and final decision |
| C    | Consulted during planning or execution         |
| I    | Informed of results or decisions               |

---

# Stakeholder Groups

| Role                  | Description                                                      |
| --------------------- | ---------------------------------------------------------------- |
| Executive Sponsor     | CIO, CTO, CFO, or equivalent                                     |
| FinOps Team           | FinOps practitioners and analysts                                |
| Finance               | Financial planning and budgeting teams                           |
| Product Owners        | Product and business owners                                      |
| Engineering           | Application engineering teams                                    |
| Platform Teams        | Cloud, infrastructure, Kubernetes, AI, and shared platform teams |
| Procurement           | Vendor and contract management teams                             |
| Security & Compliance | Security, governance, and risk management teams                  |

---

# FinOps Governance

| Activity                   | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| -------------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Define FinOps Strategy     | A         | R      | C       | C       | I           | I        | I           | I        |
| Approve FinOps Policies    | A         | R      | C       | C       | C           | C        | I           | C        |
| FinOps Maturity Assessment | I         | A/R    | C       | I       | I           | I        | I           | I        |
| Governance Reviews         | A         | R      | C       | C       | C           | C        | I           | C        |

---

# Cost Visibility & Reporting

| Activity               | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| ---------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Cost Reporting         | I         | A/R    | C       | I       | I           | I        | I           | I        |
| Executive Dashboards   | A         | R      | C       | I       | I           | I        | I           | I        |
| Engineering Dashboards | I         | R      | I       | I       | A           | C        | I           | I        |
| KPI Reporting          | I         | A/R    | C       | C       | C           | C        | I           | I        |

---

# Cost Allocation

| Activity                  | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| ------------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Cost Allocation Framework | I         | A/R    | C       | C       | C           | C        | I           | I        |
| Tagging Standards         | I         | A      | I       | I       | R           | R        | I           | C        |
| Showback Reporting        | I         | A/R    | C       | I       | I           | I        | I           | I        |
| Chargeback Model          | I         | R      | A       | C       | I           | I        | I           | I        |
| Shared Cost Allocation    | I         | A/R    | C       | C       | C           | C        | I           | I        |

---

# Budgeting & Forecasting

| Activity             | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| -------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Budget Planning      | I         | C      | A       | C       | C           | C        | I           | I        |
| Forecast Development | I         | R      | A       | C       | C           | C        | I           | I        |
| Forecast Reviews     | I         | R      | A       | C       | C           | C        | I           | I        |
| Variance Analysis    | I         | R      | A       | C       | C           | C        | I           | I        |

---

# Optimization

| Activity                | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| ----------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Optimization Program    | I         | A/R    | I       | I       | C           | C        | I           | I        |
| Rightsizing             | I         | C      | I       | I       | A/R         | C        | I           | I        |
| Resource Cleanup        | I         | C      | I       | I       | A/R         | C        | I           | I        |
| Storage Optimization    | I         | C      | I       | I       | A/R         | C        | I           | I        |
| Kubernetes Optimization | I         | C      | I       | I       | C           | A/R      | I           | I        |
| AI Cost Optimization    | I         | C      | I       | I       | C           | A/R      | I           | I        |

---

# Commitment Management

| Activity                   | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| -------------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Savings Plans Strategy     | I         | A/R    | C       | I       | C           | C        | I           | I        |
| Reserved Capacity Strategy | I         | A/R    | C       | I       | C           | C        | I           | I        |
| Commitment Reviews         | I         | A/R    | C       | I       | C           | C        | I           | I        |
| Vendor Commitments         | I         | C      | C       | I       | I           | I        | A/R         | I        |

---

# Anomaly Management

| Activity                   | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| -------------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Anomaly Detection          | I         | A/R    | I       | I       | I           | I        | I           | I        |
| Investigation Coordination | I         | A/R    | I       | I       | C           | C        | I           | I        |
| Remediation Actions        | I         | C      | I       | I       | A/R         | A/R      | I           | I        |
| Executive Escalation       | A         | R      | C       | I       | I           | I        | I           | I        |

---

# Unit Economics

| Activity              | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| --------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| Unit Cost Definition  | I         | R      | C       | A       | C           | C        | I           | I        |
| Unit Cost Reporting   | I         | A/R    | C       | C       | C           | C        | I           | I        |
| Product Cost Analysis | I         | R      | C       | A       | C           | C        | I           | I        |

---

# AI FinOps

| Activity            | Executive | FinOps | Finance | Product | Engineering | Platform | Procurement | Security |
| ------------------- | --------- | ------ | ------- | ------- | ----------- | -------- | ----------- | -------- |
| AI Cost Visibility  | I         | A/R    | C       | I       | I           | C        | I           | I        |
| GPU Cost Management | I         | C      | I       | I       | C           | A/R      | I           | I        |
| AI Forecasting      | I         | R      | A       | C       | C           | C        | I           | I        |
| AI Unit Economics   | I         | R      | C       | A       | C           | C        | I           | I        |

---

# Review and Maintenance

The FinOps Team is responsible for maintaining this RACI.

The matrix should be reviewed:

* Annually
* Following major organizational changes
* Following cloud operating model changes
* Following FinOps maturity assessments

---

# Success Criteria

The RACI is considered effective when:

* Every FinOps activity has a defined accountable owner
* Cloud spending ownership is clearly understood
* Stakeholders understand their responsibilities
* Escalation paths are defined
* Governance decisions can be made efficiently

---

# Related Documents

* finops-charter.md
* operating-model.md
* organizational-structure.md
* governance-framework.md
* cost-accountability-model.md
* policy-framework.md
