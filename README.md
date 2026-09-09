### European Open-Source Software GRC Portfolio
##### Structural Codebase Analysis & Regulatory Mapping (CRA / NIS2)
Welcome to my Software GRC portfolio. This repository serves as a live, technical demonstration of auditing modern European open-source software (OSS) ecosystems for enterprise readiness, compliance drift, and supply chain security alignment.

#### 🎯 Portfolio Objectives
* **Regulatory Compliance:** Mapping live application infrastructure to the **EU Cyber Resilience Act (CRA)** and **NIS2 Directive (Article 21)**.
* **Supply Chain Security:** Utilizing programmatic workflows to audit third-party dependency vulnerabilities (CVEs), Software Bills of Materials (SBOMs), and repository hygiene.
* **Operational Remediation:** Translating complex technical vulnerabilities and governance gaps into high-impact corporate risk models and upstream fixes.

#### 📊 The 10-Case Compliance Index
| Case | Target Software | Tech Stack & Package Lockfiles | High-Risk Audit Surface | Release Velocity & Maintenance | Primary EU Regulatory Core & Deliverable |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **01** | **openDesk** | Multi-service, Helm/K8s, Container Manifests | Cross-service SSO token passing & container provenance | **Quarterly Bundles** (Low ongoing overhead) | Sovereign M365 Suite & Identity Governance (NIS2 & CRA) – [View Audit](./case-01-opendesk/) |
| **02** | **Euro-Office / Collabora** | C++, JavaScript (package.json, CMakeLists.txt) | Document parsing buffer safety & in-transit data caching | **Bi-Monthly Releases** (Predictable) | Sovereign Document Engine & Data Minimization (GDPR & CRA) – [View Audit](./case-02-euro-office/) |
| **03** | **Nextcloud** | PHP, Vue.js (composer.json, package.json) | Unvetted 3rd-party App Store plugins & server-side encryption | **4-Month Major Cycles** (High stability) | Cloud Collaboration & CVD (CRA Annex I & GDPR) – [View Audit](./case-03-nextcloud/) |
| **04** | **Matomo** | PHP, JavaScript (composer.json) | Analytics opt-in consent toggles & PII storage schemas | **Monthly Patch Trains** (Low-impact fixes) | Data Governance & Telemetry (GDPR & CRA) – [View Audit](./case-04-matomo/) |
| **05** | **Keycloak** | Java, Quarkus (pom.xml, Maven) | MFA default enforcement, OIDC/OAuth token signing, & session isolation | **Quarterly Releases** (Enterprise focus) | Enterprise IAM Controls (NIS2 Art. 21 & DORA) – [View Audit](./case-05-keycloak/) |
| **06** | **Grafana** | Go, TypeScript (go.mod, package.json) | Unsigned community dashboard plugins & API key scope boundaries | **Monthly Releases** (Automated scanning fits well) | Observability & Steward Liability (CRA Chapter II) – [View Audit](./case-06-grafana/) |
| **07** | **Evcc** | Go (go.mod) | Hardcoded MQTT/TLS credentials & physical charging API auth | **Monthly Point Releases** (Light codebase) | EV Charging Grid & Energy Security (NIS2) – [View Audit](./case-07-evcc/) |
| **08** | **QGIS** | C++, Python (CMakeLists.txt, requirements.txt) | Unverified Python plugin repository & QGIS Server API endpoints | **1-Year LTR (Long-Term Release)** (Ultra-stable) | Telecom Fiber Network & Supply Chain (NIS2 & CRA) – [View Audit](./case-08-qgis/) |
| **09** | **Proxmox VE** | Perl, C, Rust (Debian .deb packaging) | Hypervisor patch SLAs, root privileges in LXC/VM management | **Bi-Annual Major Releases** (Very low effort) | Hypervisor & VMware Migration Risk (NIS2 & CRA) – [View Audit](./case-09-proxmox/) |
| **10** | **OPNsense** | C, PHP (FreeBSD Ports / packages) | Insecure default admin configurations & border routing crypto libraries | **Semi-Annual Majors** (Bi-weekly security hotfixes) | Network Firewall & Secure Defaults (NIS2) – [View Audit](./case-10-opnsense/) |

#### 🛠️ The Audit & Analysis Workflow
Every software target in this portfolio undergoes a standardized methodology:
1. **Codebase Structural Ingestion:** Deep asset and architectural parsing using code visualization workflows.
2. **Policy Verification:** Auditing the presence, legality, and clarity of SECURITY.md, vulnerability response SLAs, and licenses.
3. **Dependency and Supply Chain Triage:** Evaluating package registries and lockfiles for active CVE exposure.
4. **Impact Reporting:** Developing an enterprise-grade risk scorecard mapping technical findings to multi-million Euro regulatory exposures.

---
📫 **Looking to secure your software supply chain or prepare for an EU audit?** Let's connect on [LinkedIn](https://www.linkedin.com/in/dario-omerdic/) | [X / Twitter](https://x.com/IAMComDala) 
