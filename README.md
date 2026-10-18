# Hi, I'm Muhamad 👋

**DevOps engineer** building self-hosted infrastructure, Python backends and automation on Linux, packaged to run with a single `docker compose up`.

💼 **Open to freelance and contract work.**

## What I can do for you

- **Get your servers in shape**: Linux hardening, nftables firewalls, Nginx/OpenResty reverse proxies, TLS (Let's Encrypt), systemd services
- **Containerize and deploy**: Dockerfiles, Docker Compose stacks, Swarm, Kubernetes, Jenkins and CI/CD pipelines
- **Build backends and admin panels**: Django + DRF, FastAPI, PostgreSQL, Redis, Celery background jobs
- **Self-host instead of renting**: your own mail server, DNS/CDN/WAF edge, or virtualization control plane
- **Protect and observe your traffic**: WAF rules, rate limiting, brute-force bans, anti-bot/CAPTCHA, log and IP analysis
- **Automate the boring parts**: Python tooling, SSH-driven ops, data enrichment pipelines, FFmpeg tooling

## Featured projects

| Project | Why it's useful | Stack |
| --- | --- | --- |
| [Open-Shield](https://github.com/muerfox/Open-Shield) | Your own Cloudflare: authoritative DNS, caching CDN and WAF with zero-reload config | FastAPI, OpenResty/Lua, PowerDNS, Redis, PostgreSQL, Docker |
| [Node-Pilot](https://github.com/muerfox/Node-Pilot) | Multi-host KVM/QEMU control plane (VMs, storage, networks, snapshots, backups) with an agent per host, RBAC and jobs | Django, DRF, Channels, Celery, libvirt, React, TypeScript |
| [DevOps-ToolKit](https://github.com/muerfox/DevOps-ToolKit) | One self-hosted cockpit for Docker, Swarm, Kubernetes, Jenkins, Git and SSH, plus a CI/CD pipeline builder | FastAPI, Docker |
| [Novella-Mail](https://github.com/muerfox/Novella-Mail) | Multi-domain mail server with a webmail and admin panel, set up by a guided script | Django, docker-mailserver (Postfix, Dovecot, Rspamd) |
| [Port-Warden](https://github.com/muerfox/Port-Warden) | Host firewall desk: nftables policy with preview/apply, port inventory, SSH brute-force bans, rollback scripts | FastAPI, SQLite, nftables, Docker |
| [IP-Scout](https://github.com/muerfox/IP-Scout) | Pulls IPs from Nginx logs over SSH, enriches with WHOIS/geo and CIDR data, dashboard + REST API | Django, DRF, PostgreSQL, Celery, Redis, HTMX |
| [Gate-Keeper](https://github.com/muerfox/Gate-Keeper) | Layered CAPTCHA/anti-bot platform with widget, React/Vue SDKs, admin dashboard and offline mode | TypeScript, Fastify, React, Prisma, PostgreSQL, Redis |

More: [Onion-Brute](https://github.com/muerfox/Onion-Brute) (Tor v3 vanity address generator, tested and Dockerized) · [Encode-Kit](https://github.com/muerfox/Encode-Kit) (object-oriented FFmpeg command builder) · [Jelveh-Desktop](https://github.com/muerfox/Jelveh-Desktop) (Qt desktop client packaged for Linux and Windows)

## Tech

**Infra:** `Linux` `Docker` `Docker Compose` `Docker Swarm` `Kubernetes` `Jenkins` `Nginx` `OpenResty` `PowerDNS` `nftables` `KVM/QEMU` `libvirt` `systemd` `Bash`
**Backend:** `Python` `Django` `Django REST Framework` `FastAPI` `Celery` `PostgreSQL` `Redis` `SQLite`
**Also:** `TypeScript` `React` `Fastify` `Qt` `FFmpeg`

## How I work

Things I care about, as you can see in the repos: one-command deploys, safe defaults (localhost-bound panels, preview before applying, rollback scripts), and docs that explain the threat model and the tradeoffs.

## Contact

Need infrastructure set up, a backend built, or a self-hosted alternative to a SaaS? Reach out through GitHub or open an issue on any repo.
