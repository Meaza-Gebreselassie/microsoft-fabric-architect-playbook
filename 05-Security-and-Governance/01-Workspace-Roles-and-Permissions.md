# Microsoft Fabric Workspace Role Permission Matrix

> High-level reference for Microsoft Fabric workspace role permissions.

This matrix compares the capabilities available to the **Admin, Member, Contributor, and Viewer** workspace roles.

## How to Use

Search this page using `Ctrl + F` on Windows or `Command + F` on Mac.

Useful searches:

- `Viewer` — show Viewer-related rows
- `Admin` — show Admin-related rows
- `Data Access` — locate data permissions
- `Gateway & Connectivity` — locate connectivity permissions
- `ReadAll` — locate OneLake/Spark access
- `ReadData` — locate SQL/TDS access
- `Not Permitted` — locate restricted capabilities

> **Important:** Workspace role permissions are only one layer of Fabric security. Item-level permissions and data-level security may further restrict access.

---

## Permission Matrix

| Workspace Role | Permission Category | Permission / Capability | Access Status | Description / Notes |
|---|---|---|---|---|
| Admin | Workspace Management | Update and delete the workspace. | ✅ Permitted | Manage workspace configuration and deletion. |
| Member | Workspace Management | Update and delete the workspace. | ❌ Not Permitted | Manage workspace configuration and deletion. |
| Contributor | Workspace Management | Update and delete the workspace. | ❌ Not Permitted | Manage workspace configuration and deletion. |
| Viewer | Workspace Management | Update and delete the workspace. | ❌ Not Permitted | Manage workspace configuration and deletion. |
| Admin | Access Management | Add or remove people, including other admins. | ✅ Permitted | Manage workspace users, including administrators. |
| Member | Access Management | Add or remove people, including other admins. | ❌ Not Permitted | Manage workspace users, including administrators. |
| Contributor | Access Management | Add or remove people, including other admins. | ❌ Not Permitted | Manage workspace users, including administrators. |
| Viewer | Access Management | Add or remove people, including other admins. | ❌ Not Permitted | Manage workspace users, including administrators. |
| Admin | Access Management | Add members or others with lower permissions. | ✅ Permitted | Assign lower-level workspace access. |
| Member | Access Management | Add members or others with lower permissions. | ✅ Permitted | Assign lower-level workspace access. |
| Contributor | Access Management | Add members or others with lower permissions. | ❌ Not Permitted | Assign lower-level workspace access. |
| Viewer | Access Management | Add members or others with lower permissions. | ❌ Not Permitted | Assign lower-level workspace access. |
| Admin | Access Management | Allow others to reshare items. | ✅ Permitted | Allow other users to reshare workspace items. |
| Member | Access Management | Allow others to reshare items. | ✅ Permitted | Allow other users to reshare workspace items. |
| Contributor | Access Management | Allow others to reshare items. | ❌ Not Permitted | Allow other users to reshare workspace items. |
| Viewer | Access Management | Allow others to reshare items. | ❌ Not Permitted | Allow other users to reshare workspace items. |
| Admin | Content Management | Create or modify database items. | ✅ Permitted | Create or modify database items. |
| Member | Content Management | Create or modify database items. | ✅ Permitted | Create or modify database items. |
| Contributor | Content Management | Create or modify database items. | ✅ Permitted | Create or modify database items. |
| Viewer | Content Management | Create or modify database items. | ❌ Not Permitted | Create or modify database items. |
| Admin | Content Management | Create or modify database mirroring items. | ✅ Permitted | Create or modify database mirroring items. |
| Member | Content Management | Create or modify database mirroring items. | ✅ Permitted | Create or modify database mirroring items. |
| Contributor | Content Management | Create or modify database mirroring items. | ✅ Permitted | Create or modify database mirroring items. |
| Viewer | Content Management | Create or modify database mirroring items. | ❌ Not Permitted | Create or modify database mirroring items. |
| Admin | Content Management | Create or modify warehouse items. | ✅ Permitted | Create or modify warehouse items. |
| Member | Content Management | Create or modify warehouse items. | ✅ Permitted | Create or modify warehouse items. |
| Contributor | Content Management | Create or modify warehouse items. | ✅ Permitted | Create or modify warehouse items. |
| Viewer | Content Management | Create or modify warehouse items. | ❌ Not Permitted | Create or modify warehouse items. |
| Admin | Workspace Management | Create workspace identity | ✅ Permitted | Create and manage the workspace identity. |
| Member | Workspace Management | Create workspace identity | ❌ Not Permitted | Create and manage the workspace identity. |
| Contributor | Workspace Management | Create workspace identity | ❌ Not Permitted | Create and manage the workspace identity. |
| Viewer | Workspace Management | Create workspace identity | ❌ Not Permitted | Create and manage the workspace identity. |
| Admin | Git / Integration | Connect workspace to a Git repository | ✅ Permitted | Connect the workspace to source control. |
| Member | Git / Integration | Connect workspace to a Git repository | ❌ Not Permitted | Connect the workspace to source control. |
| Contributor | Git / Integration | Connect workspace to a Git repository | ❌ Not Permitted | Connect the workspace to source control. |
| Viewer | Git / Integration | Connect workspace to a Git repository | ❌ Not Permitted | Connect the workspace to source control. |
| Admin | Content Management | View and read content of pipelines, notebooks, Spark job definitions, ML models and experiments, and eventstreams. | ✅ Permitted | View and read supported Fabric items. |
| Member | Content Management | View and read content of pipelines, notebooks, Spark job definitions, ML models and experiments, and eventstreams. | ✅ Permitted | View and read supported Fabric items. |
| Contributor | Content Management | View and read content of pipelines, notebooks, Spark job definitions, ML models and experiments, and eventstreams. | ✅ Permitted | View and read supported Fabric items. |
| Viewer | Content Management | View and read content of pipelines, notebooks, Spark job definitions, ML models and experiments, and eventstreams. | ✅ Permitted | View and read supported Fabric items. |
| Admin | Content Management | View and read content of KQL databases, KQL query-sets, digital twin builder items, and real-time dashboards. | ✅ Permitted | View and read Real-Time Intelligence items. |
| Member | Content Management | View and read content of KQL databases, KQL query-sets, digital twin builder items, and real-time dashboards. | ✅ Permitted | View and read Real-Time Intelligence items. |
| Contributor | Content Management | View and read content of KQL databases, KQL query-sets, digital twin builder items, and real-time dashboards. | ✅ Permitted | View and read Real-Time Intelligence items. |
| Viewer | Content Management | View and read content of KQL databases, KQL query-sets, digital twin builder items, and real-time dashboards. | ✅ Permitted | View and read Real-Time Intelligence items. |
| Admin | Content Management | View and read content of event schema sets. | ✅ Permitted | View and read event schema sets. |
| Member | Content Management | View and read content of event schema sets. | ✅ Permitted | View and read event schema sets. |
| Contributor | Content Management | View and read content of event schema sets. | ✅ Permitted | View and read event schema sets. |
| Viewer | Content Management | View and read content of event schema sets. | ✅ Permitted | View and read event schema sets. |
| Admin | Gateway & Connectivity | Connect to SQL analytics endpoint of Lakehouse or the Warehouse | ✅ Permitted | Connect to the SQL analytics endpoint. |
| Member | Gateway & Connectivity | Connect to SQL analytics endpoint of Lakehouse or the Warehouse | ✅ Permitted | Connect to the SQL analytics endpoint. |
| Contributor | Gateway & Connectivity | Connect to SQL analytics endpoint of Lakehouse or the Warehouse | ✅ Permitted | Connect to the SQL analytics endpoint. |
| Viewer | Gateway & Connectivity | Connect to SQL analytics endpoint of Lakehouse or the Warehouse | ✅ Permitted | Connect to the SQL analytics endpoint. |
| Admin | Data Access | Read Lakehouse and Data warehouse data and shortcuts with T-SQL through TDS endpoint (ReadData). | ✅ Permitted | Query authorized data through the SQL/TDS endpoint. |
| Member | Data Access | Read Lakehouse and Data warehouse data and shortcuts with T-SQL through TDS endpoint (ReadData). | ✅ Permitted | Query authorized data through the SQL/TDS endpoint. |
| Contributor | Data Access | Read Lakehouse and Data warehouse data and shortcuts with T-SQL through TDS endpoint (ReadData). | ✅ Permitted | Query authorized data through the SQL/TDS endpoint. |
| Viewer | Data Access | Read Lakehouse and Data warehouse data and shortcuts with T-SQL through TDS endpoint (ReadData). | ✅ Permitted | Query authorized data through the SQL/TDS endpoint. |
| Admin | Data Access | Read Lakehouse and Data warehouse data and shortcuts through OneLake APIs and Spark (ReadAll). | ✅ Permitted | Read data through OneLake APIs and Spark. |
| Member | Data Access | Read Lakehouse and Data warehouse data and shortcuts through OneLake APIs and Spark (ReadAll). | ✅ Permitted | Read data through OneLake APIs and Spark. |
| Contributor | Data Access | Read Lakehouse and Data warehouse data and shortcuts through OneLake APIs and Spark (ReadAll). | ✅ Permitted | Read data through OneLake APIs and Spark. |
| Viewer | Data Access | Read Lakehouse and Data warehouse data and shortcuts through OneLake APIs and Spark (ReadAll). | ❌ Not Permitted | Read data through OneLake APIs and Spark. |
| Admin | Data Access | Read Lakehouse data through Lakehouse explorer (ReadAll). | ✅ Permitted | Read Lakehouse data through Lakehouse explorer. |
| Member | Data Access | Read Lakehouse data through Lakehouse explorer (ReadAll). | ✅ Permitted | Read Lakehouse data through Lakehouse explorer. |
| Contributor | Data Access | Read Lakehouse data through Lakehouse explorer (ReadAll). | ✅ Permitted | Read Lakehouse data through Lakehouse explorer. |
| Viewer | Data Access | Read Lakehouse data through Lakehouse explorer (ReadAll). | ❌ Not Permitted | Read Lakehouse data through Lakehouse explorer. |
| Admin | Data Access | Subscribe to OneLake events. | ✅ Permitted | Subscribe to OneLake events. |
| Member | Data Access | Subscribe to OneLake events. | ✅ Permitted | Subscribe to OneLake events. |
| Contributor | Data Access | Subscribe to OneLake events. | ✅ Permitted | Subscribe to OneLake events. |
| Viewer | Data Access | Subscribe to OneLake events. | ❌ Not Permitted | Subscribe to OneLake events. |
| Admin | Content Management | Write or delete pipelines, notebooks, Spark job definitions, ML models, and experiments, and eventstreams. | ✅ Permitted | Create, modify, or delete supported Fabric items. |
| Member | Content Management | Write or delete pipelines, notebooks, Spark job definitions, ML models, and experiments, and eventstreams. | ✅ Permitted | Create, modify, or delete supported Fabric items. |
| Contributor | Content Management | Write or delete pipelines, notebooks, Spark job definitions, ML models, and experiments, and eventstreams. | ✅ Permitted | Create, modify, or delete supported Fabric items. |
| Viewer | Content Management | Write or delete pipelines, notebooks, Spark job definitions, ML models, and experiments, and eventstreams. | ❌ Not Permitted | Create, modify, or delete supported Fabric items. |
| Admin | Content Management | Write or delete Eventhouses, KQL Querysets, Real-Time Dashboards, digital twin builder data, and schema and data of KQL Databases, Lakehouses, data warehouses, and shortcuts. | ✅ Permitted | Create, modify, or delete supported data and Real-Time Intelligence items. |
| Member | Content Management | Write or delete Eventhouses, KQL Querysets, Real-Time Dashboards, digital twin builder data, and schema and data of KQL Databases, Lakehouses, data warehouses, and shortcuts. | ✅ Permitted | Create, modify, or delete supported data and Real-Time Intelligence items. |
| Contributor | Content Management | Write or delete Eventhouses, KQL Querysets, Real-Time Dashboards, digital twin builder data, and schema and data of KQL Databases, Lakehouses, data warehouses, and shortcuts. | ✅ Permitted | Create, modify, or delete supported data and Real-Time Intelligence items. |
| Viewer | Content Management | Write or delete Eventhouses, KQL Querysets, Real-Time Dashboards, digital twin builder data, and schema and data of KQL Databases, Lakehouses, data warehouses, and shortcuts. | ❌ Not Permitted | Create, modify, or delete supported data and Real-Time Intelligence items. |
| Admin | Content Management | Create, write, or delete event schema sets, and the schemas and event types they contain. | ✅ Permitted | Manage event schema sets and event types. |
| Member | Content Management | Create, write, or delete event schema sets, and the schemas and event types they contain. | ✅ Permitted | Manage event schema sets and event types. |
| Contributor | Content Management | Create, write, or delete event schema sets, and the schemas and event types they contain. | ✅ Permitted | Manage event schema sets and event types. |
| Viewer | Content Management | Create, write, or delete event schema sets, and the schemas and event types they contain. | ❌ Not Permitted | Manage event schema sets and event types. |
| Admin | Execution & Scheduling | Execute or cancel execution of notebooks, Spark job definitions, ML models, and experiments. | ✅ Permitted | Run or cancel supported workloads. |
| Member | Execution & Scheduling | Execute or cancel execution of notebooks, Spark job definitions, ML models, and experiments. | ✅ Permitted | Run or cancel supported workloads. |
| Contributor | Execution & Scheduling | Execute or cancel execution of notebooks, Spark job definitions, ML models, and experiments. | ✅ Permitted | Run or cancel supported workloads. |
| Viewer | Execution & Scheduling | Execute or cancel execution of notebooks, Spark job definitions, ML models, and experiments. | ❌ Not Permitted | Run or cancel supported workloads. |
| Admin | Execution & Scheduling | Execute or cancel execution of pipelines. | ✅ Permitted | Run or cancel pipelines. |
| Member | Execution & Scheduling | Execute or cancel execution of pipelines. | ✅ Permitted | Run or cancel pipelines. |
| Contributor | Execution & Scheduling | Execute or cancel execution of pipelines. | ✅ Permitted | Run or cancel pipelines. |
| Viewer | Execution & Scheduling | Execute or cancel execution of pipelines. | ❌ Not Permitted | Run or cancel pipelines. |
| Admin | Execution & Scheduling | View execution output of pipelines, notebooks, ML models and experiments. | ✅ Permitted | View execution results and outputs. |
| Member | Execution & Scheduling | View execution output of pipelines, notebooks, ML models and experiments. | ✅ Permitted | View execution results and outputs. |
| Contributor | Execution & Scheduling | View execution output of pipelines, notebooks, ML models and experiments. | ✅ Permitted | View execution results and outputs. |
| Viewer | Execution & Scheduling | View execution output of pipelines, notebooks, ML models and experiments. | ✅ Permitted | View execution results and outputs. |
| Admin | Execution & Scheduling | Schedule data refreshes via the on-premises gateway. | ✅ Permitted | Schedule data refresh through the on-premises gateway. |
| Member | Execution & Scheduling | Schedule data refreshes via the on-premises gateway. | ✅ Permitted | Schedule data refresh through the on-premises gateway. |
| Contributor | Execution & Scheduling | Schedule data refreshes via the on-premises gateway. | ✅ Permitted | Schedule data refresh through the on-premises gateway. |
| Viewer | Execution & Scheduling | Schedule data refreshes via the on-premises gateway. | ❌ Not Permitted | Schedule data refresh through the on-premises gateway. |
| Admin | Gateway & Connectivity | Modify gateway connection settings. | ✅ Permitted | Modify gateway connection configuration. |
| Member | Gateway & Connectivity | Modify gateway connection settings. | ✅ Permitted | Modify gateway connection configuration. |
| Contributor | Gateway & Connectivity | Modify gateway connection settings. | ✅ Permitted | Modify gateway connection configuration. |
| Viewer | Gateway & Connectivity | Modify gateway connection settings. | ❌ Not Permitted | Modify gateway connection configuration. |

