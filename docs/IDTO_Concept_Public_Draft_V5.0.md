# Building a “Public Infrastructure for Transparency”: The IDTO Concept (Public Draft) V5.0
International Digital Transparency Organization (Provisional: IDTO) — Background and Draft Explanation (For Public Release)

**Updated:** 2026-01-02 (JST)  
**Status:** DRAFT / For Discussion (Proposed / Pre-establishment)

## Notes
- This document is a public concept draft. It does **not** guarantee the establishment of IDTO, participation by any specific entity, or adoption of the protocol.
- “IDTO” is a provisional name. Any resemblance to existing organizations is coincidental.
- This document does not constitute legal advice.
- V5.0 **rebuilds the English draft** to inherit the structure and substantive content of the long-form Japanese V4.5, while preserving the expanded RFC topics introduced in V4.6. The constitutional core (3 pillars / 6 keywords) remains unchanged.

---

## 0. Executive Summary (TL;DR)

### The Problem
Technology increasingly defines social rules *as implementation*, yet the perspective behind that implementation—its values, goals, and optimization choices—often remains difficult to see.

When intent is unclear and change history is inaccessible, accountability becomes impression-driven instead of evidence-driven. Debate polarizes, and the cost of misunderstanding rises.

### The Goal
We need more than “regulation for punishment.” We need **public infrastructure for transparency** that enables society to:
- understand a system’s intent (what it is optimizing for),
- track and audit meaningful changes over time, and
- review evidence and improve explanations through error-correction.

### The Solution
IDTO is neither a regulator nor a rating agency. It proposes a **non-regulatory, no-rating, federated transparency protocol**: a common language that makes transparency **recordable and reviewable** across digital systems.

### Vision (Adoption-first)
IDTO is protocol-first and **permissionless**: anyone can implement compatible registries, schemas, and verification workflows without centralized gatekeeping. The aim is to make transparency an interoperable public layer—similar in spirit to shared technical standards—rather than a single platform.

### 0.1 Fixed vs. Open Elements
**Fixed (Constitution)**
- Purpose: Shift digital decision-making from “impression” to “fact and verification.”
- Positioning: IDTO provides a common language (protocol), not judgments.
- The **3 Pillars (Ch. 3)** and **6 Fixed Keywords (Ch. 4)** are non-negotiable.

**Open (RFC: Request for Comments)**
- Operational details and implementation choices are intentionally open for discussion in **Chapter 8 (Future Challenges)**.

---

## 1. Introduction: Why IDTO?
Our society now relies on digital systems for search, social communication, payments, logistics, health, education, and public administration. In practice, many systems “write the law” through implementation: ranking, recommendation, access control, pricing, moderation, and automation shape outcomes at scale.

At the same time, affected people often lack the ability to answer basic questions:
- What is the system trying to optimize for?
- What data is collected, inferred, shared, and retained?
- What interventions exist, and under what logic?
- When something changes, what changed and why?
- Where is redress possible?

IDTO proposes a transparency protocol so that these questions can be answered in a **structured, traceable, and reviewable** manner—without requiring a single global authority.

---

## 2. Ethical Foundation: “Justice” as Error-Correction
This concept treats “justice” not as a final verdict, but as **error-correction**:
- We do not assume perfection.
- We prioritize the ability to discover mistakes, explain them, correct them, and learn.
- The focus shifts from “who is right” to “how we fix it.”

In digital governance, error-correction requires evidence, traceability, and a process that can evolve when reality changes.

---

## 3. The Three Pillars (Conceptual Protocol)

### 3.1 Error-Correction as an OS
IDTO assumes systems will fail. The goal is to make failures inspectable and correctable:
- surface claims and assumptions,
- enable evidence-based review,
- incorporate improvements over time.

### 3.2 Recording “Intent & Change”
Every disclosure must connect at least two points:
- **Intent:** What is the system trying to achieve? (optimization goals, priorities, constraints)
- **Change:** What was modified? (change logs, versioned policies, meaningful updates)

This creates an objective base for reviewing whether implementation matches intent.

### 3.3 Protocol, Not a Platform
IDTO is not a walled garden. It standardizes **formats and mappings**, not ownership:
- records may be hosted by their owners,
- tools can be built by anyone,
- verification can be plural and independent.

---

## 4. The 6 Fixed Keywords (Constitutional Level)

The Constitution-level core is fixed to reduce predictable misinterpretations.  
Proposals that contradict these are out of scope for this draft.

**3 Pillars**
- Error-Correction as an OS
- Recording Intent & Change
- Protocol, not a Platform

**6 Keywords**
- Good-faith by default
- Non-regulatory
- Traceable & auditable
- No rating
- Federated
- Politically neutral

(See Chapter 3 for details on the Three Pillars.)

These six keywords are fixed to reduce predictable misinterpretations.

1) **Good-faith by default**  
Start from a presumption of good faith. Require evidence for claims of misconduct, and design for correction rather than punishment.

2) **Non-regulatory**  
IDTO is not an enforcement or compliance body. It does not impose sanctions, approvals, or legal judgments.

