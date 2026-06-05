# Architecture Decision Log (DECISIONS.md)

## Purpose

This document records significant architectural, governance, operational, and strategic decisions made within the FinOps OS project.

The objective is to preserve context, rationale, and history behind key decisions to ensure consistency and prevent rework.

---

# Decision Record Format

Each decision should contain:

| Field       | Description                                                    |
| ----------- | -------------------------------------------------------------- |
| Decision ID | Unique identifier                                              |
| Date        | Date approved                                                  |
| Status      | Proposed, Approved, Superseded, Retired                        |
| Category    | Strategy, Governance, KPI, Cloud, AI, Kubernetes, Architecture |
| Decision    | Summary of the decision                                        |
| Rationale   | Why the decision was made                                      |
| Impact      | Expected outcome                                               |
| Owner       | Responsible party                                              |

---

# Approved Decisions

## DEC-001

| Field       | Value                                                            |
| ----------- | ---------------------------------------------------------------- |
| Decision ID | DEC-001                                                          |
| Date        | 2026-06-05                                                       |
| Status      | Approved                                                         |
| Category    | Strategy                                                         |
| Decision    | FinOps OS will be built as an open, community-driven repository. |
| Rationale   | Encourage adoption, collaboration, and continuous improvement.   |
| Impact      | Content must remain reusable and vendor neutral.                 |
| Owner       | FinOps OS Maintainers                                            |

---

## DEC-002

| Field       | Value                                                           |
| ----------- | --------------------------------------------------------------- |
| Decision ID | DEC-002                                                         |
| Date        | 2026-06-05                                                      |
| Status      | Approved                                                        |
| Category    | Architecture                                                    |
| Decision    | Numeric folder prefixes will be used for repository navigation. |
| Rationale   | Ensures predictable navigation and content organization.        |
| Impact      | All future folders must follow repository sequencing standards. |
| Owner       | FinOps OS Maintainers                                           |

---

## DEC-003

| Field       | Value                                                         |
| ----------- | ------------------------------------------------------------- |
| Decision ID | DEC-003                                                       |
| Date        | 2026-06-05                                                    |
| Status      | Approved                                                      |
| Category    | Cloud Strategy                                                |
| Decision    | AWS, Azure, and GCP are first-class supported platforms.      |
| Rationale   | These represent the majority of enterprise cloud consumption. |
| Impact      | All major frameworks must support these providers.            |
| Owner       | FinOps OS Maintainers                                         |

---

## DEC-004

| Field       | Value                                                         |
| ----------- | ------------------------------------------------------------- |
| Decision ID | DEC-004                                                       |
| Date        | 2026-06-05                                                    |
| Status      | Approved                                                      |
| Category    | Cloud Strategy                                                |
| Decision    | OCI support will be included in a future release.             |
| Rationale   | Growing enterprise adoption and customer demand.              |
| Impact      | OCI content will be developed after core platform completion. |
| Owner       | FinOps OS Maintainers                                         |

---

## DEC-005

| Field       | Value                                                             |
| ----------- | ----------------------------------------------------------------- |
| Decision ID | DEC-005                                                           |
| Date        | 2026-06-05                                                        |
| Status      | Approved                                                          |
| Category    | Governance                                                        |
| Decision    | Governance artifacts are mandatory before optimization artifacts. |
| Rationale   | Sustainable optimization requires accountability and ownership.   |
| Impact      | Governance content receives priority in the backlog.              |
| Owner       | FinOps OS Maintainers                                             |

---

## DEC-006

| Field       | Value                                                       |
| ----------- | ----------------------------------------------------------- |
| Decision ID | DEC-006                                                     |
| Date        | 2026-06-05                                                  |
| Status      | Approved                                                    |
| Category    | Reporting                                                   |
| Decision    | KPI-driven reporting will be the standard reporting model.  |
| Rationale   | Decisions should be driven by measurable business outcomes. |
| Impact      | All frameworks must define associated KPIs.                 |
| Owner       | FinOps OS Maintainers                                       |

---

## DEC-007

| Field       | Value                                                                   |
| ----------- | ----------------------------------------------------------------------- |
| Decision ID | DEC-007                                                                 |
| Date        | 2026-06-05                                                              |
| Status      | Approved                                                                |
| Category    | Architecture                                                            |
| Decision    | Native cloud tooling will be prioritized before third-party tools.      |
| Rationale   | Lower adoption barriers and reduced dependency on commercial platforms. |
| Impact      | AWS, Azure, and GCP native services will be referenced first.           |
| Owner       | FinOps OS Maintainers                                                   |

