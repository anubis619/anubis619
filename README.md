# 👋 Hello, I'm Alex

IAM Engineer focused on **Identity, Security Engineering, and Infrastructure Automation**.

I enjoy building systems that are **secure, observable, and reproducible** using tools like Terraform, Linux, and modern cloud platforms.

Outside of work I build **homelab infrastructure, SIEM systems, and developer tools** to explore security, monitoring, and automation.

---

# 🔐 Areas of Focus

- Identity & Access Management
- Security Engineering
- Detection Engineering / SIEM
- Infrastructure as Code
- Homelab Automation
- Backend Development (Go)

---

# 🧰 Technology Stack

### Languages

![Go](https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python)
![Bash](https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash)

### Infrastructure

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=for-the-badge&logo=terraform)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux)

### IAM & Security

![Okta](https://img.shields.io/badge/Okta-007DC1?style=for-the-badge&logo=okta)
![Azure](https://img.shields.io/badge/Microsoft%20Entra-0078D4?style=for-the-badge)
![Active Directory](https://img.shields.io/badge/Active%20Directory-003366?style=for-the-badge)
![Wazuh](https://img.shields.io/badge/Wazuh-SIEM-blue?style=for-the-badge)

### Observability

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus)
![Loki](https://img.shields.io/badge/Loki-000000?style=for-the-badge)

---

# 🚀 Featured Projects

### 📚 Chronicle
Go CLI tool that collects **book metadata via ISBN** and stores it in a database used for **Grafana dashboards and reading analytics**.

Features:

- ISBN normalization
- Metadata ingestion
- PostgreSQL storage
- Grafana visualization

---

### 🔍 SIEM Project

Personal **Wazuh-based SIEM lab** used to explore:

- detection engineering
- log ingestion
- security monitoring
- alert pipelines

---

### 🧠 Terraform Homelab

Infrastructure-as-Code driven homelab including:

- monitoring stack
- DNS infrastructure
- SIEM deployment
- media services
- automation pipelines

All infrastructure is **fully reproducible using Terraform**.

---

# 🖥 Homelab Architecture

```mermaid
flowchart TD

Internet --> Cloudflare
Cloudflare --> Ardan
Cloudflare --> Domhain

subgraph VPS["Ardan - Fedora VPS"]
    Ardan[Ardan]
    Ardan --> Grafana[Grafana]
    Ardan --> Wazuh[Wazuh]
    Ardan --> Dozzle[Dozzle]
    Ardan --> Beszel[Beszel]
    Ardan --> Ops[Other operational services]
end

subgraph Home["Drassil - Main Home Server / Steam Machine"]
    Drassil[Drassil]
    Drassil --> Media[Media services]
    Drassil --> Steam[Steam Machine role]
    Drassil --> Sandbox[Sandbox Docker workloads]
    Drassil --> BookDB[Book DB sandbox]
    Drassil --> Future[Future self-hosted services]
end

subgraph Edge["Domhain - Raspberry Pi"]
    Domhain[Domhain]
    Domhain --> AdGuard[AdGuard]
    Domhain --> Caddy[Caddy]
end

Ardan --> Drassil
Domhain --> Drassil
```

---

# 📈 Security & Monitoring Stack

My monitoring and detection pipeline includes:

| Component | Purpose |
|--------|--------|
| Wazuh | SIEM / Threat Detection |
| Grafana | Observability dashboards |
| Prometheus | Metrics collection |
| Loki | Log aggregation |
| Terraform | Infrastructure provisioning |
| Docker | Service orchestration |

---

# 📊 Development Activity

<p align="center">
<a href="https://github.com/anuraghazra/github-readme-stats">
<img src="https://github-readme-stats.vercel.app/api?username=anubis619&show_icons=true&theme=tokyonight" />
</a>
</p>

<p align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=anubis619&theme=tokyonight" />
</p>

---

# ⚡ Coding Activity

<p align="center">
<a href="https://wakatime.com/@anubis619">
<img width="500" src="https://wakatime.com/share/@anubis619/d62dfefc-3dee-4d20-8681-d38b8d88bdee.svg" />
</a>
</p>

---

# 🌱 Currently Learning

- Go development for CLI tools
- Detection engineering
- Security architecture
- Advanced Terraform workflows

---

# 🐍 Contribution Graph

<p align="center">
  <img src="https://github.com/anubis619/anubis619/blob/output/github-contribution-grid-snake.svg" alt="snake animation" />
</p>

---

# 📫 Connect With Me

GitHub:  
https://github.com/anubis619
