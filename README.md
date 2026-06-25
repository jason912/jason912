# 👋 We keep your Niagara stations running.

**Shanghai Gline Net Co., Ltd.** — Founded by Jason Zhang.  
Tridium Niagara partner since 2014. Remote operations, maintenance, and engineering for mission-critical Niagara 4 systems.

---

## The Problem

Your Niagara stations are running 24/7. When something breaks — a BACnet device goes offline, an alarm floods the console, a Modbus point stops updating — you need it fixed **now**. But:

- Your best Niagara engineer is booked on another project
- Flying someone to site costs thousands and takes days
- The local integrator who installed it is long gone
- You don't have a maintenance contract, and when you call someone it's emergency rates

---

## Our Solution: Remote Niagara O&M

We act as your **remote Niagara engineering team**. No travel, no delays, no minimum commitment.

| Service | What We Do |
|---------|------------|
| 🔧 **Remote Commissioning & Debugging** | We connect to your station remotely, diagnose issues, and fix them in real time. BACnet, Modbus, MQTT, oBIX — any protocol. |
| 🧩 **Custom Protocol Integration** | Provide us with the communication point documentation of your legacy device. We use AI-powered tools to rapidly develop the integration interface protocol — no matter how obscure the device. |
| 🛡️ **Annual Maintenance Retainer** | Fixed monthly fee. Includes remote monitoring, alarm response, performance checkups, and priority access to our engineers. **Recurring, predictable cost.** |
| 🧱 **Custom Module Development** | Need a feature Niagara doesn't have out of the box? We build custom JAR modules — SFTP, REST API, MQTT clients, AI agents, whatever you need. |
| 🤖 **AI-Assisted Operations** | Automate alarm analysis, generate daily reports, query your station in plain English. Reduce the time your team spends on routine diagnostics. |

### AI-Powered Analysis - No Direct Network Required

We use AI to analyze your Niagara system without needing permanent access to your network. This is especially valuable for clients with strict security policies.

**Offline Analysis (email-based)**

1. Your Niagara station emails us a .bog file (captured by BogSnap at alarm time) or an alarm notification
2. Our AI analyzes the file - program state, point values, alarm conditions, historical context
3. You receive an **alarm dashboard** with root cause analysis, trend identification, and actionable recommendations
4. All done without any network connection to your facility - **zero security exposure**

**On-Premise Analysis (inside your network)**

For clients who want deeper integration, we deploy lightweight analysis tools inside your corporate network:

- Connects via **oBIX**, **REST API**, or ingests **JSON from MQTT**
- No direct VPN to our office needed - data flows one-way out
- Builds **automated analysis pipelines** that run continuously
- Generates alarm dashboards, trend reports, and predictive insights

This transforms a standard Niagara system from a reactive operation to a predictive one - dramatically increasing the value of your existing infrastructure.

### Time Zone Advantage

We are based in **Asia (GMT+8)**. While your team sleeps, we work.

| Your Time | Our Time | What Happens |
|-----------|----------|-------------|
| 🕐 **Your midnight** | **Our noon** | We handle overnight alarms, batch updates, and maintenance windows |
| 🕐 **Your morning** | **Our evening** | You wake up to a daily report with everything resolved |
| 🕐 **Your afternoon** | **Our night** | Overlapping hours for real-time collaboration |

This means **24-hour coverage** for your stations without paying for 24-hour local engineers. Your day shift handles strategy; our day shift handles execution while you sleep.

### How Remote Access Works

Network security stays in your hands. **You control the access, you stay compliant.**

To start remote work, your team sets up one of the following (we do not provide or manage VPN services):

- ✅ **VPN access** to your network (your own VPN solution)
- ✅ **Niagara Fox port** or **Niagara web port** exposed temporarily
- ✅ **Subsystem access** (BACnet/IP, Modbus TCP, etc.) if integrating a specific device

