# Microsoft Fabric Architecture Playbook

> A hands-on Microsoft Fabric architecture portfolio focused on designing, securing, governing, integrating, and operating enterprise data and analytics solutions using Microsoft Fabric, Azure, and Power BI.

---

## 🎯 Purpose

- Document my Microsoft Fabric learning journey, hands-on labs, architecture patterns, and lessons learned.
- Build practical architecture-level knowledge that supports both real-world enterprise scenarios and my Microsoft certification path.
- Develop a reusable reference for designing, securing, integrating, deploying, monitoring, and operating Microsoft Fabric solutions.

---

## 🎓 Certification Focus

This repository supports my learning across the following Microsoft certifications:

- **DP-600** — Microsoft Fabric Analytics Engineer
- **PL-300** — Microsoft Power BI Data Analyst
- **AZ-305** — Designing Microsoft Azure Infrastructure Solutions
- **SC-100** — Microsoft Cybersecurity Architect

The certifications provide structure for my learning, while the repository focuses on applying those concepts through architecture, hands-on implementation, and design decisions.

---

## 📁 Repository Structure

The content is organized by architecture domains to provide a clear and logical learning path.

### 01 — [Fabric Platform Fundamentals](01-Fabric-Platform-Fundamentals/)

Core concepts and architecture of the Microsoft Fabric platform.

**Focus:** Fabric SaaS architecture, tenant, capacity, workspaces, items, OneLake fundamentals, workloads, and how the Fabric platform fits together.

---

### 02 — [Data Architecture](02-Data-Architecture/)

Architecture and design of the Fabric data layer.

**Focus:** OneLake, Lakehouse, Warehouse, Delta tables, shortcuts, medallion architecture, SQL analytics endpoint, and data architecture design decisions.

---

### 03 — [Data Engineering & Integration](03-Data-Engineering-and-Integration/)

Data ingestion, transformation, orchestration, and connectivity.

**Focus:** Data Factory, pipelines, Dataflows Gen2, notebooks, Spark, batch processing, data movement, and on-premises/cloud integration.

---

### 04 — [Analytics & Power BI](04-Analytics-and-Power-BI/)

Analytics and semantic modeling within Microsoft Fabric.

**Focus:** Semantic models, Direct Lake, Import, DirectQuery, DAX, reporting, model design, Power BI security, and analytics performance.

---

### 05 — [Security & Governance](05-Security-and-Governance/)

Identity, access control, data security, and governance.

**Focus:** Microsoft Entra ID, workspace roles, item permissions, OneLake security, RLS, CLS, service principals, workspace identity, least privilege, Microsoft Purview, lineage, and governance.

---

### 06 — [Platform Administration](06-Platform-Administration/)

Administration and configuration of the Fabric platform.

**Focus:** Tenant administration, capacity administration, workspace administration, gateway architecture & connection management and platform configuration.

---

### 07 — [DevOps & Lifecycle](07-DevOps-and-Lifecycle/)

Development, deployment, and lifecycle management for Fabric solutions.

**Focus:** Git integration, deployment pipelines, DEV/TEST/PROD, CI/CD, source control, release management, and environment configuration.

---

### 08 — [Monitoring, Performance & Resiliency](08-Monitoring-Performance-and-Resiliency/)

Operational health, performance, availability, and resiliency.

**Focus:** Fabric monitoring, capacity metrics, performance analysis, workload utilization, throttling, gateway monitoring, troubleshooting, high availability, BCDR, and operational support.

---

### 09 — [Architecture Patterns & Standards](09-Architecture-Patterns-and-Standards/)

Reusable enterprise architecture patterns and design standards.

**Focus:** Reference architectures, workspace patterns, environment strategy, naming standards, security patterns, connectivity patterns, data architecture patterns, and architecture decision records.

---

## 🛠️ Additional Sections

### 🧪 [Hands-On Labs](Labs/)

Step-by-step labs used to test and apply the architecture concepts documented throughout this repository.

### 📄 [Certification Prep](Certification-Prep/)

Study notes, exam objectives, review material, and hands-on exercises for DP-600, PL-300, AZ-305, and SC-100.


### 📝 Notes & Lessons Learned

Key takeaways, troubleshooting notes, design decisions, and lessons learned from hands-on implementation.

---

## 🚀 How I Use This Repository

- Start with **01 — Fabric Platform Fundamentals** to establish the platform foundation.
- Work through each architecture domain as I build my Fabric knowledge.
- Use **Hands-On Labs** to validate concepts through implementation.
- Use **Certification Prep** alongside the architecture topics for exam preparation.
- Capture important design decisions and lessons learned instead of only documenting product features.
- Use **Architecture Patterns & Standards** as the reusable architecture reference as the repository grows.

---

## 🔐 Security Notice

All examples in this repository use sample or fictional environments.

No production credentials, internal server names, connection strings, confidential architecture, proprietary information, or production data should be stored in this repository.

---

## 📌 Repository Status

This is a living repository and will continue to evolve as I learn, build, test, and apply Microsoft Fabric in real-world architecture scenarios.

**Learn • Build • Architect • Grow**

---

> **Disclaimer:** The notes, architecture patterns, and recommendations in this repository represent my personal learning, hands-on experience, and reference designs. They are not official Microsoft documentation and are not associated with or endorsed by my employer.