## Understanding the Security Layers

Workspace roles should not be confused with item-level or data-level permissions.

```mermaid
flowchart LR
    A["Identity"] --> B["Workspace Role"]
    B --> C["Item Permission"]
    C --> D["Data Permission"]
    D --> E["OneLake / SQL Security"]
    E --> F["Authorized Data"]
```

Each security layer answers a different question:

| Security layer | Primary question |
|---|---|
| Identity | Who is the user, group, service principal, or managed identity? |
| Workspace role | What can the identity do across the workspace? |
| Item permission | What can the identity do with a specific Fabric item? |
| Data permission | What data can the identity read, write, or manage? |
| OneLake or SQL security | Which tables, folders, rows, columns, or objects can the identity access? |
| Protection policy | Should access to a labeled item be retained or blocked across Fabric? |

> **Important:** Access provided by a workspace role does not always guarantee access to every item or all underlying data. Item permissions, data permissions, OneLake security, SQL security, and protection policies can further restrict access.

---

# Microsoft Fabric Protection Policies

## Overview

Microsoft Purview protection policies for Fabric provide centralized, sensitivity-label-based access enforcement across supported Microsoft Fabric items.

These policies help organizations apply consistent protection across the Fabric footprint instead of manually configuring the same restriction in every workspace and item.

