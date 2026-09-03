<h1 align="center">Albert Llica</h1>

<p align="center">
  <b>Software Engineer</b> &middot; Fullstack &middot; Cloud &amp; Data<br>
  Diseño y opero sistemas completos: del modelo de dominio al dominio en producción.
</p>

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/Español-activo-1f6feb?style=for-the-badge" alt="Leer en español"></a>
  <a href="./README.en.md"><img src="https://img.shields.io/badge/English-switch-30363d?style=for-the-badge" alt="Read in English"></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/albert-llica-alvarez"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:albertllica@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/AlbertLlica?tab=repositories"><img src="https://img.shields.io/badge/Repositorios-43-181717?style=flat-square&logo=github&logoColor=white" alt="Repositorios"></a>
</p>

---

## Sobre mí

Ingeniero de software con foco en **arquitectura backend**, **infraestructura cloud** y **producto**.
Trabajo end-to-end: diseño el dominio, implemento la API, construyo la interfaz y me hago cargo del
despliegue, el TLS, los backups y el runbook de operaciones.

- 🏗️ Construyo y opero **TRIADE**, un ERP para una constructora, en producción bajo dominio propio.
- 🏛️ Contribuyo a **Olympus**, un ERP corporativo en **.NET 8 / SQL Server** con arquitectura por capas.
- 🔗 Construyo y opero **LinkU**, una plataforma web sobre **FastAPI + Celery + PostgreSQL**.
- ☁️ Diseño arquitecturas **Edge → Fog → Cloud** con MQTT, GCP Cloud Run, BigQuery e IaC (Terraform / Pulumi).
- 📊 Desarrollo dashboards analíticos sobre series temporales reales: calidad del aire, planificación, finanzas.
- ⚙️ Me interesan las decisiones que envejecen bien: DDD, contratos de API explícitos, tests donde importan y despliegues reproducibles.

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

**Datos &amp; Mensajería**

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

## Proyectos destacados

### 🏢 TRIADE — ERP + landing en producción · `privado`

Plataforma completa para una constructora, servida bajo un único dominio con HTTPS.

- **Backend** — Django 5 + DRF + PostgreSQL 16, organizado en **DDD por módulo**
  (`domain` / `application` / `infrastructure` / `presentation`) sobre 8 dominios de negocio:
  proyectos, planificación, económico, colaboradores, identidad y configuración.
- **Frontend** — React 19 + TypeScript + Vite + Chakra UI, en *feature modules*, con un único
  cliente HTTP, manejo de errores tipado y autenticación JWT.
- **Landing** — Astro 5 con islas 3D (React Three Fiber) y animación GSAP.
- **Infraestructura** — Docker Compose, Nginx como reverse proxy con TLS, Gunicorn, media en object
  storage, copia de seguridad integral y runbook operativo versionado.
- **En curso** — migración a **microservicios FastAPI**: 7 servicios independientes tras un API gateway.

> Lo difícil no fue escribirlo, sino dejarlo operable: despliegue idempotente, coexistencia con otro
> proyecto en el mismo droplet y restauración de backups probada de extremo a extremo.

---

### 🏛️ Olympus — ERP corporativo · `privado · NDA`

ERP interno de empresa en producción. Por confidencialidad comparto **solo notas técnicas**,
sin dominio de negocio ni datos de cliente.

