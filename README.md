<div align="center">

# Hi, I'm Wanderley 👋

**Backend Python Developer** — building internal enterprise systems, integrations & automation

</div>

---

I design, build and maintain internal software systems that connect ERP, HR, and production data across departments — from unified web portals to automated data pipelines and BI reporting. My work sits at the intersection of **backend engineering**, **systems integration**, and **process automation**.

## 🚀 Featured Project — Portal MBS

A unified internal portal built at **Mobensani**, consolidating over a dozen previously siloed internal systems — HR, training & compliance, recruitment, procurement follow-up, room booking, organizational management, asset/locker control, sample request tracking, driver dispatch, and real-time production monitoring — into a single platform with centralized authentication and a shared data layer.

**Engineering highlights:**

- 🧩 **Multi-app architecture** — independently deployable FastAPI/Flask sub-applications sharing a single PostgreSQL database (organized by schema per business domain), mounted behind a unified gateway with single sign-on across every module.
- 🔐 **Enterprise identity integration** — centralized authentication via LDAP/Active Directory, with per-module, role- and department-based access control.
- 🏭 **ERP/MES integration** — real-time production, quality and cost analytics pulled directly from **SAP Business One / SAP HANA**, including re-engineering legacy reporting-tool queries into optimized, parameterized SQL for a live operational dashboard.
- 📄 **Automated document generation** — server-side PDF generation for compliance and operational records (attendance sheets, reports).
- 🖐️ **Hardware integration** — bridged a legacy Windows biometric SDK into a modern browser-based workflow for enrollment and verification.
- 🔄 **Safe, continuous schema evolution** — version-controlled SQL migrations applied automatically on deploy, enabling frequent iteration without manual DBA steps or downtime.
- ☁️ **Production infrastructure** — deployed behind a secure tunnel with a Git-based deploy flow (commit → push → pull → restart), no exposed public server.

## 🔗 Other Projects (Mobensani)

- **Connect — WhatsApp Customer Service Platform** — real-time messaging system with queue management (open/assigned/closed), department routing, and agent assignment. Built with Python, PostgreSQL, AWS EC2 and Cloudflare Tunnel.
- **Workflow automation (n8n)** — event-driven flows triggered directly from internal systems: approval/rejection notifications, scheduled data exports, and status-change alerts routed to Microsoft Teams and WhatsApp for real-time cross-team visibility.
- **SOC compliance automation** — Playwright/Chromium bot running on EC2 that checks and validates compliance data automatically.
- **WhatsApp expense tracking bot** — n8n pipeline that classifies intent via WhatsApp messages and saves/queries expense records in PostgreSQL, mirrored to Google Sheets.
- **Power BI reporting** — dashboards consuming data from the centralized application database and SAP HANA, giving leadership visibility into production, HR, procurement and carrier delivery KPIs.

## 🛠️ Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-D71F00?style=flat)
![SAP HANA](https://img.shields.io/badge/SAP%20HANA-0FAAFF?style=flat&logo=sap&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![LDAP](https://img.shields.io/badge/LDAP%2FActive%20Directory-0078D4?style=flat&logo=microsoft&logoColor=white)
![AWS EC2](https://img.shields.io/badge/AWS%20EC2-FF9900?style=flat&logo=amazonaws&logoColor=white)

## 📈 GitHub Stats

<div align="center">
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api?username=WanderleyB&show_icons=true&theme=tokyonight&include_all_commits=true&locale=en&cache_seconds=0" />
  &nbsp;&nbsp;&nbsp;
  <img height="165" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=WanderleyB&theme=tokyonight&layout=compact&custom_title=Technologies&langs_count=9" />
</div>

## 📫 Get in touch

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/wanderley-bigosinski)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:zucari94@gmail.com)
