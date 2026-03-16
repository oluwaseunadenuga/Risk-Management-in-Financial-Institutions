# 🏦 Risk Management in Financial Institutions

![Project](https://img.shields.io/badge/Project-Risk%20Assessment-0075ca?style=flat-square)
![Domain](https://img.shields.io/badge/Domain-Financial%20Services-8a6520?style=flat-square)
![Status](https://img.shields.io/badge/Status-Complete-2ea44f?style=flat-square)
![Frameworks](https://img.shields.io/badge/Frameworks-6%20Mapped-6f42c1?style=flat-square)
![Risks](https://img.shields.io/badge/Risks%20Found-34%20Identified-e36209?style=flat-square)
![Duration](https://img.shields.io/badge/Duration-6%20Weeks-0e7490?style=flat-square)

A comprehensive **cybersecurity and operational risk assessment** conducted for a mid-tier UK financial institution. This project identifies, quantifies, and prioritises 34 risks across five domains using a qualitative-quantitative hybrid methodology — producing a full risk register, executive briefing pack, and 180-day remediation roadmap.

> *The assessment aligns with FCA PS21/3, DORA (ICT Risk), ISO/IEC 27001:2022, NIST CSF 2.0, PCI DSS v4.0, and UK GDPR — providing a unified compliance posture for Board-level reporting.*

> [!NOTE]
> **Portfolio Project** — All organisation names and data used in this repository are fictional and created for demonstration purposes only.

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Scope & Engagement Details](#-scope--engagement-details)
- [Methodology](#%EF%B8%8F-methodology)
- [Risk Register (Sample)](#-risk-register-sample)
- [Key Findings](#-key-findings)
- [Control Recommendations](#%EF%B8%8F-control-recommendations--roadmap)
- [Compliance Framework Mapping](#%EF%B8%8F-compliance-framework-mapping)
- [Tools & Techniques](#-tools--techniques)
- [Outcomes & Deliverables](#-outcomes--deliverables)
- [Skills Demonstrated](#-skills-demonstrated)
- [Contact](#-contact)

---

## 🎯 Project Overview

This project delivers a structured cybersecurity risk assessment for a mid-tier UK financial institution, evaluating threats across **information security, operational resilience, third-party exposure, regulatory compliance, and fraud**. Using a Likelihood × Impact matrix (1–25 scale), 34 risks were identified, scored, and escalated appropriately for Risk & Compliance Committee review.

Key activities included stakeholder interviews, asset inventory, threat modelling using MITRE ATT&CK for Financial Services and TIBER-EU, a gap analysis against ISO 27001:2022 Annex A and NIST CSF 2.0, and a live ransomware tabletop exercise with the CSIRT team.

---

## 🔭 Scope & Engagement Details

| Attribute | Detail |
|-----------|--------|
| **Engagement Type** | Internal Risk Assessment |
| **Duration** | 6 Weeks |
| **Scope** | Core banking infrastructure, internet banking platform, cloud-hosted data warehouses, third-party payment processors, staff endpoints (3 office sites) |
| **Total Risks Identified** | 34 — (5 Critical · 9 High · 14 Medium · 6 Low) |
| **Control Gaps Found** | 18 across 6 domains |
| **Regulatory Frameworks** | ISO 27001:2022 · NIST CSF 2.0 · DORA · UK GDPR · PCI DSS v4.0 · FCA PS21/3 |
| **Key Deliverables** | Risk Register · Executive Briefing Pack · Control Roadmap · Tabletop Exercise Report |

---

## ⚙️ Methodology

A five-phase approach was adopted, combining stakeholder interviews, document review, threat modelling, and a ransomware tabletop exercise:

<details>
<summary><strong>Phase 1 — Scoping & Asset Inventory</strong></summary>

Defined assessment boundaries and conducted asset classification, mapping critical, major, and minor information assets to business processes and regulatory obligations. Produced an **Asset Register** covering 148 information assets across the organisation.

</details>

<details>
<summary><strong>Phase 2 — Threat Intelligence & Modelling</strong></summary>

Applied **MITRE ATT&CK for Financial Services** and **TIBER-EU** threat intelligence to identify plausible threat actors — including nation-state APTs, cybercriminal groups, and malicious insiders — and mapped their TTPs to the organisation's attack surface.

</details>

<details>
<summary><strong>Phase 3 — Vulnerability & Control Review</strong></summary>

Reviewed existing technical and procedural controls against **ISO 27001:2022 Annex A** and **NIST CSF 2.0**. Gap analysis identified **18 control weaknesses** across 6 domains including access management, patch management, cloud security, and third-party oversight.

</details>

<details>
<summary><strong>Phase 4 — Risk Scoring & Register Construction</strong></summary>

Applied inherent and residual risk scoring using a **5×5 Likelihood × Impact matrix** (scores 1–25). All Critical (≥20) and High (15–19) risks were escalated to Board-level reporting with formal treatment plans and assigned ownership.

</details>

<details>
<summary><strong>Phase 5 — Reporting & Treatment Planning</strong></summary>

Delivered an executive summary, full risk register, and 180-day control roadmap with ownership, target remediation dates, cost estimates, and KRI metrics aligned to the institution's risk appetite statement.

</details>

---

## 📊 Risk Register (Sample)

The table below is an extract from the full 34-risk register. Risks are scored using **Inherent Risk = Likelihood × Impact (1–25)**. Residual risk reflects post-control effectiveness.

| ID | Risk Description | Domain | Likelihood | Impact | Inherent Score | Residual Score | Treatment |
|----|-----------------|--------|:----------:|:------:|:--------------:|:--------------:|-----------|
| `R-001` | Ransomware via phishing targeting core banking systems | Information Security | 4 | 5 | 🔴 **20 — Critical** | 🟠 15 — High | Mitigate |
| `R-002` | Third-party payment processor supply chain breach | TPRM | 3 | 5 | 🔴 **15 — Critical** | 🟠 12 — High | Transfer / Mitigate |
| `R-003` | Privileged account misuse leading to data exfiltration | Insider Threat | 3 | 4 | 🟠 **12 — High** | 🔵 8 — Medium | Mitigate |
| `R-004` | Cloud misconfiguration exposing customer PII | Cloud Security | 4 | 4 | 🟠 **16 — High** | 🔵 9 — Medium | Mitigate |
| `R-005` | Unpatched CVEs in internet banking application | Application Security | 4 | 4 | 🟠 **16 — High** | 🟠 12 — High | Mitigate |
| `R-006` | DORA ICT incident reporting SLA failure | Regulatory Compliance | 3 | 4 | 🟠 **12 — High** | 🔵 8 — Medium | Mitigate |
| `R-007` | DDoS attack disrupting online banking (>4 hours) | Operational Resilience | 3 | 3 | 🔵 **9 — Medium** | 🔵 6 — Medium | Transfer / Mitigate |
| `R-008` | BEC fraud enabled by inadequate security awareness | Human Risk | 4 | 3 | 🟠 **12 — High** | 🔵 8 — Medium | Mitigate |
| `R-009` | Encryption key management failure (data at rest) | Cryptography | 2 | 5 | 🔵 **10 — Medium** | 🟢 4 — Low | Mitigate |
| `R-010` | Legacy COBOL core banking — unsupported & unpatched | Technology Risk | 3 | 5 | 🔴 **15 — Critical** | 🟠 15 — High | Accept (interim) / Avoid |

> 📁 Full 34-risk register available in [`Risk-Register-Financial-Institutions.xlsx`](./Risk-Register-Financial-Institutions.xlsx)

---

## 🔍 Key Findings

### F1 — Absence of Privileged Access Management (PAM)

No centralised PAM solution was in place. **47 privileged accounts** were identified across production systems with shared credentials and no session recording — creating a critical insider threat gap and audit trail deficiency under the FCA's Senior Managers & Certification Regime (SMCR).

### F2 — DORA Non-Compliant Third-Party ICT Contracts

**14 of 22 critical ICT vendor contracts** lacked mandatory DORA Article 30 clauses — including audit rights, sub-outsourcing visibility, and exit strategy provisions — creating direct regulatory exposure from January 2025.

### F3 — Patch Management SLA Breach

The internet banking platform carried **23 unpatched CVEs** (9 rated High/Critical), with some unpatched for more than 90 days — directly violating the organisation's own 30-day patch SLA and **PCI DSS Requirement 6.3**.

### F4 — AWS S3 Bucket Misconfiguration (Public Read Access)

Three AWS S3 buckets containing KYC documentation were found with public read permissions enabled. Sensitive customer data (passports, proof of address) was accessible without authentication — constituting a **UK GDPR Article 32 breach risk** requiring immediate notification assessment.

### F5 — Cyber Incident Response Plan Not Tested Within 12 Months

The IRP had not been exercised in **over 18 months**. Both DORA Article 26 and FCA PS21/3 require regular scenario testing of operational resilience plans — a direct and documented compliance gap.

### F6 — Unsupported Legacy Core Banking System

The COBOL-based core banking system has operated without vendor support since 2021. No compensating controls (network segmentation, enhanced monitoring) were formally documented. **Residual risk cannot be fully reduced without a system replacement programme.**

> [!WARNING]
> **Urgent Escalation** — Findings F1, F2, F3, and F4 were escalated to the Risk & Compliance Committee immediately upon identification, as they represent active regulatory exposure and exploitable vulnerabilities.

---

## 🛡️ Control Recommendations & Roadmap

### ⚡ Immediate Actions (0–30 days)

- Remediate 9 Critical/High CVEs on the internet banking platform
- Revoke public access on 3 misconfigured AWS S3 buckets
- Enable MFA on all 47 privileged accounts as an interim PAM control
- Isolate legacy COBOL system to a strictly ACL-controlled network segment
- Brief Risk & Compliance Committee on all Critical and High findings

### 📅 Short-Term Programme (31–90 days)

- Deploy **CyberArk PAM** for full privileged account session management and audit trail
- Remediate 14 DORA non-compliant vendor contracts (insert Article 30 mandatory clauses)
- Implement automated patch management using **Qualys Patch Management**
- Conduct full CSIRT tabletop exercise — ransomware incident scenario
- Launch phishing simulation programme for all 1,200 staff

### 🛣️ Strategic Transformation (91–180 days)

- Begin legacy COBOL core banking modernisation programme
- Implement **Zero Trust architecture** across the core banking network perimeter
- Establish continuous Third-Party Risk Management (TPRM) monitoring programme
- Operationalise **SIEM + SOAR** with financial sector-specific threat intelligence feeds
- Initiate **ISO 27001:2022 certification** gap closure programme and roadmap

---

## ⚖️ Compliance Framework Mapping

| Framework | Relevant Areas | Key Controls Referenced |
|-----------|---------------|------------------------|
| **ISO/IEC 27001:2022** | Annex A gap analysis | A.5.9 (Asset Inventory) · A.8.8 (Vuln. Mgmt) · A.5.23 (Cloud) · A.6.4 (Disciplinary) · A.8.15 (Logging) |
| **NIST CSF 2.0** | Full 6-function maturity assessment | GV · ID · PR · DE · RS · RC — scored 1–4 maturity per category |
| **DORA 2022/2554** | ICT risk management, incidents, TPRM | Chapter II · III (Articles 19–20) · Chapter V (Article 30 contracts) |
| **UK GDPR / DPA 2018** | Data security & breach notification | Article 32 (security of processing) · Article 33 (72-hour notification) |
| **PCI DSS v4.0** | Cardholder data environment | Requirement 6 (secure systems) · 8 (access controls) · 12 (policies) |
| **FCA PS21/3** | Operational resilience | IBS mapping · Impact tolerance setting · Annual scenario testing evidence |

---

## 🔧 Tools & Techniques

```
Threat Modelling     MITRE ATT&CK Navigator (Financial Services profile)
                     TIBER-EU Threat Intelligence Framework
                     STRIDE / PASTA Threat Modelling Methodology

Vulnerability Mgmt   Nessus Pro (Internal Vulnerability Scanning)
                     Qualys Cloud Platform (Patch Management)
                     OSINT: Shodan · SpiderFoot (External Attack Surface)

Cloud Security       AWS Security Hub · AWS Config · S3 Bucket Analyser

GRC Platforms        OneTrust GRC · RSA Archer IRM
                     Microsoft Excel (Risk Register & Scoring Matrix)

SIEM / PAM           Splunk Enterprise SIEM
                     CyberArk PAM (Privileged Access — Recommended)

Reporting            Power BI (Risk Heat Map Dashboard)
                     Microsoft Office 365 (Word, PowerPoint, Excel)
```

---

## 📈 Outcomes & Deliverables

| Metric | Result |
|--------|--------|
| Total Risks Identified | **34** |
| Critical Risks (Score ≥20) | **5** |
| High Risks (Score 15–19) | **9** |
| Control Weaknesses Found | **18** |
| Regulatory Frameworks Mapped | **6** |
| Recommendations Delivered | **22** |
| Engagement Duration | **6 Weeks** |

#### 📦 Deliverables Produced

- ✅ Full 34-risk register with inherent/residual scoring, treatment owners, KRIs, and escalation thresholds
- ✅ Executive briefing pack — 15-slide deck for Risk & Compliance Committee and Board
- ✅ 180-day prioritised control remediation roadmap with RACI matrix and cost estimates
- ✅ Post-tabletop exercise report — ransomware scenario, 7 IRP gaps identified and remediated
- ✅ DORA Article 30 contract compliance checklist for 22 critical ICT vendors
- ✅ Risk heat map dashboard (Power BI) with live KRI tracking

---

## 🎓 Skills Demonstrated

![Cyber Risk Assessment](https://img.shields.io/badge/GRC-Cyber%20Risk%20Assessment-0075ca?style=flat-square)
![Risk Register](https://img.shields.io/badge/GRC-Risk%20Register%20Construction-0075ca?style=flat-square)
![MITRE ATT&CK](https://img.shields.io/badge/Threat-MITRE%20ATT%26CK%20Modelling-e36209?style=flat-square)
![ISO 27001](https://img.shields.io/badge/Standard-ISO%2027001%3A2022-8a6520?style=flat-square)
![NIST CSF](https://img.shields.io/badge/Standard-NIST%20CSF%202.0-8a6520?style=flat-square)
![DORA](https://img.shields.io/badge/Regulation-DORA%20Compliance-6f42c1?style=flat-square)
![UK GDPR](https://img.shields.io/badge/Regulation-UK%20GDPR%20%2F%20DPA%202018-6f42c1?style=flat-square)
![PCI DSS](https://img.shields.io/badge/Regulation-PCI%20DSS%20v4.0-0e7490?style=flat-square)
![FCA](https://img.shields.io/badge/Regulation-FCA%20Operational%20Resilience-0e7490?style=flat-square)
![TPRM](https://img.shields.io/badge/GRC-Third--Party%20Risk%20Management-0075ca?style=flat-square)
![Vulnerability Management](https://img.shields.io/badge/Technical-Vulnerability%20Management-586069?style=flat-square)
![Cloud Security](https://img.shields.io/badge/Technical-Cloud%20Security%20%28AWS%29-586069?style=flat-square)
![PAM](https://img.shields.io/badge/Technical-Privileged%20Access%20Management-586069?style=flat-square)
![Tabletop](https://img.shields.io/badge/Soft%20Skill-Tabletop%20Exercise%20Facilitation-2ea44f?style=flat-square)
![Stakeholder Reporting](https://img.shields.io/badge/Soft%20Skill-Stakeholder%20Reporting-2ea44f?style=flat-square)
![Gap Analysis](https://img.shields.io/badge/Soft%20Skill-Regulatory%20Gap%20Analysis-2ea44f?style=flat-square)

---

## 📬 Contact

If you have questions about this project or would like to discuss GRC, cybersecurity risk, or financial services compliance:

- 🔗 **GitHub:** [@oluwaseunadenuga](https://github.com/oluwaseunadenuga)
- 💼 **LinkedIn:** [linkedin.com/in/oluwaseunadenuga](https://linkedin.com/in/oluwaseunadenuga)
- 📧 **Email:** Available via LinkedIn

---

<div align="center">

⭐ **If you found this project useful, please consider starring the repository**

*All organisation data is fictional and for portfolio demonstration purposes only.*

</div>
