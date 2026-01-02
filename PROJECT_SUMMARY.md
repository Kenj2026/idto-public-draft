# PROJECT_SUMMARY — IDTO Public Draft Repository

**Status:** DRAFT / For Discussion (Proposed / Pre-establishment)  
**IDTO (International Digital Transparency Organization) is proposed and not established.**  
This repository publishes a public draft of the IDTO concept: a **non-regulatory, no-rating, federated transparency protocol**.

This summary is intended to help readers quickly understand:
- what IDTO is (and is not),
- what is fixed vs. open for discussion,
- how this repository is organized,
- how to participate constructively.

---

## 1) What IDTO is (and is not)

### What IDTO is
IDTO proposes a **protocol-first** approach to transparency: a shared format that makes digital systems **recordable and reviewable** by the public.
The aim is to move from reactive debates to evidence-based improvement by standardizing how systems are documented.

IDTO is designed to be **permissionless** at the implementation layer:
anyone can build tools, registries, or verification layers on top of a shared format.

### What IDTO is not
IDTO is **not**:
- a regulator,
- an enforcement authority,
- a rating agency,
- a centralized gatekeeper,
- a single platform that owns everyone’s data.

IDTO provides a **common language (protocol)** so that others can build and verify in their own contexts.

---

## 2) Fixed vs. Open

### Fixed (Constitution-level core)
These are non-negotiable in this draft:

**3 Pillars**
1) Error-Correction as an OS  
2) Recording Intent & Change  
3) Protocol, not a Platform  

**6 Keywords**
- Good-faith by default  
- Non-regulatory  
- Traceable & auditable  
- No rating  
- Federated  
- Politically neutral  

Proposals that contradict these are out of scope for this draft.

### Open (RFC: Request for Comments)
Operational details and implementation choices are intentionally open for discussion.
The open design space is organized in **Chapter 8 (Future Challenges / RFC)** of the draft.

---

## 3) Conceptual model (high level)

IDTO is described as a “public infrastructure for transparency” with a protocol-oriented structure:

- **IDTOpedia (Open Knowledge Base):** human-readable explanations and references  
- **Open Disclosure Registry (Structured Ledger):** machine-readable primary disclosure (intent, data handling, change logs, etc.)  
- **Verification Layer (Public Peer Review):** review and improvement proposals (critique → patch)

A useful metaphor is: **“a README for society.”**
IDTO standardizes the headers and minimal structure so systems can be understood, compared (without scoring), and improved.

---

## 4) Repository structure

### Primary documents
- `docs/IDTO_public_draft_latest.md`  
  The pointer to the current latest draft (always updated).
- `docs/IDTO_Concept_Public_Draft_Vx.y.md`  
  Versioned drafts for stable citation (e.g., V4.6).

### Project governance & operations (repository-level)
- `README.md` — the entry point
- `CHANGELOG.md` — what changed and why (major updates)
- `UPDATE_PLAYBOOK.md` — how updates/releases are performed
- `CONTRIBUTING.md` — where to post and how to propose changes
- `FAQ.md` — common questions and clarifications
- `LICENSE` — CC BY 4.0

---

## 5) How to read and cite

### Where to read the latest
- Repository home: `https://github.com/Kenj2026/idto-public-draft`
- Latest draft pointer: `docs/IDTO_public_draft_latest.md`
- Releases: `https://github.com/Kenj2026/idto-public-draft/releases`

### Citation guidance
For stable citation, reference a **versioned file** (e.g., `V4.6`) and/or a **Release tag** (e.g., `v4.6`), not the “latest” pointer.

---

## 6) Discussion areas (how to participate)

IDTO is a draft for discussion. Please use GitHub Discussions/Issues:

### Discussions
- **RFC (design discussions):** the main venue for Chapter 8 topics  
- **Q&A (questions):** clarifications and terminology  
- **Announcements:** release updates (latest announcement is pinned)

RFC category index:
- `https://github.com/Kenj2026/idto-public-draft/discussions/categories/rfc`

### Issues
Use Issues for concrete, actionable edits:
- wording that is easily misunderstood,
- missing references or links,
- specific suggested replacement text.

### Proposed format for high-quality proposals
When posting (RFC/Q&A/Issue), please include:
- **Proposed change**
- **Rationale**
- **Trade-offs / risks**
- **Alternatives** (optional)
- **Minimal viable version** (what can ship first)

---

## 7) Update policy (practical)

This repository follows a simple pattern:
1) Add a versioned draft under `docs/`  
2) Update `docs/IDTO_public_draft_latest.md`  
3) Update `CHANGELOG.md`  
4) Create a GitHub Release (tagged `vX.Y`)  
5) Post an Announcement and pin it (unpin the previous)

This keeps:
- stable references (versioned files + releases),
- a clear “latest” pointer,
- an auditable history of changes.

---

## 8) Current focus (V4.6 and beyond)

Recent updates emphasize **RFC expansion** (discussion topics) without changing the constitutional core.
Key open topics include:
- Defensive disclosure & safe-harbor-by-protocol (without IDTO granting immunity)
- Incentives & trust signals (without rating)
- Machine readability & structured schemas (how far to formalize, staged maturity, constraints)
- Verification quality, neutrality & community norms (constructive review, COI handling, moderation)

---

## 9) License
Repository content is licensed under **CC BY 4.0**. See `LICENSE`.

---

## 10) Disclaimer
This is a public draft for discussion.  
It does not represent a legally established organization, does not provide legal advice, and does not guarantee adoption or endorsement by any entity.
