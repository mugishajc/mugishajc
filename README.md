### Mugisha Jean Claude

Kigali, Rwanda. I build ERPs, mobile apps and payment systems for businesses in East Africa.

Backend and infrastructure first: Python, Go, Rust, Java, Kotlin, TypeScript. Spring Boot, FastAPI, Django, Next.js. PostgreSQL. Kubernetes, Helm, Argo CD, GitHub Actions in production.

Most of my work is private. Public pieces:

**Infrastructure and DevOps**
- [fleetpulse](https://github.com/mugishajc/fleetpulse): event-driven fleet operations platform, 4 Go microservices on NATS, geofencing with haversine, k6 load tests, Grafana dashboard, Kubernetes with Kustomize overlays, Helm chart, Argo CD GitOps
- [basecamp-aws](https://github.com/mugishajc/basecamp-aws): Terraform landing zone modules for AWS: 3-AZ VPC with flow logs, customer-managed KMS, encrypted S3 log bucket with lifecycle, IAM baseline, with fmt, validate, tflint and checkov in CI
- [pipebench](https://github.com/mugishajc/pipebench): reusable GitHub Actions: Buildx + Cosign keyless signing, test-matrix with coverage floor, Terraform plan-apply gated by OIDC
- [obsidian](https://github.com/mugishajc/obsidian): opinionated observability stack for Kubernetes: Prometheus, Loki, Tempo and OpenTelemetry Collector in one Helm chart, with SLO burn-rate alerts and dashboards
- [helmscape](https://github.com/mugishajc/helmscape): two FastAPI microservices to Kubernetes with Helm charts, Argo CD app-of-apps and GitHub Actions to GHCR

**Backend**
- [tollgate](https://github.com/mugishajc/tollgate): concurrent token-bucket rate limiter for Go with a net/http middleware
- [tally](https://github.com/mugishajc/tally): parallel word-count CLI in Rust, streaming I/O and Rayon across files
- [taskforge](https://github.com/mugishajc/taskforge): ASP.NET Core 8 Web API for projects and tasks, JWT, EF Core, xUnit integration tests
- [keygate](https://github.com/mugishajc/keygate): JWT access and refresh tokens, USER/ADMIN roles on Spring Security 6
- [shelftrack](https://github.com/mugishajc/shelftrack): library management on Spring Boot 3, books, members, loans and overdue fines with Flyway
- [sprintline](https://github.com/mugishajc/sprintline): task API on Quarkus 3 with Panache, OpenAPI and health checks
- [linkbit](https://github.com/mugishajc/linkbit): URL shortener on Eclipse Vert.x 4 with base62 codes and click stats
- [vaultcore](https://github.com/mugishajc/vaultcore): AES-GCM, PBKDF2, HMAC and RSA-PSS primitives on plain Java JCA
- [scholaris](https://github.com/mugishajc/scholaris): school management REST API on Django 5 and DRF, grades and term reports
- [coinlog](https://github.com/mugishajc/coinlog): expenses, monthly budgets and overrun alerts on FastAPI with JWT
- [upcheck](https://github.com/mugishajc/upcheck): URL uptime monitor on Flask and APScheduler with alert hooks
- [mushahara](https://github.com/mugishajc/mushahara): VB.NET library for Rwandan monthly payroll, PAYE across RRA bands, RSSB and CBHI
- [feathermvc](https://github.com/mugishajc/feathermvc): small MVC framework in plain PHP 8.2 with router, DI, CSRF and a task board demo
- [sentinel-auth](https://github.com/mugishajc/sentinel-auth): PHP 8.2 authentication with Argon2id, login throttling, session hardening and hashed email tokens

**Data**
- [calibratorrr](https://github.com/mugishajc/calibratorrr): court case API with JWT auth and a Spark analytics lab, Spring Boot
- [who-health-etl-pipeline](https://github.com/mugishajc/who-health-etl-pipeline): WHO GHO to PostgreSQL ETL with validation and checkpointing

**Frontend and mobile**
- [pollster](https://github.com/mugishajc/pollster): Next.js 15 polls with Server Actions for votes and SSE for live results
- [skycast](https://github.com/mugishajc/skycast): weather and 7-day forecast in Kotlin with Jetpack Compose and Open-Meteo
- [jotdown](https://github.com/mugishajc/jotdown): offline Android notes in Java with Room, MVVM and Material 3
- [QT-Mail-Guard](https://github.com/mugishajc/QT-Mail-Guard): SHA-256 verification of email over Protocol Buffers

**Business systems**
- [uok_bank_group7](https://github.com/mugishajc/uok_bank_group7): mobile money simulator with P2P, agent cash-in/out and admin dashboard
- [JDD-Hotels-CRM](https://github.com/mugishajc/JDD-Hotels-CRM): hospitality CRM with leads, invoicing and payments

[linkedin.com/in/mugisha-jean-claude](https://www.linkedin.com/in/mugisha-jean-claude)
