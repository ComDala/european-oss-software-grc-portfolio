# 🇪🇺 European Open-Source Software GRC Portfolio

## Public-Source Software Supply Chain and Product Security Assessments

This repository documents an independent portfolio of technical readiness assessments for European open-source software. The work focuses on publicly observable evidence: repository governance, dependency management, release integrity, vulnerability handling, CI/CD controls, and enterprise identity integration.

These are **not certification audits or legal determinations**. A public repository does not reveal every organizational, contractual, operational, or production control. Completed cases therefore distinguish confirmed evidence from items that are not observable or not assessable from public sources.

## 🎯 Portfolio Objectives

- Build reproducible Software Bill of Materials and dependency-governance evidence.
- Review public CI/CD, release, vulnerability-disclosure, and secure-development controls.
- Evaluate enterprise identity capabilities including OIDC, SAML, MFA, privileged access, secrets, and workload identities.
- Explain how technical observations may support CRA, NIS2, DORA, GDPR, or other obligations when applicability has first been established.
- Translate validated findings into prioritized remediation and verification steps.

## Assessment Roadmap

| Case | Project | Bounded assessment focus | Stage | Report |
| :---: | :--- | :--- | :---: | :---: |
| 01 | **openDesk** | Multi-repository architecture, container provenance and SSO boundaries | ⚪ Planned | — |
| 02 | **Collabora Online** | Dependency governance, release integrity and document-processing boundaries | ⚪ Planned | — |
| 03 | **Nextcloud** | Vulnerability handling, application ecosystem, dependency and release evidence | ⚪ Queued | — |
| 04 | **Matomo** | Dependency governance, telemetry documentation, CI/CD and disclosure controls | 🟡 Next | — |
| 05 | **Keycloak** | Identity security, OIDC/OAuth configuration, release and vulnerability governance | ⚪ Queued | — |
| 06 | **Grafana** | Plugin ecosystem, release provenance and service/API identities | ⚪ Planned | — |
| 07 | **evcc** | Go dependency governance, secrets, updates and disclosure processes | ⚪ Planned | — |
| 08 | **QGIS** | Plugin ecosystem, release integrity and QGIS Server exposure | ⚪ Planned | — |
| 09 | **Proxmox VE** | Multi-package release governance, security updates and privileged operations | ⚪ Planned | — |
| 10 | **OPNsense** | Secure defaults, update channels, packages and firewall administration | ⚪ Planned | — |

**Stage legend:** ⚪ planned or queued · 🟡 next or in progress · 🟢 completed. The Report column is linked only after a case contains meaningful published work.

A case will be marked **Completed** only after the report identifies its target version and commit, includes an evidence register and reproducible artifacts, records limitations, and validates every published finding.

## Standard Method

1. **Scope and applicability** - define the product, repository set, version, intended use scenario, legal roles, exclusions, and assumptions.
2. **Evidence collection** - inspect source, documentation, manifests, lockfiles, workflows, releases, advisories, and public governance material.
3. **Technical analysis** - generate SBOM and dependency artifacts; examine disclosure, CI/CD, release-integrity, and identity controls.
4. **Validation** - reproduce observations, remove false positives, record confidence, and distinguish absence of evidence from evidence of absence.
5. **Risk and regulatory mapping** - explain technical and business relevance without treating a public-source review as a conformity assessment.
6. **Remediation and disclosure** - provide prioritized actions and use private coordinated-disclosure channels for security-sensitive findings.

## Evidence Status Vocabulary

- **Confirmed** - directly supported by reproducible evidence.
- **Partial** - some elements are present, but the control is incomplete or uncertain.
- **Not observed** - not found within the defined public scope; this does not prove the control does not exist elsewhere.
- **Not assessable** - requires private organizational, contractual, repository-setting, or production evidence.
- **Not applicable** - excluded after a documented applicability decision.

## Responsible Disclosure

Potential vulnerabilities will not be published as compliance findings before coordinated disclosure. Security-sensitive observations will follow the target project's documented reporting channel. Public case studies will contain only evidence appropriate for disclosure.

📫 [LinkedIn](https://www.linkedin.com/in/dario-omerdic/)
