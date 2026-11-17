### Hi, I'm Chabib 👋

**Server Engineer** in Indonesia. I build and run the infrastructure behind hospital information systems: PostgreSQL HA clusters, Kubernetes on Proxmox, site-to-site VPN meshes, monitoring that pages the right person, and security tooling on every endpoint.

Most of my day-to-day work lives in private repos, so the labs below rebuild the same patterns from scratch for anyone to run.

#### 🧪 Labs you can run

| Repo | What it shows |
|---|---|
| [**pg-ha-lab**](https://github.com/mchabib/pg-ha-lab) | PostgreSQL 16 + Patroni + etcd + HAProxy. Crashes the leader during writes and measures the gap: **20.7 s** on a crash, **7.0 s** on a clean stop. Includes a real bug it caught: a DNS lookup that stalled promotion for 43 s. |
| [**pg-backup-verified**](https://github.com/mchabib/pg-backup-verified) | Backups that prove they restore. Checksummed manifests, weekly restore drills in an isolated container, staleness alerts. shellcheck + bats + end-to-end CI. |
| [**server-report-go**](https://github.com/mchabib/server-report-go) | Scheduled per-client server health reports to Telegram from a federated Prometheus. Single Go binary. |
| [**genshin-build-checker**](https://github.com/mchabib/genshin-build-checker) | Side project: an offline damage and rotation calculator in TypeScript. |

#### 🛠️ What I work with

- **Infra**: Proxmox VE · LXC · RHEL / AlmaLinux / Ubuntu · Docker · k3s
- **Databases**: PostgreSQL (Patroni, streaming replication, pgBackRest) · MySQL · Redis
- **Observability**: Prometheus · Alertmanager · Grafana · Loki · Alloy · Zabbix
- **Network & security**: NetBird / WireGuard · HAProxy · keepalived · Nginx · Caddy · Wazuh
- **Automation**: Bash · Python (FastAPI) · Go · TypeScript · Jenkins

#### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/mcrahman/) · mchabiiib@gmail.com
