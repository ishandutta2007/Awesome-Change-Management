# Awesome-Change-Management
<<<<<<< HEAD

=======
>>>>>>> 7c2fc0b7cf2d79dd5cfa1702b3f85bea76de7ec1
## Top Change Management Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on ITIL Change Enablement, Risk Assessment & Release Governance*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Change Management**. These tools enable IT teams to plan, assess, approve, and implement changes to production systems with controlled risk—minimizing service disruption while enabling continuous improvement and rapid delivery.



**Examples** include ServiceNow Change Management, Jira Service Management, BMC Helix Remedyforce, Freshservice, Ivanti Neurons, ManageEngine ServiceDesk Plus, SolarWinds Service Desk, SysAid, Cherwell, and Alloy Software (the category leaders).



**Open-source emphasis**: This section is expanded with active projects for self-hosted ITIL change workflows, approval automation, and CMDB-linked change planning—ideal for organizations building sovereign change management infrastructure without per-agent licensing lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[ServiceNow Change Management](https://www.servicenow.com/)**  

  Enterprise change enablement on the Now Platform with ITIL-aligned Change Types (Standard, Normal, Emergency) for risk and approval governance, and Change Models for customizable workflows per change context (network, application, server) ; integrates with CMDB for impact analysis and supports CAB approval automation.



- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  

  Change management within Atlassian's ITSM platform with a visual Change Calendar for scheduling and conflict avoidance, maintenance and freeze windows, and workflow approvals; integrates with Jira Software for developer-driven changes .



- **[BMC Helix Remedyforce](https://www.bmc.com/)**  

  Change management with defined roles (CAB member, Change Coordinator, Change Manager), queues, categories, and templates; supports the full lifecycle from risk and impact assessment through approval and closure, with CMDB linkage for configuration item changes .



- **[Freshservice](https://www.freshworks.com/freshservice/)**  

  Change Lifecycle feature for controlling step-by-step transitions with enforced conditions (tasks complete, approvals obtained, mandatory fields); supports Standard, Minor, Major, and Emergency change types with configurable statuses and transitions .



- **[Ivanti Neurons](https://www.ivanti.com/)**  

  ITIL-based change workflows with CAB management and change impact analysis; supports team-based assignment through customization of the OwnerTeam field on the Change Request business object .



- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/products/service-desk/)**  

  ITIL-aligned change management with customizable change templates, Change Roles and CAB configuration, drag-and-drop visual workflows spanning eight stages, Zia Change Risk Prediction trained on historical data, and Change Calendar with freeze/maintenance windows .



- **[SolarWinds Service Desk](https://www.solarwinds.com/service-desk)**  

  Change Catalog Items for reusable templates (plan, rollback plan, test plan), CMDB-linked risk assessment, configurable workflow approvals and tasks, and audit trail from request through post-implementation review .



- **[SysAid](https://www.sysaid.com/)**  

  Policy-driven change management with pre-configured request templates, no-code workflow builder, CMDB integration for impact visibility, CAB coordination with auto-notifications, SLA timers, and audit-ready documentation .



- **[Cherwell](https://www.cherwell.com/)**  

  Change Management mApp Solution providing streamlined Change Request form, ITIL-aligned lifecycle, advanced risk assessment, updated Approvals, and a Change Management Dashboard; introduces Change Model Business Object for reusable change patterns .



- **[Alloy Software](https://www.alloysoftware.com/)**  

  Change Tracking within AlloyScan for detecting configuration changes across devices (hardware, software, security settings, user accounts, cloud assets); provides per-device change history and site-scope change logs with before/after values and configurable retention .



## Open-Source GitHub Projects



- **[Audita](https://hub.docker.com/r/skylarng89/audita-api)**  

  Open-source, self-hosted, multi-tenant ITIL/ITSM Change Management platform (Apache 2.0); provides structured, auditable change workflows across creation, approvals, collaboration, SLA tracking, and immutable audit trails with schema-per-tenant data isolation; Docker-deployable via `skylarng89/audita-api` .



- **[GLPI](https://github.com/glpi-project/glpi)**  

  Complete open-source IT service management platform (GPL) with ITIL-compliant Change Management; changes can be created from tickets or problems, linked to impacted items, and managed through analysis (impacts/checklist), plans (deployment/backup), approvals, costs, and projects; includes Impact Analysis for visualizing infrastructure dependencies and a full history/audit trail .



- **[iTop](https://github.com/Combodo/iTop)**  

  Complete open-source web-based ITSM platform with fully configurable CMDB, helpdesk, and document management; includes ITIL-compliant Change Management as a core feature with graphical impact analysis and CSV import/synchronization tools .



- **[OTRS/Znuny (ITSM)](https://github.com/znuny/Znuny)**  

  Open-source ITIL-compliant ITSM solution with Change Management module; supports Change Builder and Change Manager roles, CAB templates, category/impact/priority matrix for suggested priority, state machine for valid state transitions, and work order management linked to changes .



### Additional Strong Open-Source Options



- **Audita API** — The backend service for Audita, providing a REST API for multi-tenant change management with SLA tracking and immutable audit trails .

- **GLPI Recurrent Changes** — Feature within GLPI for scheduling periodic changes (e.g., weekly patch verification) with automatic creation based on configured periodicity .



**Frameworks for building custom systems**: Combine **GLPI** for full ITIL change management with CMDB impact analysis and approval workflows, **Audita** for multi-tenant change management with immutable audit trails, and **iTop** for CMDB-centric change planning in a self-hosted change management stack; integrate with existing ticketing and deployment pipelines for end-to-end governance.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Change management platforms handling production access and deployment approvals must comply with applicable security policies and regulatory requirements (SOX, ISO 27001, PCI DSS); segregation of duties and audit trails are critical.

- Self-hosted open-source solutions vary in scope—GLPI and iTop provide mature ITIL change management with CMDB integration, while Audita focuses on auditable change workflows; full enterprise change enablement with risk prediction and automated CAB orchestration typically requires commercial platforms.

- Verify license terms for commercial use; GLPI uses GPL, iTop is open-source, Znuny uses GPL-3.0, and Audita uses Apache 2.0 .



---



**Made for change managers, release managers, CAB members, and IT service management teams.**  

Let's make change management more open, risk-aware, and audit-ready.
