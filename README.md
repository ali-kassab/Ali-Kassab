<!--
  GitHub profile README — github.com/ali-kassab
  Local graphics live in ./assets (pure SVG + CSS, no JavaScript; animations respect prefers-reduced-motion).
  External cards: skillicons.dev, shields.io, github-readme-stats, streak-stats, activity-graph, komarev.
-->

<div align="center">

<img src="./assets/hero.svg" width="100%" alt="Ali Abdelaal Mohamed — Backend Software Engineer · Node.js, NestJS, Express, Java, Spring Boot, ASP.NET Core" />

<br />

<img src="./assets/typing.svg" width="78%" alt="Building REST APIs with Node.js, NestJS and Express · designing multi-tenant SaaS backends · shipping Java / Spring Boot and ASP.NET Core services" />

<p>
  <a href="https://portfolio-alikassab.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=2DD4BF" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/ali-kassab-8428161b8"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:alikassab155@gmail.com"><img src="https://img.shields.io/badge/Email-0F172A?style=for-the-badge&logo=gmail&logoColor=818CF8" alt="Email" /></a>
  <a href="https://wa.me/201010044102"><img src="https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" /></a>
</p>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

## About me

I'm a backend engineer at **DevGlobal LLC** (remote, since 04/2024), where I build **Node.js / Express** services for a multi-tenant SaaS product: REST APIs, JWT and role-based access, Stripe billing and real-time notifications with Socket.IO and SSE.
Outside work I build complete projects in **NestJS**, **Java / Spring Boot** and **ASP.NET Core** to go deeper on architecture, data modelling and testing.

```ts
const ali = {
  role:      "Backend Software Engineer",
  location:  "Giza, Egypt · open to remote",
  daily:     ["Node.js", "TypeScript", "Express", "NestJS"],      // professional, 2.5+ years
  alsoShip:  ["Java", "Spring Boot", "C#", "ASP.NET Core"],       // freelance & project work
  focus:     ["REST API design", "multi-tenancy", "JWT / RBAC", "data modelling", "real-time"],
  practices: ["layered & modular architecture", "validation at every boundary", "automated tests"],
  exploring: ["system design", "Docker & CI/CD", "cloud deployment", "AI-assisted engineering"],
};
```

<img src="./assets/divider.svg" width="100%" alt="" />

## Featured projects

<a href="https://github.com/ali-kassab/crm-platform"><img src="./assets/projects/crm-platform.svg" width="100%" alt="CRM Platform — multi-tenant CRM and field-service SaaS (in progress)" /></a>

A **Spring Boot 4 modular monolith** that rebuilds a legacy JavaScript CRM: customers, work orders, visits, maintenance, finance, subscriptions and a platform-admin console. Fail-closed tenant isolation, JWT / RBAC, an append-only audit log, Arabic / English PDF reports and a **NestJS + Socket.IO** real-time service over Redis. Tested with JUnit, Testcontainers and Playwright.

<a href="https://github.com/ali-kassab/tradeflow"><img src="./assets/projects/tradeflow.svg" width="100%" alt="TradeFlow — bilingual B2B wholesale management (MVP)" /></a>

Wholesale trade from stock to statement, in **Arabic (RTL)** or **English (LTR)**: products and a stock ledger, customers and suppliers, sales and purchase orders, payments, statements and reports. A **NestJS** modular monolith on **SQL Server** via Prisma, with tenant isolation enforced by composite foreign keys, rotating hashed refresh tokens with replay detection, Owner / Manager / Staff roles and GitHub Actions CI.

<a href="https://github.com/ali-kassab/notification-service"><img src="./assets/projects/notification-service.svg" width="100%" alt="Notification Service — self-hostable notifications as a service" /></a>

A REST API and **TypeScript SDK** that store notifications in PostgreSQL and push them over **Socket.IO**, with acknowledged delivery, per-user inboxes that survive going offline, SHA-256-hashed API keys, scoped short-lived user tokens and a React dashboard. Tested with Jest and Supertest against a real database.

<a href="https://github.com/ali-kassab/banking-operations-system"><img src="./assets/projects/banking-operations-system.svg" width="100%" alt="Banking Operations System — bank back-office on ASP.NET Core and Angular" /></a>

A bank back-office: customers, accounts, deposits, withdrawals, **atomic transfers** in an explicit transaction and per-account history. A layered **ASP.NET Core** Web API with EF Core, SQL Server and JWT (Admin / Employee roles), an **Angular** client and financial rules covered by xUnit tests.

<a href="https://github.com/ali-kassab/True-Social"><img src="./assets/projects/true-social.svg" width="100%" alt="True Social — social network REST API on Spring Boot" /></a>

