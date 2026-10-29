# 📖 NexusFlow ERP | Enterprise User Manual

Welcome to the **NexusFlow ERP** operational guide. This manual outlines how to manage multi-tenant workspaces, navigate Kanban operational pipelines, and review compliance audit logs.

---

## 🏢 1. Tenant Management & Authentication

NexusFlow supports secure multi-tenant partitioning:
* **Logging In:** Use your corporate credentials (e.g., Apex Logistics admin account) to access your organization's isolated workspace.
* **Tenant Switching:** Use the top-right tenant dropdown in the navigation header to toggle between active organizational partitions instantly.
* **Tenant Registration:** Register a brand-new corporate entity directly from the welcome onboarding modal to initialize a fresh database partition.

---

## 📋 2. Managing the Kanban Workflow Pipeline

The operational pipeline is structured into four sequential phases:
1. **Backlog:** Newly submitted tasks and incoming operational requests.
2. **In Progress:** Active tasks currently being executed by team members.
3. **In Review:** Tasks undergoing QA verification, code review, or compliance audits.
4. **Completed:** Successfully finished workflows fulfilling SLA requirements.

### Actions:
* **Create Task:** Click the **+ Create Task** button to open the creation modal, assign an owner, and set priority (*High*, *Medium*, *Low*).
* **Search & Filter:** Use the instant search bar to find tasks by title or assignee, or filter by priority levels.
* **State Transitions:** Use the inline action buttons on each task card to advance or reverse task states across the pipeline columns.

---

## 👥 3. Enterprise Directory & Role Management

The **Team & Client Directory** tab allows administrators to:
* View active personnel and assigned departmental roles.
* Manage access privileges ranging from standard contributor access to restricted system administration permissions.

---

## 🔍 4. Compliance & Audit Logs

To maintain strict adherence to enterprise security frameworks:
* Every major action (such as pipeline deployments, tenant migrations, and task state changes) is automatically recorded in the **Compliance Audit Logs** table with precise UTC/local timestamps and actor attribution.