> We do not guide or manage your VPN or firewall configuration. Your IT/security team decides what to expose and how. If you need recommendations, we can discuss — but the control remains entirely with you.

### Security & Compliance

| Principle | What It Means |
|-----------|---------------|
| **Read-only by default** | All inside-network operations are read-only unless explicitly authorized |
| **Write requires approval** | Any write operation (set point, rename, delete) requires your prior written approval |
| **Method Statement & Risk Assessment** | Before any write operation, we provide a detailed method statement and risk assessment for your review and sign-off |
| **You own the network** | VPN, port exposure, firewall rules — all managed by your team. We never push for permanent changes.

### Why Remote Works

| Traditional On-site | Gline Remote |
|---|---|
| Schedule 2 weeks out | Connect **today** |
| Flight + hotel: $2,000–$5,000 | **Zero travel cost** |
| 1–2 days on site | **2–4 hours** to resolve most issues |
| Only available 9–5 | **Follow-the-sun coverage** |

---

## Proof of Capability: Our Free Modules

We publish free, production-tested Niagara 4 modules on GitHub. They serve two purposes:

1. **They solve real problems** — use them today, zero cost
2. **They prove we know what we're doing** — inspect the code, test the JARs, see the quality

| Module | What It Shows |
|--------|---------------|
| [BogSnap](https://github.com/jason912/Niagara-bogsnap) | Deep understanding of Niagara program objects, BQL, and station internals |
| [REST API](https://github.com/jason912/Niagara-Rest-API-service---Free) | We build production-grade REST endpoints for AI automation |
| [MQTT Client](https://github.com/jason912/Niagara4-MQTTClient) | We write reliable protocol drivers |
| [FRPC Tunnel](https://github.com/jason912/Niagara-4-FRPC-Module) | We solve real-world remote access problems |
| [BQL→JSON](https://github.com/jason912/NiagaraExportBql2json) | We bridge Niagara data with modern application stacks |
| [SFTP/SSH Client](https://github.com/jason912/NiagaraSFTP-SSHClient) | We build secure, enterprise-grade integrations |

> **All free to use. No license, no trial, no upsell.** If they help you, great. If you need something custom, call us.

---

## Pricing

### Annual Maintenance Retainer (Recurring)

| Plan | Monthly | What's Included |
|------|:-------:|-----------------|
| 🟢 **Essential** | Contact us | Remote monitoring, alarm response (8×5), quarterly health check |
| 🔵 **Professional** | Contact us | Everything in Essential + priority response (24×7), monthly reporting |
| 🏢 **Enterprise** | Contact us | Dedicated engineer, custom SLA, on-site option |

### One-Time Services

| Service | Starting From |
|---------|:------------:|
| Remote troubleshooting & debugging | **$200** |
| Custom protocol / device integration | Contact us |
| Custom module / JAR development | Contact us |
| Station migration (AX → N4) | Contact us |
| System integration & consulting | Contact us |

---

## About Us

```
Founded:    2014
Focus:      Tridium Niagara ecosystem only
Team:       Remote-first, Asia-based
Clients:    Enterprise facilities in Asia, Japan, Europe
Time zone:  GMT+8 (follow-the-sun with欧美)
Certified:  Niagara 4 Certified · EnOcean Alliance Member
```

---

## Contact

| | |
|---|-----|
| **Jason Zhang** | Founder & Managing Director |
| **Email** | [jason.zhang@gline-net.com](mailto:jason.zhang@gline-net.com) |
| **WhatsApp** | [+86 1380 190 9968](https://wa.me/8613801909968) |
| **Web** | [www.glineweb.com](https://www.glineweb.com) |
| **GitHub** | [github.com/jason912](https://github.com/jason912) |

**Have a station that needs attention? Send us a brief description and we'll reply within 24 hours.**

---

*Shanghai Gline Net Co., Ltd. — Remote Niagara Engineering & Operations*
