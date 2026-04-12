# Dan Koe Full Corpus Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Add a durable corpus layer, source index, source templates, and second-pass distillation skeleton for `dan-koe-skill`.

**Architecture:** Create a three-layer repository layout: raw corpus, normalized corpus, and distilled research notes. Keep source tracking in a single CSV so every future synthesis can be traced back to public materials.

**Tech Stack:** Markdown, CSV, local Codex skill repository

---

### Task 1: Create corpus structure

**Files:**
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\README.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\source-index.csv`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\youtube\_template.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\newsletters\_template.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\podcasts\_template.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\courses\_template.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\social\x\_template.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\social\linkedin\_template.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\social\instagram\_template.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\normalized\_template.md`

- [ ] Add the corpus directories and templates.
- [ ] Add a CSV header that can serve as the single source ledger.
- [ ] Document naming rules and workflow in `corpus/README.md`.

### Task 2: Create second-pass distillation files

**Files:**
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\07-source-map.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\08-theme-clusters.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\09-mental-models.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\10-heuristics.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\11-voice-dna.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\12-contradictions-and-tensions.md`
- Create: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\13-content-to-product-map.md`

- [ ] Add templates for future distillation work.
- [ ] Keep each file focused on one output layer.

### Task 3: Verify repository structure

**Files:**
- Verify: `C:\Users\28948\.codex\skills\dan-koe-skill\corpus\`
- Verify: `C:\Users\28948\.codex\skills\dan-koe-skill\references\research\`

- [ ] Confirm all expected directories and files exist.
- [ ] Confirm the CSV header is intact.
- [ ] Confirm no placeholder path is broken.
