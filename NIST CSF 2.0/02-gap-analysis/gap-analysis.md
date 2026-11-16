# NIST Cybersecurity Framework (CSF) 2.0 — Gap Analysis

> **Portfolio Project | GRC / Cybersecurity Risk Management**

## Disclaimer

This repository is a **fictional, educational portfolio project** created by an aspiring Governance, Risk, and Compliance (GRC) Analyst to demonstrate familiarity with the NIST Cybersecurity Framework (CSF) 2.0 and the gap analysis process.

- The organization, its business environment, systems, processes, and identified gaps are fictional.
- The observations in this document are hypothetical examples and have not been validated through interviews, evidence collection, technical testing, or an actual audit.
- This document does not represent a real security assessment, legal or regulatory opinion, certification, or assurance report.
- NIST CSF 2.0 references are included for learning and portfolio demonstration. Organizations should validate applicability and tailor cybersecurity outcomes to their own context.

**Purpose:** Demonstrate how an aspiring GRC Analyst can organize hypothetical cybersecurity gaps and map them to relevant NIST CSF 2.0 categories and subcategories.

---

## 1. Project Overview

This gap analysis identifies hypothetical weaknesses in a fictional organization with a business environment that includes physical warehouses, operational technology (OT), Internet of Things (IoT) devices, public-facing portals, and cloud/SaaS services.

The analysis is organized around the six NIST CSF 2.0 Functions:

| NIST CSF 2.0 Function | Number of identified gaps |
|---|---:|
| Govern | 3 |
| Identify | 4 |
| Protect | 3 |
| Detect | 2 |
| Respond | 3 |
| Recover | 2 |
| **Total** | **17** |

### Objectives

- Identify hypothetical cybersecurity control and process gaps.
- Associate each gap with a relevant NIST CSF 2.0 Category Identifier.
- Record the related CSF subcategory references for traceability.
- Provide a structured starting point for risk assessment and remediation planning.

## 2. Scope and Approach

### In-scope themes represented in the fictional scenario

- Cybersecurity governance, policies, and accountability
- Third-party and supply chain risk management
- Asset inventory, OT/IoT visibility, and data flows
- Vulnerability identification and access control
- Network security and data protection
- Security monitoring and event analysis
- Incident response, communications, and external support
- Backup validation, business continuity, and continual improvement

### High-level gap analysis approach

1. **Define the context:** Establish the fictional organization and the technology/process areas being considered.
2. **Identify expected outcomes:** Use relevant NIST CSF 2.0 Categories and Subcategories as a reference point.
3. **Describe the hypothetical gap:** State the weakness or missing capability in clear business language.
4. **Map the reference:** Associate the observation with the CSF Category Identifier and key Subcategory reference(s).
5. **Prepare for risk assessment:** Use the gap register as an input to a separate risk assessment and remediation process.

> **Important:** The workbook provides identified gap statements and framework references. It does not provide evidence-based control testing results, maturity ratings, risk scores, owners, target dates, or verified remediation status. Those items are intentionally not presented as established facts in this README.

## 3. Gap Analysis Register

The following register is transcribed from the workbook's **Gap analysis** tab. The Function grouping below is derived from the NIST CSF identifier prefix (for example, `GV` = Govern and `PR` = Protect).

### Govern

| # | Identified Gap | Category Identifier | NIST CSF Subcategory Description (as recorded) | Key Subcategories |
|---:|---|---|---|---|
| 1 | Lack of Supply Chain / Third-Party Risk Management (SCRM) | `GV.SC` | Third-party and supplier risks are proactively evaluated through upfront planning and due diligence prior to formal onboarding, and then continuously documented, prioritized, mitigated, and monitored throughout the entire relationship lifecycle. | `GV.SC-06, GV.SC-07` |
| 2 | Undefined Security Roles & Responsibilities | `GV.RR` | Organizational leadership is accountable for cybersecurity risk and cultivating a risk-aware, ethical culture of continuous improvement, supported by clearly defined, communicated, and enforced security roles and authorities across the organization. | `GV.RR-01, GV.RR-02` |
| 3 | Absence of Formal Cyber Policies for Warehouses | `GV.PO` | Cybersecurity risk management policies are established in alignment with organizational context, strategy, and priorities, and are continuously reviewed, updated, communicated, and enforced to adapt to evolving threats, technologies, requirements, and mission changes. | `GV.PO-01, GV.PO-02` |

