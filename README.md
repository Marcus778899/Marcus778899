# Marcus Lin (Sheng-Lun Lin)

### Big Data Engineer | Digital Transformation Architect

I build **data platforms** — consolidating data scattered across systems into a layered, governed, reusable asset, so business teams never have to ask "where does this number come from" twice.

My background spans data engineering and backend development; my previous role was backend full-time. That means I don't just consume data downstream — I can intervene at the source: system design, API contracts, and the moment an event is produced. In platform work, that is often what decides success or failure.

With 3+ years of experience, I care less about which tools are on the list and more about designing the right thing for the situation.

---

### What I Handle

**Building a Data Platform from Zero**

The company has data but no architecture; reports are assembled by hand and metric definitions differ across departments. I start from raw landing in the data lake and design the full layering — staging, ODS, data warehouse, data marts — defining the responsibility and metric semantics of each layer so data is traceable, re-runnable, and shareable across business units.

**Data Modeling and Metric Governance**

I use a bus matrix to align business processes with conformed dimensions — clarifying who needs to see what, and at what grain, before deciding on fact and dimension design. This avoids the common trap where every department builds its own model and the numbers stop agreeing.

**Pipeline Design and Operations**

I orchestrate the full data lifecycle with **Airflow**: scheduling dependencies, incremental versus full-load strategies, retry semantics, and data quality checks. The goal is not a pipeline that runs — it is a pipeline where, when something breaks, you know exactly where it broke and can recover safely.

**Real-Time and Change Data Capture**

I use CDC (**Debezium**) with **Kafka** to capture change events from source systems, moving reporting from T+1 batch toward near real-time without adding query pressure to the source database.

**Analytical Performance Tuning**

Against terabytes of historical data, I apply OLAP engines with partitioning and indexing strategies to bring multi-minute queries down to seconds — turning analysis from waiting in line for results into live exploration.

**Backend Services and Data Interfaces**

I design and implement data service APIs that deliver platform output to frontends, reporting layers, and external systems. I also work in the other direction, on event design and write paths in source systems. The wall between backend and data engineering is one I can stand on both sides of.

**Data Access Layer for AI Agents**

I build MCP servers so AI agents can access internal enterprise data under controlled permissions and boundaries — the bridge between data governance and AI applications.

---

### Technical Scope

| Category | Technologies |
| --- | --- |
| **Cloud** | GCP, AWS |
| **Storage & Query** | BigQuery, ClickHouse, Redshift, PostgreSQL, MongoDB, Redis |
| **Streaming & CDC** | Kafka, Debezium, Spark |
| **Transformation & Orchestration** | dbt, Airflow |
| **Backend & Deployment** | FastAPI, Spring Boot, Docker, Docker Compose |
| **AI** | MCP Server, LangGraph |

---

### Technical Interests

Database internals and distributed systems. Currently exploring advanced data modeling techniques and improving observability across large-scale data infrastructure.

---

### Connect

- **LinkedIn**: [linkedin.com/in/marcus-807788284](https://www.linkedin.com/in/marcus-807788284/)
- **Email**: [s09203647@gmail.com](mailto:s09203647@gmail.com)
- **Location**: Taipei, Taiwan
