# UPDATE_PLAYBOOK

This repository maintains the **latest** public draft of the IDTO concept while preserving **versioned** snapshots and **Releases** for stable citation.

**Status:** DRAFT / not established  
**Core policy:** Keep the constitutional core consistent. Use Discussions (RFC / Q&A) for open questions.

---

## What “updating” means in this repo

For each new version (e.g., `V5.1`), we typically do all of the following:

1) Add a **versioned draft file** under `docs/`  
2) Update the **latest pointer**: `docs/IDTO_public_draft_latest.md`  
3) Update `CHANGELOG.md`  
4) Update repository guidance if needed (`README.md`, `FAQ.md`, `CONTRIBUTING.md`, `PROJECT_SUMMARY.md`)  
5) Create a **tag** (`vX.Y`) and a **GitHub Release**  
6) Post a brief **Announcement** in Discussions (optional but recommended)

**Important:** `docs/IDTO_public_draft_latest.md` is a pointer file.  
The single source of truth for the full text is the **versioned draft file** (e.g., `docs/IDTO_Concept_Public_Draft_V5.0.md`).

---

## Versioning guidelines (recommended)

Use simple semantic intent:

- **Major (X.0):** structural rebuilds or major narrative reorganization (e.g., inheriting a long-form structure)
- **Minor (X.Y):** meaningful additions/clarifications that preserve structure
- **Patch (X.Y.Z, optional):** typo fixes, link fixes, or minor phrasing corrections

If you want to keep tags strictly `vX.Y` only, treat patch-level fixes as `X.(Y+1)` and describe them in `CHANGELOG.md`.

---

## Pre-flight checklist (before editing)

- Confirm you are on the **main** branch.
- Decide the target version number (e.g., `V5.1`) and tag (e.g., `v5.1`).
- Confirm whether the change affects the **Constitution-level core**:
  - If yes, start with an RFC discussion and document rationale carefully.
  - If no, state explicitly: **“No changes to the Constitution-level core.”**
- Prepare a short summary of changes (2–6 bullets) for:
  - `CHANGELOG.md`
  - Release notes
  - Announcement post
- Confirm that previous versioned drafts remain in `docs/` (e.g., `V5.0`, `V4.6`, `V4.5`).

---

## Step-by-step update procedure

### Step 1 — Add the new versioned draft file (single source of truth)

Create a new file:

- Path: `docs/IDTO_Concept_Public_Draft_VX.Y.md`  
  Example: `docs/IDTO_Concept_Public_Draft_V5.1.md`

Paste the **full updated draft content**.

Recommendations inside the draft:
- Keep Chapter numbering stable where possible.
- Keep Chapter 8 as the RFC / open design space.
- If you include a “Constitution fixed block,” ensure the fixed wording matches repository guidance exactly:
  - **3 Pillars:** Error-Correction as an OS / Recording Intent & Change / Protocol, not a Platform  
  - **6 Keywords:** Good-faith by default / Non-regulatory / Traceable & auditable / No rating / Federated / Politically neutral

Commit message example:
- `Add IDTO Concept Public Draft V5.1 (EN)`

---

### Step 2 — Update the latest pointer (no full-text duplication)

Edit:
- `docs/IDTO_public_draft_latest.md`

Update:
- “Latest version” link to `IDTO_Concept_Public_Draft_VX.Y.md`
- Release tag link to `releases/tag/vX.Y`
- Updated date
- “What changed (high level)” bullets
- Fixed (Constitution) block (exact wording)
- RFC pointer (Chapter 8) and participation links

Commit message example:
- `Update latest pointer to V5.1`

---

### Step 3 — Update CHANGELOG.md

Edit:
- `CHANGELOG.md`

Add a new section at the top:

```markdown
## V5.1 — YYYY-MM-DD (JST)

**Added / Changed / Clarified**
- Bullet 1 (what changed)
- Bullet 2 (why it matters)
- Bullet 3 (optional)

**No changes**
- No changes to the Constitution-level core (3 pillars / 6 keywords). (if applicable)
```

Keep bullets consistent with:
- the release notes, and
- the “What changed” section in `docs/IDTO_public_draft_latest.md`.

Commit message example:
- `Update changelog for V5.1`

---

### Step 4 — Update repository guidance (only if needed)

Edit as necessary:
- `README.md` (latest pointer + versioned file + release guidance)
- `FAQ.md` (latest pointers, definitions, verification ≠ rating)
- `CONTRIBUTING.md` (examples like “Publishing new versions (e.g., V5.1)”)
- `PROJECT_SUMMARY.md` (reading order + pointer policy)
- `UPDATE_PLAYBOOK.md` (this file, if the process evolves)

Rule of thumb:
- If the change is purely in the draft text, you may not need to edit guidance files.
- If the update changes terminology, structure, or repository navigation, update guidance.

---

### Step 5 — Run the consistency checks (recommended)

These checks prevent the most common drift:

**A) File existence**
- `docs/IDTO_Concept_Public_Draft_VX.Y.md` exists
- `docs/IDTO_public_draft_latest.md` exists
- older versioned drafts remain in `docs/`

**B) Version strings**
- README / FAQ / PROJECT_SUMMARY / docs/latest reference the new `Vx.y` where appropriate
- No “Latest version (V4.x)” remnants remain unless intentionally preserved as “previous versions”

**C) Constitution fixed wording (exact match)**
Ensure these exact strings appear (in guidance and/or docs/latest):
- `Error-Correction as an OS`
- `Recording Intent & Change`
- `Protocol, not a Platform`
- `Good-faith by default`
- `Non-regulatory`
- `Traceable & auditable`
- `No rating`
- `Federated`
- `Politically neutral`

**D) Links**
- Versioned draft link in README works
- `docs/IDTO_public_draft_latest.md` links to the correct versioned file
- Discussions/Issues links are stable (prefer absolute URLs)

If you maintain a local check script, run it here.

---

### Step 6 — Tag and Release

After merging/pushing commits to `main`:

1) Create an annotated tag:
- Tag: `vX.Y`

2) Push tag:
- `git push --tags`

3) Create a GitHub Release:
- Title: `vX.Y`
- Body: copy the same bullets used in `CHANGELOG.md` and docs/latest “What changed”
- Attachments: optional (usually not needed for markdown-only repositories)

---

### Step 7 — Announce (recommended)

Post in **Discussions → Announcements**:
- one-line summary,
- 3–6 bullets (same as release notes),
- links to:
  - the versioned draft file,
  - the release page,
  - the RFC chapter guidance (Chapter 8).

This keeps public discussion anchored to a stable snapshot.

---

## Post-update verification (quick)

- Open repository home page: README links resolve
- Open `docs/IDTO_public_draft_latest.md`: points to the correct versioned file
- Open the versioned file: content is correct, headings render, Chapter 8 RFC is intact
- Open Releases page: `vX.Y` is visible and correct

---

## Notes on editing older versions

Versioned draft files (e.g., `V5.0`) are intended as stable citation targets.  
If you must correct a serious error in a published version, prefer:
- releasing a patch version (e.g., `V5.0.1`) or a new minor version (`V5.1`), and
- clearly recording the reason in `CHANGELOG.md`.
