# Engineering KPIs

| Attribute    | Value                                  |
| ------------ | -------------------------------------- |
| Owner        | Engineering Leadership and FinOps Team |
| Version      | 1.0                                    |
| Status       | Active                                 |
| Last Updated | YYYY-MM-DD                             |
| Review Cycle | Annual                                 |

---

# Purpose

This document defines the engineering-focused Key Performance Indicators (KPIs) used to measure cloud efficiency, resource utilization, operational effectiveness, optimization adoption, and workload management.

The objective is to provide engineering, platform, and operations teams with actionable metrics that support performance improvement, cost efficiency, scalability, and responsible cloud consumption.

These KPIs align with FinOps Foundation principles of accountability, visibility, collaboration, and business value realization.

---

# Scope

This document applies to:

* AWS
* Microsoft Azure
* Google Cloud Platform
* Kubernetes Platforms
* AI and Machine Learning Workloads
* Shared Services Platforms
* Application Teams
* Platform Teams
* Cloud Engineering Teams
* Site Reliability Engineering Teams

---

# KPI Design Principles

Engineering KPIs should:

* Support operational decision-making.
* Encourage efficient resource utilization.
* Promote optimization ownership.
* Enable continuous improvement.
* Align with business objectives.
* Avoid creating incentives that negatively impact reliability, performance, or customer experience.

---

# Engineering KPI Categories

The Engineering KPI framework is organized into five categories.

## Resource Efficiency

Measures how effectively cloud resources are utilized.

---

## Optimization Adoption

Measures engineering participation in optimization initiatives.

---

## Platform Efficiency

Measures performance and efficiency of shared platforms.

---

## Reliability and Sustainability

Measures engineering decisions that influence long-term operational efficiency.

---

## Cost Accountability

Measures ownership, governance, and cost awareness.

---

# Resource Efficiency KPIs

## Compute Utilization

Measures average utilization of compute resources.

### Purpose

Identify overprovisioned or underutilized resources.

### Calculation

```text
Consumed Capacity ÷ Provisioned Capacity
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

## Storage Utilization

Measures utilized storage relative to allocated storage.

### Purpose

Identify storage overallocation and lifecycle management opportunities.

### Calculation

```text
Used Storage ÷ Allocated Storage
```

### Reporting Frequency

Monthly

### KPI Owner

Application and Platform Teams

---

## Database Utilization

Measures effective consumption of database resources.

### Purpose

Identify rightsizing and optimization opportunities.

### Examples

* CPU utilization
* Memory utilization
* Connection utilization
* Storage utilization

### Reporting Frequency

Monthly

### KPI Owner

Database and Application Teams

---

# Optimization Adoption KPIs

## Optimization Recommendation Adoption Rate

Measures implementation of approved optimization recommendations.

### Purpose

Track engineering engagement with optimization activities.

### Calculation

```text
Implemented Recommendations ÷ Approved Recommendations
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

## Resource Cleanup Rate

Measures removal of unused or abandoned cloud resources.

### Purpose

Reduce cloud waste and improve resource governance.

### Examples

* Unattached storage
* Unused snapshots
* Idle resources
* Unused IP addresses

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

## Rightsizing Adoption Rate

Measures implementation of rightsizing opportunities.

### Purpose

Improve resource efficiency and cost optimization.

### Calculation

```text
Implemented Rightsizing Actions ÷ Identified Rightsizing Opportunities
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

# Platform Efficiency KPIs

## Kubernetes Resource Efficiency

Measures effective utilization of Kubernetes resources.

### Purpose

Evaluate efficiency of containerized workloads.

### Examples

* CPU utilization
* Memory utilization
* Resource request efficiency
* Node utilization

### Reporting Frequency

Monthly

### KPI Owner

Platform Teams

---

## Shared Platform Cost Efficiency

Measures cost effectiveness of shared services.

### Purpose

Evaluate efficiency of shared technology platforms.

### Examples

* Cost per workload
* Cost per cluster
* Cost per platform user

### Reporting Frequency

Monthly

### KPI Owner

Platform Owners

---

## AI Infrastructure Utilization

Measures effective utilization of AI infrastructure resources.

### Purpose

Improve visibility into GPU and AI platform efficiency.

### Examples

* GPU utilization
* Training utilization
* Inference utilization

### Reporting Frequency

Monthly

### KPI Owner

AI Platform Teams

---

# Reliability and Sustainability KPIs

## Production Resource Stability

Measures frequency of unplanned infrastructure changes.

### Purpose

Evaluate operational stability and planning effectiveness.

### Examples

* Emergency scaling events
* Capacity incidents
* Resource shortages

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

## Commitment Utilization Support

Measures engineering alignment with commitment strategies.

### Purpose

Support effective use of cloud commitments.

### Examples

* Workload stability
* Predictable consumption patterns
* Commitment alignment

### Reporting Frequency

Monthly

### KPI Owner

Engineering and Platform Teams

---

## Optimization Backlog Closure Rate

Measures completion of approved optimization actions.

### Purpose

Track execution effectiveness.

### Calculation

```text
Completed Optimization Actions ÷ Total Approved Actions
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

# Cost Accountability KPIs

## Resource Ownership Coverage

Measures percentage of cloud resources assigned to an accountable owner.

### Purpose

Improve accountability and governance.

### Calculation

```text
Owned Resources ÷ Total Resources
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

## Tag Compliance Rate

Measures compliance with organizational tagging standards.

### Purpose

Support allocation, reporting, and governance processes.

### Calculation

```text
Compliant Resources ÷ Total Resources
```

### Reporting Frequency

Monthly

### KPI Owner

Engineering Teams

---

## Allocation Coverage

Measures percentage of cloud spend allocated to identifiable owners.

### Purpose

Improve financial visibility and accountability.

### Calculation

```text
Allocated Spend ÷ Total Spend
```

### Reporting Frequency

Monthly

### KPI Owner

FinOps and Engineering Teams

---

# KPI Review Process

Engineering KPI reviews should evaluate:

* Resource efficiency trends
* Optimization progress
* Platform utilization
* Cost drivers
* Governance compliance
* Improvement opportunities

Reviews should be incorporated into monthly FinOps and engineering operating cadences.

---

# KPI Reporting Requirements

Engineering KPI reporting should provide visibility into:

* Resource utilization
* Optimization adoption
* Platform efficiency
* Kubernetes efficiency
* AI infrastructure utilization
* Cost accountability
* Operational trends

Reports should support engineering managers, platform owners, FinOps teams, and leadership stakeholders.

---

# Governance Requirements

Engineering KPI definitions should:

* Remain consistent across reporting periods
* Use approved calculation methodologies
* Align with KPI Dictionary definitions
* Be reviewed periodically
* Support continuous improvement

Changes should be reviewed through established governance processes.

---

# Success Measures

An effective engineering KPI framework should result in:

* Improved resource utilization
* Increased optimization adoption
* Better platform efficiency
* Improved ownership accountability
* Reduced cloud waste
* Better operational planning
* Increased engineering cost awareness

---

# Related Documents

* README.md
* kpi-dictionary.md
* executive-kpis.md
* unit-economics-kpis.md
* allocation-framework.md
* budget-framework.md
* forecasting-framework.md
* commitment-planning.md
* kubernetes-finops-framework.md
* ai-finops-framework.md
