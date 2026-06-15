# AWS Service Optimization Guide

| Attribute    | Value                                  |
| ------------ | -------------------------------------- |
| Owner        | FinOps Team and Cloud Engineering Team |
| Version      | 1.0                                    |
| Status       | Active                                 |
| Last Updated | YYYY-MM-DD                             |
| Review Cycle | Quarterly                              |

---

# Purpose

This guide provides AWS service-specific optimization practices designed to improve resource efficiency, reduce waste, maximize utilization, and support sustainable cloud financial management.

The objective is to provide engineering teams, platform teams, architects, and FinOps practitioners with practical optimization guidance for the AWS services that typically represent the largest areas of cloud spend.

This document complements the AWS Cost Optimization Framework by focusing on service-level optimization opportunities.

---

# Scope

This guide applies to:

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
* AWS Fargate
* AWS Lambda
* Amazon Bedrock
* Amazon SageMaker
* Shared Platform Services

---

# Optimization Methodology

Every optimization opportunity should follow the same process.

```text id="s1lm9u"
Identify
   │
   ▼
Analyze
   │
   ▼
Validate
   │
   ▼
Implement
   │
   ▼
Measure
```

Optimization activities should always balance cost, performance, reliability, security, and business requirements.

---

# Amazon EC2

## Common Cost Drivers

* Instance size
* Instance family
* Runtime hours
* Operating system
* Region
* Licensing

---

## Optimization Opportunities

### Rightsizing

Review:

* CPU utilization
* Memory utilization
* Network utilization

Focus on:

* Oversized instances
* Underutilized instances
* Legacy instance families

---

### Instance Modernization

Evaluate migration to newer generations.

Examples:

* M5 → M7i
* R5 → R7i
* C5 → C7i

Benefits may include:

* Improved performance
* Lower cost per workload
* Better efficiency

---

### Scheduling

Schedule non-production environments.

Examples:

* Development
* Testing
* QA
* Sandbox

---

### Spot Adoption

Evaluate Spot Instances for:

* Batch workloads
* Analytics workloads
* CI/CD pipelines
* Container platforms

---

# Amazon EBS

## Common Cost Drivers

* Provisioned capacity
* Volume type
* Snapshot storage

---

## Optimization Opportunities

### Unattached Volumes

Identify and remove:

* Orphaned volumes
* Retired workload volumes

---

### Volume Rightsizing

Review:

* Capacity utilization
* Growth patterns

Reduce excessive allocations where appropriate.

---

### Snapshot Management

Implement:

* Retention policies
* Lifecycle management
* Automated cleanup

---

### Storage Tier Selection

Review use of:

* gp3
* io2
* st1
* sc1

Align storage performance with workload requirements.

---

# Amazon S3

## Common Cost Drivers

* Storage volume
* Request activity
* Data transfer
* Replication

---

## Optimization Opportunities

### Lifecycle Policies

Automate movement between storage tiers.

Examples:

* Standard
* Intelligent-Tiering
* Standard-IA
* Glacier Instant Retrieval
* Glacier Flexible Retrieval
* Deep Archive

---

### Data Retention Reviews

Identify:

* Obsolete data
* Duplicate data
* Expired datasets

---

### Intelligent-Tiering

Evaluate for datasets with unpredictable access patterns.

---

### Replication Review

Validate business requirements for:

* Cross-region replication
* Same-region replication

---

# Amazon RDS and Aurora

## Common Cost Drivers

* Database instance size
* Storage
* Backup retention
* High availability

---

## Optimization Opportunities

### Instance Rightsizing

Review:

* CPU utilization
* Memory utilization
* Connection counts

---

### Storage Optimization

Evaluate:

* Allocated storage
* Growth trends
* Storage classes

---

### Backup Optimization

Review:

* Retention periods
* Snapshot policies

---

### High Availability Alignment

Validate Multi-AZ deployment requirements.

---

# Amazon DynamoDB

## Common Cost Drivers

* Read capacity
* Write capacity
* Storage
* Global tables

---

## Optimization Opportunities

### Capacity Mode Selection

Evaluate:

* Provisioned Capacity
* On-Demand Capacity

---

### Auto Scaling

Review:

* Scaling thresholds
* Capacity allocations

---

### Global Table Optimization

Validate business requirements and usage patterns.

---

# Amazon Redshift

## Common Cost Drivers

* Cluster size
* Node count
* Storage
* Query patterns

---

## Optimization Opportunities

### Rightsizing

Review:

* Cluster utilization
* Query performance
* Workload demand

---

### Reserved Capacity

Evaluate predictable workloads for commitment opportunities.

---

### Storage Management

Review:

* Data retention
* Historical data requirements

---

### Workload Management

