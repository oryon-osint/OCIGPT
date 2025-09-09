# [OSINT360 ⌁ Cyber Intelligence GPT](https://tntpp9.short.gy/osint360-gpt)


![AI](https://img.shields.io/badge/AI-GPT5-critical)

## 🛡️ Overview

OSINT360 ⌁ Cyber Intelligence is a specialized **GPT-5-powered assistant** designed for **open-source intelligence (OSINT), digital forensics (DFIR), cyber investigations, ethical hacking, and operational security (OPSEC)**. It provides end-to-end support for intelligence operations, from collection and analysis to reporting and adversary profiling.

This GPT instance is optimized for:

- **OSINT collection & enrichment** (domains, IPs, usernames, social media, dark web)
    
- **DFIR workflows** (forensic triage, malware analysis, chain of custody)
    
- **Cybercrime investigations** (threat actor profiling, campaign mapping, crypto tracing)
    
- **Red/Blue/Purple Teaming** (adversary emulation, detection engineering, threat hunting)
    
- **OPSEC & Privacy** (anonymization, persona building, de-anonymization defense)
    
- **Compliance** (GDPR, AI Act, global cyber laws)
    

## ✨ Features

- **Command-based interaction** for fast execution of playbooks, reports, and checklists.
    
- **Structured outputs**: every report follows _Executive Summary → Key Findings → Evidence → Analysis → Risks → Recommendations → Next Steps_.
    
- **Tool-first approach**: always suggests open-source GitHub tools before commercial alternatives.
    
- **Up-to-date intelligence**: integrates live web lookups when fresh data is required.
    
- **Chain of custody compliance**: hashes, metadata preservation, evidence integrity.
    
- **Framework alignment**: MITRE ATT&CK, Diamond Model, Cyber Kill Chain.
    

## 📂 Core Commands

### Case & Workflow

- `/help` → Show full command reference.
    
- `/new` → Start a new case (OSINT, DFIR, Red Team, etc.).
    

### Reporting & Profiles

- `/report [entity]` → Full-spectrum OSINT report.
    
- `/profile [entity]` → Dossier profile (person, org, asset).
    
- `/timeline [entity]` → Exposure/events timeline.
    
- `/darkweb [entity]` → Dark web intelligence scan.
    

### Enrichment & Analysis

- `/enrich [IOC|entity]` → Enrich IP, domain, email, hash, wallet.
    
- `/exif [file|image]` → Extract metadata/EXIF.
    
- `/mitre [actor|incident]` → ATT&CK mapping of TTPs.
    
- `/iocs [campaign]` → IOC tables (CSV/Markdown/STIX).
    
- `/actor [name]` → Adversary group profile.
    
- `/campaign [name]` → Campaign infrastructure mapping.
    
- `/infrastructure [org]` → Org’s exposed infrastructure map.
    

### Playbooks & Templates

- `/playbook [scenario]` → IR/Red/Blue playbooks.
    
- `/template [scenario]` → Full investigation template.
    
- `/checklist [scenario]` → Step-by-step task checklist.
    

## 🛠️ Open-Source Tools Integration

The assistant prioritizes **free & open-source intelligence tooling**, including but not limited to:

- **OSINT**: Maigret, Sherlock, Maltego CE, Spiderfoot
    
- **Forensics**: Volatility, Autopsy, Redline, Velociraptor
    
- **Threat Intel**: MISP, IntelOwl, Yeti
    
- **Automation**: Shuffle SOAR, TheHive + Cortex, Sigma rules
    
- **Hunting**: Zeek, Suricata, Elastic SIEM
    

## 📊 Output Formats

- Markdown / HTML (default)
    
- CSV / JSON (for IOCs & structured data)
    
- STIX 2.1 (optional export for threat intel platforms)
    
- Mermaid diagrams for infra/timeline visualization
    

## ⚖️ Compliance & Ethics

OSINT360 GPT adheres to strict **OPSEC, legality, and evidentiary integrity** principles:

- Avoids disclosure of confidential sources.
    
- Prioritizes privacy and anonymization methods.
    
- Ensures all recommendations are ethical and legal.
    

## 📌 Example Usage

```bash
/report threatintel.com                   # Generate a full-spectrum OSINT report on a domain
/enrich 192.168.100.45         # Enrich and investigate an IP address (network asset / infrastructure)
/profile Microsoft Corporation # Build a detailed profile of a company or organization (corporate entity)
/darkweb "stolen credit cards" # Search the dark web for mentions of sensitive data (financial/PII exposure)
/mitre Lazarus Group           # Map an advanced persistent threat (APT) group’s TTPs to MITRE ATT&CK
/checklist Digital Forensics   # Get a structured task checklist for digital forensic investigations (DFIR workflow)
```

### More Examples

```bash
/report john_doe               # Full OSINT report on an individual (person of interest)
/enrich jane.doe@example.com   # Enrich and investigate an email address (digital identifier)
/profile @randomuser123        # Social media profile analysis (online persona)
/darkweb "passport scans"      # Dark web search for leaked identity documents (PII)
/mitre Conti Ransomware        # Map ransomware campaign TTPs to MITRE ATT&CK (malware family)
/checklist Incident Response   # Checklist for SOC and IR teams (operational workflow)
```

## 🚀 Access
**🔗 [Launch OSINT360 GPT](https://tnTpp9.short.gy/osint360-gpt)**  

## 📖 Methodology & Foundations

The model builds on best practices in **OSINT, digital forensics, red teaming, privacy engineering, and cybersecurity strategy**.  
It leverages frameworks and standards including **MITRE ATT&CK, NIST, OWASP, OWASP GenAI, GDPR, and AI Act**, with a focus on open-source tooling.

## ⚠️ Disclaimer

This model is provided for **educational, research, and defensive purposes only**.  
It does **not** endorse or support any unlawful or malicious activity.

## 📖 License

This project is intended for **educational, research, and defensive security purposes only**. Users must comply with applicable laws and regulations. The maintainers assume no liability for misuse.
