<!-- Profile README for github.com/ali-kassab. Local assets live in ./assets (SVG, no JavaScript). -->

<div align="center">

<img src="./assets/header.svg" width="100%" alt="Ali Abdelaal Mohamed — Backend Software Engineer (Node.js, NestJS, Java, Spring Boot)" />

<img src="./assets/typing.svg" width="80%" alt="Building REST APIs with Node.js, NestJS and Express · Designing multi-tenant SaaS backends · Shipping Java and Spring Boot services" />

<p>
  <a href="https://portfolio-alikassab.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0B1020?style=for-the-badge&logo=vercel&logoColor=22D3EE" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ali-kassab-8428161b8"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:alikassab155@gmail.com"><img src="https://img.shields.io/badge/Email-0B1020?style=for-the-badge&logo=gmail&logoColor=8B5CF6" alt="Email" /></a>
  <a href="https://wa.me/201010044102"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
</p>

<sub>📍 Giza, Egypt &nbsp;·&nbsp; Open to backend engineering roles</sub>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## About me

I'm a **Software Engineer** at **DevGlobal LLC** (remote, since 04/2024), where I build **Node.js / Express** backend services for a multi-tenant SaaS product. Outside work I build complete projects in **NestJS**, **Java / Spring Boot** and **ASP.NET Core** to go deeper on architecture, data modelling and testing.

- 🧱 **What I focus on:** REST API design, authentication and role-based access (JWT, RBAC), multi-tenant data isolation, relational data modelling, real-time features
- 🧪 **How I work:** layered or modular architecture, validation at every boundary, consistent error responses, automated unit and integration tests
- 🌱 **Currently deepening:** backend architecture and system design, Docker and CI/CD, cloud deployment
- 🤖 **Interested in:** AI-assisted engineering and modern developer tooling

<img src="./assets/divider.svg" width="100%" alt="" />

## Featured projects

### 🛠️ [CRM Platform](https://github.com/ali-kassab/crm-platform) &nbsp;<sub>`in progress`</sub>
Multi-tenant field-service and operations SaaS: customers, work orders, visits, equipment and preventive maintenance, finance, subscriptions and a platform-admin console. A **Spring Boot 4** modular monolith with fail-closed tenant isolation, JWT/RBAC, an append-only audit log, Arabic/English PDF reports and a **NestJS + Socket.IO** real-time service over Redis. Backend tests use JUnit and Testcontainers; browser tests use Playwright.

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_4-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

### 📦 [TradeFlow](https://github.com/ali-kassab/tradeflow) &nbsp;<sub>`MVP`</sub>
Bilingual (Arabic RTL / English LTR) B2B wholesale management: products and stock ledger, customers and suppliers, sales and purchase orders, payments, ledger-style statements and reports. A **NestJS** modular monolith on **SQL Server** via Prisma, with tenant isolation enforced by composite foreign keys, rotating refresh tokens and Owner / Manager / Staff roles.

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)

### 🔔 [Notification Service](https://github.com/ali-kassab/notification-service)
Self-hostable "notification as a service": a REST API and TypeScript SDK to send notifications that are stored in PostgreSQL and pushed over Socket.IO, with acknowledged delivery, per-user inboxes, hashed API keys, scoped user tokens and a React dashboard. Tested with Jest and Supertest against a real database.

![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)

### 🏦 [Banking Operations System](https://github.com/ali-kassab/banking-operations-system)
Bank back-office: customers, accounts, deposits, withdrawals, atomic transfers in an explicit transaction, optimistic concurrency on balances, and JWT with Admin / Employee roles. A layered **ASP.NET Core** Web API with an **Angular** client, unit-tested with xUnit.

![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![EF Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat-square&logo=angular&logoColor=white)

### 🌐 [True Social](https://github.com/ali-kassab/True-Social)
Social network REST API: posts, comments, likes, follows, a personalised feed, saved posts, blocking and notifications. Stateless JWT with owner-or-admin authorization, DTO validation, RFC 7807 errors and no N+1 queries on paginated lists; unit and integration tests with JUnit 5, Mockito and MockMvc.

![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

<details>
<summary><b>Earlier work</b> (not public)</summary>
<br />

| Project | Description |
|---|---|
| **Java Spring Posts System** | RESTful API with Spring Boot, JWT authentication, layered architecture and role-based access control |
| **Java Spring Blog System** | Posts and comments with validation, global exception handling and a clean layered architecture |
| **Node.js Real-Time Notifications** | Socket.io and SSE for real-time notifications and messaging |
| **Stripe Payment Integration** | Node.js backend integrating Stripe for secure payment processing |
| **Twilio SMS/Call Automation** | Node.js service using the Twilio API for automated SMS and call workflows |

</details>

<img src="./assets/divider.svg" width="100%" alt="" />

## Tech stack

| | |
|:--|:--|
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,ts,nestjs,express,java,spring,cs,dotnet&theme=dark" height="40" alt="Node.js, TypeScript, NestJS, Express, Java, Spring Boot, C#, .NET" /> |
| **Data** | <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,prisma&theme=dark" height="40" alt="PostgreSQL, MySQL, MongoDB, Redis, Prisma" /> &nbsp;+ SQL Server |
| **DevOps & tooling** | <img src="https://skillicons.dev/icons?i=docker,githubactions,aws,linux,git,postman&theme=dark" height="40" alt="Docker, GitHub Actions, AWS, Linux, Git, Postman" /> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,angular,nextjs,tailwind,vite&theme=dark" height="40" alt="React, Angular, Next.js, Tailwind CSS, Vite" /> |
| **Testing** | JUnit 5 · Mockito · Testcontainers · Jest · xUnit · Playwright |
| **Practices** | REST · JWT & RBAC · multi-tenancy · modular monolith · SOLID · design patterns |

<img src="./assets/divider.svg" width="100%" alt="" />

## GitHub activity

<div align="center">

<a href="https://github.com/ali-kassab?tab=repositories"><img height="165" src="https://github-readme-stats.vercel.app/api?username=ali-kassab&show_icons=true&hide_border=true&border_radius=14&bg_color=0B1020&title_color=22D3EE&icon_color=8B5CF6&text_color=CBD5E1&ring_color=22D3EE" alt="Ali's GitHub stats" /></a>
<a href="https://github.com/ali-kassab?tab=repositories"><img height="165" src="https://streak-stats.demolab.com/?user=ali-kassab&hide_border=true&border_radius=14&background=0B1020&ring=22D3EE&fire=8B5CF6&currStreakLabel=22D3EE&sideLabels=CBD5E1&currStreakNum=F8FAFC&sideNums=F8FAFC&dates=94A3B8&stroke=1E293B" alt="Contribution streak" /></a>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=ali-kassab&bg_color=0B1020&color=CBD5E1&line=22D3EE&point=8B5CF6&area=true&area_color=22D3EE&hide_border=true&radius=14&title_color=F8FAFC" alt="Contribution activity graph" />

<sub>Stats count public activity only. If a card does not load, see my <a href="https://github.com/ali-kassab?tab=repositories">repositories</a> directly.</sub>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">

**Let's talk backend.** I'm happy to discuss roles, APIs or architecture — reach me on [LinkedIn](https://www.linkedin.com/in/ali-kassab-8428161b8) or by [email](mailto:alikassab155@gmail.com).

<img src="https://komarev.com/ghpvc/?username=ali-kassab&color=22D3EE&style=flat-square&label=profile+views" alt="Profile views" />

</div>
