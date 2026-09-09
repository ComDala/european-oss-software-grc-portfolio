### European Open-Source Software GRC Portfolio
##### Structural Codebase Analysis & Regulatory Mapping (CRA / NIS2)
Welcome to my Software GRC portfolio. This repository serves as a live, technical demonstration of auditing modern European open-source software (OSS) ecosystems for enterprise readiness, compliance drift, and supply chain security alignment[cite: 1, 2].

#### 🎯 Portfolio Objectives
* **Regulatory Compliance:** Mapping live application infrastructure to the **EU Cyber Resilience Act (CRA)** and **NIS2 Directive (Article 21)**[cite: 1, 2].
* **Supply Chain Security:** Utilizing programmatic workflows to audit third-party dependency vulnerabilities (CVEs), Software Bills of Materials (SBOMs), and repository hygiene[cite: 1, 2].
* **Operational Remediation:** Translating complex technical vulnerabilities and governance gaps into high-impact corporate risk models and upstream fixes[cite: 1, 2].

#### 📊 The 10-Case Compliance Index
| Case | Target Software | Tech Stack & Package Lockfiles | High-Risk Audit Surface | Release Velocity & Maintenance | Primary EU Regulatory Core & Deliverable |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **01** | **openDesk**[cite: 1] | Multi-service, Helm/K8s, Container Manifests | Cross-service SSO token passing & container provenance[cite: 1] | **Quarterly Bundles** (Low ongoing overhead)[cite: 1] | Sovereign M365 Suite & Identity Governance (NIS2 & CRA) – [View Audit](./case-01-opendesk/)[cite: 1, 2] |
| **02** | **Euro-Office / Collabora**[cite: 1] | C++, JavaScript (package.json, CMakeLists.txt)[cite: 1] | Document parsing buffer safety & in-transit data caching[cite: 1] | **Bi-Monthly Releases** (Predictable)[cite: 1] | Sovereign Document Engine & Data Minimization (GDPR & CRA) – [View Audit](./case-02-euro-office/)[cite: 1, 2] |
| **03** | **Nextcloud**[cite: 1] | PHP, Vue.js (composer.json, package.json)[cite: 1] | Unvetted 3rd-party App Store plugins & server-side encryption[cite: 1] | **4-Month Major Cycles** (High stability)[cite: 1] | Cloud Collaboration & CVD (CRA Annex I & GDPR) – [View Audit](./case-03-nextcloud/)[cite: 1, 2] |
| **04** | **Matomo**[cite: 1] | PHP, JavaScript (composer.json)[cite: 1] | Analytics opt-in consent toggles & PII storage schemas[cite: 1] | **Monthly Patch Trains** (Low-impact fixes)[cite: 1] | Data Governance & Telemetry (GDPR & CRA) – [View Audit](./case-04-matomo/)[cite: 1, 2] |
| **05** | **Keycloak**[cite: 1] | Java, Quarkus (pom.xml, Maven)[cite: 1] | MFA default enforcement, OIDC/OAuth token signing, & session isolation[cite: 1] | **Quarterly Releases** (Enterprise focus)[cite: 1] | Enterprise IAM Controls (NIS2 Art. 21 & DORA) – [View Audit](./case-05-keycloak/)[cite: 1, 2] |
| **06** | **Grafana**[cite: 1] | Go, TypeScript (go.mod, package.json)[cite: 1] | Unsigned community dashboard plugins & API key scope boundaries[cite: 1] | **Monthly Releases** (Automated scanning fits well)[cite: 1] | Observability & Steward Liability (CRA Chapter II) – [View Audit](./case-06-grafana/)[cite: 1, 2] |
| **07** | **Evcc**[cite: 1] | Go (go.mod)[cite: 1] | Hardcoded MQTT/TLS credentials & physical charging API auth[cite: 1] | **Monthly Point Releases** (Light codebase)[cite: 1] | EV Charging Grid & Energy Security (NIS2) – [View Audit](./case-07-evcc/)[cite: 1, 2] |
| **08** | **QGIS**[cite: 1] | C++, Python (CMakeLists.txt, requirements.txt)[cite: 1] | Unverified Python plugin repository & QGIS Server API endpoints[cite: 1] | **1-Year LTR (Long-Term Release)** (Ultra-stable)[cite: 1] | Telecom Fiber Network & Supply Chain (NIS2 & CRA) – [View Audit](./case-08-qgis/)[cite: 1, 2] |
| **09** | **Proxmox VE**[cite: 1] | Perl, C, Rust (Debian .deb packaging)[cite: 1] | Hypervisor patch SLAs, root privileges in LXC/VM management[cite: 1] | **Bi-Annual Major Releases** (Very low effort)[cite: 1] | Hypervisor & VMware Migration Risk (NIS2 & CRA) – [View Audit](./case-09-proxmox/)[cite: 1, 2] |
| **10** | **OPNsense**[cite: 1] | C, PHP (FreeBSD Ports / packages)[cite: 1] | Insecure default admin configurations & border routing crypto libraries[cite: 1] | **Semi-Annual Majors** (Bi-weekly security hotfixes)[cite: 1] | Network Firewall & Secure Defaults (NIS2) – [View Audit](./case-10-opnsense/)[cite: 1, 2] |

#### 🛠️ The Audit & Analysis Workflow
Every software target in this portfolio undergoes a standardized methodology:
1. **Codebase Structural Ingestion:** Deep asset and architectural parsing using code visualization workflows[cite: 1, 2].
2. **Policy Verification:** Auditing the presence, legality, and clarity of SECURITY.md, vulnerability response SLAs, and licenses[cite: 1, 2].
3. **Dependency and Supply Chain Triage:** Evaluating package registries and lockfiles for active CVE exposure[cite: 1, 2].
4. **Impact Reporting:** Developing an enterprise-grade risk scorecard mapping technical findings to multi-million Euro regulatory exposures[cite: 1, 2].

---
📫 **Looking to secure your software supply chain or prepare for an EU audit?** Let's connect on [LinkedIn](YOUR_LINK_HERE) or explore my IAMComDala technical workflows[cite: 1, 2, 3].
