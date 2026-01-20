# AcaPro AI Risk Control Framework

**Document ID:** 07_RISK_CONTROL  
**Standard:** 2026 Skill / Agent Platform  
**Status:** Constitutional Specification  
**Applies To:** All high-risk learning scenarios, examinations, assessments, and pathway decisions within the AcaPro AI platform  
**Effective Date:** 20 January 2026 (Melbourne Time)

---

## 1. Purpose of Risk Control

This document defines the **Risk Control Framework** of the AcaPro AI platform.

Its purpose is to:

- Identify and govern high-risk educational scenarios  
- Prevent unsafe, opaque, or overconfident AI behavior  
- Enforce human accountability where consequences are significant  
- Protect learners, institutions, and educators from systemic risk  

This document is binding under the authority of:

- `01_PLATFORM_CONSTITUTION.md`  
- `02_ARCHITECTURE_OVERVIEW.md`  
- `03_AGENT_SYSTEM.md`  
- `05_DECISION_ENGINE.md`  
- `06_DATA_GOVERNANCE.md`  

---

## 2. Definition of Risk in Education

Within AcaPro AI, **Risk** is defined as:

> Any situation where AI guidance, interpretation, or decision  
> may materially affect academic outcomes, learner wellbeing,  
> institutional compliance, or long-term educational pathways.

Risk is evaluated by **impact**, not by intent.

---

## 3. Risk Classification Levels

All AI-supported actions MUST be classified into one of the following levels.

### 3.1 Low-Risk Scenarios

Low-risk scenarios include:

- Practice activity suggestions  
- Content sequencing  
- Non-binding feedback  

Low-risk scenarios may proceed without human escalation.

---

### 3.2 Medium-Risk Scenarios

Medium-risk scenarios include:

- Study plan adjustments  
- Diagnostic interpretations  
- Learning strategy recommendations  

Medium-risk scenarios require Agent-level validation  
before delivery.

---

### 3.3 High-Risk Scenarios

High-risk scenarios include:

- Formal assessment interpretation  
- Curriculum acceleration or delay  
- Subject or pathway selection guidance  
- High-stakes examinations (e.g. VCE, ATAR-related decisions)  

High-risk scenarios MUST NOT proceed  
without mandatory human-in-the-loop approval.

---

## 4. High-Risk Examination Contexts

High-risk examination contexts include, but are not limited to:

- National or state examinations  
- Certification or credential-linked assessments  
- University or tertiary pathway prerequisites  

In these contexts, AI MUST:

- Explicitly surface uncertainty  
- Avoid definitive or absolute claims  
- Provide reasoning traceability  
- Defer final authority to qualified humans  

---

## 5. Risk Detection and Classification

Risk detection MUST occur **before** any recommendation or output delivery.

Risk classification is determined by:

- Decision type  
- Potential long-term impact  
- Regulatory or institutional constraints  
- Learner dependency on the outcome  

Risk classification MUST be logged and auditable.

---

## 6. Mandatory Safeguards for High-Risk Scenarios

For all high-risk scenarios, the platform MUST enforce:

- Human review and approval  
- Explicit confidence and uncertainty disclosure  
- Clear explanation of reasoning boundaries  
- Option to defer or decline AI guidance  

No safeguard may be disabled for convenience or speed.

---

## 7. Prohibited Behaviors in High-Risk Contexts

In high-risk scenarios, AI systems MUST NOT:

- Present speculative output as certainty  
- Encourage irreversible actions without review  
- Replace educator or institutional authority  
- Suppress alternative options or dissenting signals  

Any such behavior is non-compliant.

---

## 8. Escalation and Override Mechanisms

High-risk decisions MUST support:

- Immediate escalation to qualified humans  
- Manual override of AI recommendations  
- Suspension of automated execution  

Override actions MUST be logged and reviewable.

---

## 9. Risk Logging and Auditability

All risk-related actions MUST be logged, including:

- Risk classification  
- Initiating Agent  
- Invoked Skills  
- Human review outcomes  
- Final decision  

Risk logs MUST be immutable and available for audit.

---

## 10. Continuous Risk Review

Risk definitions and controls MUST be reviewed periodically to:

- Reflect curriculum or regulatory changes  
- Address newly identified failure modes  
- Incorporate lessons from incidents or near-misses  

Risk review is an ongoing obligation, not a one-time setup.

---

## 11. Incident Response in High-Risk Failures

If a high-risk failure occurs:

- The incident MUST be logged immediately  
- Impact MUST be assessed and contained  
- Affected learners and institutions MUST be notified where required  
- Corrective actions MUST be documented  

Concealment or minimization of failures is prohibited.

---

## 12. Accountability and Responsibility

AI systems assist decision-making.

Responsibility remains with:

- Educators  
- Institutions  
- Platform governance authorities  

AI does not assume legal, academic, or ethical accountability.

---

## 13. Compliance and Enforcement

All high-risk handling MUST comply with:

- Platform Constitution  
- Decision Engine rules  
- Data Governance requirements  

Non-compliance may result in:

- Agent suspension  
- Skill deactivation  
- System-level restriction  

---

## 14. Foundational Statement

In education, the cost of error is human.

Risk control exists to ensure  
that intelligence proceeds  
with caution, humility,  
and accountability.
