# BTL1 Easter Prep 2026

Documented evidence of a focused two-week study block completed during Easter leave 2026, 
as part of active preparation for the Blue Team Labs 1 (BTL1) certification exam.

---

## Background

I'm currently transitioning into cybersecurity, 
targeting a Tier 1 SOC Analyst role. This repository documents the practical lab 
work completed during Easter leave 2026 — covering five of the six BTL1 exam domains 
through a combination of TryHackMe rooms, Immersive Labs modules, and a custom-built 
mock investigation.

Existing certifications: CompTIA Security+ | Splunk Core Certified User (SPLK-1001)  
Target: BTL1 — Security Blue Team 

---

## Repository Structure

| Folder | Content | Platform | Key Tools |
|---|---|---|---|
| `01_phishing-analysis` | Phishing Emails 3 & 4, Greenholt Fish CTF, Snapped Phish-ing Line | TryHackMe | Wireshark, any.run, VirusTotal, MXToolbox, CyberChef |
| `02_incident-response` | IR: Data Exfiltration | Immersive Labs | Wireshark, SMB/FTP analysis |
| `03_mock-investigation` | Operation Harbour Watch — custom IR scenario | Self-built | Wireshark, binwalk, dd, exiftool, CyberChef |
| `04_network-analysis` | Wireshark series — 10 labs across TLS, BPF, SMTP, TCPDump, display filters, stream extraction, packet capture basics | Immersive Labs | Wireshark, tcpdump |
| `05_digital-forensics` | Autopsy, KAPE, File Carving | TryHackMe | Autopsy, KAPE/gkape, EZViewer, binwalk, foremost, scalpel, exiftool, Okteta |
| `06_threat-intelligence` | MITRE ATT&CK Navigator, OpenCTI, MISP | TryHackMe | ATT&CK Navigator, OpenCTI, MISP |

---

## Labs Completed

### 01 — Phishing Analysis
- **THM Phishing Emails 3** — sandbox analysis via any.run, CVE-2017-11882 identification, malicious PDF and XLSX investigation
- **THM Phishing Emails 4** — Wireshark SMTP analysis, IMF filter, attachment extraction
- **THM Greenholt Fish CTF** — full phishing triage: headers, SPF/DMARC, VirusTotal, SHA256 verification
- **THM Snapped Phish-ing Line** — credential harvesting investigation, CyberChef base64 decode, full attack chain reconstruction

### 02 — Incident Response
- **IL IR: Data Exfiltration** — SMB2 file access analysis, FTP session reconstruction, credential recovery from packet capture

### 03 — Mock Investigation
- **Operation Harbour Watch** — self-contained IR scenario built from scratch: C2 beacon detection, User-Agent anomaly identification, base64-encoded data exfiltration decoding, disk image carving across JPEG/PDF/HTML artefacts

### 04 — Network Analysis
- **IL Wireshark series** — 10 labs covering display filters, SMTP analysis, network investigation, statistics, TCPDump, BPF syntax, TLS handshake, TLS traffic decryption, stream/object extraction, packet capture basics, and a demonstrate-your-skills assessment

### 05 — Digital Forensics
- **THM Autopsy** — disk image triage, keyword search, cloud storage artefacts, deleted file recovery, timeline analysis, HTML report generation
- **THM KAPE** — KapeTriage collection, !EZParser module processing, EZViewer artefact analysis
- **THM File Carving** — manual carving with Okteta, automated carving with foremost/scalpel, binwalk signature analysis, exiftool metadata extraction, dd extraction

### 06 — Threat Intelligence
- **THM MITRE ATT&CK** — ATT&CK Navigator enterprise matrix exploration
- **THM OpenCTI** — malware profiling, attack pattern mapping, intrusion set analysis, threat actor investigation
- **THM MISP** — event creation, attribute tagging, galaxy clusters, taxonomy, OSINT correlation

---

## Skills Demonstrated

- Network traffic analysis and protocol dissection (Wireshark, tcpdump)
- Phishing email triage and sandbox detonation
- File carving and disk image forensics
- Digital artefact recovery and metadata analysis
- Threat intelligence platform usage (MISP, OpenCTI)
- MITRE ATT&CK TTP mapping
- Incident response methodology across data exfiltration scenarios
- BPF filter construction for targeted packet capture

---

## Related

- [Splunk Lab Portfolio](https://github.com/emilebarnard242/splunk-lab-portfolio) — 
  BOTSv1 Cyber Kill Chain investigation and STEP linux_secure sourcetype analysis  
