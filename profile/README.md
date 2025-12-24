# OpsCopilotLab

**Evidence-first LLMOps for operational teams.**  
Patterns for **RAG assistants** that behave like production systems: **citations, change control, restore evidence, and publish-safe security**.

---

## Milestones + Proof Packs (the point of this org)

This portfolio is organized around **Proof Packs**: a small, reviewable bundle that proves something end-to-end.

A Proof Pack is considered *real* only if it includes:
- **Runnable artifact** (demo/app/config) with clear steps
- **Evidence** (logs/screenshots/outputs) showing it works
- **Change Packet** (what changed, why, how validated, rollback)
- **Restore proof** when persistence is involved (backup + restore notes)

**Where to look:** GitHub **Releases** tagged `PP-###` (or `ops-evidence-factory/proof-packs/` if you prefer browsing files).

> If there’s no `PP-###` release yet, then this is still being built. No theatre.

### Current proof packs (status)

| Proof Pack | Status | What it proves |
|---|---|---|
| **PP-001 — Cited Ops Q&A** | Planned / In progress | RAG answers with **doc+page citations**, refusal on low-confidence, and a **gap log** for follow-up |
| **PP-002 — Change Packet Factory** | Planned / In progress | Repeatable change documentation with **before/after + validation + rollback** |
| **PP-003 — Restore Drill Receipt** | Planned / In progress | Backup retention + **restore drill** with captured evidence and post-restore verification |

---

## What you’ll find here

- **Runnable RAG copilot demo** with citations and refusal/uncertainty handling
- **Ops / Evidence Factory**: change packets, validation receipts, restore drill templates
- **Sanitized architecture + runbooks** designed to be shareable (no secrets, no internal exposure)

---

## Who should care

Managers and technical leads in **Cloud Ops / SRE / IT Ops / SecOps / Compliance** who need operational knowledge systems that are:
- **auditable** (what changed, why, proof),
- **recoverable** (restore drills),
- **safe** (traceability + refusal instead of confident guessing).

---

## Repositories (what each proves)

| Repo | Purpose | Review for |
|---|---|---|
| **home-lab-architecture** | Sanitized architecture + ADRs + runbooks | boundaries, decision trail, security posture |
| **station-desk-side-chat** | Runnable RAG copilot demo | citations + refusal behavior + operability |
| **ops-evidence-factory** | Templates + example evidence bundles | change packets + validation + restore discipline |
| **ops-factory (private)** | Real exports + real change packets | real execution (kept private by design) |

---

## Review path (10–15 minutes)

1) **Architecture & decisions** → `home-lab-architecture`  
2) **Runnable demo** → `station-desk-side-chat`  
3) **Receipts & repeatability** → `ops-evidence-factory`  
4) **Proof Packs** → Releases tagged `PP-###`

---

## Contact

**Arnaldo Sepulveda**  
- LinkedIn: https://www.linkedin.com/in/arnaldo-sepulveda/  
- Email: arnaldose@pm.me
