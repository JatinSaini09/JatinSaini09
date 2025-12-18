<p align="center">
  <img src="https://raw.githubusercontent.com/JatinSaini09/JatinSaini09/main/banner-n8n.webp"
       alt="Jatin Saini GitHub Banner" width="100%" />
</p>

<h1 align="center">Jatin Saini</h1>
<h3 align="center">Operations × Automation Architect</h3>

<p align="center">
I build <b>quiet systems</b> that remove friction — automations, workflows, and data pipelines that help teams move faster with fewer mistakes.<br/>
📍 Bangalore, India · 💌 <a href="mailto:jatinsaini1019@gmail.com">jatinsaini1019@gmail.com</a> ·
<a href="https://www.linkedin.com/in/jatinsaini09/">LinkedIn</a>
</p>

---

## Recruiter Snapshot

- **4+ years** in Operations, Growth Ops, and Automation (EdTech & Scale-ups)
- Scaled programs to **4,700+ learners** via GTM strategy, webinars, and partnerships
- Delivered **+30% funnel conversion** and **−70% operational errors** through CRM & workflow redesign
- Built **50+ production-grade automations** using **n8n**, **Google Apps Script**, and APIs
- Reduced SLA breaches by **60%**; improved support TAT by **50%**
- Recognized as **Emerging Leader 2025** for high-impact operations execution

> Strong executor with systems thinking and cross-functional ownership.

---

## My Operating Stack

**Automation & Orchestration**  
`n8n` · `Google Apps Script` · `Webhooks` · `Zapier (selective)`

**Backend & Logic**  
`Python` · `Node.js` · `REST APIs`

**Data & Visibility**  
`Google Sheets` · `Metabase` · `Looker Studio`

**Comms & Execution**  
`Slack` · `WhatsApp APIs` · `Email / SMS`

---

## How I Design Systems

```mermaid
flowchart LR
  subgraph Intake
    A[Leads & Forms] -->|Webhook/API| B[CRM]
    C[Inbound DMs] -->|Keyword Routing| B
  end

  subgraph Automation Layer
    B --> D[n8n Orchestrator]
    D --> E[Apps Script Jobs]
    D --> F[Slack / WhatsApp Bots]
    D --> G[Email / SMS]
  end

  subgraph Data Layer
    E --> H[Google Sheets]
    D --> H
    H --> I[Metabase / Looker Dashboards]
  end

  subgraph Governance
    D -.-> J[SOPs & Escalation Trees]
    H -.-> K[KPIs · SLA Alerts]
  end

  I --> L[Decisions · Experiments · Growth]