A social network REST API: posts, comments, likes, follows, a personalised feed, saved posts, blocking and notifications. Stateless JWT with owner-or-admin authorization, DTO validation, RFC 7807 errors and no N+1 queries on paginated lists; unit and integration tests with JUnit 5, Mockito and MockMvc.

<details>
<summary><b>Earlier work</b> (private repositories)</summary>
<br />

| Project | Description |
|---|---|
| **Java Spring Posts System** | RESTful API with Spring Boot, JWT authentication, layered architecture and role-based access control |
| **Java Spring Blog System** | Posts and comments with validation, global exception handling and a clean layered architecture |
| **Node.js Real-Time Notifications** | Socket.IO and SSE for real-time notifications and messaging |
| **Stripe Payment Integration** | Node.js backend integrating Stripe for secure payment processing |
| **Twilio SMS/Call Automation** | Node.js service using the Twilio API for automated SMS and call workflows |

</details>

<img src="./assets/divider.svg" width="100%" alt="" />

## Tech stack

| | |
|:--|:--|
| **Languages** | <img src="https://skillicons.dev/icons?i=ts,js,java,cs&theme=dark" height="40" alt="TypeScript, JavaScript, Java, C#" /> |
| **Backend** | <img src="https://skillicons.dev/icons?i=nodejs,express,nestjs,spring,dotnet&theme=dark" height="40" alt="Node.js, Express, NestJS, Spring Boot, .NET" /> |
| **Data** | <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,prisma&theme=dark" height="40" alt="PostgreSQL, MySQL, MongoDB, Redis, Prisma" /> <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" /> |
| **DevOps & tooling** | <img src="https://skillicons.dev/icons?i=docker,githubactions,aws,linux,git,postman&theme=dark" height="40" alt="Docker, GitHub Actions, AWS, Linux, Git, Postman" /> |
| **Frontend** <sub>(supporting)</sub> | <img src="https://skillicons.dev/icons?i=react,nextjs,angular,tailwind&theme=dark" height="40" alt="React, Next.js, Angular, Tailwind CSS" /> |

**Depth, honestly:** Node.js / Express / NestJS professionally · Java / Spring Boot in freelance and project work · C# / ASP.NET Core in project work.

**Also worked with:** `Spring Security` `Spring Data JPA` `Hibernate` `EF Core` `OpenAPI / Swagger` `Socket.IO` `SSE` `Stripe` `Twilio` `JUnit 5` `Mockito` `Testcontainers` `Jest` `xUnit` `Playwright`
**Ops exposure:** `Kubernetes` `Terraform` `Prometheus` `Grafana` `Loki` · incident handling and root-cause analysis in application support

<img src="./assets/divider.svg" width="100%" alt="" />

## GitHub activity

<div align="center">

<a href="https://github.com/ali-kassab?tab=repositories"><img height="170" src="https://github-readme-stats.vercel.app/api?username=ali-kassab&show_icons=true&count_private=true&include_all_commits=true&hide_rank=true&hide_border=true&border_radius=16&bg_color=0F172A&title_color=2DD4BF&icon_color=818CF8&text_color=CBD5E1" alt="GitHub stats for ali-kassab" /></a>
<a href="https://github.com/ali-kassab?tab=repositories"><img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ali-kassab&layout=compact&langs_count=6&hide=html,css,scss&hide_border=true&border_radius=16&bg_color=0F172A&title_color=2DD4BF&text_color=CBD5E1" alt="Most used languages in public repositories" /></a>

<img src="https://streak-stats.demolab.com/?user=ali-kassab&hide_border=true&border_radius=16&background=0F172A&ring=2DD4BF&fire=818CF8&currStreakLabel=2DD4BF&sideLabels=CBD5E1&currStreakNum=F8FAFC&sideNums=F8FAFC&dates=94A3B8&stroke=1E293B" width="70%" alt="Contribution streak" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=ali-kassab&bg_color=0F172A&color=94A3B8&line=2DD4BF&point=818CF8&area=true&area_color=2DD4BF&hide_border=true&radius=16&title_color=F8FAFC" width="100%" alt="Contribution activity graph" />

<sub>Cards are served by third-party services and count public activity. If one doesn't load, browse my <a href="https://github.com/ali-kassab?tab=repositories">repositories</a> directly.</sub>

</div>

<img src="./assets/divider.svg" width="100%" alt="" />

<div align="center">

**Let's talk backend.** I'm happy to discuss roles, APIs or architecture — reach me on [LinkedIn](https://www.linkedin.com/in/ali-kassab-8428161b8), by [email](mailto:alikassab155@gmail.com) or through my [portfolio](https://portfolio-alikassab.vercel.app/).

<img src="./assets/footer.svg" width="100%" alt="Thanks for stopping by — let's build reliable backends." />

<img src="https://komarev.com/ghpvc/?username=ali-kassab&color=2DD4BF&style=flat-square&label=profile+views" alt="Profile views" />

</div>
