<div align="center">

# Hola, soy Darwin Montiel Mora 👋

### Desarrollador RPA & Backend · Ingeniero de Sistemas · Bogotá, Colombia

Construyo **bots que automatizan procesos sobre aplicativos web** y los sistemas que los hacen
confiables en producción: colas de mensajes, trazabilidad, monitoreo, despliegues y datos.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Darwin%20Montiel%20Mora-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/darwin-montiel-mora-925216206)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?logo=rabbitmq&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white)
![Ruby on Rails](https://img.shields.io/badge/Rails-D30001?logo=rubyonrails&logoColor=white)

</div>

---

## Sobre mí

- 🤖 **3 años** en desarrollo de software, **automatización robótica de procesos (RPA)** y análisis de datos.
- 🏦 En una **fintech multinacional de gestión de cartera** (Colombia, Chile y Perú) desarrollé bots en
  Python que operan aplicativos web, integrados con **RabbitMQ** y **PostgreSQL**, y el proyecto de
  **monitoreo de bots**; además gestioné servidores **Windows y Linux** y los **despliegues a producción**.
- 🧩 Experiencia en **Ruby on Rails** (Turbo/Stimulus), **Robocorp** y **Blue Prism** (Control Room),
  y en **BI**: Power BI, DAX, Pandas y Excel avanzado.
- 🎯 Me interesa la **hiperautomatización**, las **arquitecturas orientadas a mensajes** y la
  **eficiencia operativa** en cobranza y gestión de cartera.

## Proyectos destacados

| Proyecto | Qué demuestra | Stack |
|---|---|---|
| [**rpa-orchestrator**](https://github.com/DarwinMontiel/rpa-orchestrator) · [demo](https://darwinmontiel.github.io/rpa-orchestrator/) | Plataforma de bots RPA a escala: tareas por colas RabbitMQ con reintentos TTL y DLQ, idempotencia, trazabilidad en PostgreSQL, monitoreo de bots y despliegue en Linux y Windows Server | Python · RabbitMQ · PostgreSQL · Playwright · FastAPI · Docker |
| [**cartera-analytics**](https://github.com/DarwinMontiel/cartera-analytics) · [tablero](https://darwinmontiel.github.io/cartera-analytics/) | ETL de cartera y cobranza: 29 reglas de calidad de datos, modelo estrella, KPIs (PAR30, roll rates, recaudo), Power BI/DAX y reporte Excel; pandas y SQL verificados entre sí | Python · pandas · PostgreSQL · SQL · Power BI · Excel |
| [**cartera-crm**](https://github.com/DarwinMontiel/cartera-crm) | CRM de cobranza: bandeja de cobro, gestiones y promesas, acuerdos de pago en días hábiles, API REST para bots e integridad garantizada por la base de datos | Ruby on Rails 8 · Hotwire · PostgreSQL · Kamal |
| [**llm-gateway**](https://github.com/DarwinMontiel/llm-gateway) | Cliente unificado para LLM locales y en la nube con streaming, reintentos y *fallback* | Python · httpx · Ollama · Groq |
| [**robocorp-order-robot**](https://github.com/DarwinMontiel/robocorp-order-robot) | Bot de la certificación Robocorp: Page Object, reintentos, recibos PDF y resiliencia por pedido | Python · Robocorp · RPA Framework |

### Cómo se conectan

```mermaid
flowchart TB
    LLM["llm-gateway<br/>IA local y en la nube"] -. clasificar y resumir .-> BOT
    BOT["rpa-orchestrator<br/>bots + colas + monitoreo"] -- API REST --> CRM["cartera-crm<br/>gestión de cobranza"]
    CRM -- exportes --> ETL["cartera-analytics<br/>ETL + KPIs + Power BI"]
    ETL -- priorización --> BOT
```

Los tres primeros modelan una operación de cobranza completa: los bots ejecutan el trabajo
repetitivo, el CRM es la herramienta de los gestores y la analítica mide los resultados.

## Tecnologías

**Lenguajes:** ![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![SQL](https://img.shields.io/badge/-SQL-336791?logo=postgresql&logoColor=white) ![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Ruby](https://img.shields.io/badge/-Ruby-CC342D?logo=ruby&logoColor=white)

**RPA y automatización:** ![Playwright](https://img.shields.io/badge/-Playwright-2EAD33?logo=playwright&logoColor=white) ![Robocorp](https://img.shields.io/badge/-Robocorp-00A39E) ![Blue Prism](https://img.shields.io/badge/-Blue%20Prism-0F2C5C)

**Backend y mensajería:** ![RabbitMQ](https://img.shields.io/badge/-RabbitMQ-FF6600?logo=rabbitmq&logoColor=white) ![FastAPI](https://img.shields.io/badge/-FastAPI-009688?logo=fastapi&logoColor=white) ![Rails](https://img.shields.io/badge/-Ruby%20on%20Rails-D30001?logo=rubyonrails&logoColor=white) ![Hotwire](https://img.shields.io/badge/-Hotwire-5CD8E5) ![REST](https://img.shields.io/badge/-APIs%20REST-555555)

**Bases de datos:** ![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![SQL Server](https://img.shields.io/badge/-SQL%20Server-CC2927?logo=microsoftsqlserver&logoColor=white) ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?logo=mysql&logoColor=white)

**Infraestructura y DevOps:** ![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black) ![Windows Server](https://img.shields.io/badge/-Windows%20Server-0078D6?logo=windows&logoColor=white) ![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/-GitHub%20Actions-2088FF?logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)

**Datos y BI:** ![pandas](https://img.shields.io/badge/-pandas-150458?logo=pandas&logoColor=white) ![Power BI](https://img.shields.io/badge/-Power%20BI%20·%20DAX-F2C811?logo=powerbi&logoColor=black) ![Excel](https://img.shields.io/badge/-Excel%20avanzado-217346?logo=microsoftexcel&logoColor=white)

## Experiencia

| Período | Rol | Empresa |
|---|---|---|
| 2026 | Desarrollador RPA | **Liquitty** · fintech de gestión de cartera (Colombia, Chile y Perú) |
| 2025 – 2026 | Desarrollador de Software | **Narnaja Business Intelligence** · RPA e IA, dashboards de BI y plataformas web |
| 2023 – 2024 | Desarrollador de Software | **PulpiFrut** · scripts de datos con pandas, frontend y dashboards de Power BI |
| 2022 – 2023 | Analista BI Junior (prácticas) | **Emtelco** · línea de cobranzas |

## Certificaciones

- **Blue Prism Developer Certification** — SS&C Blue Prism
- **Automation Developer – Python** — Robocorp
- **PCAP – Programming Essentials in Python** — Cisco
- **DevOps** — Cisco

## Formación

**Ingeniería de Sistemas** — Universidad ECCI (2020 – 2025, pensum académico finalizado)

---

<div align="center">
<sub>¿Hablamos de automatización, backend o datos? Escríbeme por <a href="https://www.linkedin.com/in/darwin-montiel-mora-925216206">LinkedIn</a>.</sub>
</div>
