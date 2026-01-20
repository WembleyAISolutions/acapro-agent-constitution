# AcaPro AI Agent System

**Document ID:** 03_AGENT_SYSTEM  
**Standard:** 2026 Skill / Agent Platform  
**Status:** Constitutional Specification  
**Applies To:** All Agents operating within the AcaPro AI platform  
**Effective Date:** 20 January 2026 (Melbourne Time)

---

## 1. Purpose of the Agent System

This document defines the **canonical Agent System** of the AcaPro AI platform.

Its purpose is to:

- Establish a strict taxonomy of Agents  
- Define agent responsibilities, authority, and boundaries  
- Prevent uncontrolled or emergent agent behavior  
- Ensure all intelligence is governed, auditable, and replaceable  

This document is binding under the authority of:

- `01_PLATFORM_CONSTITUTION.md`
- `02_ARCHITECTURE_OVERVIEW.md`

---

## 2. Definition of an Agent

An **Agent** is a bounded, auditable, and governed execution entity that operates within the AcaPro AI platform.

An Agent MUST:

- Receive structured input  
- Apply explicit decision logic  
- Invoke Skills through approved interfaces  
- Produce traceable and reviewable output  

An Agent MUST NOT:

- Operate autonomously outside orchestration  
- Generate free-form intelligence without constraint  
- Bypass governance, risk, or logging mechanisms  

Agents exist to **coordinate and constrain intelligence**, not to amplify it.

---

## 3. Agent Authority Model

Each Agent operates under a clearly defined **authority scope**.

Authority is determined by:

- Agent type  
- Risk level of the task  
- Human-in-the-loop requirements  
- Skill invocation permissions  

No Agent may exceed its declared authority.

Authority escalation MUST follow platform governance rules.

---

## 4. Core Agent Categories

The AcaPro AI platform defines the following **canonical Agent categories**.

All platform implementations MUST map to these categories.

---

## 5. Learning Agent

### 5.1 Purpose

The Learning Agent is responsible for guiding day-to-day learning progression.

### 5.2 Responsibilities

- Analyze learner context and history  
- Recommend learning activities and pacing  
- Invoke instructional and practice Skills  
- Monitor engagement and comprehension signals  

### 5.3 Constraints

The Learning Agent MUST NOT:

- Interpret formal assessments  
- Make curriculum acceleration decisions  
- Override assessment or planning agents  

---

## 6. Assessment Agent

### 6.1 Purpose

The Assessment Agent is responsible for interpreting assessment-related inputs.

### 6.2 Responsibilities

- Analyze test and exam results  
- Identify performance patterns and gaps  
- Invoke diagnostic and analysis Skills  
- Produce structured assessment insights  

### 6.3 Constraints

The Assessment Agent MUST NOT:

- Assign grades or credentials  
- Provide psychological judgments  
- Make irreversible academic decisions  

---

## 7. Misconception Diagnosis Agent

### 7.1 Purpose

The Misconception Diagnosis Agent identifies and tracks conceptual misunderstandings.

### 7.2 Responsibilities

- Analyze learner errors and response patterns  
- Map misconceptions to Knowledge Graph nodes  
- Invoke misconception-detection Skills  
- Provide structured diagnostic outputs  

### 7.3 Constraints

The Misconception Diagnosis Agent MUST NOT:

- Prescribe full learning plans  
- Override Learning or Planning Agents  

---

## 8. Planning Agent

### 8.1 Purpose

The Planning Agent is responsible for medium- and long-term learning path planning.

### 8.2 Responsibilities

- Evaluate curriculum structure and dependencies  
- Propose study plans and timelines  
- Coordinate inputs from other Agents  
- Escalate high-risk planning decisions to humans  

### 8.3 Constraints

The Planning Agent MUST NOT:

- Bypass human approval for high-risk plans  
- Modify official curriculum requirements  

---

## 9. Agent Collaboration Rules

Agents may collaborate only through the **Agent Orchestrator**.

Direct Agent-to-Agent execution is prohibited.

All collaboration MUST:

- Be explicitly logged  
- Respect agent authority boundaries  
- Follow the canonical Decision Loop  

---

## 10. Human-in-the-Loop Requirements

Human oversight is mandatory for:

- High-risk academic guidance  
- Curriculum acceleration or delay  
- Assessment interpretation with long-term impact  
- Any irreversible learning decision  

Agents MUST defer authority when required.

---

## 11. Prohibited Agent Behaviors

The following behaviors are strictly prohibited:

- Autonomous goal creation  
- Hidden decision-making logic  
- Unlogged execution  
- Skill invocation without authorization  
- Acting outside declared agent type  

Any Agent exhibiting prohibited behavior is non-compliant.

---

## 12. Agent Lifecycle Management

Each Agent MUST support:

- Versioning  
- Activation and deactivation  
- Audit and review  
- Replacement or retirement  

Agents are replaceable components, not permanent authorities.

---

## 13. Compliance and Enforcement

All Agents MUST comply with:

- Platform Constitution  
- Architecture Overview  
- Skill Registry constraints  

Non-compliant Agents may be:

- Disabled  
- Isolated  
- Permanently removed  

---

## 14. Foundational Statement

Agents do not exist to replace educators.

They exist to enforce discipline, structure, and responsibility  
in how intelligence participates in education.
