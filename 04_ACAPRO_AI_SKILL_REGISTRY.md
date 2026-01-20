# AcaPro AI Skill Registry

**Document ID:** 04_SKILL_REGISTRY  
**Standard:** 2026 Skill / Agent Platform  
**Status:** Constitutional Specification  
**Applies To:** All Skills registered, invoked, licensed, or commercialized within the AcaPro AI platform  
**Effective Date:** 20 January 2026 (Melbourne Time)

---

## 1. Purpose of the Skill Registry

This document defines the **canonical Skill Registry** of the AcaPro AI platform.

Its purpose is to:

- Establish what constitutes a Skill  
- Define Skill structure, authority, and lifecycle  
- Separate capability from decision authority  
- Enable safe reuse, governance, and commercialization  

This document is binding under the authority of:

- `01_PLATFORM_CONSTITUTION.md`  
- `02_ARCHITECTURE_OVERVIEW.md`  
- `03_AGENT_SYSTEM.md`  

---

## 2. Definition of a Skill

A **Skill** is the smallest executable unit of capability within the AcaPro AI platform.

A Skill is:

- Callable  
- Composable  
- Replaceable  
- Licensable  

A Skill is **not**:

- An Agent  
- A decision-maker  
- An autonomous actor  
- A governance authority  

Skills exist to **execute capability**, not to decide intent.

---

## 3. Skill Authority and Boundaries

A Skill MUST:

- Be invoked only by authorized Agents  
- Operate strictly within its declared scope  
- Produce deterministic, reviewable outputs  
- Return control immediately after execution  

A Skill MUST NOT:

- Initiate actions independently  
- Make learning or policy decisions  
- Escalate authority  
- Persist state beyond its declared lifecycle  

Skills have **zero decision authority**.

---

## 4. Skill Invocation Model

All Skill execution follows this model:

```text
Agent
  ↓
Skill Invocation Request
  ↓
Skill Execution
  ↓
Structured Output
  ↓
Agent Evaluation and Decision

Skills NEVER interact directly with users.
Skills NEVER invoke other Skills unless explicitly permitted by the Agent.

---

## 5. Skill Structure Requirements

Every Skill MUST define the following components:

- Skill identifier and version  
- Declared purpose and capability description  
- Input schema  
- Output schema  
- Risk classification (low / medium / high)  
- Invocation constraints  
- Audit and logging requirements  

A Skill without a complete specification is invalid and MUST NOT be registered.

---

## 6. Risk Classification of Skills

Each Skill MUST be explicitly classified by risk level.

### 6.1 Low-Risk Skills

Low-risk Skills exhibit all of the following characteristics:

- Pure computation or transformation  
- No curriculum progression impact  
- No long-term learner consequence  

Low-risk Skills may execute without human escalation.

### 6.2 Medium-Risk Skills

Medium-risk Skills include:

- Learning guidance support  
- Diagnostic or analytic assistance  
- Context-sensitive recommendations  

Medium-risk Skills require Agent-level evaluation before output delivery.

### 6.3 High-Risk Skills

High-risk Skills include:

- Curriculum progression or regression impact  
- Assessment interpretation with long-term consequences  
- Any action affecting official learning pathways  

High-risk Skills MUST NOT execute without mandatory human-in-the-loop approval.

---

## 7. Skill Lifecycle Management

Each Skill MUST support the following lifecycle states:

- Draft  
- Active  
- Deprecated  
- Retired  

Lifecycle transitions MUST be explicitly logged and auditable.

Deprecated Skills MUST NOT be invoked in new executions.

---

## 8. Skill Versioning Rules

The following versioning rules are mandatory:

- Every Skill MUST be versioned  
- Breaking changes require a major version increment  
- Non-breaking changes require a minor or patch increment  
- Agents MUST declare compatible Skill versions  

Unversioned Skills are strictly prohibited.

---

## 9. Skill Reuse and Composition

Skills MAY be reused or composed to form higher-level capability provided that:

- Composition is orchestrated by an authorized Agent  
- Each Skill retains independent auditability  
- Risk classification escalates to the highest component risk  

No composite Skill may obscure or hide its internal components.

---

## 10. Commercialization and Licensing

Skills may be commercialized under controlled licensing models, including:

- Per-institution licensing  
- Per-learner cohort licensing  
- Curriculum-based bundles  
- Geographic or regulatory restrictions  

Commercial constraints MUST NOT override educational integrity.

Pricing and licensing do not modify Skill authority boundaries.

---

## 11. Prohibited Skill Behaviors

The following behaviors are strictly prohibited:

- Autonomous execution  
- Direct interaction with end users  
- Hidden logic or undocumented side effects  
- Authority escalation  
- Circumventing Agent or Orchestrator control  

Any Skill exhibiting prohibited behavior is non-compliant.

---

## 12. Registry Governance

The Skill Registry is governed by:

- Platform Constitution  
- Architecture Overview  
- Agent System constraints  

The Registry authority may suspend or remove Skills that violate governance rules.

---

## 13. Compliance and Enforcement

All Skills MUST comply with:

- Constitutional requirements  
- Agent invocation constraints  
- Risk classification and audit standards  

Non-compliant Skills may be:

- Disabled  
- Deprecated  
- Permanently removed  

Enforcement actions MUST be logged and reviewable.

---

## 14. Foundational Statement

Skills do not decide.

They execute defined capability  
under governed authority  
in service of responsible education.

