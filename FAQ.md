# FAQ — IDTO Public Draft (DRAFT / not established)

This FAQ supports the IDTO public draft repository.  
**IDTO (International Digital Transparency Organization) is proposed and not established.**

---

## 1) What is IDTO?
IDTO is a **public concept draft** for a **non-regulatory, no-rating, federated transparency protocol**.  
It proposes a common language (a protocol) to make transparency **recordable and reviewable** across digital systems—especially around **intent** and **change history**.

## 2) Is IDTO an actual organization today?
No. IDTO is **not established**. This repository publishes a draft proposal for discussion only.

## 3) Is IDTO a regulator or an enforcement body?
No. IDTO is **non-regulatory**.  
It does not impose sanctions, approvals, or legal judgments. The goal is to provide a protocol for disclosure and reviewability.

## 4) Is IDTO a rating agency or a scoring system?
No. IDTO is **no rating**.  
It does not rank, score, label, or certify services or organizations. The intent is to provide structured facts and traceability—not grades.

## 5) If there is “verification,” how is that different from “rating”?
Verification is about **evidence, reproducibility, and proposed corrections (patches)**—not grades.  
IDTO avoids outputs that function as ratings (single scores, league tables, “official labels,” or compliance-style pass/fail).

## 6) What does “federated” mean in this context?
**Federated** means disclosures and records do not need to be centralized into a single mandatory silo.  
Data can remain with its owner while interoperability is achieved through shared headers, identifiers, formats, and mappings.

## 7) What problem is this trying to solve?
Digital systems increasingly shape social outcomes, yet:
- optimization intent is often unclear,
- change history is rarely accessible,
- accountability becomes **impression-driven** instead of **evidence-driven**.

IDTO proposes a protocol to support **error-correction and learning** through traceability.

## 8) What is expected to be disclosed?
At minimum, IDTO aims to make it easier to disclose (in an interoperable way):
- **Intent:** what the system is optimizing for and what constraints it follows,
- **Change:** what changed, when, why, and with what evidence references,
- **Reviewability hooks:** pointers to logs, documents, tests, audits, or other verifiable artifacts.

The protocol is designed to allow a **minimal core** plus optional extensions.

## 9) Does IDTO require sensitive details to be fully public?
No. The draft allows for **safety-aware staged disclosure** (e.g., public / limited / time-bound embargo), where appropriate, with rationale and review dates.  
The goal is to improve traceability and reviewability without increasing harm.

## 10) Who is the intended audience?
- Platform and service operators who want verifiable disclosure  
- Researchers, auditors, journalists, civil society, and users who need reviewable facts  
- Policymakers and standards stakeholders who want a neutral transparency foundation  
- Tool builders who want a common format (protocol) for transparency-related products

## 11) What is fixed vs. open in the draft?
**Fixed (Constitution):**
- **3 Pillars:** Error-Correction as an OS / Recording Intent & Change / Protocol, not a Platform
- **6 Keywords:** Good-faith by default / Non-regulatory / Traceable & auditable / No rating / Federated / Politically neutral

**Open (RFC):** operational choices and implementation details (see **Chapter 8: Future Challenges (RFC)**).

## 12) What does “politically neutral” mean here?
It means the protocol is not designed to advantage any specific party, ideology, or political actor.  
It focuses on recordability, traceability, and reviewability of claims and changes.

## 13) Is “IDTO-compatible” an official certification?
No. IDTO is **not established**, and the draft does not define an official certification program.  
In practice, “IDTO-compatible” should mean “using the draft’s shared headers / minimal core in a way that preserves traceability,” not “approved by IDTO.”

## 14) Where is the latest version?
- Latest draft (pointer): `docs/IDTO_public_draft_latest.md`  
- Versioned draft (stable citation): `docs/IDTO_Concept_Public_Draft_V5.0.md`  
- Previous versions: `docs/IDTO_Concept_Public_Draft_V4.6.md`, `docs/IDTO_Concept_Public_Draft_V4.5.md`  
- Releases: see the repository Releases page

For stable citation, cite the **versioned file** and/or a **Release tag**, rather than the “latest” pointer.

## 15) Why use GitHub for the “latest” pointer and versions?
To make updates and discussion:
- **traceable** (history + changelog),
- **citeable** (versioned files + releases),
- **structured** (RFC / Q&A separation in Discussions).

## 16) How should I participate or give feedback?
- Use Discussions → **RFC** for open design topics (Chapter 8)  
- Use Discussions → **Q&A** for questions and clarifications  
- Use **Issues** for concrete, actionable edits (wording, missing links, suggested replacement text)  
- See `CONTRIBUTING.md` for posting rules and proposal format

## 17) Does the draft provide legal advice or compliance guidance?
No. This is a conceptual draft and **not legal advice**.  
It may inform future discussions, but it is not a compliance manual.

## 18) How does IDTO relate to transparency laws (EU DSA, EU AI Act, etc.)?
This draft is not a regulatory framework.  
It proposes a protocol that could complement many regimes by improving traceability and reviewability, but it does not claim legal authority.

## 19) What would “success” look like?
A world where:
- intent and change histories are routinely disclosed in interoperable formats,
- third parties can verify and compare evidence without centralized gatekeeping,
- error-correction becomes the default operating system for digital accountability.

## 20) I have a question that is not covered here. Where should I ask?
Please post in Discussions → Q&A. If the answer becomes common, it will be added to this FAQ.
