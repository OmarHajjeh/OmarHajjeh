<div align="center">

# Omar Hajjeh

**Cloud & DevOps · AWS Certified Cloud Practitioner · Paris, France**

<p>
  <a href="https://omarlab.me"><img src="https://img.shields.io/badge/Portfolio-omarlab.me-000000?style=for-the-badge&logo=firefox&logoColor=white" /></a>
  <a href="https://linkedin.com/in/omar-hajjeh"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge" /></a>
  <a href="mailto:omarhj.fr@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>

</div>

Computer Engineering graduate, currently a research intern at the EFREI Paris Research Lab working on post-quantum cryptography for 5G/6G networks.

The rest of my time goes to cloud infrastructure and automation. Most of it runs on one server I manage entirely from Git.

## Projects

### [Homelab: GitOps Cloud Platform](https://omarlab.me)

My own server on Oracle Cloud, managed entirely from a Git repository. Every merge to `main` is deployed by GitHub Actions through a self-hosted runner, and secrets are stored in the repo encrypted with SOPS. It runs:

- **Traefik** in front of every service, with automatic HTTPS (Let's Encrypt via Cloudflare DNS-01)
- **NetBird** as a self-hosted VPN: admin tools are only reachable from my own devices
- **Prometheus + Grafana** monitoring with alerting to Telegram, plus an external check in case the whole server goes down
- an **AI assistant in an isolated Linux container** (Incus) with its own firewall and automated security tests before every update
- **Renovate** for dependency update PRs and unattended security patching

`GitHub Actions` `Docker` `Traefik` `NetBird` `Prometheus` `Grafana` `Incus` `Oracle Cloud`

### [Multi-Tenant Cloud Hosting Platform](https://github.com/OmarHajjeh/erpnext-saas)

ERPNext SaaS on Oracle Cloud. A Bash CLI provisions a full per-customer stack in one command, and Traefik issues SSL for every tenant subdomain through the Cloudflare DNS-01 API with no manual steps.

`Docker Compose` `Traefik` `Cloudflare` `Oracle Cloud` `Bash`

### [Proxy Comparative Analysis](https://github.com/OmarHajjeh/Proxy-Comparative-Analysis)

Benchmarked Nginx, HAProxy and Caddy as load balancers in front of a stateless 3-tier architecture, with MySQL replication and Redis session caching.

`Nginx` `HAProxy` `Caddy` `MySQL` `Redis`

---

## Stack

| Category | Technologies |
| :--- | :--- |
| **Cloud & Containers** | ![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square) ![Oracle](https://img.shields.io/badge/-Oracle_Cloud-F80000?style=flat-square) ![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Linux Containers](https://img.shields.io/badge/-Incus_/_LXC-333333?style=flat-square&logo=linuxcontainers&logoColor=white) ![Cloudflare](https://img.shields.io/badge/-Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white) |
| **CI/CD & Automation** | ![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white) ![Bash](https://img.shields.io/badge/-Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Renovate](https://img.shields.io/badge/-Renovate-1A1F6C?style=flat-square&logo=renovate&logoColor=white) |
| **Monitoring** | ![Prometheus](https://img.shields.io/badge/-Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/-Grafana-F46800?style=flat-square&logo=grafana&logoColor=white) |
| **Networking & Security** | ![Traefik](https://img.shields.io/badge/-Traefik-24A1C1?style=flat-square&logo=traefikproxy&logoColor=white) ![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![NetBird](https://img.shields.io/badge/-NetBird-F68330?style=flat-square&logo=wireguard&logoColor=white) ![Let's Encrypt](https://img.shields.io/badge/-Let's_Encrypt-003A70?style=flat-square&logo=letsencrypt&logoColor=white) |
| **Databases** | ![MySQL](https://img.shields.io/badge/-MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![Redis](https://img.shields.io/badge/-Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Programming & OS** | ![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=white) ![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |

**Learning now:** Terraform, Kubernetes. Working toward the AWS Solutions Architect – Associate certification.
