<h1 align="center">Albert Llica</h1>

<p align="center">
  <b>Software Engineer</b> &middot; Fullstack &middot; Cloud &amp; Data<br>
  I design and operate complete systems: from the domain model to the domain in production.
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/Español-switch-30363d?style=for-the-badge" alt="Leer en español"></a>
  <a href="./README.en.md"><img src="https://img.shields.io/badge/English-active-1f6feb?style=for-the-badge" alt="Read in English"></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/albert-llica-alvarez"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:albertllica@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/AlbertLlica?tab=repositories"><img src="https://img.shields.io/badge/Repos-43-181717?style=flat-square&logo=github&logoColor=white" alt="Repositories"></a>
</p>

---

## About me

Software engineer focused on **backend architecture**, **cloud infrastructure** and **product**.
I work end-to-end: I design the domain, implement the API, build the UI and own the deployment,
TLS, backups and the operations runbook.

- 🏗️ I build and operate **TRIADE**, an ERP for a construction company, in production on its own domain.
- 🏛️ I contribute to **Olympus**, a corporate ERP on **.NET 8 / SQL Server** with a layered architecture.
- 🔗 I build and operate **LinkU**, a web platform on **FastAPI + Celery + PostgreSQL**.
- ☁️ I design **Edge → Fog → Cloud** architectures with MQTT, GCP Cloud Run, BigQuery and IaC (Terraform / Pulumi).
- 📊 I build analytical dashboards over real time series: air quality, planning, finance.
- ⚙️ I care about decisions that age well: DDD, explicit API contracts, tests where they matter and reproducible deployments.

---

## Stack

**Backend**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Django_5-092E20?style=flat-square&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/Django_REST-A30000?style=flat-square&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/.NET_8-512BD4?style=flat-square&logo=dotnet&logoColor=white">
  <img src="https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white">
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white">
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white">
</p>

**Frontend**

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white">
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white">
  <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white">
  <img src="https://img.shields.io/badge/Ant_Design-0170FE?style=flat-square&logo=antdesign&logoColor=white">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white">
</p>

**Cloud &amp; DevOps**

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white">
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white">
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white">
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=flat-square&logo=terraform&logoColor=white">
  <img src="https://img.shields.io/badge/Pulumi-F7BF2A?style=flat-square&logo=pulumi&logoColor=black">
  <img src="https://img.shields.io/badge/DigitalOcean-0080FF?style=flat-square&logo=digitalocean&logoColor=white">
</p>

**Data &amp; Messaging**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white">
  <img src="https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white">
  <img src="https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white">
  <img src="https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=mqtt&logoColor=white">
  <img src="https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/YOLOv8-111111?style=flat-square&logo=ultralytics&logoColor=white">
</p>

---

## Featured projects

### 🏢 TRIADE — ERP + landing in production · `private`

A complete platform for a construction company, served under a single domain over HTTPS.

- **Backend** — Django 5 + DRF + PostgreSQL 16, organized as **DDD per module**
  (`domain` / `application` / `infrastructure` / `presentation`) across 8 business domains:
  projects, planning, finance, collaborators, identity and configuration.
- **Frontend** — React 19 + TypeScript + Vite + Chakra UI, in *feature modules*, with a single
  HTTP client, typed error handling and JWT authentication.
- **Landing** — Astro 5 with 3D islands (React Three Fiber) and GSAP animation.
- **Infrastructure** — Docker Compose, Nginx as a TLS reverse proxy, Gunicorn, media in object
  storage, full-system backups and a version-controlled operations runbook.
- **In progress** — migration to **FastAPI microservices**: 7 independent services behind an API gateway.

> The hard part wasn't writing it, but making it operable: idempotent deployment, coexistence with
> another project on the same droplet, and backup restore tested end to end.

---

### 🏛️ Olympus — corporate ERP · `private · NDA`

An internal company ERP in production. Due to confidentiality I share **technical notes only**,
no business domain or client data.

