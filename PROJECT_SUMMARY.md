# PROJECT_SUMMARY — IDTO Public Draft Repository

**Status:** DRAFT / For Discussion (Proposed / Pre-establishment)  
**IDTO (International Digital Transparency Organization) is proposed and not established.**  
This repository publishes a public draft of the IDTO concept: a **non-regulatory, no-rating, federated transparency protocol**.

This summary helps readers quickly understand:
- what IDTO is (and is not),
- what is fixed vs. open for discussion,
- how this repository is organized,
- how to participate constructively.

---

## 1) What IDTO is (and is not)

### What it is
A public concept draft for a transparency protocol that makes **intent** and **change history** recordable and reviewable across digital systems.

### What it is not
- Not a regulator or enforcement body (non-regulatory)
- Not a rating/scoring/labeling scheme (no rating)
- Not a centralized platform or monopoly registry (federated / protocol-first)

---

## 2) What is fixed vs. open

### Fixed (Constitution)
Non-negotiable core principles:
- **3 Pillars:** Error-Correction / Intent & Change / Protocol, not a Platform
- **6 Keywords:** Good-faith by default / Non-regulatory / Traceable & auditable / No rating / Federated / Politically neutral

Proposals that contradict these are out of scope for this draft.

### Open (RFC: Request for Comments)
Operational details and implementation choices are intentionally open for discussion.  
The open design space is organized in **Chapter 8 (Future Challenges / RFC)** of the draft.

---

## 3) Conceptual model (high level)

IDTO’s practical draft explanation (Part II of the concept draft) uses a three-layer structure:

1) **IDTOpedia** — an open knowledge base for definitions, context, and evidence-based explanations  
2) **Open Disclosure Registry** — structured primary disclosures (intent, data handling, interventions, redress, change logs)  
3) **Verification Layer** — public peer review focused on evidence and patches (not ratings)

---

## 4) Repository organization

- `docs/IDTO_public_draft_latest.md` — latest draft pointer (updated as the draft evolves)
- `docs/IDTO_Concept_Public_Draft_V5.0.md` — versioned file for stable citation
- `FAQ.md` — quick clarifications (what IDTO is / is not)
- `CONTRIBUTING.md` — how to participate (RFC / Q&A / Issues / PRs)
- `CHANGELOG.md` — why and how the draft changed between versions

For stable citation, reference a **versioned file** and/or a **Release tag**, not the “latest” pointer.

---

## 5) How to participate

- Use Discussions → RFC for open design topics (Chapter 8)
- Use Discussions → Q&A for questions and clarifications
- Use Issues for actionable edits with suggested text
- Use PRs for clarity improvements, templates, and examples (see CONTRIBUTING.md)

---

## 6) Current focus (V5.0 and beyond)

Near-term work that improves adoption without breaking the Constitution-level core:
- Define a minimal disclosure core (fields + templates)
- Define a change event model (supersedes / correction without deletion)
- Specify interoperability mappings for federated registries
- Define verification norms that avoid capture and harassment (no rating)
- Publish reference schemas (JSON Schema / OpenAPI) as optional specs