- **Backend** — ASP.NET Core 8 (C#) en **arquitectura por capas estricta**
  (API / CapaNegocio / CapaDatos / Models): los controladores solo coordinan, los servicios
  concentran la lógica de negocio y los repositorios son la única capa que habla con la BD.
- **Persistencia** — SQL Server con **Entity Framework Core** (LINQ) y stored procedures para lo
  pesado; patrón **Repository + Unit of Work** con transacciones explícitas (`Begin` / `Commit` / `Rollback`).
- **Frontend** — React 18 + TypeScript + Vite + Ant Design, con capa de servicios sobre Axios e
  interceptor de token; los tipos del contrato viven aislados en `modelos/`.
- **Identidad** — JWT firmado (HMAC-SHA256), autorización por atributos (`[Authorize]` /
  `[AllowAnonymous]`) y la identidad resuelta **siempre desde el claim del token**, nunca desde
  parámetros del cliente.
- **Seguridad** — corregí una vulnerabilidad **IDOR** en un portal público (enumeración de datos
  por id en la URL), migré los enlaces de correo a **capability URLs** con token aleatorio y
  reforcé queries parametrizadas y DTOs de salida sin campos sensibles.

---

### 🔗 LinkU — plataforma web · `privado`

Aplicación web que construyo y opero en un droplet propio.

- **Backend** — FastAPI con workers **Celery** sobre **Redis**, PostgreSQL 16 y migraciones con
  **Alembic** (`alembic upgrade head` al arrancar la API).
- **Frontend** — SPA en React servida por Nginx.
- **Infraestructura** — Docker Compose, Nginx como edge TLS con renovación automática de
  certificados (certbot) y **coexistencia en el mismo host con TRIADE**: un único Nginx posee
  los puertos 80/443 y proxea ambos dominios a través de una red Docker compartida.

---

### 🌐 [IoT-Cloud-Fog-Computing](https://github.com/AlbertLlica/IoT-Cloud-Fog-Computing) · `Python`

Arquitectura de tres capas **Edge → Fog → Cloud** para monitoreo IoT.

Sensores en el borde, agregación y filtrado en la capa fog (para reducir el ancho de banda hacia la nube),
ingesta vía **MQTT sobre TLS** e inferencia serverless con **YOLOv8 sobre Cloud Run**. Persistencia
analítica en **BigQuery**, objetos en **Cloud Storage**, infraestructura declarada con **Terraform**
y clientes en **Next.js** y **Flutter**.

---

### 📈 [AirQuality-Imputation-Dashboard](https://github.com/AlbertLlica/AirQuality-Imputation-Dashboard) · `TypeScript`

Dashboard de calidad del aire con **imputación de datos faltantes** en series temporales.
Visualizaciones adaptativas (sparkbox, series multi-métrica), tema claro / oscuro / sistema
y navegación por estación de medición.

---

### 🧭 [Comparação de Caminhos](https://github.com/AlbertLlica/Compara-o-de-Caminhos) · `C++`

Banco de pruebas comparativo de algoritmos de camino más corto — **A\***, **Dijkstra**, **D\*Lite**
y **BMSSP** — midiendo coste de la ruta, nodos expandidos y comportamiento ante replanificación.

---

### 🔥 [IoT-app-fire-detector](https://github.com/AlbertLlica/IoT-app-fire-detector) · `Flutter`

App multiplataforma (web / Android / iOS) conectada a HiveMQ Cloud por MQTT, que captura foto y audio
y los sube a Google Cloud Storage. Incluye abstracción del transporte por plataforma: WebSocket seguro
en web, TLS sobre 8883 en móvil.

---

### ☁️ [Autoscaling](https://github.com/AlbertLlica/Autoscaling) · `Python`

Infraestructura como código sobre **AWS con Pulumi**: aprovisionamiento declarativo,
ciclo `preview` / `up` / `destroy` reproducible y stacks separados por entorno.

---

## Cómo trabajo

| | |
|---|---|
| **Arquitectura** | Separo el dominio de la infraestructura. El caso de uso no debería saber si detrás hay Django, FastAPI o un CSV. |
| **Contratos** | La API es el contrato: tipos del frontend que reflejan el serializer del backend, todo versionado bajo `/api/v1/`. |
| **Operaciones** | Si no está en el runbook, no está desplegado. Scripts idempotentes, backups verificados y logs accesibles. |
| **Calidad** | Tests donde equivocarse cuesta dinero o confianza: cálculo económico, permisos y migraciones. |

---

## Actividad

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/AlbertLlica/AlbertLlica/output/snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/AlbertLlica/AlbertLlica/output/snake.svg" />
    <img alt="Snake animation" src="https://raw.githubusercontent.com/AlbertLlica/AlbertLlica/output/snake.svg" />
  </picture>
</div>

---

<p align="center">
  <sub>¿Un proyecto en mente o una vacante que encaje? Escríbeme por
  <a href="https://www.linkedin.com/in/albert-llica-alvarez">LinkedIn</a> o a
  <a href="mailto:albertllica@gmail.com">albertllica@gmail.com</a>.</sub>
</p>
