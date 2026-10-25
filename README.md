# Ragchaa Battsengel

**Software Engineer — Full-Stack Systems, Cloud Infrastructure & Multi-Agent Engineering**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-ragchaa--battsengel-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ragchaa-battsengel-79b6183bb)
[![Email](https://img.shields.io/badge/Email-ari.whysari%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ari.whysari@gmail.com)
[![Sentinel-SRE Live](https://img.shields.io/badge/Live_Console-Sentinel--SRE-10b981?style=flat-square&logo=vercel&logoColor=white)](https://sentinel-sre-iota.vercel.app)
[![Aegis-CI Live](https://img.shields.io/badge/Live_Console-Aegis--CI-3b82f6?style=flat-square&logo=vercel&logoColor=white)](https://aegis-ci.vercel.app)

---

### Profile Summary

- **Software Engineer** with a proven track record delivering resilient full-stack web applications, multi-country FinTech compliance platforms (UK HMRC & German ELSTER), high-concurrency digital trading marketplaces, and private cloud infrastructure from concept to production.
- Well-rounded technical skill set across **front-end frameworks (React 19, Next.js 16 App Router, Vue 3, TypeScript 7)**, **back-end & APIs (Laravel 12, FastAPI, Node.js, Express, PHP 8, Python 3.13)**, **databases (PostgreSQL 18, Redis 8)**, and **cloud/SRE (OpenStack, Docker, Kubernetes, Prometheus, Grafana)**.
- Deep expertise in **ACID transaction integrity**, **PostgreSQL Wait-For Graph lock analysis**, **zero-downtime SQL migrations**, and **AI-assisted software engineering (Claude Code)**, enforcing **Test-First Defect Reproduction (2:1 test-to-code ratio)** and **Automated CI/CD Release Gates** (**228 commercial PRs merged with 0 rollbacks**).

---

### Featured Systems & Open-Source Platforms

| System | Architecture & Engineering Highlights | Verification & Links |
| :--- | :--- | :--- |
| **[sentinel-sre](https://github.com/whysari/sentinel-sre)**<br>`Next.js 16` · `FastAPI` · `Postgres 18` · `K8s` | **Autonomous Multi-Agent Incident Diagnostics & Verified DR Platform**<br>Dispatches 3 parallel telemetry agents across **OpenStack OVS/VXLAN 50B MTU blackholes**, interactive SVG **PostgreSQL `pg_locks` Wait-For Graph ($G=(V,E)$) deadlocks**, and **Linux cgroup v2 `OOMKilled`** counters. Fuses priors with a **BM25 + TF-IDF Cosine Runbook RAG** engine via Reciprocal Rank Fusion, enforces a `shlex` read-only command firewall, and runs cryptographic **SHA-256 SQL backup/restore drills**. | [![Live](https://img.shields.io/badge/Live_App-sentinel--sre-10b981?style=flat-square&logo=vercel)](https://sentinel-sre-iota.vercel.app)<br>[![CI](https://github.com/whysari/sentinel-sre/actions/workflows/ci.yml/badge.svg)](https://github.com/whysari/sentinel-sre/actions/workflows/ci.yml)<br>`24/24 Top-1 · p95 4.91ms · RTO 3.84ms` |
| **[aegis-ci](https://github.com/whysari/aegis-ci)**<br>`Next.js 16` · `FastAPI` · `Python AST` · `SQL` | **Multi-Agent Worktree Release Gate & PostgreSQL 18 DDL Lock Analyzer**<br>Coordinates 4 parallel coding agents across isolated `git worktree` branches through a deterministic **5-Stage Release Gate**: 2:1 test-to-code ratio, **Red-to-Green mutation verification**, **Python `ast.NodeVisitor` security auditing** (`AST-SEC-001`..`005`), and static **PostgreSQL 18 DDL lock analysis** catching `ACCESS EXCLUSIVE` / `SHARE` hazards (`PG-LOCK-001`..`006`) with **Expand/Contract rewrites**. | [![Live](https://img.shields.io/badge/Live_App-aegis--ci-3b82f6?style=flat-square&logo=vercel)](https://aegis-ci.vercel.app)<br>[![CI](https://github.com/whysari/aegis-ci/actions/workflows/ci.yml/badge.svg)](https://github.com/whysari/aegis-ci/actions/workflows/ci.yml)<br>`18/18 Unsafe PRs Blocked · 0 Rollbacks` |
| **[openstack-caracal-multinode](https://github.com/whysari/openstack-caracal-multinode)**<br>`OpenStack Caracal` · `OVS/VXLAN` · `LVM/iSCSI` | **5-Node Private Cloud & SDN Overlay Infrastructure**<br>Multi-node private cloud cluster on Ubuntu 22.04 LTS provisioning **Keystone v3**, **Glance**, **Placement**, **Nova/KVM** compute hypervisors, **Neutron ML2/OVS** dual-tier SDN networking (tenant VXLAN overlays + flat provider floating IP pools with verified SNAT routing), **Cinder LVM/iSCSI** block storage, and **Swift** multi-ring object storage. | [Repository & Runbooks ↗](https://github.com/whysari/openstack-caracal-multinode)<br>`5-Node Cluster · OVS VXLAN · Swift Rings` |
| **[jewelry_rcg](https://github.com/whysari/jewelry_rcg)**<br>`Python` · `TensorFlow/Keras` · `Flask` · `OpenCV` | **Encoder-Decoder Computer Vision & Captioning Service**<br>Evaluated 6 CNN + RNN architectures (VGG-16, InceptionV3, MobileNet paired with LSTM and GRU) across $\approx$2,500 augmented samples, selecting **VGG-16 + GRU** and deploying an interactive **Flask** and **OpenCV** inference web service. | [Repository & Thesis Code ↗](https://github.com/whysari/jewelry_rcg)<br>`91.18% CCR · 95.71% Caption Acc · >94% F1` |

---

### Technical Stack

| Layer | Technologies |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript (ES6+), Python, PHP 8, SQL, Bash, Dart, C/C++ |
| **Frontend** | React 19, Next.js 16 (App Router, Server Actions), Vue 3, Mantine UI, DevExtreme React, Tailwind CSS |
| **Backend & APIs** | Laravel 12, FastAPI, Node.js, Express.js, Flask, RESTful APIs, Server-Sent Events (SSE) |
| **Databases & Storage** | PostgreSQL 18 (`pg_locks` Wait-For Graphs, zero-downtime DDL, ACID ledgers), Redis 8, MariaDB/MySQL, SQLite WAL, Cinder LVM/iSCSI, Swift Object Rings |
| **Cloud, SRE & Observability** | OpenStack (Nova/KVM, Neutron ML2/OVS VXLAN, Keystone, Glance, Cinder, Swift), Docker, Kubernetes, Linux cgroup v2, Prometheus, Grafana, Cryptographic DR Drills |
| **Testing, Security & AI** | Claude Code, Multi-Agent `git worktree` Orchestration, Hybrid BM25 + TF-IDF Cosine RRF RAG, PHPUnit, Playwright E2E, Python AST Security Auditing, PHPStan, OWASP ZAP, Gitleaks, GitHub Actions |