- **Backend** — ASP.NET Core 8 (C#) in a **strict layered architecture**
  (API / business layer / data layer / models): controllers only coordinate, services hold the
  business logic, and repositories are the only layer that talks to the database.
- **Persistence** — SQL Server with **Entity Framework Core** (LINQ) plus stored procedures for the
  heavy work; **Repository + Unit of Work** pattern with explicit transactions (`Begin` / `Commit` / `Rollback`).
- **Frontend** — React 18 + TypeScript + Vite + Ant Design, with a service layer over Axios and a
  token interceptor; contract types kept isolated in `modelos/`.
- **Identity** — signed JWT (HMAC-SHA256), attribute-based authorization (`[Authorize]` /
  `[AllowAnonymous]`), and identity **always resolved from the token claim**, never from client
  parameters.
- **Security** — fixed an **IDOR** vulnerability on a public portal (data enumeration via an id in
  the URL), moved email links to **capability URLs** with a random token, and hardened parameterized
  queries and output DTOs with no sensitive fields.

---

### 🔗 LinkU — web platform · `private`

A web application I build and operate on my own droplet.

- **Backend** — FastAPI with **Celery** workers over **Redis**, PostgreSQL 16, and **Alembic**
  migrations (`alembic upgrade head` on API startup).
- **Frontend** — React SPA served by Nginx.
- **Infrastructure** — Docker Compose, Nginx as the TLS edge with automatic certificate renewal
  (certbot), and **coexistence on the same host with TRIADE**: a single Nginx owns ports 80/443 and
  proxies both domains over a shared Docker network.

---

### 🌐 [IoT-Cloud-Fog-Computing](https://github.com/AlbertLlica/IoT-Cloud-Fog-Computing) · `Python`

A three-tier **Edge → Fog → Cloud** architecture for IoT monitoring.

Sensors at the edge, aggregation and filtering in the fog layer (to cut bandwidth to the cloud),
ingestion over **MQTT with TLS**, and serverless inference with **YOLOv8 on Cloud Run**. Analytical
storage in **BigQuery**, objects in **Cloud Storage**, infrastructure declared with **Terraform**,
and clients in **Next.js** and **Flutter**.

---

### 📈 [AirQuality-Imputation-Dashboard](https://github.com/AlbertLlica/AirQuality-Imputation-Dashboard) · `TypeScript`

An air-quality dashboard with **missing-data imputation** on time series.
Adaptive visualizations (sparkbox, multi-metric series), light / dark / system themes,
and navigation by measuring station.

---

### 🧭 [Comparação de Caminhos](https://github.com/AlbertLlica/Compara-o-de-Caminhos) · `C++`

A comparative testbench for shortest-path algorithms — **A\***, **Dijkstra**, **D\*Lite**
and **BMSSP** — measuring path cost, expanded nodes and replanning behavior.

---

### 🔥 [IoT-app-fire-detector](https://github.com/AlbertLlica/IoT-app-fire-detector) · `Flutter`

A cross-platform app (web / Android / iOS) connected to HiveMQ Cloud over MQTT that captures a photo
and audio and uploads them to Google Cloud Storage. Includes a per-platform transport abstraction:
secure WebSocket on web, TLS over 8883 on mobile.

---

### ☁️ [Autoscaling](https://github.com/AlbertLlica/Autoscaling) · `Python`

Infrastructure as code on **AWS with Pulumi**: declarative provisioning,
a reproducible `preview` / `up` / `destroy` cycle, and per-environment stacks.

---

## How I work

| | |
|---|---|
| **Architecture** | I keep the domain separate from the infrastructure. A use case shouldn't know whether Django, FastAPI or a CSV sits behind it. |
| **Contracts** | The API is the contract: frontend types that mirror the backend serializer, all versioned under `/api/v1/`. |
| **Operations** | If it isn't in the runbook, it isn't deployed. Idempotent scripts, verified backups and accessible logs. |
| **Quality** | Tests where being wrong costs money or trust: financial calculation, permissions and migrations. |

---

## Activity

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AlbertLlica/AlbertLlica/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AlbertLlica/AlbertLlica/output/snake.svg" />
    <img alt="Snake animation" src="https://raw.githubusercontent.com/AlbertLlica/AlbertLlica/output/snake.svg" />
  </picture>
</div>

---

<p align="center">
  <sub>Have a project in mind or a role that fits? Reach out on
  <a href="https://www.linkedin.com/in/albert-llica-alvarez">LinkedIn</a> or at
  <a href="mailto:albertllica@gmail.com">albertllica@gmail.com</a>.</sub>
</p>
