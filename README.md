# Enterprise IT Service Management & Fulfillment Lab (ServiceNow)

## Overview
Hands-on laboratory simulation demonstrating end-to-end ITIL service operations, incident management, catalog request fulfillment, and KPI governance within an enterprise ServiceNow instance.

---

## Technical Workflows Executed

### 1. Incident Management (`INC0010004`)
* **Incident Scope:** VPN access failure impacting remote personnel connectivity.
* **Resolution Steps:** Conducted triage, verified network routing policies, and confirmed credential handshake stability.
* **Outcome:** Successfully transitioned record to **Resolved** status adhering to operational SLA guidelines.

### 2. Service Catalog Fulfillment (`REQ0010002` / `RITM0010002`)
* **Request Item:** Provisioning a **Developer Laptop (Mac)** with Eclipse IDE.
* **Catalog Task Execution (`SCTASK0010001`):** Completed asset inventory tagging, OS base image staging, and software package installation.
* **Lifecycle Completion:** Closed fulfillment task as **Closed Complete**, driving the parent Requested Item (`RITM0010002`) to **Closed Complete**.

### 3. Operational Governance & Backlog Monitoring
* Validated system queues via the **Shared Admin Dashboard**.
* Confirmed clear queues with **0** open P1 incidents, **0** aging incidents, and **0** overdue request items.

---

## Evidence Artifacts

### Request Fulfillment Closure
![RITM0010002 Closed Complete](assets/Screenshot%202026-10-08%20004933.jpg)

### Queue Governance & Cleared Backlog
![Admin Home Dashboard](assets/Screenshot%202026-10-08%20005736.jpg)

---

## Key Competencies Demonstrated
* ITIL Foundation Service Lifecycle (Incident, Request Fulfillment, Task Orchestration)
* Record State Transitions & Audit Integrity
* ServiceNow Next Experience Navigation & Operational Dashboarding