3) **Traceable & auditable**  
Disclosures should support traceability: stable identifiers, version history, and “do-not-delete” correction practices where feasible.

4) **No rating**  
IDTO does not rank, score, label, or issue grades about services or organizations. It provides structured facts and traceability.

5) **Federated**  
Records should not be forced into a single centralized silo. Interoperability is achieved via shared headers, identifiers, and mappings.

6) **Politically neutral**  
The protocol is not designed to advantage any specific party, ideology, or political actor. It focuses on recordability and reviewability.

---

## 5. Part I — Background: Why IDTO is needed

### 5.1 The problem is not “convenience,” but “opacity”
We can no longer avoid questions about intent, data, interventions, and redress. The critical issue is that answers often exist only in forms that specialists can track—leaving most of society without usable evidence.

Without accessible, reviewable facts, discourse and policy swing toward extremes, and accountability becomes a contest of narratives.

### 5.2 The core issue is information asymmetry, not whether regulation exists
Regulation may be necessary. But before any governance regime can work well, society needs a baseline: the ability to learn—in a verifiable way—what systems are optimizing for, how they operate, and what changed over time.

### 5.3 Partial solutions already exist, but they are not connected
There are registries, common schemas, incident databases, audits, and indices. However, differences in format, terminology, and granularity make cross-reading and change-tracking difficult. We have “points,” but not “lines.”

### 5.4 Therefore we need a “Public Infrastructure for Transparency”
Rather than building a single global super-regulator, we should build public infrastructure that connects existing efforts, complements them, and makes them reviewable. With that foundation, users, companies, governments, researchers, and civil society can all move forward with shared evidence.

---

## 6. Part II — Draft Explanation: What IDTO builds

### 6.1 Mission: not regulation, but recordable and reviewable transparency
IDTO aims to make it possible for society to understand and verify the “perspective” of a digital service or public AI system—what it is optimizing for and how that changes.

To be useful, disclosures should support:
- **Transparency:** understandable explanations for humans,
- **Comparability:** shared headers enabling cross-reading where appropriate,
- **Verifiability:** traceable evidence references and change history enabling review.

### 6.2 Core mechanism: a three-layer structure (knowledge × primary disclosures × verification)
IDTO is designed as a three-layer structure: a practical minimum that translates the conceptual pillars into implementable components.

A critical constraint is to avoid flattening diverse realities into a single rigid form. Therefore, the disclosure model should support:
- **Minimal core (shared headers):** the smallest common set needed for interoperability,
- **Narrative context:** free text to preserve nuance and domain specificity,
- **Extensions (domain profiles):** optional structured fields for particular sectors,
- **Non-comparability notes:** explicit flags where comparison would mislead.

#### 6.2.1 IDTOpedia (Open Knowledge Base)
A collaboratively maintained knowledge base that:
- is readable by non-specialists,
- keeps version history,
- is evidence-based and citeable.

Its role is to reduce misunderstanding, provide shared definitions, and document context.

#### 6.2.2 Open Disclosure Registry (Structured Registry / Primary Disclosures)
A registry for machine-readable primary disclosures produced by operators (companies, governments, institutions). Its goal is to make **intent, operations, and change history** reviewable.

A minimal core disclosure typically includes:
- **Intent & optimization:** goals, priorities, constraints, trade-offs,
- **Data handling:** collection, inference, sharing, retention,
- **Interventions:** ranking/recommendation/moderation/pricing/access mechanisms (as applicable),
- **Redress:** how affected parties can contest, appeal, or seek correction,
- **Change Logs:** “what changed, when, why,” with references to evidence.

**Staged disclosure (safety-aware):** the registry may support levels such as *public / limited / time-bound embargo*, with rationale and review dates, so transparency does not increase harm.

> Terminology note: “registry” is used in the generic sense (structured records). It does not imply blockchain/DLT.

#### 6.2.3 Verification Layer (Public Peer Review)
A layer for third-party review to improve disclosures through error-correction:
- check consistency and sufficiency of claims,
- request evidence references,
- propose corrections (“patches”) rather than issuing grades.

Here, “audit” means reviewability for improvement—not enforcement.

### 6.3 Federation design: do not replace existing organizations
Federation means: keep originals with their owners, while enabling interoperability through mapping and shared identifiers.
- Records remain where they are produced.
- Different disclosure formats can be mapped to shared headers for cross-search and diff tracking.
- Mutual recognition can reduce duplicated reviews without forcing consolidation.

### 6.4 Non-goals (red lines)
To prevent predictable failure modes, IDTO must not:
- issue value judgments, grades, rankings, or labels (**no rating**),
- act as law enforcement or an approval/compliance body (**non-regulatory**),
- centralize all records into a single mandatory silo (**federated**),
- seize or extract intellectual property under the banner of transparency,
- compromise political neutrality (**politically neutral**).

