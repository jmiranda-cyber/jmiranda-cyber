# Hi, I'm Javier Miranda 👋
### Cybersecurity Analyst | IT Support Specialist | Florida, USA

> I build, break, and secure things in my homelab so I can protect them better in production.  
> IT Support Specialist with 3+ years of enterprise experience, transitioning into Network Security and SOC operations.  
> Security+ and CCNA certified with hands-on homelab infrastructure and active SOC training.

---

## 🎓 Certifications

| Certification | Issuer | Status |
|---|---|---|
| CompTIA Security+ | CompTIA | ✅ Earned |
| Cisco CCNA | Cisco | ✅ Earned |
| CompTIA Network+ | CompTIA | ✅ Earned |
| CompTIA A+ | CompTIA | ✅ Earned |
| TryHackMe SOC Analyst 1 | TryHackMe | ✅ Earned |
| AWS Cloud Foundations | Amazon Web Services | ✅ Earned |
| TestOut Server Pro: Install & Storage | TestOut | ✅ Earned |
| TestOut Client/PC Pro | TestOut | ✅ Earned |

---

## 🛡️ Homelab & Practical Projects

---

### 🔒 [Homelab DNS Security Audit](https://github.com/jmiranda-cyber/homelab-security-audit)
Self-directed security audit of a Pi-hole v6 + Unbound + Tailscale DNS privacy stack on Raspberry Pi Zero 2W.
- Identified and remediated **8 findings** across Critical, High, Medium, and Informational severity levels
- Verified CVE-2024-1488 exposure on Unbound remote control interface
- Applied 10 Unbound hardening directives — blocked DNS fingerprinting, DNSSEC downgrade, and amplification attacks
- Discovered and fixed silent **IPv6 DNS leak** via NetworkManager — completely invisible during normal operation
- Deployed **Fail2ban** with live brute-force testing from an untrusted network segment
- Enforced **MFA on Tailscale identity provider** (GitHub OAuth) — identified as the single weakest link in the stack
- Automated weekly backups and unattended OS security patching
- Documented all findings with live command output — verified before and after each remediation

**Stack:** `Pi-hole v6` `Unbound` `Tailscale` `Fail2ban` `Debian 12` `Quad9 DoT` `DNSSEC` `nftables`

---

### 🌐 OPNsense Firewall & VLAN Network Segmentation
Enterprise-grade network segmentation on a home network using OPNsense as the perimeter firewall.
- Designed and deployed **4 isolated VLANs** — Main, Guest, IoT, and Internal
- Configured inter-VLAN firewall rules enforcing least-privilege access between segments
- Deployed **UniFi U7 Lite AP** (WiFi 7) with per-SSID VLAN tagging over 2.5GbE uplink
- Forced all DNS traffic through Pi-hole — blocked port 53/853 bypass at the firewall level
- Configured DHCP per VLAN via Dnsmasq with Pi-hole and Quad9 as DNS resolvers
- Implemented Zero Trust principles — devices isolated by default, access granted explicitly

**Stack:** `OPNsense` `UniFi` `VLAN` `802.1Q` `nftables` `Dnsmasq` `Zero Trust`

---

### 📊 Splunk Log Analysis & Dashboard Building
Analyzed GitHub and home router logs using Splunk to build monitoring dashboards and simulate SOC workflows.
- Ingested and parsed real log data from multiple sources
- Built dashboards to visualize anomalies, traffic patterns, and suspicious activity
- Simulated monitoring and reporting workflows used in enterprise IT and SOC environments
- Practiced alert triage and documentation as part of incident response simulation

**Stack:** `Splunk` `Log Analysis` `SIEM` `Dashboard` `Incident Response`

---

### 🎣 Phishing Analysis Lab
Conducted hands-on phishing email analysis simulating SOC email triage workflows.
- Examined raw email headers to identify malicious indicators and delivery paths
- Analyzed `Return-Path`, `Received` headers, and sender infrastructure to detect suspicious IPs
- Verified **SPF, DKIM, and DMARC** authentication results to assess email legitimacy
- Identified spoofing attempts and documented findings following SOC incident reporting procedures

**Stack:** `Email Forensics` `SPF/DKIM/DMARC` `Header Analysis` `Phishing Triage` `SOC Workflows`

---

### 🥧 [Raspberry Pi 4 OS Installation Guide](https://github.com/jmiranda-cyber/pi4os-installation-guide)
Comprehensive guide for installing Raspberry Pi OS on a Pi 4, including Windows Defender conflict resolution and SD card recovery procedures.

**Stack:** `Raspberry Pi` `Linux` `SD Card Recovery` `Windows`

---

## 🧰 Technical Skills

```
Network Security     OPNsense · VLAN Segmentation · Firewall Rules · Zero Trust · Netskope Private Access
DNS & Privacy        Pi-hole · Unbound · DNS-over-TLS · DNSSEC · Quad9
Monitoring & SIEM    Splunk · SolarWinds · Microsoft Sentinel · Wireshark · tcpdump · Fail2ban
Cloud & IAM          Microsoft Azure · Azure Active Directory · AWS Fundamentals
Linux                Debian · Kali Linux · Bash · systemd · cron · SSH hardening
Remote Access        Tailscale · VPN · Zero Trust Networking
Frameworks           MITRE ATT&CK · NIST · OSI Model · TCP/IP
IT Operations        ServiceNow · Windows · macOS · Active Directory · Imaging · Hardware
CTF & Training       TryHackMe SOC Analyst 1 · 70+ structured labs · OSCP path (in progress)
```

---

## 📚 Currently Working On

- 🔴 **TryHackMe** — progressing through OSCP learning path
- 🔴 **OPNsense hardening** — enforcing DNS firewall rules on Guest and IoT VLANs
- 🟡 **SSH key authentication** — replacing password auth on all homelab nodes
- 🟡 **Synology NAS** — self-hosted offsite backup and media infrastructure
- 🟢 **Kali Linux** — dual-boot lab for penetration testing practice

---



---

## 🤝 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Javier%20Miranda-blue?style=flat&logo=linkedin)](https://linkedin.com/in/javier-miranda-3060701b9)
[![GitHub](https://img.shields.io/badge/GitHub-jmiranda--cyber-black?style=flat&logo=github)](https://github.com/jmiranda-cyber)

---

*"Security is not a product, it's a process."* — Bruce Schneier
