# Arvyxa Resolver

A free, privacy focused and encrypted public DNS resolver with servers in India and Singapore.
Both nodes are synchronized and load balanced for optimal latency and redundancy.

> **Uptime (Last Month)** - 99.985% 🇮🇳 India and 99.992% 🇸🇬 Singapore, resulting in an overall 100% network uptime.

---

### ✨ Features

- **Zero Logs** - Nothing is stored    
- **Dual Stack** - Native IPv4 and IPv6 support
- **Encrypted DNS** - Supports DoH, DoT, DoQ, DoH3 (no plain DNS)
- **QNAME Minimization** - Sends only necessary info to upstream servers
- **DNSSEC Validation** - Cryptographically verifies domain authenticity
- **No EDNS Client Subnet** - Prevents leaking your location via subnet data
- **Ads, Trackers & Malware Blocking** - Actively blocks ads, trackers and phishing domains  

---

### 🔗 Supported Protocols

| Protocol | Hostname                           | Port      |
|----------|------------------------------------|-----------|
| **DoH**  | `https://dns.arvyxa.com/dns-query`  | 443/tcp   |
| **DoH3** | `https://dns.arvyxa.com/dns-query`  | 443/udp   |
| **DoT**  | `dns.arvyxa.com`                    | 853/tcp   |
| **DoQ**  | `dns.arvyxa.com`                    | 853/udp   |

---

## 🔒 Privacy Policy & Disclaimer

I run this resolver because I wanted a reliable and encrypted DNS option apart from big tech in this region.
I don't collect or store any information about you or your DNS queries.
The only filtering that happens is to block domains known for ads, malware, or trackers.
Every other query is resolved just as it should be without any censorship or profiling.

All of the configuration files available here in this GitHub repository.
If you find something in them that unintentionally logs or leaks data, I would genuinely appreciate it if you opened an issue and if possible a fix or suggestion.
I run this as a personal hobby project and community feedback helps me make it better and safer for everyone.

> This Resolver is provided as-is with no uptime guarantees so use at your own discretion.

## 🙏 Thank You

This project would not have been possible without the incredible open-source ecosystem.  
Special thanks to:

- 🌀 **[Knot Resolver](https://www.knot-resolver.cz/)** - The core DNS engine  
- 🛡️ **[dnsdist](https://dnsdist.org/)** - Smart and secure load-balancer  
- ✖️ **[hagezi blocklists](https://github.com/hagezi/dns-blocklists)** - High-quality blocklists

---
