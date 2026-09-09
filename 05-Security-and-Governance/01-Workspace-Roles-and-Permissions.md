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

---

## Understanding the Security Layers

Workspace roles should not be confused with item-level or data-level permissions.

```mermaid
flowchart LR
    A["Identity"] --> B["Workspace Role"]
    B --> C["Item Permission"]
    C --> D["Data Permission"]
    D --> E["OneLake / SQL Security"]
    E --> F["Authorized Data"]
