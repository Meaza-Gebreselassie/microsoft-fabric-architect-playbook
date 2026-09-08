# Fabric Platform Fundamentals

This section covers the foundational concepts of Microsoft Fabric and how the platform is structured.

The goal is to understand the Fabric platform before moving into individual workloads, data architecture, security, administration, and enterprise design.

---

## Topics

### 1. Microsoft Fabric Overview

- What is Microsoft Fabric?
- Fabric as a Software as a Service (SaaS) platform
- Why organizations use Fabric?
- Unified data and analytics platform

### 2. Fabric Platform Architecture

- Fabric tenant
- Capacity
- Workspaces
- Fabric items
- Relationship between tenant, capacity, workspace, and items

### 3. Fabric Workloads

Overview of the major workloads and experiences available within Microsoft Fabric.

- Data Engineering
- Data Factory
- Data Warehouse
- Power BI
- Real-Time Intelligence
- Data Science
- Databases
- Industry solutions and other Fabric experiences

The focus here is understanding **what each workload is responsible for and how the workloads work together**, rather than detailed implementation.

### 4. OneLake Fundamentals

- What is OneLake?
- OneLake within the Fabric platform
- OneLake and the Fabric tenant
- Centralized storage concept
- Open data formats
- How Fabric workloads access data through OneLake

Detailed OneLake and storage architecture is covered under:

**[02 - Data Architecture](../02-Data-Architecture/)**

### 5. Capacity Fundamentals

- What is Fabric capacity?
- Capacity SKUs
- Capacity Units (CU)
- How workspaces are assigned to capacity
- Shared vs. dedicated capacity concepts
- Relationship between workloads and capacity resources

Detailed capacity administration and monitoring are covered in the Platform Administration and Monitoring sections.

### 6. Workspace Fundamentals

- What is a Fabric workspace?
- Workspaces as containers for Fabric items
- Relationship between workspaces and capacities
- Workspace organization
- Environment concepts such as DEV, TEST/PRE-PROD, and PROD

Detailed workspace administration and security are covered in their respective sections.

### 7. Fabric Items

Understand the concept of an **item** within a Fabric workspace.

Examples include:

- Lakehouse
- Warehouse
- Semantic model
- Report
- Notebook
- Pipeline
- Dataflow
- Eventhouse
- KQL database
- Mirrored database

### 8. How Fabric Components Work Together

A simplified view of the Fabric platform:

```mermaid
flowchart TD
    A["Microsoft Fabric Tenant"]
    B["Fabric Capacity"]
    C["Workspace"]
    D["Fabric Items"]
    E["OneLake"]

    A --> B
    B --> C
    C --> D
    D --> E
