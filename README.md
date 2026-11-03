<div align="center">

  <!-- Isometric Artistic Workspace Hero Illustration -->
  <img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="700" alt="Artistic Isometric Workspace" />

  <br/><br/>

  <!-- Dynamic Typing Header -->
  <a href="https://github.com/0xAndyNew">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=24&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&height=50&lines=0xAndyNew+%E2%80%A2+Systems+%26+Infrastructure+Architect;Automating+Linux%2C+Clouds+%26+High-Availability+Networks;Hardening+Security+%E2%80%A2+Orchestrating+Containers" alt="Typing Header" />
  </a>

  <p align="center">
    <em>"Architecting resilient systems, optimizing uptime, and hardening enterprise infrastructure."</em>
  </p>

  <!-- Clean Contact & Identity Badges -->
  <p align="center">
    <a href="mailto:179321164+0xAndyNew@users.noreply.github.com">
      <img src="https://img.shields.io/badge/Direct_Mail-179321164+0xAndyNew-38BDF8?style=for-the-badge&logo=minutemailer&logoColor=white" alt="Email" />
    </a>
    <a href="https://github.com/0xAndyNew">
      <img src="https://img.shields.io/badge/Identity-0xAndyNew-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=0xAndyNew&label=TOTAL_VIEWS&style=for-the-badge&color=38bdf8" alt="Views" />
  </p>

</div>

---

### 🗺️ Production Infrastructure Architecture

```mermaid
flowchart TD
    subgraph PERIMETER["🌐 Perimeter & Ingress Layer"]
        CF["Cloudflare DNS & Edge Protection"] -->|HTTPS / TLS 1.3| NGINX["Nginx Reverse Proxy & Load Balancer"]
        CERT["Certbot / Let's Encrypt"] -.->|Auto SSL Renewal Pipeline| NGINX
    end

    subgraph CORE["🐧 Linux Core & Workloads (CentOS / RHEL / Ubuntu)"]
        NGINX -->|Proxy Pass| ZIMBRA["Zimbra Mail Cluster (SMTP / IMAP / Webmail)"]
        NGINX -->|Routing| DOCKER["Docker Containers & Microservices"]
        SCRIPTS["Bash & Python Automation Engines"] -.->|Cron & Daemons| ZIMBRA
        SCRIPTS -.->|Maintenance Tasks| DOCKER
    end

    subgraph SECURITY["🛡️ Perimeter Security & Defense"]
        FW["Firewall (IPTables / UFW)"] --- CORE
        VPN["WireGuard VPN Bastion"] -->|Zero-Trust Admin Tunnel| CORE
    end
```

---

### 📊 Engineering Domain & Workload Distribution

```mermaid
pie title Infrastructure & Engineering Allocation
    "Linux Systems Administration & Tuning" : 35
    "Automation & Scripting (Bash / Python / Cron)" : 25
    "Enterprise Mail & SSL (Zimbra / Postfix / PKI)" : 20
    "DevOps & Security (Docker / WireGuard / Firewall)" : 20
```

---

### 🎛️ Technical Competencies & Proficiency

| Engineering Domain | Execution Index | Core Responsibilities & Tooling |
| :--- | :---: | :--- |
| **Linux Systems Engineering** | `████████████████████` 100% | Kernel Hardening, SSH Bastions, CentOS, RHEL, Ubuntu |
| **PKI & Certificate Automation** | `████████████████████` 100% | Let's Encrypt automated renewal, OpenSSL, TLS 1.3 |
| **Automation & Shell Scripting** | `██████████████████░░` 90% | Production Bash pipelines, Python sysadmin daemons |
| **Enterprise Mail Infrastructure** | `█████████████████░░░` 85% | Zimbra Collaboration Suite, Postfix, SPF/DKIM/DMARC |
| **Network Security & Firewalls** | `█████████████████░░░` 85% | WireGuard VPN, IPTables, Nginx Reverse Proxy |
| **Containers & Deployment** | `████████████████░░░░` 80% | Docker containerization, GitHub Actions CI/CD |

---

### 🎨 Isometric Tech Arsenal

<div align="center">
  <p><em>Curated technologies & toolchains powering the infrastructure:</em></p>
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=linux,ubuntu,debian,bash,python,docker,nginx,cloudflare,git,githubactions,ansible,openssl&perline=6&theme=dark" alt="Isometric Tech Icons" />
  </a>
</div>

---

### 📈 Activity & Telemetry

<div align="center">
  <!-- 3D Area Wave Activity Graph -->
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=0xAndyNew&theme=tokyo-night&bg_color=0d1117&color=38bdf8&line=38bdf8&point=ffffff&area=true&hide_border=false&border_radius=12" width="100%" alt="Activity Wave Graph" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=0xAndyNew&show_icons=true&theme=tokyonight&hide_border=false&border_radius=12&border_color=38bdf8&title_color=38bdf8&icon_color=38bdf8&text_color=94a3b8&bg_color=0d1117" height="170" alt="Stats" />
  &nbsp;&nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xAndyNew&layout=compact&theme=tokyonight&hide_border=false&border_radius=12&border_color=38bdf8&title_color=38bdf8&text_color=94a3b8&bg_color=0d1117" height="170" alt="Top Languages" />
</div>

---

<div align="center">
  <sub>Designed with precision for <strong>0xAndyNew</strong> • Powered by Linux & Open Source</sub>
</div>
