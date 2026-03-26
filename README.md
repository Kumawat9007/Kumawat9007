<h1 align="center">Jagdish Kumawat</h1>
<h3 align="center">Linux / DevOps • Networking • Server Security</h3>

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=22&duration=3000&color=00F7FF&center=true&vCenter=true&width=800&lines=VPS+Provisioning+%26+Deployment;Nginx+Reverse+Proxy+%26+PM2;Cloudflare+DNS+%2F+SSL+%2F+Caching;SSH+Hardening+%26+Firewall;Backups+%2F+Automation+%2F+Monitoring" />
</p>

---

## 🧭 What I Do

- Provision and secure **Ubuntu-based VPS**
- Deploy **Node.js apps** behind **Nginx reverse proxy**
- Manage **processes with PM2** (cluster, logs, startup)
- Configure **Cloudflare DNS, SSL, caching**
- Implement **security hardening** (SSH, UFW, Fail2Ban)
- Automate **backups, cron jobs, log rotation**

---

## 🧰 Stack

<p align="center">
<img src="https://skillicons.dev/icons?i=linux,nginx,nodejs,mongodb,mysql,git,github,cloudflare,bash,docker" />
</p>

---

## ⚙️ Capabilities (Practical)

| Area | What I Handle |
|---|---|
| Linux | users/permissions, systemd, logs (`journalctl`), disk/IO basics |
| Nginx | reverse proxy, SSL, gzip, caching, rate limiting |
| PM2 | cluster mode, auto-start, log management |
| DB | MongoDB / MySQL backups & restore |
| Security | SSH hardening, UFW, Fail2Ban, key-based auth |
| DNS/CDN | Cloudflare (A/AAAA/CNAME, proxy, SSL modes) |
| Automation | cron jobs, backup scripts |
| Containers | Docker (run images, ports, volumes – basic) |
| Monitoring | logs, uptime checks, CPU/RAM observation |
| Networking | ports, firewall rules, basic routing/NAT |

---

## 🔐 Security Baseline

```bash id="secblock01"
# SSH
PermitRootLogin no
PasswordAuthentication no
PubkeyAuthentication yes

# UFW (example)
ufw default deny incoming
ufw allow 22/tcp
ufw allow 80,443/tcp
ufw enable
