# AcaPro AI Decision Engine

**Document ID:** 05_DECISION_ENGINE  
**Standard:** 2026 Skill / Agent Platform  
**Status:** Constitutional Specification  
**Applies To:** All decision-making, recommendation, escalation, and execution flows within the AcaPro AI platform  
**Effective Date:** 20 January 2026 (Melbourne Time)

---

## 1. Purpose of the Decision Engine

This document defines the **Decision Engine** of the AcaPro AI platform.

Its purpose is to:

- Govern how intelligence becomes action  
- Enforce risk-aware, auditable decision-making  
- Prevent uncontrolled or opaque recommendations  
- Ensure human accountability in high-risk education contexts  

This document is binding under the authority of:

- `01_PLATFORM_CONSTITUTION.md`  
- `02_ARCHITECTURE_OVERVIEW.md`  
- `03_AGENT_SYSTEM.md`  
- `04_SKILL_REGISTRY.md`  

---

## 2. Definition of a Decision

Within AcaPro AI, a **Decision** is defined as:

> Any action, recommendation, or output  
> that may influence learning behavior,  
> curriculum progression, assessment interpretation,  
> or long-term educational outcomes.

Not all outputs are decisions,  
but **all decisions produce outputs**.

---

## 3. Decision Authority Model

Decision authority within the platform is layered and constrained.

Authority is determined by:

- Decision risk level  
- Agent type and scope  
- Skill invocation context  
- Human-in-the-loop requirements  

No single component holds absolute decision authority.

---

## 4. Decision Risk Classification

Every Decision MUST be classified into one of the following risk levels.

### 4.1 Low-Risk Decisions

Low-risk Decisions include:

- Content sequencing suggestions  
- Practice activity recommendations  
- Non-binding feedback  

Low-risk Decisions may be delivered automatically.

---

### 4.2 Medium-Risk Decisions

Medium-risk Decisions include:

- Study plan adjustments  
- Diagnostic interpretations  
- Learning strategy recommendations  

Medium-risk Decisions require Agent-level evaluation  
before delivery.

---

### 4.3 High-Risk Decisions

High-risk Decisions include:

- Curriculum acceleration or delay  
- Assessment interpretation with long-term impact  
- Pathway or subject selection guidance  

High-risk Decisions MUST NOT be delivered  
without mandatory human review and approval.

---

## 5. Canonical Decision Flow

All Decisions MUST follow the canonical Decision Flow.

```text
1. Context Ingestion
2. Risk Classification
3. Agent Authorization Check
4. Skill Invocation
5. Output Evaluation
6. Human Escalation (if required)
7. Decision Confirmation
8. Decision Logging

## 6. Decision Validation Rules

Every Decision MUST satisfy all of the following validation rules before delivery:

- Context completeness is verified  
- Risk classification is explicit and correct  
- Agent authority is confirmed  
- Skill outputs are evaluated for correctness and scope  
- Human escalation rules are enforced where required  

A Decision that fails validation is invalid  
and MUST NOT be delivered to any user.

---

## 7. Human-in-the-Loop Enforcement

Human involvement is mandatory for:

- All high-risk Decisions  
- Any irreversible educational outcome  
- Any Decision with regulatory, compliance, or credential impact  

Human reviewers retain final authority.

AI assistance does not transfer responsibility or accountability.

---

## 8. Decision Logging and Auditability

Every Decision MUST be logged with the following attributes:

- Timestamp  
- Initiating Agent  
- Invoked Skills and their versions  
- Risk classification  
- Human review status  
- Final confirmed outcome  

Decision logs MUST be:

- Immutable  
- Reviewable  
- Retained according to governance policy  

Unlogged Decisions are strictly prohibited.

---

## 9. Prohibited Decision Behaviors

The following behaviors are strictly prohibited:

- Hidden or implicit Decisions  
- Prompt-only policy enforcement  
- Model-driven Decisions without Agent control  
- Decisions delivered without logging  
- Decisions that bypass human escalation rules  

Any Decision exhibiting prohibited behavior is non-compliant.

---

## 10. Separation of Decision and Capability

The Decision Engine enforces a strict separation between:

- **Decision authority** (Agents and Governance)  
- **Capability execution** (Skills)  

Skills execute defined capability.  
Agents decide intent.  
The Decision Engine governs transformation from intent to action.

---

## 11. Failure Handling and Rollback

If a Decision is later determined to be invalid:

- The Decision MUST be reversible where possible  
- A rollback or corrective action MUST be logged  
- Affected stakeholders MUST be notified  

Silent failure, silent correction, or unlogged rollback is prohibited.

---

## 12. Compliance and Enforcement

All Decisions MUST comply with:

- Platform Constitution  
- Architecture constraints  
- Agent authority rules  
- Skill risk classifications  

Non-compliant Decisions may result in:

- Agent suspension  
- Skill deactivation  
- System-level safeguard activation  

---

## 13. Evolution and Change Control

Changes to the Decision Engine require:

- Explicit version updates  
- Documented rationale  
- Impact assessment on Agents and Skills  
- Approval under governance authority  

Ad-hoc or undocumented modification is prohibited.

---

## 14. Foundational Statement

Decisions are not answers.

They are governed commitments  
made under risk, responsibility,  
and human accountability.

