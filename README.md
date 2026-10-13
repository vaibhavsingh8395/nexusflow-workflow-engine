# NexusFlow ERP | Enterprise Multi-Tenant Workflow Engine

**NexusFlow ERP** is a production-grade, multi-tenant enterprise workflow and task automation engine. Built with modern, minimalist architecture, it provides secure tenant isolation, role-based user directory management, real-time Kanban pipeline tracking, and immutable audit logging.

🌐 **Live Production Deployment:** [NexusFlow Live Portal](https://vaibhavsingh8395.github.io/nexusflow-workflow-engine/)

---

## Key Features

* **Multi-Tenant Architecture:** Isolated company workspaces with secure authentication and data partitioning.
* **Team & User Directory (`👥 Team Members`):** Company administrators can invite new colleagues by email, assign specialized departmental roles (Business Analyst, Systems Engineer, Database Administrator, Team Member), and manage workspace access.
* **Operational Task Pipeline (`📋 Workflow Pipeline`):** Real-time Kanban board with instant priority filtering, status transitions (*Backlog*, *In Progress*, *In Review*, *Done*), and live KPI metrics (*Total Tasks*, *In Progress*, *Completed*).
* **Enterprise Audit Logs (`🔍 Audit Logs & Compliance`):** Immutable event tracking recording every tenant registration, user login, invitation, task creation, and status change for compliance governance.
* **Modern Minimalist UI:** Sleek, high-contrast typography, soft surface cards, responsive design, and intuitive tabbed navigation.

---

## Getting Started & Testing

1. Access the live application at [NexusFlow Live Portal](https://vaibhavsingh8395.github.io/nexusflow-workflow-engine/).
2. Log in using the pre-configured enterprise demo tenant credentials:
   * **Company:** Apex Logistics Inc.
   * **Email:** `admin@apexlogistics.com`
   * **Password:** `admin123`
3. Alternatively, click **"Register a new company tenant"** on the company portal screen to initialize your own custom corporate workspace.

---

## Tech Stack
* **Front-End:** Vanilla HTML5, CSS3 (Custom CSS Variables, Grid, Flexbox), ES6+ JavaScript.
* **State Persistence:** Normalized relational schema backed by browser Session/Local Storage.
* **Hosting:** GitHub Pages CI/CD pipeline.

---

## Documentation
* Refer to the [User Manual](USER_MANUAL.md) for detailed operational instructions.
