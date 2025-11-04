<p align="center">
  <img src="https://raw.githubusercontent.com/JatinSaini09/JatinSaini09/main/banner-n8n.webp"
       alt="Jatin Saini GitHub Banner" width="100%" />
</p>

<h1 align="center">Jatin Saini — Ops × Automation Architect</h1>
<p align="center">
I design invisible systems that scale — workflows, data pipes, bots, and guardrails that make teams faster.<br/>
📍 Bangalore, India · 💌 <a href="mailto:jatinsaini1019@gmail.com">jatinsaini1019@gmail.com</a> · 
<a href="https://www.linkedin.com/in/jatinsaini09/">LinkedIn</a>
</p>

---

## TL;DR (signal, not noise)

- Scaled **EmpowerHer** & **MasaiOne** to **4,700+ learners** with structured GTM, webinars, and creator partnerships  
- Funnel upgrades delivered **+30% conversion** and **−70% ops errors** through CRM + workflow redesign  
- Built **50+ automations** using **n8n**, **Apps Script**, and **API integrations** across Slack/WhatsApp  
- Cut SLA breaches by **60%**; support TAT improved **50%** with SOPs, escalation trees, and dashboards  
- **Emerging Leader 2025** for high-leverage ops + automation delivery  

> I ship flows, not slides. Daily drivers → `n8n` · `Google Apps Script` · `Python` · `Node.js` · `APIs` · `Metabase` · `Data Studio`

---

## Systems Map (how I think & build)

```mermaid
flowchart LR
  subgraph Intake
    A[Leads & Forms] -->|Webhook/API| B[CRM]
    C[Inbound DMs] -->|Keywords| B
  end

  subgraph Automation
    B --> D[n8n Orchestrator]
    D --> E[Apps Script Jobs]
    D --> F[Slack/WhatsApp Bots]
    D --> G[Email/SMS]
  end

  subgraph Data
    E --> H[Google Sheets]
    D --> H
    H --> I[Metabase Dashboards]
  end

  subgraph Governance
    D -.-> J[SOPs & Escalations]
    H -.-> K[KPIs & SLA Alerts]
  end

  I --> L[Decisions · Experiments · Growth]
