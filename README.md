# Hi, I'm Hussein 👋

**Senior Fibre Maintenance Engineer at Earthlink Telecom, Baghdad** · I automate network operations with Python.

I've spent almost six years keeping fibre networks running, from leading field technicians on Iraq's first FTTH site to monitoring backbone, metro and FTTH networks end to end. Along the way I started writing Python to take repetitive work off my team's plate, and that is now a large part of my job: API integrations, data pipelines and scheduled automations that turn raw network data into reports people act on.

For larger internal web tools I use AI-assisted development: I define the problem, direct the build, review the code and ship it. I keep that separate from what I write and maintain myself, and mark it with **†** below.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat&logo=flask&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)

---

## What I build at work

Most of my work lives in private company repositories, so here is what it does rather than the code itself.

- **Fibre monitoring rollout:** planned, deployed and maintained VIAVI ONMSi fibre monitoring across backbone, metro and FTTH networks down to end users, then trained the whole department to use it.
- **Vendor API clients:** REST clients for Microsoft Graph, VIAVI ONMSi, Grafana and Creatio, with token handling, retries, timeouts and workarounds for vendor pagination quirks.
- **OTDR and readiness pipelines:** process OTDR test events and landmarks, resolve spans and links, classify readiness and send daily reports with escalation.
- **SharePoint ↔ PostgreSQL sync:** app-only OAuth against Microsoft Graph, `$batch` requests and delta sync to keep SharePoint Lists and PostgreSQL in step.
- **Power equipment polling:** SNMP polling of rectifiers and other site power equipment.
- **Scheduled automation:** around 30 cron jobs on live Ubuntu hosts, alerting through email, Microsoft Teams and Telegram.
- **Operational dashboards:** Grafana over Python-fed PostgreSQL for task management, labour cost and fibre-cut tracking.
- **Readiness web application †:** a Dockerised Flask and PostgreSQL web application for network readiness.

## Public projects

<!-- Replace YOUR-USERNAME and the repo names with your real ones. Delete any row whose repo isn't public yet. -->

| Project | What it does | Stack |
|---|---|---|
| [OpenFiberOps](https://github.com/hussein-sameer/OpenFiberOps) 🚧 | Fiber-network incident tracking API with SLA metrics, on synthetic data, to mock my private repos work without compromising company data | Python · PostgreSQL · Docker |
| [IoT MQTT Platform](https://github.com/hussein-sameer/iot-mqtt-platform) | Self-hosted IoT platform for ESP8266 edge devices, using MQTT for low-power, low-bandwidth messaging and Node-RED for orchestration | C++ (Arduino) · Node-RED · MySQL |
| [CV Builder](https://github.com/hussein-sameer/cv-builder) † | Cloud-hosted on Northflank Cloud Platform, ATS-friendly CV generator with International/EU formatting options: DOCX and text-based PDF export with new AI export idea without API, AI-drafted summaries, multi-user accounts | Python, FastAPI, PostgreSQL, Docker |

## Toolbox

Things I can read, debug and explain without help:

| Area | Tools |
|---|---|
| Languages | Python, SQL (PostgreSQL), Bash, VBA |
| Automation | cron, Flask endpoints that trigger scripts, Selenium, Google Sheets API (gspread) |
| Integrations | REST APIs, Microsoft Graph / SharePoint Lists, SNMP (pysnmp), Postman |
| Data and reporting | PostgreSQL, Grafana, DBeaver |
| Alerting | SMTP email, Microsoft Teams webhooks, Telegram bots |
| Infrastructure | Ubuntu VM administration |
| Low-code | Power Apps, Power Automate, Power BI, SharePoint |

## Background

- **Fibre and telecom:** OTDR, optical loss budgets, FTTH deployment and operations, fibre-cut and power ticket lifecycles, site power (rectifiers, inverters, batteries, solar)
- **Education:** B.Sc. Electronics and Communications Engineering, Al-Nahrain University, first in class
- **Teaching:** Teaching Assistant at Al-Nahrain University (2023–2025) for programming (C++, Assembly, MATLAB), telecom and electronics labs

## Right now

- 🔭 Building a public internet-outage data pipeline
- 🎯 Open to roles in network automation, Python, AI Developer, and data engineering

## Get in touch

<!-- Replace the two links below. -->
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hussein-sameer)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:husseinsamirh@gmail.com)

---

<sub>† Delivered through AI-assisted development: I set the requirements, directed the build, reviewed the code and shipped it.</sub>
