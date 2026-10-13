# nexusflow-workflow-engine
# NexusFlow ERP & Multi-Tenant Workflow Engine

## 1. Executive Summary & Architecture Overview
NexusFlow ERP is a multi-tenant, role-based enterprise workflow and task-automation SaaS platform engineered for small-to-medium businesses. The application replaces fragmented spreadsheets and rigid legacy software by providing isolated company workspaces, structured task pipelines, and immutable audit logs.

## 2. Technical Stack
* **Front-End:** Modular HTML5, responsive CSS3 (Grid/Flexbox, custom design tokens), and native ES6+ JavaScript.
* **State Management & Persistence:** LocalStorage/SessionStorage mapped to structured multi-tenant JSON schemas.
* **Security & Access Control:** Role-Based Access Control (RBAC) and tenant-isolated session state.

## 3. Database Schema & Multi-Tenant Data Modeling
The application utilizes a normalized relational JSON schema supporting multi-tenant isolation:

### Entities:
1. **Tenants (`nexus_tenants`):**
   - `company_id` (Primary Key / Company Name)
   - `admin_email` (Unique String)
   - `password_hash` (Secured credential reference)
   - `role` (Tenant Admin / Operator)
2. **Tasks (`nexus_tasks`):**
   - `id` (Primary Key / Timestamp)
   - `tenant` (Foreign Key mapping to Tenant Company)
   - `title` & `desc` (Task metadata)
   - `role` (Assigned Department: Business Analyst, Systems Engineer, DBA, Executive)
   - `priority` (Normal, High, Critical)
   - `status` (Backlog, In Progress, In Review, Done)
3. **Audit Trail (`nexus_audit`):**
   - `timestamp` (ISO datetime)
   - `tenant` (Tenant isolation key)
   - `user` (Actor email)
   - `action` (Event type: `TENANT_REGISTER`, `TASK_CREATE`, `TASK_STATUS_CHANGE`)
   - `details` (Descriptive audit payload)
