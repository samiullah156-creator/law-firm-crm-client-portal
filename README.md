<!-- styled:v2 -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1d1726,50:167dfe,100:9533fa&height=180&section=header&text=Law%20Firm%20CRM%20%26%20Client%20Portal&fontSize=38&fontColor=ffffff&fontAlignY=36&desc=Case%20study%20%E2%80%A2%20Legal%20%E2%80%A2%20Custom%20CRM%20and%20client%20portal&descAlignY=58&descSize=16&animation=fadeIn" width="100%" alt="Law Firm CRM & Client Portal" />

**A custom CRM built around a law firm's intake and case process, with a branded portal where clients track their case and upload documents.**

<p>
  <img src="https://img.shields.io/badge/Legal-167dfe?style=flat-square" alt="Legal" />
  <img src="https://img.shields.io/badge/Custom%20CRM%20and%20client%20portal-9533fa?style=flat-square" alt="Custom CRM and client portal" />
  <img src="https://img.shields.io/badge/React-231f20?style=flat-square" alt="React" />
  <img src="https://img.shields.io/badge/Node.js-231f20?style=flat-square" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-231f20?style=flat-square" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/n8n-231f20?style=flat-square" alt="n8n" />
  <img src="https://img.shields.io/badge/OpenAI-231f20?style=flat-square" alt="OpenAI" />
  <img src="https://img.shields.io/badge/REST%20API-231f20?style=flat-square" alt="REST API" />
</p>

<p>
  <a href="#overview">Overview</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#key-features">Key features</a> ·
  <a href="#results">Results</a> ·
  <a href="#screens">Screens</a> ·
  <a href="#tech-stack">Tech stack</a>
</p>

</div>

---

![Law firm CRM matter timeline with client portal preview](assets/cover.webp)

## Overview

Off-the-shelf CRMs did not match the firm's intake and case process. We built a custom-coded CRM and client portal around how the firm works: lead capture from the website and calls, custom intake pipeline stages, case records with secure document upload, a timeline of every call, document and update, and a portal where clients see their case stage, upload documents and message their attorney. Automated email and SMS reminders and reports reduce manual follow-up.

## The challenge

Generic CRMs forced the team to work around the software, and clients had no simple way to check their case or send documents.

## The solution

A React and Node.js CRM on PostgreSQL with custom pipeline stages, matter timelines and tasks, secure document upload, a branded client portal and n8n automations for reminders and reports.

## How it works

```mermaid
flowchart LR
    A(["Every matter in<br/>one list"]) --> B
    B["A full timeline<br/>per case"] --> C
    C["Open tasks with<br/>due dates"] --> D
    D(["The client portal"])

    classDef box fill:#1d1726,stroke:#167dfe,color:#e5e7eb
    classDef ends fill:#2e1065,stroke:#9533fa,color:#ffffff
    class B,C box
    class A,D ends
```

1. **Every matter in one list.** Matters are listed with their practice area and current stage, so the team sees the whole caseload at a glance.
2. **A full timeline per case.** Calls with AI summaries, uploaded documents, status updates and signed agreements appear in order.
3. **Open tasks with due dates.** Each matter has its own task list, with overdue items highlighted for the team.
4. **The client portal.** Clients see their case stage, upload requested documents, check appointments and message their attorney.

## Key features

- Lead capture from the website and calls
- Custom intake pipeline stages
- Case records with secure document upload
- Client portal for case status and messages
- Automated email and SMS reminders and reports

## Results

- One system that fits how the firm works
- Clients track their case without calling
- Less manual follow-up for the team

## Tech stack

![React](https://img.shields.io/badge/React-1d1726?style=for-the-badge) ![Node.js](https://img.shields.io/badge/Node.js-1d1726?style=for-the-badge) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-1d1726?style=for-the-badge) ![n8n](https://img.shields.io/badge/n8n-1d1726?style=for-the-badge) ![OpenAI](https://img.shields.io/badge/OpenAI-1d1726?style=for-the-badge) ![REST API](https://img.shields.io/badge/REST%20API-1d1726?style=for-the-badge)

## Screens

![How Law Firm CRM & Client Portal works: Website and call leads, Intake pipeline, Matter record and documents, Client portal, Reminders and reports](assets/screen-1.webp)

![Law Firm CRM & Client Portal: before and after](assets/screen-2.webp)

## Privacy

Client names and records are confidential. Every screen in this repository uses sample data, and source code that belongs to the client is not published.

## Links

- Case study on Lexvaxa: https://lexvaxa.com/work/law-firm-crm-client-portal

---

<div align="center">

**Built by [Ch Muhammad Samiullah](https://github.com/samiullah156-creator)** · AI Automation Engineer and Full-Stack Developer at [Lexvaxa](https://lexvaxa.com)

<a href="https://github.com/samiullah156-creator"><img src="https://img.shields.io/badge/More%20projects-181717?style=for-the-badge&logo=github&logoColor=white" alt="More projects" /></a>
<a href="https://lexvaxa.com/contact"><img src="https://img.shields.io/badge/Work%20with%20me-167dfe?style=for-the-badge&logo=googlecalendar&logoColor=white" alt="Work with me" /></a>
<a href="https://www.linkedin.com/in/sami-lexvaxa/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

<sub>⭐ Star this repo if you found it useful</sub>

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:9533fa,50:167dfe,100:1d1726&height=110&section=footer" width="100%" alt="" />