Protection policies are especially useful for sensitive data such as:

- Payroll information
- Financial information
- Personally identifiable information
- Healthcare information
- Legal and compliance information
- Confidential business information

---

## Sensitivity Label vs. Protection Policy

A sensitivity label and a protection policy have related but different responsibilities.

| Capability | Purpose |
|---|---|
| Sensitivity label | Classifies an item based on its sensitivity |
| Protection policy | Controls who can retain access to items carrying the label |
| DLP policy | Detects sensitive data and responds to policy violations |
| Workspace role | Provides general workspace-level permissions |
| Item permission | Provides access to a specific Fabric item |
| OneLake security | Controls access to data stored in OneLake |

The easiest way to remember the relationship is:

> **The sensitivity label identifies the sensitive item. The protection policy enforces access to the labeled item.**

---

## How Protection Policies Work

Each Fabric protection policy is associated with one Microsoft Purview sensitivity label.

The policy identifies the users and groups allowed to retain their existing permissions on items carrying that label.

Users and groups not included in the policy are blocked from accessing the labeled items.

```mermaid
flowchart LR
    A["Sensitivity Label"] --> B["Protection Policy"]
    B --> C["Supported Fabric Items"]
    C --> D["Approved users retain existing access"]
    C --> E["Other users are blocked"]
```

