# C# / .NET Backend Developer (Middle+)

[English](README.md) | [Russian](README.ru.md)

**Open to offers** — in Moscow: remote / hybrid / office / any format. Remotely — open to offers from any region or country. Also considering relocation.

### Summary

Middle+ backend developer with **9+ years** in IT and **5+ years** of commercial .NET development. I specialize in microservices: ASP.NET Core, GraphQL, RabbitMQ, PostgreSQL, Docker. On a Beeline (Amdocs) project, I integrated network-infrastructure data from a legacy Oracle service into a new platform and cut load time by about 2x.

Graduate of **Bauman Moscow State Technical University** (IU3). English — C1.

---

## Skills

- **Languages & platforms:** C#, .NET 8, ASP.NET Core
- **Architecture:** microservices, REST API, GraphQL (HotChocolate), CQRS, Event Sourcing, Clean Architecture, MediatR
- **Data:** PostgreSQL, MS SQL, MongoDB, EF Core
- **Infrastructure:** RabbitMQ, MassTransit, Quartz.NET, Docker, GitLab CI/CD
- **Testing:** xUnit, unit / module tests
- **Other:** Git, Scrum/Agile, PowerShell

---

## Work experience

### .NET Developer — independent work
*June 2025 — present*

Independent C# / .NET products and targeted maintenance. Main projects — User Secrets Manager and BuzzMini — are in [Projects](#projects).

---

### Software Development Specialist — Amdocs / Beeline  
*November 2023 — June 2025 · 1 year 8 months*

- Backend for a Beeline system that tracks network infrastructure, equipment, and connections: feature work, PostgreSQL, GraphQL API (HotChocolate) and EF Core, MediatR, Docker, GitLab CI/CD, unit and integration tests (xUnit).
- Built data integration from a legacy Oracle service into a .NET and PostgreSQL microservice platform. In each integration, data landed in staging tables: in some scenarios I loaded it myself via HttpClient against a Swagger contract in batches of about 10,000 records; in others I worked with data that Beeline had already loaded into the same tables. A Quartz.NET and CQRS handler compared staging with the previous snapshot, assembled internal entities (including when one source entity mapped to several), and published changes to RabbitMQ / MassTransit.
- Improved an already-running production integration: incremental fetch by change date, configurable batch sizes (read 10,000, further processing 1,000), query optimization, and index alignment with Beeline specialists. Load time for related integrations dropped by about 2x — from 30–60 to 15–30 minutes.
- Worked on consumers in adjacent microservices, including DLX handling.
- Delivered IP allocation (including Loopback and P2P between devices) under an incomplete and contradictory spec: gathered old and new requirements, checked the external API docs against actual behavior, added endpoints for the scenarios, and took the feature to production, including getting bugs fixed on the customer's API side.

**Stack:** .NET 6 / ASP.NET Core 8, GraphQL, EF Core, MediatR, RabbitMQ, MassTransit, Quartz.NET, PostgreSQL, Docker, xUnit, GitLab

---

### Developer — Stoloto  
*August 2020 — January 2021 · 6 months*

Backend for a new lottery web service on ASP.NET Core.

- CQRS + Event Sourcing, MediatR
- REST API, pagination, filtering, integrations
- Unit and module tests, legacy refactoring
- JSON Schema validation (Newtonsoft.Json.Schema), documentation generation
- Updates to a WPF terminal client (MVVM)

**Stack:** ASP.NET Core, WPF, MediatR, CQRS, Event Sourcing, EF Core, GitLab, Jira, Confluence

---

### Back-end developer — HSE Art and Design School  
*November 2019 — August 2020 · 10 months*

Designed and built product microservices.

- .NET Core 3.1 and Node.js (Express) services for PDF generation
- MongoDB schema, Docker deploy scripts
- REST API for internal projects, migration from Web Forms to API
- Independently designed service architecture

**Stack:** .NET Core, ASP.NET Core, JavaScript, MongoDB, Docker

---

### Earlier IT experience — Softline, EY, Hostline, Akura Print Shop, and others  
*2013 — 2019*

Systems engineer / helpdesk / junior developer: infrastructure support, automation, and the start of commercial C# / .NET development (Windows Forms, Clean Architecture, PostgreSQL).

<details class="chronology">
<summary>Full timeline — other roles</summary>
<div class="chronology-body">
<p class="chronology-note" hidden>Does not repeat the blocks above (Amdocs, Stoloto, HSE). Newest first.</p>

<div class="job">
<strong>C# Developer — Aytik</strong><br>
<em>October 2022 — May 2023 · 8 months</em>
<p>Backend for a company product promotions service (WCF).</p>
</div>

<div class="job">
<strong>IT Service Delivery Developer — VTB Capital</strong><br>
<em>December 2021 — January 2022 · 2 months</em>
<p>Self-service portal, IT service automation, and first-line support.</p>
<p><strong>Stack:</strong> C#, PowerShell, System Center Service Manager / Orchestrator</p>
</div>

<div class="job">
<strong>Junior Developer — Akura Print Shop</strong><br>
<em>November 2018 — August 2019 · 10 months</em>
<p>Corporate production solution: new features, refactoring, SQL/triggers, Confluence docs, Jira.</p>
<p><strong>Stack:</strong> C#, Windows Forms, Clean Architecture, PostgreSQL</p>
</div>

<div class="job">
<strong>C# WPF Software Engineer — Caspel</strong><br>
<em>October 2018 — November 2018 · 2 months</em>
<p>Feature work, bug fixes, MS SQL and ERP module setup for clients.</p>
</div>

<div class="job">
<strong>Systems Engineer — Softline</strong><br>
<em>June 2016 — August 2017 · 1 year 3 months</em>
<p>Outsourcing at the client (Herbalife): IT projects, networks, security (SEP, PGP), user support, training, software and online cash-register rollout.</p>
</div>

<div class="job">
<strong>IT Help Desk Specialist — EY Russia</strong><br>
<em>September 2014 — May 2016 · 1 year 9 months</em>
<p>IT infrastructure support for an office (~3000 employees): ServiceNow, hardware, networks, accounts.</p>
</div>

<div class="job">
<strong>Technical Support Specialist — Hostline</strong><br>
<em>January 2013 — June 2013 · 6 months</em>
<p>Hosting client support: websites, CMS, domains, servers, billing.</p>
</div>
</div>
</details>

---

## Projects

### [User Secrets Manager](https://github.com/kurskiev-t/UserSecretsManager)  
Visual Studio extension: switch user secrets sections (LOCAL / DEV / PROD) across projects in a solution.

- On [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=kurskiev-t.userSecretsManager) · **200+ downloads**
- Backup / Restore, multilingual sections, open the secrets file from the IDE

### [BuzzMini](https://github.com/kurskiev-t/BuzzMini)  
Local offline push-to-talk dictation on faster-whisper (Windows, NVIDIA CUDA, PyQt6). Audio never leaves the machine.

---

## Education

**Bachelor's** — Bauman Moscow State Technical University, Moscow (2014)  
Faculty of Informatics and Control Systems · Information Systems and Telecommunications (**IU3**)

---

## Contacts

| | |
| --- | --- |
| **Phone** | [+7 (903) 500-57-67](tel:+79035005767) |
| **Telegram** | [@timur_kurskiev](https://t.me/timur_kurskiev) |
| **Email** | [kurskievtr@gmail.com](mailto:kurskievtr@gmail.com) |
| **GitHub** | [github.com/kurskiev-t](https://github.com/kurskiev-t) |
| **City** | Moscow |

---

*PDF resume available on request via the contacts above.*
