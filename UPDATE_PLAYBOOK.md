# UPDATE_PLAYBOOK

This repository maintains the **latest** public draft of the IDTO concept, while preserving **versioned** snapshots and **Releases** for stable citation.

**Status:** DRAFT / not established  
**Core policy:** Keep the concept consistent. Use Discussions (RFC / Q&A) for open questions.

---

## What “updating” means in this repo

For each new version (e.g., V4.6), we do all of the following:

1) Add a **versioned draft file** under `docs/`  
2) Update the **latest pointer** (`docs/IDTO_public_draft_latest.md`)  
3) Update `CHANGELOG.md`  
4) Create a **GitHub Release** (tagged `vX.Y`)  
5) Post an **Announcement** and pin it (unpin the previous)

This keeps:
- “Latest” easy to find
- Each version stable and citeable
- Discussion tied to a known version

---

## Pre-flight checklist (before editing)

- Confirm you are on the **main** branch.
- Confirm the target version number (e.g., `V4.6`) and tag (e.g., `v4.6`).
- Prepare a short summary of changes (2–5 bullets) for Changelog/Release/Announcement.

---

## Step-by-step update procedure

### Step 1 — Add the new versioned draft file
Create a new file:

- Path: `docs/IDTO_Concept_Public_Draft_VX.Y.md`  
  Example: `docs/IDTO_Concept_Public_Draft_V4.6.md`

Paste the full updated draft content and commit.

**Commit message example:**  
`Add IDTO Concept Public Draft V4.6 (EN)`

---

### Step 2 — Update the latest pointer
Edit:

- `docs/IDTO_public_draft_latest.md`

Update:
- “Current latest” version number and date
- The link to the new versioned file (VX.Y)

**Commit message example:**  
`Update latest pointer to V4.6`

---

### Step 3 — Update CHANGELOG.md
Edit:

- `CHANGELOG.md`

Add a new section at the top (or above older entries):

```markdown
## V4.6 — YYYY-MM-DD (JST)
- Bullet 1 (what changed)
- Bullet 2 (why it matters)
- Bullet 3 (optional)
