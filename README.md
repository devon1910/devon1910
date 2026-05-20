# Davidson Ekpokpobe

Software engineer, 5+ years. Production systems across compliance-tech, fintech, and AI-powered platforms. Currently leading infrastructure, DevOps, and SOC 2 compliance at Norebase.

Lagos, Nigeria · [davidsonekpokpobe@gmail.com](mailto:davidsonekpokpobe@gmail.com) · [GitHub](https://github.com/devon1910) · [LinkedIn](https://linkedin.com/in/davidson-ekpokpobe)

---

## Stack

**Languages** &nbsp; C# · Go · Python · TypeScript
**Backend** &nbsp; .NET · REST APIs · PostgreSQL · Redis · ClickHouse · Debezium (CDC) · Entity Framework
**Cloud & Infra** &nbsp; Azure (App Service, Front Door/WAF, ACR, Functions, Service Bus, VNets) · AWS · Docker · Pulumi (IaC)
**Observability** &nbsp; Prometheus · Loki · Grafana · Tempo · Alloy · OpenTelemetry
**ML / AI** &nbsp; ML.NET · XGBoost · scikit-learn · Anthropic API
**Other** &nbsp; SOC 2 · CVE remediation · CI/CD · system design

---

## Selected projects

### 🛰️ [DSV Tracking MCP Server](https://github.com/devon1910/dsv-tracking-mcp-server) — Go
Model Context Protocol server that lets LLMs query DB Schenker shipment data. Three tools, browser-backed extraction against the public tracking endpoint, conditional caching with stale-fallback, eight-code error taxonomy, ADR-documented design decisions. Verified end-to-end across ten live reference shipments.

### ⚽ [OpenBet](https://github.com/devon1910/OpenBet) — AI football prediction engine
Three-model stacking ensemble (Poisson + XGBoost + meta-learner) with a Claude reasoning layer. 81.5% accuracy and 17% ROI across 12 competitions. Fully autonomous 6-hour pipeline; in-memory bulk features cut DB load from 17 queries per match to 2 total.

### 🏃‍♂️‍➡️ [SpartanStats](https://github.com/devon1910/spartan-stats) — TypeScript, Postgres
Match-level stats tracker for my Tuesday soccer group. Per-player goals, assists, MOTM, ELO-style ratings for different months. Built so everyone can back their banter with data.

### ⏱️ [theSwiftline](https://www.theswiftline.com/) — C#, .NET, ML.NET
PWA queue-management system with offline-first architecture and ML.NET wait-time predictions trained on historical throughput. 1,500+ users, ~2.5 hours saved per user per week. Full organizer dashboard for queue control, analytics, and real-time notifications.

### 🎓 [StandardSchoolsPortal](https://github.com/devon1910/Standard-Schools-Portal) — C#, .NET
School management system for a two-campus institution. Enrollment, fee tracking, academic records, parent-facing dashboards.

---

## Experience

**Software Engineer (Engineering Lead), Norebase** &nbsp; · &nbsp; 2025 — Present
Led SOC 2 compliance remediation end-to-end: 15+ Vanta security tests resolved, container CVEs reduced from 3,800+ (Critical: 134, High: 3,679) to under 10 across all production registries. Built PR-scoped CI/CD pipelines with ephemeral Postgres and queue infrastructure per PR, running full API test suites and blocking merges on failure across three environments. Designed and deployed a full observability stack from scratch (Prometheus, Loki, Grafana, Tempo, Alloy, OpenTelemetry) with WhatsApp on-call alerting via Twilio webhooks. Provisioned all cloud infrastructure as code with Pulumi. Implemented legal traceability in AutoComply, linking compliance obligations to source legislation across multiple African jurisdictions.

**Software Engineer, Divverse** &nbsp; · &nbsp; 2023 — 2024
Cut report generation time by 25% through stored procedures, Entity Framework optimization, and Redis caching in Docker. Improved bug resolution speed by 10% with centralized logging via AWS CloudWatch and Serilog. Set up AWS Glue jobs ensuring data persistence and integrity into the Tableau data source.

**Software Engineer, Uridium Technologies** &nbsp; · &nbsp; 2022 — 2023
Built an internal metrics dashboard used by 8 teams. Shipped a referral microservices API spanning 5 fintech products. Improved transaction flow on Slick Hustle, clarifying API logic and ensuring full commission retention.

---

## Education

**BSc Computer Science, First Class Honours** &nbsp; · &nbsp; Covenant University, 2017 — 2021
