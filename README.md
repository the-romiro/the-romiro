# Antonio Albuquerque Loiola (Romiro)

## Software & Data Engineer

I'm a Software Engineer and Data Engineer at Grendene S/A, one of Brazil's largest footwear makers. I joined the company in 2010 and have spent the last 6+ years, since 2019, in software and data. I build the web apps teams use every day and the data pipelines behind them, which process millions of records a day. I also work on the architecture of a cloud-agnostic Data Lakehouse (Stage → Bronze → Silver → Gold) with data contracts and automated quality checks.

[![Portfolio](https://img.shields.io/badge/Portfolio-romiro.dev-000000?style=flat&logo=react&logoColor=white)](https://romiro.dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/antonio-albuquerque-loiola/)
[![Email](https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white)](mailto:contato@romiro.dev)

## Highlights

- Cut processing time by up to 80% by tuning queries on PostgreSQL, SQL Server and DuckDB.
- Moved pipelines that handle millions of records a day to incremental loads, so each run processes only new data.
- Delivered GAM, the tooling department's activity management system, from the back end to the screens.
- Mentor the team's data analysts on software and data practices.

## Featured projects

| Project | What it is | Stack | Link |
|---------|-----------|-------|------|
| Lakehouse Local | A company data platform similar to Databricks that runs on local servers, with no cloud provider. It ingests data in scheduled loads and as changes happen, runs quality checks automatically, quarantines bad records and traces every number back to its source. | Spark, Iceberg, Trino, dbt, Airflow, Kafka, Debezium | Internal |
| G Home Lab | The five-server cluster that runs Grendene's factory systems: more than 30 internal apps (10 of them factory-floor dashboards), the data pipeline and a private AI assistant. An automated check on each server repairs network, storage and container failures. | Docker Swarm, Traefik, PostgreSQL, Airflow, Ollama | Internal |
| GAM | Web system for production activities in Grendene's tooling department. Each user sees what their role allows. | React, NestJS, Prisma, PostgreSQL | Internal |
| Grendene AI Tools | Extensions for the company's private AI assistant that let it read live web pages, spreadsheets and data files. The assistant answers from a private knowledge base. | Python, Open WebUI, Ollama, RAG, pgvector | Internal |
| Sophia Laços | Online store for a handmade hair bow atelier. Customers order through WhatsApp or pay online, and an admin panel handles products, photos and orders. | React, tRPC, Hono, Drizzle, Cloudflare Workers, Stripe | [sophia-lacos.com.br](https://sophia-lacos.com.br) |
| MICROTECH | Website for an Apple repair shop. Its iPhone repair quote tool gives an estimated price and passes the conversation to WhatsApp. | React, TypeScript, Cloudflare Workers | [lojamicrotech.com.br](https://lojamicrotech.com.br) |
| ALU Alarm Simulator | Teaching app that shows how processor logic works through a simulated alarm system, made as class material for Faculdade Anhanguera Sobral. | Python, Flask | [Repo](https://github.com/the-romiro/aula-anhanguera-ula-alarme) |

The full list is on [romiro.dev](https://romiro.dev/#projects).

## Technical stack

### Frontend

![React](https://img.shields.io/badge/react-%2320232a.svg?style=flat&logo=react&logoColor=%2361DAFB)
![Next JS](https://img.shields.io/badge/Next-black?style=flat&logo=next.js&logoColor=white)
![React Router](https://img.shields.io/badge/React%20Router-CA4245?style=flat&logo=reactrouter&logoColor=white)
![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=flat&logo=typescript&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=flat&logo=tailwind-css&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn/ui-000000?style=flat&logo=shadcnui&logoColor=white)
![TanStack Query](https://img.shields.io/badge/-TanStack%20Query-FF4154?style=flat&logo=react%20query&logoColor=white)
![Zustand](https://img.shields.io/badge/zustand-%23000000.svg?style=flat&logo=react&logoColor=white)
![Zod](https://img.shields.io/badge/zod-%233E67B1.svg?style=flat&logo=zod&logoColor=white)

### Backend

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=flat&logo=node.js&logoColor=white)
![NestJS](https://img.shields.io/badge/nestjs-%23E0234E.svg?style=flat&logo=nestjs&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54)
![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=flat&logo=fastapi&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white)
![SQLModel](https://img.shields.io/badge/SQLModel-7E56C2?style=flat&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat&logo=dotnet&logoColor=white)
![C#](https://img.shields.io/badge/c%23-%23239120.svg?style=flat&logo=csharp&logoColor=white)
![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=flat&logo=rust&logoColor=white)

### Data engineering

![Apache Spark](https://img.shields.io/badge/Apache%20Spark-FDEE21?style=flat&logo=apachespark&logoColor=black)
![Apache Airflow](https://img.shields.io/badge/Apache%20Airflow-017CEE?style=flat&logo=Apache%20Airflow&logoColor=white)
![dbt](https://img.shields.io/badge/dbt-FF694B?style=flat&logo=dbt&logoColor=white)
![Apache Iceberg](https://img.shields.io/badge/Apache%20Iceberg-3D9BE9?style=flat&logoColor=white)
![Apache Polaris](https://img.shields.io/badge/Apache%20Polaris-0A66C2?style=flat&logoColor=white)
![Delta Lake](https://img.shields.io/badge/Delta%20Lake-00ADD4?style=flat&logoColor=white)
![Apache Parquet](https://img.shields.io/badge/Apache%20Parquet-50ABF1?style=flat&logoColor=white)
![Trino](https://img.shields.io/badge/Trino-DD00A1?style=flat&logo=trino&logoColor=white)
![MinIO](https://img.shields.io/badge/MinIO-C72E49?style=flat&logo=minio&logoColor=white)
![Apache Kafka](https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white)
![Debezium](https://img.shields.io/badge/Debezium-91D443?style=flat&logoColor=black)
![Great Expectations](https://img.shields.io/badge/Great%20Expectations-FF6310?style=flat&logoColor=white)
![OpenMetadata](https://img.shields.io/badge/OpenMetadata-7147E8?style=flat&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-CD792C?style=flat&logo=polars&logoColor=white)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=flat&logo=pandas&logoColor=white)

### Databases

![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=flat&logo=postgresql&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat&logo=duckdb&logoColor=black)
![MicrosoftSQLServer](https://img.shields.io/badge/Microsoft%20SQL%20Server-CC2927?style=flat&logo=microsoft%20sql%20server&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=flat&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/redis-%23DD0031.svg?style=flat&logo=redis&logoColor=white)

### DevOps & infrastructure

![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
![Docker Swarm](https://img.shields.io/badge/docker%20swarm-%230db7ed.svg?style=flat&logo=docker&logoColor=white)
![Portainer](https://img.shields.io/badge/Portainer-13BEF9?style=flat&logo=portainer&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=flat&logo=traefikproxy&logoColor=white)
![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=flat&logo=nginx&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat&logo=githubactions&logoColor=white)

### AI / LLM

![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat&logo=ollama&logoColor=white)
![Open WebUI](https://img.shields.io/badge/Open%20WebUI-000000?style=flat&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-000000?style=flat&logoColor=white)
![pgvector](https://img.shields.io/badge/pgvector-316192?style=flat&logo=postgresql&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6446?style=flat&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI%20API-412991?style=flat&logo=openai&logoColor=white)

### BI & analytics

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logoColor=black)
![Qlik Sense](https://img.shields.io/badge/Qlik%20Sense-009848?style=flat&logo=qlik&logoColor=white)

### Testing

![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat&logo=vitest&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat&logo=jest&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=flat&logo=pytest&logoColor=white)
![xUnit](https://img.shields.io/badge/xUnit-512BD4?style=flat&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat&logo=playwright&logoColor=white)

## GitHub activity

<div align="center">

![GitHub Streak](https://streak-stats.demolab.com/?user=the-romiro&theme=dracula&hide_border=false)

</div>
