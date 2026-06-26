# Exodus-RIF
Operational response to a major tech layoff event — how AI was used to consolidate fragmented tracking across a 500k sq ft campus into a single, actionable system.
# Exodus RIF — Operational Response to a Major Tech Layoff Event

> *"Don't stop when you're tired. Stop when you're done."* — Goggins

When a major tech company announced a significant global workforce reduction, the facilities team didn't get a warning. We got a list — and a clock nobody set.

This project documents how AI was used to transform operational chaos into a structured, executable response system adopted across all campus stakeholders.

---

## The Situation

A layoff at scale doesn't just affect people — it hits the physical infrastructure they leave behind. Hundreds of seats, dozens of spaces, multiple buildings, and a campus that still had to run without interruption.

When the reduction hit, this is what we were working with:

- **No central source of truth.** Every team had their own tracking sheet — different formats, different assumptions, different data. None of them talked to each other.
- **No visibility on impact.** Nobody had a clean picture of which spaces were involved, what the timeline looked like, or what actions needed to happen and in what order.
- **Facilities was getting pulled in every direction.** Without a unified system, every stakeholder was operating from a different version of reality. Every conversation started from scratch.

The expectation from leadership was a 45+ day turnaround to collect assets, reset workspaces, and reconcile everything into a reportable system. There was no hard deadline — just a long horizon and a lot of moving pieces.

---

## The Approach

Rather than manually reconciling every sheet by hand — which would have taken weeks and still produced errors — AI was used as a consolidation and structuring tool.

The process looked like this:

**Step 1 — Data Intake**
Collected all existing tracking sheets from every team touching the reduction. Identified the overlaps, the gaps, and the inconsistencies across all of them.

**Step 2 — AI-Assisted Consolidation**
Used iterative prompting to build a Master Tracking Sheet architecture that could absorb all stakeholder data into one unified structure. AI helped identify which fields were redundant, which were missing, and how to standardize across formats.

**Example prompt used:**
```
I have tracking sheets from multiple teams covering the same workforce reduction event.
Each has different column structures and naming conventions.
Help me design a master schema that captures all critical fields without duplication,
prioritized by what facilities operations needs to act on first.
```

**Step 3 — Attack List Generation**
From the master sheet, distilled a condensed priority action list — the spaces that needed to be addressed first, the timelines attached to each, and the responsible parties. Leadership could read it in under two minutes and know exactly where things stood.

**Step 4 — Stakeholder Alignment**
The master system was shared across all operational and client-side stakeholders on campus. One source of truth. No more competing versions. No more duplicate effort.

---

## The Outcome

| Metric | Result |
|--------|--------|
| Expected timeline | 45+ days |
| Actual execution window | 14 days |
| Workspace resets & asset collection | Completed in full |
| Operational errors during transition | Zero |
| Stakeholder alignment | Campus-wide — all teams on one system |

What leadership expected to take over a month was executed in two weeks — with higher accuracy than any manual process would have produced. The system didn't just solve the immediate problem. It became the standard.

---

## What This Project Demonstrates

- **AI as an operational tool** — not a novelty, but a structured part of a real response under pressure
- **Prompt engineering for data consolidation** — using iterative prompting to build systems, not just get answers
- **Stakeholder management at scale** — producing a deliverable that multiple teams with different needs could all use
- **Execution under ambiguity** — no hard deadline, no playbook, just a problem that needed to get done

---

## What's In This Repo

| File | Description |
|------|-------------|
| `master-tracking-template.xlsx` | Sanitized version of the Master Tracking Sheet architecture |
| `prompt-library.md` | The actual prompts used during consolidation and structuring |
| `attack-list-template.md` | The condensed priority action list format used for leadership reporting |

---

## A Note on Confidentiality

All sensitive data — employee names, specific headcount figures, and proprietary organizational information — has been removed or anonymized. What's shared here is the system architecture, the process, and the prompts. The thinking, not the data.

---

*Part of a broader portfolio exploring AI as a universal problem-solving layer across operations, finance, real estate, and fitness.*
[← Back to main portfolio](../README.md)
