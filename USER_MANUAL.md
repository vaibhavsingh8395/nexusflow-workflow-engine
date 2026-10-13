# NexusFlow ERP - User Manual

## 1. Getting Started & Authentication
1. Access the live portal via your GitHub Pages deployment: [NexusFlow Live Portal](https://vaibhavsingh8395.github.io/nexusflow-workflow-engine/).
2. Sign in using the pre-configured enterprise demo tenant credentials:
   - **Company:** Apex Logistics Inc.
   - **Email:** `admin@apexlogistics.com`
   - **Password:** `admin123`
3. Alternatively, click **"Register a new company tenant"** to create your own isolated multi-tenant environment and company workspace.

---

## 2. Core Features & Navigation

### A. Workflow Pipeline (Kanban)
* **Overview:** View all active tasks assigned across your workspace, complete with real-time operational KPI metrics at the top of the dashboard (*Total Tasks*, *In Progress*, and *Completed*).
* **Creating Tasks:** Click the **"+ New Task"** button in the header, specify the task title, description, assigned department (*Business Analyst*, *Systems Engineer*, *Database Administrator*, *Executive Management*), and priority level (*Normal*, *High*, *Critical*).
* **State Transitions:** Update task progress instantly using the dropdown status selector in the action column (*Backlog* $\rightarrow$ *In Progress* $\rightarrow$ *In Review* $\rightarrow$ *Done*).

### B. Managing Team Members (`👥 Team Members` Tab)
* **Directory Control:** Navigate to the **Team Members** tab to view all authorized users operating within your company's isolated workspace.
* **Inviting Colleagues:** Click **"+ Invite Team Member"**, enter their full name, work email, specialized access role, and temporary password to grant them immediate collaborative access to your tenant pipeline.
* **User Offboarding:** Administrators can remove user accounts from the directory when personnel change roles or leave the organization.

### C. Audit Logs & Compliance (`🔍 Audit Logs & Compliance` Tab)
* **Immutable Tracking:** Access the audit log to review real-time, timestamped event trails tracking every user login, tenant registration, task creation, status transition, and user invitation for regulatory governance and compliance.

### D. Session Security
* Use the **"Sign Out"** button in the header to securely terminate your active session and return to the company portal sign-in screen.
