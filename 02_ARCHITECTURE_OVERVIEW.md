# AcaPro AI Architecture Overview  
**Document ID:** 02_ARCHITECTURE_OVERVIEW  
**Standard:** 2026 Skill / Agent Platform  
**Status:** Constitutional Architecture  
**Applies To:** All platform implementations, runtimes, and integrations  
**Effective Date:** 20 January 2026 (Melbourne Time)

---

## 1. Architectural Purpose

This document defines the **authoritative system architecture** of the  
**AcaPro AI Education Agent Platform**.

Its purpose is to ensure that:
- All implementations follow an **Agent-first design**
- Large Language Models (LLMs) are treated as **components**, not systems
- Decision-making is explicit, traceable, and governed
- The platform remains stable under scale, commercial pressure, and model change

This document is binding under the authority of  
`01_PLATFORM_CONSTITUTION.md`.

---

## 2. Core Architectural Position

### 2.1 Agent-First, Not Model-First

AcaPro AI is architected as an **Agent System**, not an LLM application.

- LLMs are **replaceable inference engines**
- Agents are **decision-bearing entities**
- Skills are **callable capability units**
- Orchestration governs all execution

No LLM may:
- Operate autonomously
- Decide learning paths independently
- Bypass agent or governance layers

---

## 3. High-Level System Layers

The platform is composed of the following **non-negotiable layers**:

```text
User / Teacher / Parent
        ↓
Agent Interface Layer
        ↓
Agent Orchestration & Decision Loop
        ↓
Skill Invocation Layer
        ↓
LLM / Tool / Knowledge Graph Layer
        ↓
Audit, Logging, and Governance

---

## 4. Agent Orchestration Model

### 4.1 What Is an Agent?

An Agent is a bounded, auditable entity that:
- Receives structured input
- Applies decision logic
- Invokes Skills
- Produces traceable output

Agents do not generate intelligence freely.
They coordinate and constrain intelligence.

### 4.2 Orchestrator Responsibilities

The Agent Orchestrator:
- Routes tasks to appropriate agents
- Enforces decision authority
- Manages agent collaboration
- Prevents illegal or unsafe execution paths

The orchestrator is the system governor, not a convenience layer.

---

## 5. Decision Loop (Canonical)

All meaningful platform behavior MUST follow the **canonical Decision Loop**.

This loop defines how intelligence is safely transformed into action.

```text
1. Context Ingestion
2. Risk Classification
3. Agent Selection
4. Skill Invocation
5. Output Evaluation
6. Human Escalation (if required)
7. Decision Logging

### 5.1 Enforcement Rules

- No step in the decision loop may be skipped  
- No agent may bypass risk classification  
- No output may be delivered without evaluation  
- All decisions **MUST** be logged for auditability  

The Decision Loop is a **governance mechanism**, not a technical convenience.

---

## 6. Skill Invocation Architecture

### 6.1 Skills as Atomic Capability Units

Within AcaPro AI, a **Skill** is the smallest executable unit of capability.

A Skill is:

- Callable  
- Composable  
- Replaceable  
- Licensable  

Skills:

- **NEVER** initiate actions  
- **NEVER** make decisions  
- **ALWAYS** operate under Agent invocation  

### 6.2 Why Skills Exist

Skills exist to:

- Prevent monolithic agent intelligence  
- Enable safe reuse across contexts  
- Support commercial modularization  
- Allow controlled experimentation and replacement  

Skills separate **capability** from **decision authority**.

## 7. Knowledge Graph Integration

Knowledge Graphs serve as the structured source of truth for the platform.

They provide:

- Curriculum-aligned concept structures  
- Skill dependency relationships  
- Misconception and mastery tracking  
- Versioned syllabus mappings  

### 7.1 Mandatory Constraints

- Agents MUST reference structured knowledge in critical paths  
- Free-form reasoning is prohibited in high-risk decisions  
- Knowledge versions MUST be explicitly declared  

Knowledge Graphs anchor intelligence to reality.

---

## 8. Human-in-the-Loop Enforcement

Human involvement is a structural requirement, not a feature toggle.

Mandatory human checkpoints apply to:

- High-risk academic guidance  
- Curriculum acceleration or delay  
- Assessment interpretation  
- Any irreversible learning decision  

### 8.1 Human Authority Model

- Teachers may override AI decisions  
- Parents may view and question outcomes where applicable  
- Students retain agency and consent  

AI may assist, but humans remain accountable.

---

## 9. Architectural Constraints (Hard Rules)

The AcaPro AI platform SHALL NEVER:

- Grant direct LLM-to-user decision authority  
- Encode learning policy purely inside prompts  
- Hard-wire business logic into models  
- Treat agents as stateless chat handlers  

Any architecture violating these rules is non-compliant.

---

## 10. Implementation Neutrality

This architecture is technology-agnostic by design.

Valid implementations may include:

- FastAPI, NestJS, or equivalent frameworks  
- Any compliant cloud infrastructure  
- Any replaceable model provider  

### 10.1 Compliance Standard

Architecture compliance is judged by behavior, not tools.

---

## 11. Long-Term Architectural Vision

This architecture enables AcaPro AI to:

- Survive model obsolescence  
- Scale across curricula and regions  
- Support regulation, audit, and compliance  
- Separate intelligence from execution  

The system is designed for longevity, not short-term optimization.

---

## 12. Foundational Statement

The strength of an AI education system  
lies not in how much it can generate,  
But in how carefully it decides.

This architecture exists to enforce that discipline.





