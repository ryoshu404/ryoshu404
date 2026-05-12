# Hi, I'm R. Santos 👋

Security engineer building production tooling in Python, Go, and Rust with a focus on static analysis, DFIR, threat intelligence and detection.

Background: 4+ years Security Engineering at USAF (malware analysis, incident response, detection engineering) + 3 years SIGINT analysis at NSA.

---

## 🔨 Featured Projects

**[pydetect](https://github.com/ryoshu404/pydetect)** — Detection-as-code repository covering Sigma rules organized by attacker TTP across the telemetry stack. Python pytest harness with per-framework adapters; tests are generated from rule files at collection time, with fail-fast validation that prevents ship-without-test. Per-rule decision documentation. GitHub Actions CI.

**[Statica](https://github.com/ryoshu404/statica)** — Format-agnostic static analysis pipeline in Python. Extracts hashes, strings, and IOC patterns; produces deterministic, deduplicated JSON for downstream automation.

**[intelextract](https://github.com/ryoshu404/intelextract)** — Python CLI for extracting structured threat intelligence from threat-research text via the Anthropic API. Captures actors, malware, ATT&CK techniques, IOCs, and targeting context as deterministic JSON. Pydantic schema as single source of truth for both the tool's input_schema and response validation; forced tool-use contract; malformed output surfaces as explicit ValidationError.

**[macollect](https://github.com/ryoshu404/macollect)** — Modular macOS forensic artifact collector in Python. Eight independent modules covering persistence mechanisms, process snapshots, code signing metadata, TCC permissions, and Unified Log activity. Zero third-party dependencies; read-only collection model.



---

## 🛠 Languages & Tools

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
<!--![Go](https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat&logo=rust&logoColor=white)-->

**Security:** Ghidra · IDA Pro · x64dbg · FLARE VM · Microsoft XDR · Splunk · Sigma · KQL · SQL

---

## 📚 Currently Learning

- **Go** — backend systems and service development (Gorelate)
- **Rust** — systems programming and zero-dependency tooling (porting Statica to Rust)