The protection policy does not automatically grant new permissions.

An approved user must already have access through a workspace role, item permission, or another Fabric permission mechanism. The policy only allows that user to retain the access already assigned.

---

## Fabric-Wide Enforcement

Protection policies are designed to apply consistently across supported Fabric items in all workspaces.

This means administrators do not have to configure the same protection separately in every workspace.

The enforcement process is:

1. An administrator creates a sensitivity label in Microsoft Purview.
2. The label is applied to a supported Fabric item.
3. A protection policy is associated with the sensitivity label.
4. The policy identifies the users and groups allowed to retain access.
5. Fabric evaluates labeled items across its supported footprint.
6. Users not included in the policy are blocked.

> **Fabric-wide enforcement means centralized enforcement across supported Fabric items. It does not mean every Fabric and Power BI item type is currently supported.**

---

## Supported Fabric Items

Protection policies support native Fabric items, including:

- Lakehouses
- Warehouses
- SQL databases
- KQL databases
- Eventhouses
- Notebooks
- Pipelines
- Other native Fabric items
- Power BI semantic models

Power BI reports and dashboards are not currently supported by Fabric protection policies.

---

## Relationship to Workspace Roles

Workspace roles and protection policies work together, but they serve different purposes.

Workspace roles grant broad capabilities within a workspace. Protection policies can further restrict access to individual items carrying a protected sensitivity label.

