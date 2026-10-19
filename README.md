<div align="center">

# Omar Hajjeh

**Cloud & DevOps Engineer · Paris, France**

[![Portfolio](https://shields.io)](https://omarlab.me)
[![LinkedIn](https://shields.io)](https://linkedin.com/in/omar-hajjeh)
[![Email](https://shields.io)](mailto:omarhj.fr@gmail.com)

</div>

Computer Engineering graduate, currently a research intern at the EFREI Paris Research Lab working on post-quantum cryptography migrations for next-generation networks.

The rest of my focus goes toward cloud infrastructure, systems automation, and self-hosted environments.

---

## Technical Core Labs

### 🚀 [Homelab: GitOps Cloud Platform](https://omarlab.me)
A production-ready single-node instance on Oracle Cloud managed via GitOps workflows. Every merge to `main` auto-deploys via GitHub Actions utilizing a self-hosted runner, with secrets securely encrypted natively via SOPS.
- **Ingress & TLS:** Traefik edge proxy with automated Let's Encrypt handling via Cloudflare DNS-01 API validation.
- **Mesh Networking:** NetBird private overlay network isolating management dashboards behind a zero-trust plane.
- **Telemetry ring:** Central Prometheus engine gathering system metrics matched with Grafana dashboarding and Telegram alerts.
- **Security Sandboxing:** Isolated Linux micro-containers (Incus) hosting autonomous AI services bounded by restrictive internal firewalls.

`GitHub Actions` `Docker` `Traefik` `NetBird` `Prometheus` `Grafana` `Incus` `Oracle Cloud`

### 📦 [Multi-Tenant Cloud Hosting Platform](https://github.com/OmarHajjeh/erpnext-saas)
An ERPNext SaaS engine built out on Oracle Cloud environments. Features an automation Bash CLI capable of spinning up isolated, single-tenant container configurations on command while binding structural routing parameters through Traefik seamlessly.

`Docker Compose` `Traefik` `Cloudflare` `Oracle Cloud` `Bash`

### 🔬 [Proxy Comparative Analysis](https://github.com/OmarHajjeh/Proxy-Comparative-Analysis)
An experimental infrastructure laboratory monitoring and benchmark testing Nginx, HAProxy, and Caddy load balancers routing across a high-availability stateless 3-tier layout supported by Redis memory caches and replicated MySQL nodes.

`Nginx` `HAProxy` `Caddy` `MySQL` `Redis`

---

## Ecosystem Stack

| Layer | Tools |
| :--- | :--- |
| **Cloud & Runtime** | AWS, Oracle Cloud, Docker, Incus / LXC, Cloudflare |
| **CI/CD & Shell** | GitHub Actions, Git, Linux Bash, Python, Automated Renovate |
| **Monitoring** | Prometheus, Grafana Stack |
| **Network & Mesh** | Traefik Core, Nginx Edge, NetBird VPN, Let's Encrypt Security |
| **Storage Engines** | MySQL Core, Redis Enterprise Cache |

*Currently expanding architectures around:* **Terraform**, **Kubernetes (K8s)**, and prepping the **AWS Solutions Architect – Associate** track.
