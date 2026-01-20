# AcaPro AI Data Governance

**Document ID:** 06_DATA_GOVERNANCE  
**Standard:** 2026 Skill / Agent Platform  
**Status:** Constitutional Specification  
**Applies To:** All data collection, processing, storage, access, and audit activities within the AcaPro AI platform  
**Effective Date:** 20 January 2026 (Melbourne Time)

---

## 1. Purpose of Data Governance

This document defines the **Data Governance framework** of the AcaPro AI platform.

Its purpose is to:

- Establish clear data ownership and custodianship  
- Govern how learning, decision, and system data are handled  
- Ensure transparency, auditability, and regulatory alignment  
- Prevent misuse, leakage, or opaque data practices  

This document is binding under the authority of:

- `01_PLATFORM_CONSTITUTION.md`  
- `02_ARCHITECTURE_OVERVIEW.md`  
- `03_AGENT_SYSTEM.md`  
- `05_DECISION_ENGINE.md`  

---

## 2. Core Data Principles

All data practices within the platform MUST adhere to the following principles:

- Purpose limitation  
- Data minimization  
- Transparency and explainability  
- Security by design  
- Auditability by default  

Data exists to support responsible learning decisions,  
not unrestricted analytics or experimentation.

---

## 3. Data Ownership and Custodianship

### 3.1 Student Data

- Students are the primary owners of their personal learning data  
- Student data MUST NOT be sold or transferred  
- Student data MAY be accessed only for defined educational purposes  

### 3.2 Institutional Data

- Schools retain ownership of institutional and assessment records  
- Institutional data usage MUST comply with contractual and regulatory obligations  

### 3.3 Platform Custodianship

- AcaPro AI acts solely as a **data custodian**, not a data owner  
- Custodianship implies responsibility without ownership rights  

---

## 4. Data Classification

All data MUST be classified into one of the following categories:

- Personal learning data  
- Assessment and performance data  
- Decision and audit data  
- System and operational data  

Each data category MUST have explicit handling and access rules.

---

## 5. Data Access Control

Data access MUST be:

- Role-based  
- Least-privilege  
- Explicitly authorized  

Agents, Skills, and services may access data **only** within their declared scope.

Unauthorized access is prohibited.

---

## 6. Data Usage Constraints

Data MAY be used for:

- Learning personalization  
- Decision support  
- System improvement under governance  

Data MUST NOT be used for:

- Unrelated commercial exploitation  
- Behavioral manipulation  
- Undisclosed profiling  

All usage MUST be traceable and reviewable.

---

## 7. Data Retention and Deletion

Each data category MUST define:

- Retention duration  
- Deletion triggers  
- Archival requirements  

Upon expiration or valid request:

- Data MUST be deleted or anonymized  
- Deletion actions MUST be logged  

Silent retention is prohibited.

---

## 8. Data Security Requirements

All data MUST be protected through:

- Encryption at rest and in transit  
- Secure authentication and authorization mechanisms  
- Regular security review and monitoring  

Security controls MUST align with applicable regulatory standards.

---

## 9. Decision and Audit Data

Decision-related data MUST include:

- Initiating Agent  
- Invoked Skills and versions  
- Risk classification  
- Human review status  
- Final outcome  

Audit data MUST be immutable and tamper-resistant.

---

## 10. Data Sharing and Third Parties

Data sharing with third parties:

- Requires explicit authorization  
- Must be purpose-bound and minimal  
- Must comply with legal and contractual obligations  

Third parties MUST NOT assume data ownership.

---

## 11. Regulatory and Compliance Alignment

The platform MUST align with:

- Applicable education regulations  
- Privacy and data protection laws  
- Institutional governance requirements  

Compliance is enforced by design, not retroactively.

---

## 12. Monitoring and Audit

Data practices MUST be continuously monitored.

Audit mechanisms MUST support:

- Internal review  
- External inspection where required  
- Incident investigation  

Lack of audit capability constitutes non-compliance.

---

## 13. Incident Handling and Breach Response

In the event of a data incident:

- The incident MUST be logged immediately  
- Impact MUST be assessed  
- Affected parties MUST be notified where required  
- Corrective actions MUST be documented  

Concealment of incidents is prohibited.

---

## 14. Foundational Statement

Data is not a resource to be exploited.

It is a responsibility to be governed  
with transparency, restraint,  
and respect for learners.