### Identify

| # | Identified Gap | Category Identifier | NIST CSF Subcategory Description (as recorded) | Key Subcategories |
|---:|---|---|---|---|
| 1 | Inadequate OT & IoT Asset Discovery | `ID.AM` | All physical devices, OT/IoT hardware, software, services, and data are formally inventoried and actively managed across their entire operational lifecycles. | `ID.AM-01, ID.AM-08` |
| 2 | Lack of Public Portal Vulnerability Mapping | `ID.RA` | Vulnerabilities in assets are identified, validated, and recorded | `ID.RA-01` |
| 3 | Unmapped Data Flows | `ID.AM` | Inventories of data and corresponding metadata for designated data types are maintained | `ID.AM-07` |
| 4 | Post-Incident Root-Cause Analysis | `ID.IM & RC.RP` | Continuously maintain and improve operational cybersecurity and incident response plans, aligning mission-critical risk management to set post-incident norms | `ID.IM-04, RC.RP-06` |

### Protect

| # | Identified Gap | Category Identifier | NIST CSF Subcategory Description (as recorded) | Key Subcategories |
|---:|---|---|---|---|
| 1 | Weak Access Control and Authentication | `PR.AA` | All users, services, and hardware must be properly authenticated, while access permissions and authorizations are governed by formal policy actively managed, enforced, and regularly reviewed using the principles of least privilege and separation of duties. | `PR.AA-03, PR.AA-05` |
| 2 | Flat Network Architecture in Warehouses | `PR.IR` | Networks and environments are protected from unauthorized logical access and usage | `PR.IR-01` |
| 3 | Insufficient Data Encryption | `PR.DS` | The confidentiality, integrity, and availability (CIA) of organizational data are protected across all states, whether stored on systems (data-at-rest) or moving across networks (data-in-transit). | `PR.DS-01, PR.DS-02` |

### Detect

| # | Identified Gap | Category Identifier | NIST CSF Subcategory Description (as recorded) | Key Subcategories |
|---:|---|---|---|---|
| 1 | Security Continuous Monitoring | `DE.CM` | Network infrastructure, network services, personnel activity, and technology usage are continuously monitored to detect potentially adverse security events across the environment. | `DE.CM-01, DE.CM-03` |
| 2 | Adverse Event Analysis | `DE.AE` | Potentially adverse events are investigated to understand their underlying activity, and are formally declared as security incidents once they meet established threshold criteria. | `DE.AE-02, DE.AE-08` |

### Respond

| # | Identified Gap | Category Identifier | NIST CSF Subcategory Description (as recorded) | Key Subcategories |
|---:|---|---|---|---|
| 1 | Lack of a Tailored Incident Response Plan (IRP) | `RS.MA` | The incident response plan is executed in coordination with relevant third parties once an incident is declared | `RS.MA-01` |
| 2 | Undefined Client Communication Protocols | `RS.CO` | Incident notifications and relevant information are shared with designated internal and external stakeholders | `RS.CO-02, RS.CO-03` |
| 3 | No Incident Retainers or Response Team | `RS.MA & RS.MI` | Once an incident is declared, the incident response plan is immediately executed with relevant third parties to contain the event. | `RS.MA-01, RS.MI-01` |

### Recover

| # | Identified Gap | Category Identifier | NIST CSF Subcategory Description (as recorded) | Key Subcategories |
|---:|---|---|---|---|
| 1 | Cloud SaaS Backup Verification | `RC.RP` | The integrity of backups and other restoration assets is verified before using them for restoration | `RC.RP-03` |
| 2 | Business Continuity for Physical Warehouses | `RC.RP` | Risk-based prioritization and execution of recovery actions to restore critical mission operations. | `RC.RP-02, RC.RP-04` |

## 4. Observations by Function

