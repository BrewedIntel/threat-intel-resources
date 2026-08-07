# Threat Intelligence Resources
A curated list of open-source tools, datasets, sandboxes, scanning engines, and OSINT resources for cyber threat hunters, incident responders, DFIR analysts, and researchers.

This collection is designed to make investigation work easier by keeping high-value, free or community-driven resources in one place.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

---

## Table of Contents
- [Network Scanning & Exposure Mapping](#network-scanning--exposure-mapping)
- [IP, ASN & Geolocation Intelligence](#ip-asn--geolocation-intelligence)
- [Malware Analysis & Sandboxes](#malware-analysis--sandboxes)
- [Threat Feeds & IOC Sources](#threat-feeds--ioc-sources)
- [DNS & Domain Intelligence](#dns--domain-intelligence)
- [Threat Actor Profiles & Frameworks](#threat-actor-profiles--frameworks)
- [OSINT & Digital Footprinting](#osint--digital-footprinting)
- [Routing, Certificates & Infrastructure Mapping](#routing-certificates--infrastructure-mapping)
- [Dark Web & Leak Monitoring](#dark-web--leak-monitoring)
- [Tools & Utilities](#tools--utilities)
- [Contributing](#contributing)

---

## Network Scanning & Exposure Mapping
Tools that help identify exposed services, discover internet-facing infrastructure, and pivot across assets.

- **Censys** — https://search.censys.io  
  Large-scale internet scanning for hosts, certs, and services.

- **Shodan** — https://www.shodan.io  
  Search engine for exposed devices, protocols, and vulnerabilities.

- **modat.io** — https://modat.io  
  Simple interface for identifying externally exposed services.

- **urlscan.io** — https://urlscan.io  
  Sandboxes URLs and displays redirects, network calls, and metadata.

- **SecurityTrails** — https://securitytrails.com  
  DNS history, IP metadata, and domain intelligence.

- **OpenNIC Project**  
  - Wiki: https://wiki.opennic.org/opennic/dot  
  - Servers: https://servers.opennic.org  
  Alternative DNS root servers and open DNS infrastructure.

- **Netlas** — https://netlas.io  
  Internet indexing for DNS, certificates, and service enumeration.

- **Rapid7 Project Sonar** — https://opendata.rapid7.com/sonar.fdns_v2/  
  Open DNS and scanning datasets.

---

## IP, ASN & Geolocation Intelligence
Helpful for attribution, routing analysis, enrichment, and network-level context.

- **Team Cymru IP-ASN Mapping** — https://www.team-cymru.com/ip-asn-mapping  
  Accurate IP-to-ASN mapping and reputation lookups.

- **IPStack** — https://ipstack.com  
  IP geolocation, ASN, and risk scoring.

- **IP2Location** — https://www.ip2location.com  
  Geolocation and ISP metadata.

- **bgp.tools** — https://bgp.tools  
  BGP path, ASN visibility, and prefix insights.

- **Hurricane Electric BGP Toolkit** — https://bgp.he.net  
  Routing, ASN info, IX peering, and prefix analysis.

- **PeeringDB** — https://www.peeringdb.com  
  ASN peering, IXPs, and network operator data.

---

## Malware Analysis & Sandboxes
Detonation platforms for behavioral analysis, static inspection, and threat classification.

- **VirusTotal** — https://www.virustotal.com  
  File, IP, URL scanning across multiple engines.

- **Hybrid Analysis** — https://www.hybrid-analysis.com  
  Dynamic sandbox analysis by CrowdStrike.

- **Joe Sandbox** — https://www.joesandbox.com  
  In-depth static and dynamic analysis.

- **Triage** — https://tria.ge  
  Malware detonation, clustering, and behavioral logs.

- **ANY.RUN** — https://any.run  
  Interactive real-time sandbox environment.

- **Intezer Analyze** — https://analyze.intezer.com  
  Code-reuse and “genetic” malware analysis.

- **MalwareBazaar (Abuse.ch)** — https://bazaar.abuse.ch  
  Public malware sample repository.

- **CAPA** — https://github.com/mandiant/capa  
  Detects malware capabilities in binaries.

---

## Threat Feeds & IOC Sources
Community-driven IOC collections for malware C2s, botnets, ransomware, and malicious infrastructure.

- **ThreatFox (Abuse.ch)** — https://threatfox.abuse.ch  
  IPs, URLs, hashes, and malware indicators.

- **Feodo Tracker (Abuse.ch)** — https://feodotracker.abuse.ch  
  Qakbot, Dridex, and Feodo botnet tracking.

- **Viriback Tracker** — https://tracker.viriback.com  
  Botnet and malware infrastructure tracking.

- **MalBeacon** — https://malbeacon.com  
  Beaconing behavior detection and network telemetry.

- **Ransomwatch** — https://ransomwatch.telemetry.ltd/#/profiles  
  Ransomware leak site monitoring.

- **RansomLook** — https://www.ransomlook.io/groups  
  Ransomware group profiles and leak tracking.

- **MalwareIntel** — https://malwareintel.es  
  Free threat intelligence platform with 1.7M+ IOCs, 5,500+ Sigma detection rules, malware family profiles with MITRE ATT&CK TTPs, and downloadable detection packages.

- **MISP Project** — https://www.misp-project.org  
  Threat intel sharing platform used globally.

- **OpenPhish** — https://openphish.com  
  Free phishing IOC feed.

- **PhishTank** — https://phishtank.org  
  Community phishing URL verification.

---

## DNS & Domain Intelligence
Resolve infrastructure changes, pivot on DNS records, and explore domain history.

- **GreyNoise** — https://www.greynoise.io  
  Noise vs targeted activity, IP reputation.

- **PassiveDNS.info** — https://www.passivedns.info  
  Historical DNS resolution data.

- **DNSlytics** — https://dnslytics.com  
  Reverse DNS, hosting metadata, and subdomains.

- **ProjectDiscovery Chaos** — https://chaos.projectdiscovery.io  
  Massive community DNS dataset.

- **crt.sh** — https://crt.sh  
  Certificate Transparency search for domain discovery.

- **CertSpotter** — https://sslmate.com/certspotter  
  CT log monitoring for new domain certificates.

---

## Threat Actor Profiles & Frameworks

- **MITRE ATT&CK** — https://attack.mitre.org  
  Adversary TTP framework with techniques, groups, and software.

- **APT Map** — https://aptmap.net  
  Visualized APT relationships, campaigns, and activity.

- **CrowdSec Threat Intelligence** — https://crowdsec.net/threat-intelligence  
  Community IP reputation and attack telemetry.

---

## OSINT & Digital Footprinting
Useful for identity research, infrastructure mapping, and investigations.

- **Hunter.io** — https://hunter.io  
  Email enumeration and domain footprinting.

- **Epieos** — https://epieos.com  
  Email and account OSINT lookup.

- **Have I Been Pwned** — https://haveibeenpwned.com  
  Breach exposure lookup.

- **GitHub Archive** — https://www.gharchive.org  
  Developer activity and OSINT on code commits.

- **Wayback Machine** — https://archive.org/web  
  Historical snapshots of domains and infrastructure.

---

## Routing, Certificates & Infrastructure Mapping
Tools for BGP, TLS fingerprinting, CT logs, and network-level pivoting.

- **CIRCL Certificate Search** — https://www.circl.lu/services/certificate-search  
  Certificate metadata, SANs, and fingerprint pivoting.

- **JA3 Fingerprinting** — https://github.com/salesforce/ja3  
  TLS client fingerprinting.

- **JARM** — https://github.com/salesforce/jarm  
  TLS server fingerprinting.

- **RIPEstat** — https://stat.ripe.net  
  Routing history, visibility, and ASN analysis.

- **Shadowserver** — https://www.shadowserver.org/what-we-do/public-benefit-services/  
  Botnet, exposure, and security scans.

---

## Dark Web & Leak Monitoring
Some free, OSINT-safe resources exist for monitoring leaked data and Tor infrastructure.

- **dark.fail** — https://dark.fail  
  Tor service status and verified links.

- **Public BreachForum mirrors**  
  Mirrors used for OSINT on leaked data (avoid criminal sites).

---

## Tools & Utilities

- **CyberChef** — https://gchq.github.io/CyberChef  
  Universal data manipulation toolkit.

- **ProjectDiscovery Tools** — https://projectdiscovery.io  
  Recon and scanning tools (subfinder, nuclei, dnsx, httpx, etc.)

- **OWASP Amass** — https://github.com/owasp-amass/amass  
  Attack surface and subdomain enumeration.

- **Hindsight / Dumpzilla**  
  Browser forensics utilities.

---

## Contributing
Suggestions, PRs, and new tool recommendations are welcome!  
Feel free to submit improvements or new resources.