### Example

A user has the Contributor role in a Finance workspace.

Normally, the Contributor role allows the user to create, modify, and read supported items.

However, a warehouse in that workspace has the **Highly Confidential - Payroll** sensitivity label. A protection policy allows only members of the Payroll security group to retain access.

If the Contributor is not included in the approved group, the protection policy blocks access to the labeled warehouse.

```mermaid
flowchart TD
    A["User has Contributor workspace role"] --> B["User opens labeled warehouse"]
    B --> C{"Included in protection policy?"}
    C -->|Yes| D["Retains existing access"]
    C -->|No| E["Access blocked"]
```

Therefore:

> **Workspace access does not override a Fabric protection policy.**

---

## Requirements

Fabric protection policies require:

- Appropriate Microsoft 365 E3 or E5 licensing for Microsoft Purview sensitivity labels
- At least the Information Protection Administrator role to create the policy
- A sensitivity label configured in Microsoft Purview
- The label must be scoped to **Files and other data assets**
- The label must include the **Control access** protection setting
- The Fabric tenant setting **Allow users to apply sensitivity labels for content** must be enabled

Only appropriately configured sensitivity labels can be associated with Fabric protection policies.

---

## Creating a Protection Policy

The high-level configuration process is:

1. Open the Microsoft Purview portal.
2. Open the **Protection policies** page.
3. Select **New protection policy**.
4. Enter the policy name and description.
5. Select the sensitivity label associated with the policy.
6. Select Microsoft Fabric as the data source.
7. Add the users and groups allowed to retain access.
8. Decide whether to activate the policy immediately.
9. Review and submit the policy.

