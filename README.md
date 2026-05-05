# Hi, I'm R. Santos 👋

Security engineer building production tooling in Python, Go, and Rust with a focus on static analysis, DFIR, threat intelligence and detection.

Background: 5 years Security Engineering at USAF (malware analysis, incident response, detection engineering) + 3 years SIGINT analysis at NSA.

---

## 🔨 Featured Projects

**[Statica](https://github.com/ryoshu404/statica)** — Format-agnostic static analysis pipeline in Python. Extracts hashes, strings, and IOC patterns; produces deterministic, deduplicated JSON for downstream automation.

**[gorelate](https://github.com/ryoshu404/gorelate)** *(in development)* — Threat intelligence pipeline in Go. Ingests public IOC feeds (OTX, URLHaus, abuse.ch), correlates across sources, confidence-scores by source count, and generates YARA stubs with LLM-assisted triage summaries. Target ship: late 2026.

**[pydetect](https://github.com/ryoshu404/pydetect)** *(in development)* — Detection-as-code repository covering Sigma, Falco, and KQL rules organized by attacker TTP across the telemetry stack. Python pytest harness with per-framework adapters; tests are generated from rule files at collection time, with fail-fast validation that prevents ship-without-test. Per-rule decision documentation. GitHub Actions CI. Target ship: late 2026.

**[macollect](https://github.com/ryoshu404/macollect)** — Modular macOS forensic artifact collector in Python. Eight independent modules covering persistence mechanisms, process snapshots, code signing metadata, TCC permissions, and Unified Log activity. Zero third-party dependencies; read-only collection model.



---

## 🛠 Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Security:** Ghidra · IDA Pro · x64dbg · FLARE VM · Microsoft XDR · Splunk · Falco · Sigma · KQL · SQL

---

## 📚 Currently Learning

- **Go** — backend systems and service development (Gorelate as capstone)
- **Rust** — systems programming and zero-dependency tooling (porting Statica to Rust)