### 6.5 Operations: design trust with guardrails
If IDTO were ever instantiated institutionally, trust must be designed, not assumed. Guardrails may include:
- caps and diversification of funding sources,
- multi-stakeholder governance,
- conflict-of-interest disclosure norms,
- editorial independence for knowledge and verification,
- publishing IDTO’s own intent and change logs as first-class records.

### 6.6 Implementation capacity: separate public-interest governance from operations (proposal)
To balance public interest and delivery:
- **Foundation (public-interest governance):** mission, constitutional constraints, independence guardrails
- **Secretariat (operations & technical delivery):** running registries, tooling, connectors, maintenance
- **Functional units:** knowledge, schemas, federation mappings, verification norms, etc.

### 6.7 What to build first (MVP)
A realistic initial set of deliverables:
1) **IDTOpedia** (open knowledge base)
2) **Open Disclosure Registry** (structured primary disclosures)
3) **Federation API / mappings** (interoperability without centralization)

---

## 7. The Metaphor: “A README for Society”
This concept can be seen as building a shared README for the world’s digital systems.

A README states intent. It is improved through review. It is updated through change logs.  
**IDTO defines the standard for “how to write the README” (the format), not who is good or bad.** The content evolves through plural authorship, peer review, and continuous correction.

---

## 8. Future Challenges (RFC / Invitation to Discuss)
IDTO does not impose a “complete” design at day one. What this draft fixes is the purpose, positioning, and minimal common language. Operational design and interoperability must be refined in stages, respecting institutional, legal, safety, and domain constraints.

The following are unavoidable design challenges. They are not declarations of “the correct answer,” but a checklist to align discussion and reduce misunderstanding.

### 8.1 Independence: how do we protect transparency infrastructure from capture?
- What must remain independent (governance, funding, knowledge editing, verification)?
- What guardrails prevent agenda capture without becoming a regulator?
- What is the minimum viable independence model for early adoption?

### 8.2 Change governance: who can change the protocol itself?
- What is the process for proposing, reviewing, and adopting protocol changes?
- How do we version breaking vs non-breaking changes?
- What emergency procedures exist, and how are they audited after the fact?

### 8.3 Traceability specs: how do we standardize “do-not-delete” correction?
- What is the minimal event model for changes (supersedes, corrections, retractions)?
- How do we ensure records remain citeable over time?
- How should evidence references be represented?

### 8.4 Federated operations: interoperability without centralizing power
- What mappings are needed across registries and domain profiles?
- How do we avoid “one registry to rule them all” in practice?
- How do we support cross-search while allowing local autonomy?

### 8.5 Role separation & decision-making: preventing a single final judge
- Which decisions must be distributed (schema stewardship, verification norms, dispute handling)?
- How do we design checks, balances, and appeals without turning IDTO into an authority?
- What conflict-of-interest rules are necessary and enforceable in a non-regulatory setting?

### 8.6 Funding independence & capture-resilience
- How do we prevent funding from becoming control?
- What transparency should apply to IDTO’s own funding and governance changes?
- What funding models preserve neutrality across jurisdictions?

### 8.7 Privacy, safety, and law: ensuring transparency does not increase harm
- How do we handle sensitive disclosures (security, abuse, vulnerable groups)?
- What should staged disclosure (public / limited / embargo) require?
- How can defensive disclosure reduce risk while remaining auditable?

#### 8.7.1 Defensive disclosure & safe-harbor-by-protocol (RFC)
IDTO cannot provide legal immunity. However, it may provide **good-faith evidence trails** and safety-aware disclosure procedures that support responsible disclosure practices.

### 8.8 Defining the protocol artifacts: what is standardized?
- What are the minimum interoperable artifacts (shared headers, identifiers, minimal schema, citation format)?
- Which reference specs should exist (JSON Schema, OpenAPI, mapping specs, event types)?
- How do we provide conformance tests without over-constraining innovation?
- Where is the boundary between protocol core and optional domain extensions?

#### 8.8.1 Machine readability & structured schemas (RFC)
How far should we formalize machine-readability, and what should remain narrative? What is the staged maturity path (Minimal / Standard / Advanced)?

### 8.9 Incentives & trust signals (without rating) (RFC)
- How can adoption be incentivized without turning verification into ranking?
- What “trust signals” can exist as evidence-based descriptors rather than grades?
- How do we prevent incentives from becoming coercion?

### 8.10 Verification quality, neutrality & community norms (RFC)
- What norms prevent harassment, capture, or “gotcha” dynamics?
- How do we define quality of review without issuing scores?
- What moderation or dispute processes are compatible with non-regulation and neutrality?

---

## 9. Closing: Build an understandable world before “regulation”
Debates on digital governance are often framed as a choice between state regulation and corporate self-regulation. IDTO proposes a third approach: **public infrastructure for transparency**.

By standardizing how systems document intent, changes, and reviewability, society can shift from reactive arguments to proactive, evidence-based improvement—without requiring a single centralized gatekeeper.

---

## How to Contribute
Please see `CONTRIBUTING.md` in this repository for where and how to participate (RFC, Q&A, Issues, PRs).
