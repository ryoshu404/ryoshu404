# Hi, I'm R. Santos 👋

Security engineer building security tooling and detection content in Python for static analysis, DFIR, threat intel, and detection engineering.

Background: 5 years Security Engineering at USAF (malware analysis, incident response) + 3 years SIGINT analysis at NSA.

---

## 🔨 Featured Projects

<!---**[detection-lab](https://github.com/ryoshu404/detection-lab)** — Detection engineering lab provisioned end-to-end in Terraform: AWS telemetry sources (CloudTrail, GuardDuty, VPC Flow Logs → S3/SQS) and a two-node Proxmox cluster hosting a self-hosted Elastic SIEM, Fleet, and enrolled endpoints. All sources land as canonical ECS data streams; Sigma detections compiled by pySigma and deployed to the Detection Engine, with alerts pushed outbound to a Tines SOAR layer. Detection-as-code from rule source through burn-in to deployed rule, tuned against continuous endpoint telemetry. -->

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

**Security:** Microsoft XDR · Splunk · Sigma · KQL · FLARE VM · REMnux · SQL · Elastic · Tines

---

## 📚 Currently Learning

- **Go** — backend systems and service development
- **Rust** — systems programming and zero-dependency tooling