The register covers governance, asset and vulnerability identification, protective controls, detection capabilities, incident response, and recovery. These groupings describe the themes represented by the hypothetical gaps; they do not indicate that a function has been formally assessed or assigned a maturity level.

| Function | Example themes represented in the register |
|---|---|
| **Govern** | Supplier risk management, security roles and responsibilities, cybersecurity policies |
| **Identify** | OT/IoT asset discovery, vulnerability mapping, data-flow inventory |
| **Protect** | Authentication and access control, warehouse network segmentation, encryption |
| **Detect** | Continuous security monitoring, adverse event analysis |
| **Respond** | Incident response planning, stakeholder communication, incident response support |
| **Recover** | Backup integrity verification, warehouse business continuity, post-incident improvement |

## 5. Recommended Next Steps for a GRC Analyst

The following are **suggested next steps for developing this portfolio exercise**. They are not documented findings or approved remediation decisions from the fictional organization.

1. **Validate each gap:** Identify what evidence would confirm or disprove the observation, such as policies, asset inventories, access reviews, vulnerability reports, monitoring records, or incident response plans.
2. **Determine applicability:** Confirm that each referenced CSF outcome is relevant to the organization's business context, technology, and risk profile.
3. **Assess the current state:** Document the actual process or control in place, supported by evidence. Avoid assuming that a control is absent solely because documentation was not provided.
4. **Define the desired state:** Agree on the target outcome and what acceptable implementation would look like.
5. **Assess risk:** Evaluate likelihood, impact, existing safeguards, and business consequences using an approved risk methodology.
6. **Develop a remediation plan:** Assign an accountable owner, actions, priority, target date, required resources, and measurable completion criteria.
7. **Track and validate closure:** Retain evidence that the agreed action was implemented and operating as intended.

### Example of evidence an analyst might request

| Gap theme | Example evidence to request |
|---|---|
| Supplier risk management | Supplier inventory, due diligence records, security clauses, periodic supplier reviews |
| Security roles and responsibilities | Security policies, RACI matrix, role descriptions, approval records |
| OT/IoT asset discovery | OT/IoT asset inventory, network diagrams, discovery scan records |
| Access control | Access control policy, user access listings, MFA configuration evidence, access review records |
| Vulnerability management | Vulnerability scan reports, remediation tickets, exception approvals |
| Incident response | Incident response plan, escalation matrix, tabletop exercise records |
| Backup and recovery | Backup schedules, restore-test results, recovery procedures, continuity plans |

> Evidence examples are illustrative. The analyst should request only appropriate evidence, follow organizational authorization and data-handling requirements, and protect confidential information.

## 6. Limitations

- This is a hypothetical gap register, not a completed NIST CSF Organizational Profile.
- No interviews, document reviews, configuration reviews, vulnerability scans, or control tests were performed for a real organization.
- The gap statements are not proof that the described weaknesses exist in any actual company.
- The listed Category Identifiers and Subcategory references are reproduced from the source workbook; their applicability and wording should be checked against the official NIST CSF 2.0 publication before use in a real engagement.
- A gap does not automatically equal a confirmed risk, audit finding, or control failure. Further validation and risk analysis are required.

## 7. Reference

- [NIST Cybersecurity Framework (CSF) 2.0 — Official publication](https://doi.org/10.6028/NIST.CSWP.29)
- [NIST Cybersecurity Framework — Official website](https://www.nist.gov/cyberframework)

## 8. Portfolio Learning Outcomes

Through this exercise, I aim to demonstrate the ability to:

- Explain the purpose of a cybersecurity gap analysis.
- Organize observations using the six NIST CSF 2.0 Functions.
- Map hypothetical gaps to relevant framework Category Identifiers and Subcategory references.
- Identify evidence that could be requested during a control assessment.
- Understand the difference between an initial gap observation, a validated finding, a risk assessment, and a remediation plan.

---

**Author note:** This project is part of my learning journey toward a career in Governance, Risk, and Compliance (GRC). It is intended to demonstrate my developing knowledge, analytical approach, and willingness to learn—not to claim professional audit experience or certification.