---

## DEC-008

| Field       | Value                                                                                 |
| ----------- | ------------------------------------------------------------------------------------- |
| Decision ID | DEC-008                                                                               |
| Date        | 2026-06-05                                                                            |
| Status      | Approved                                                                              |
| Category    | AI FinOps                                                                             |
| Decision    | AI FinOps will be treated as a standalone domain.                                     |
| Rationale   | AI workloads introduce unique financial management challenges.                        |
| Impact      | Dedicated AI governance, KPI, reporting, and optimization content will be maintained. |
| Owner       | FinOps OS Maintainers                                                                 |

---

## DEC-009

| Field       | Value                                                                       |
| ----------- | --------------------------------------------------------------------------- |
| Decision ID | DEC-009                                                                     |
| Date        | 2026-06-05                                                                  |
| Status      | Approved                                                                    |
| Category    | Kubernetes                                                                  |
| Decision    | Kubernetes FinOps will be treated as a standalone domain.                   |
| Rationale   | Shared infrastructure and allocation complexity require dedicated guidance. |
| Impact      | Kubernetes-specific frameworks and playbooks will be maintained.            |
| Owner       | FinOps OS Maintainers                                                       |

---

## DEC-010

| Field       | Value                                                                                |
| ----------- | ------------------------------------------------------------------------------------ |
| Decision ID | DEC-010                                                                              |
| Date        | 2026-06-05                                                                           |
| Status      | Approved                                                                             |
| Category    | Framework                                                                            |
| Decision    | FinOps OS will align with the FinOps Foundation framework while extending beyond it. |
| Rationale   | Maintain industry alignment while addressing practical implementation gaps.          |
| Impact      | New content should map to FinOps capabilities where applicable.                      |
| Owner       | FinOps OS Maintainers                                                                |

---

## DEC-011

| Field       | Value                                                                             |
| ----------- | --------------------------------------------------------------------------------- |
| Decision ID | DEC-011                                                                           |
| Date        | 2026-06-05                                                                        |
| Status      | Approved                                                                          |
| Category    | Documentation                                                                     |
| Decision    | All major documents must follow the repository standards defined in STANDARDS.md. |
| Rationale   | Consistency improves usability and maintainability.                               |
| Impact      | Non-compliant artifacts should be updated during reviews.                         |
| Owner       | FinOps OS Maintainers                                                             |

---

## DEC-012

| Field       | Value                                                                                                 |
| ----------- | ----------------------------------------------------------------------------------------------------- |
| Decision ID | DEC-012                                                                                               |
| Date        | 2026-06-05                                                                                            |
| Status      | Approved                                                                                              |
| Category    | Optimization                                                                                          |
| Decision    | Optimization recommendations must include business impact, savings estimates, risk, and effort level. |
| Rationale   | Cost savings alone should not drive decision making.                                                  |
| Impact      | All optimization playbooks will use a common recommendation format.                                   |
| Owner       | FinOps OS Maintainers                                                                                 |

---

# Proposed Decisions

Use this section to capture ideas awaiting approval.

| ID       | Proposal                     | Status   |
| -------- | ---------------------------- | -------- |
| DEC-P001 | FinOps OS Certification Path | Proposed |
| DEC-P002 | FinOps OS Training Program   | Proposed |
| DEC-P003 | FinOps OS Automation Library | Proposed |
| DEC-P004 | FinOps AI Agent Framework    | Proposed |

---

# Retired Decisions

Move superseded or retired decisions here.

| ID   | Original Decision | Retirement Date |
| ---- | ----------------- | --------------- |
| None | None              | N/A             |

---

# Decision Governance

## When to Create a Decision

Create a decision record when:

* Repository structure changes
* New cloud platforms are added
* Governance models change
* New domains are introduced
* Major standards change
* Significant architectural changes occur

---

## Review Cycle

Review decision records quarterly.

Retire obsolete decisions when replacement decisions are approved.

---

## Document Metadata

| Attribute    | Value                 |
| ------------ | --------------------- |
| Owner        | FinOps OS Maintainers |
| Version      | 1.0                   |
| Status       | Active                |
| Last Updated | 2026-06-05            |
| Review Cycle | Quarterly             |