Optimize:

* Query performance
* Resource allocation
* Concurrency settings

---

# Amazon OpenSearch Service

## Common Cost Drivers

* Node count
* Instance types
* Storage
* Data retention

---

## Optimization Opportunities

### Cluster Rightsizing

Review:

* CPU utilization
* Memory utilization
* Search activity

---

### Index Lifecycle Management

Implement:

* Retention policies
* Archive strategies
* Data aging processes

---

### Replica Optimization

Review replica counts based on resiliency requirements.

---

### Storage Optimization

Evaluate:

* gp3 adoption
* Retention requirements
* Index growth trends

---

# Amazon EKS

## Common Cost Drivers

* Worker nodes
* Storage
* Data transfer
* Platform services

---

## Optimization Opportunities

### Node Utilization

Review:

* CPU utilization
* Memory utilization

---

### Resource Requests and Limits

Identify:

* Overallocated workloads
* Excessive reservations

---

### Cluster Consolidation

Evaluate opportunities to reduce cluster sprawl.

---

### Autoscaling

Implement:

* Cluster Autoscaler
* Karpenter
* Horizontal Pod Autoscaler

---

# Amazon ECS and AWS Fargate

## Common Cost Drivers

* Task sizing
* Runtime hours
* Scaling configuration

---

## Optimization Opportunities

### Task Rightsizing

Review:

* CPU allocation
* Memory allocation

---

### Service Scaling

Evaluate:

* Minimum capacity settings
* Scaling policies

---

### Platform Selection

Review:

* ECS on EC2
* ECS on Fargate

Select based on workload requirements and economics.

---

# AWS Lambda

## Common Cost Drivers

* Request volume
* Duration
* Memory allocation

---

## Optimization Opportunities

### Memory Tuning

Optimize memory allocations based on actual execution patterns.

---

### Code Optimization

Reduce:

* Execution time
* Resource consumption

---

### Architecture Selection

Evaluate:

* x86
* Graviton (ARM)

---

# Amazon Bedrock

## Common Cost Drivers

* Input tokens
* Output tokens
* Model selection
* Request volume

---

## Optimization Opportunities

### Model Selection

Use the smallest model that satisfies business requirements.

---

### Prompt Optimization

Reduce unnecessary token consumption.

---

### Response Optimization

Limit excessive output generation.

---

### Request Governance

Review:

* User activity
* Application demand
* Consumption trends

---

# Amazon SageMaker

## Common Cost Drivers

* Training jobs
* Endpoints
* Notebook instances

---

## Optimization Opportunities

### Endpoint Management

Identify:

* Idle endpoints
* Underutilized endpoints

---

### Notebook Scheduling

Automatically stop inactive environments.

---

### Training Optimization

Review:

* Resource selection
* Job duration
* Training schedules

---

# GPU Workloads

## Common Cost Drivers

* GPU runtime
* Accelerator selection
* Utilization levels

---

## Optimization Opportunities

### GPU Utilization

Monitor:

* GPU activity
* Idle periods
* Queue efficiency

---

### Accelerator Selection

Evaluate:

* NVIDIA GPUs
* AWS Trainium
* AWS Inferentia

---

### Scheduling Controls

Reduce idle runtime through workload scheduling.

---

# Shared Services Optimization

Focus areas include:

* Logging platforms
* Monitoring platforms
* Networking services
* Security services
* Kubernetes platforms

Optimization opportunities should be reviewed regularly and allocated appropriately.

---

# Optimization Prioritization

Opportunities should be prioritized using:

| Priority | Characteristics                 |
| -------- | ------------------------------- |
| Critical | High value, low effort          |
| High     | Significant savings opportunity |
| Medium   | Moderate impact                 |
| Low      | Limited financial impact        |

Organizations should define prioritization criteria based on business requirements.

---

# Service Optimization KPIs

Recommended KPIs include:

* Resource Utilization
* Rightsizing Adoption Rate
* Resource Cleanup Rate
* Cost per Workload
* Cost per Transaction
* Kubernetes Resource Efficiency
* GPU Utilization
* Optimization Realization Rate

Definitions should align with the KPI Dictionary.

---

# Success Measures

An effective AWS service optimization program should result in:

* Reduced cloud waste
* Improved utilization
* Increased operational efficiency
* Better commitment utilization
* Improved forecasting accuracy
* Increased engineering accountability
* Sustainable cloud cost management

---

# Related Documents

* aws-cost-optimization-framework.md
* aws-cost-management-framework.md
* aws-commitment-management.md
* aws-ai-finops.md
* aws-reporting-and-analytics.md
* engineering-kpis.md
* kpi-dictionary.md
* optimization-playbook.md
* aws-playbook.md