After creation, it can take up to 24 hours for the policy to begin detecting and protecting items associated with the sensitivity label.

---

## Service Principal Considerations

Service principals cannot be added directly to a protection policy through the Microsoft Purview portal.

If a service principal requires access to protected Fabric items:

1. Add the service principal to a Microsoft Entra security group.
2. Add that security group to the protection policy.
3. Confirm that the service principal already has the required Fabric permissions.
4. Test all dependent applications and automated processes.

If a required service principal is not included in an allowed security group, the protection policy can block it and cause failures in:

- Pipelines
- Applications
- Semantic-model access
- API integrations
- Automated processes
- Other service-principal-based connections

> **The impact on service principals must be evaluated before enabling a protection policy in production.**

---

## Limitations and Considerations

- A tenant can have up to 50 protection policies.
- A policy can contain up to 100 users and groups.
- Each policy is associated with one sensitivity label.
- Guest and external users are not currently supported.
- Policy enforcement can take up to 24 hours.
- Power BI reports and dashboards are not currently supported.
- Deployment pipelines and Git integration use workspace permissions and do not enforce protection-policy item permissions during deployment operations.
- The user who last applied the sensitivity label is treated as the label issuer and is not blocked by the associated protection policy.
- Automatically applied or inherited labels may have special issuer behavior.
- Service principals must be included through Microsoft Entra security groups.

---

## Recommended Implementation Approach

Before enabling a protection policy in production:

1. Identify the business data requiring protection.
2. Confirm the sensitivity-label design with the security and compliance teams.
3. Identify all users, groups, service principals, and automated processes requiring access.
4. Use Microsoft Entra security groups instead of adding many individual users.
5. Test the policy with a limited group of nonproduction Fabric items.
6. Validate interactive user access.
7. Validate pipeline, API, semantic-model, and application access.
8. Review the effect on deployment pipelines and Git-integrated workspaces.
9. Document the policy owner and approval process.
10. Monitor restricted access through the OneLake catalog and Fabric administration experiences.

---

## Example: Payroll Data Protection

An organization has a Finance workspace containing a warehouse with employee payroll information.

### Configuration

- Sensitivity label: **Highly Confidential - Payroll**
- Protected item: Finance Payroll Warehouse
- Approved group: Payroll Data Users
- Approved administrators: Selected Fabric and security administrators
- Approved automation: Payroll service principal added through an Entra security group

### Expected Result

- Approved users retain their existing permissions.
- The payroll service principal continues to operate.
- Other workspace users are blocked from the labeled warehouse.
- The source item remains in the Finance workspace.
- Enforcement is controlled centrally through Microsoft Purview.

---

## Key Takeaways

- Fabric protection policies provide centralized access enforcement across supported Fabric items.
- Policies use Microsoft Purview sensitivity labels to identify protected items.
- Approved identities retain their existing access.
- Protection policies do not grant new permissions.
- Users not included in the policy are blocked from labeled items.
- Protection policies can restrict access normally provided through a workspace role.
- Service principals must be included through Microsoft Entra security groups.
- Policies should be tested carefully before production implementation.
- Protection policies complement workspace roles, item permissions, OneLake security, and DLP policies.

The main concept is:

> **Sensitivity labels classify Fabric items, while protection policies enforce who is permitted to retain access across the supported Fabric footprint.**

---

## References

- [Protection policies in Microsoft Fabric](https://learn.microsoft.com/fabric/governance/protection-policies-overview)
- [Create and manage protection policies for Fabric](https://learn.microsoft.com/fabric/governance/protection-policies-create)
- [Information protection in Microsoft Fabric](https://learn.microsoft.com/fabric/governance/information-protection)
- [Microsoft Fabric permission model](https://learn.microsoft.com/fabric/security/permission-model)
- [Workspace roles in Microsoft Fabric](https://learn.microsoft.com/fabric/fundamentals/roles-workspaces)
