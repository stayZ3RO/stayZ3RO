### Hey, I'm Christopher 👋

I'm an IT Service Desk Analyst II. I work on automation, infrastructure, and making operations easier to support. I automate the repetitive parts, then check the result.

🔗 **[View my portfolio](https://chrisalorenzo.com/)**: projects, evidence, resume, and contact.

Lab notes are at **[blog.chrisalorenzo.com](https://blog.chrisalorenzo.com/)**. `stayz3ro.dev` redirects there. The posts cover home DNS, the move onto Proxmox, the managed network, and the public VPS.

Public status is at **[status.chrisalorenzo.com](https://status.chrisalorenzo.com/)**. The page is public. The admin UI stays on my tailnet.

---

### What I'm working on right now

At work, I build AI Ops tools for a global service desk: n8n queue reporting, Jira automation, agent-assisted shift handoffs, and KBA lifecycle tooling. They are governed and git-backed, with the goal of reducing manual work.

At home, I'm rolling my three-node Proxmox cluster onto 9.2.21 and using a live Prometheus/Grafana dashboard to keep an eye on the lab. The domain move is complete: the blog and public status page now sit under chrisalorenzo.com.

I've also finished the design for a read-only AI lab assistant (Track G) and drafted private SSO with local recovery accounts. Those are designs, not deployed services. Infrastructure changes still need my approval.

---

### Featured projects

| Project | What it is |
| --- | --- |
| **[Home Network Infrastructure / HA DNS](https://github.com/stayZ3RO/dns)** | High-availability DNS: Pi-hole, Unbound, Keepalived, and Prometheus/Grafana. Gravity Sync is inactive. I've prepared Nebula Sync adoption and VRRP credential rotation with failover checks; deployment is still ahead. [v1.0.0](https://github.com/stayZ3RO/dns/releases/tag/v1.0.0). |
| **[Managed Network Infrastructure Lab](https://github.com/stayZ3RO/netlab)** | UniFi UDM Pro and USW-24-PoE replaced the Omada core on 2026-09-27. The network is still flat; VLAN and firewall design come next. [v1.0.0](https://github.com/stayZ3RO/netlab/releases/tag/v1.0.0). |
| **[VPS Cloud Infrastructure Lab](https://github.com/stayZ3RO/vps-lab)** | Netcup VPS with Caddy and HTTPS. Eight Uptime Kuma monitors, including a redirect check. Discord and self-hosted ntfy. Public status page at [status.chrisalorenzo.com](https://status.chrisalorenzo.com/), admin on the tailnet. Backups are planned. |
| **[AWS Network Automation Lab](https://github.com/stayZ3RO/cloud-netlab)** | AWS networking as code: a reusable Terraform/OpenTofu VPC module, a Python drift-check CLI with tests, and CI. Learning project, not deployed infrastructure. |

My [portfolio also has a v1.0.0 release](https://github.com/stayZ3RO/portfolio/releases/tag/v1.0.0). I keep the detailed lab controls private, but I'm happy to walk through the design choices.

---

### Technical stack

- **Infrastructure:** Linux · Proxmox · Docker / Compose · Tailscale
- **Networking & DNS:** Pi-hole · Unbound · Keepalived · UniFi
- **Automation & validation:** Python · Bash · PowerShell · pytest · GitHub Actions
- **Observability:** Prometheus · Grafana · Alertmanager
- **Cloud & IaC:** OpenTofu / Terraform · AWS networking-as-code
- **AI & Automation:** n8n · Jira API · Copilot Studio (work context)

---

### Certifications in progress

- CompTIA Network+ (studying)
- CompTIA Security+ (next)
- An AWS cloud certification (considering, likely SAA-C03)
- HashiCorp Terraform Associate (considering)

---

### How I work

- I learn the fundamentals, then build something real with them.
- A test, a CI run, or a captured result has to back the claim.
- I write down what was proven, and I keep private operational detail out of the public notes.
- AI speeds the draft. I still review what it produced.

---

### Let's connect

My portfolio is at **[chrisalorenzo.com](https://chrisalorenzo.com/)**. I'm always happy to talk shop.
