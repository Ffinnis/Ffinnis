# Roman Potapov

**Senior Backend Engineer · Go · Distributed Systems**

[LinkedIn](https://www.linkedin.com/in/roman-p-golang/) · [Email](mailto:roman.potapov.an@gmail.com)

I build distributed systems in Go, with 7 years of engineering experience across marketplaces, fintech, logistics, and warehouse automation. My work includes services used by millions of people, payment routing at scale, and systems that coordinate autonomous robots.

Currently at **Vinted Go**, working on warehouse topology and AI agents for parcel-exception resolution.

## Selected impact

| System | Scale | Result |
| :--- | :--- | :--- |
| Warehouse topology | 40+ autonomous robots | 31% fewer topology incidents; recovery from 20 to 8 minutes |
| Parcel investigation agent | WMS and carrier API integrations | 64% of investigations automated; handling from 12 to 4 minutes |
| Geospatial search | 6M+ monthly users · 2.2M active listings | 55% lower p95 map-refresh latency |
| Payment routing | Platform processing 20M+ transactions per month | ML-based provider ranking integrated into Go routing services |

## Experience

### Vinted Go · Senior Backend Engineer, Go

**Apr 2024 – Present** · Contract · Lisbon, Portugal · Remote

- Architected a Go warehouse topology service coordinating **40+ autonomous robots**, modeling zones, aisles, stations, and routes as a versioned graph in MySQL.
- Implemented optimistic concurrency control, transactional invariant validation, idempotent APIs, and auditable rollback. Reduced topology incidents by **31%** and recovery time from **20 to 8 minutes**.
- Built a Go AI agent for parcel exceptions using **Google ADK**, RAG over Elasticsearch, and tool calls to WMS and carrier APIs. Automated **64%** of investigations and reduced average handling time from **12 to 4 minutes**.

### Alterra Bills · Back End Developer, Go

**Apr 2023 – Apr 2024** · Contract · Jakarta, Indonesia · Remote

- Integrated a pre-trained provider-ranking model into Go routing services, with Redis for real-time features and RabbitMQ for transaction feedback, across a platform processing **20M+ monthly transactions**.
- Led a configuration-driven merchant onboarding portal for **20+ marketplace partners**, automating provider mappings, commission rules, credentials, and access controls to eliminate merchant-specific code releases.

### OLX Uzbekistan · Backend Developer, Golang

**Feb 2022 – Apr 2023** · Full-time · Tashkent, Uzbekistan · Remote

- Built a Go geospatial search service for **6M+ monthly users**, combining Solr bounding-box retrieval with a multi-resolution H3 cluster index. Reduced p95 map-refresh latency by **55%** across **2.2M active listings**.
- Built a Go media API serving batched, CDN-backed thumbnails for map searches, replacing per-marker image lookups with a single viewport request.

### Andersen Lab · Junior Backend Engineer

**May 2020 – Feb 2022** · Full-time · Remote

- Built a Node.js microservice for real-time inventory synchronization using WebSockets and Redis pub/sub, handling **50K+ concurrent connections** for a retail client.
- Implemented a file-processing pipeline with Bull queues for bulk CSV imports, reducing processing time from **4 hours to 15 minutes** for a logistics client.
- Developed a REST API layer for a multi-tenant SaaS platform, with JWT authentication, role-based access control, and audit logging for **300+ enterprise accounts**.

## Tools I work with

| Area | Technologies |
| :--- | :--- |
| Languages | Go, SQL, Node.js / JavaScript |
| Data & search | PostgreSQL, MySQL, Redis, Elasticsearch, Solr, H3 |
| Messaging | Apache Kafka, RabbitMQ |
| APIs | gRPC, REST, WebSockets |
| Infrastructure | Docker, Kubernetes |
| AI agents | Google ADK, RAG, tool calling |

## Let's connect

Happy to talk about Go, distributed systems, search, payment routing, or warehouse automation.

Find me on [LinkedIn](https://www.linkedin.com/in/roman-p-golang/) or reach me at [roman.potapov.an@gmail.com](mailto:roman.potapov.an@gmail.com).
