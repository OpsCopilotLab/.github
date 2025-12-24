# OpsCopilotLab — Evidence‑First LLMOps for Operational Teams

**I build AI copilots that operations managers can *trust* in production.**  
Not “chatbots.” **Operational systems**: cited answers, change control, restore evidence, and secure-by-default delivery.

If you manage **Cloud Ops / SRE / IT Ops / SecOps / Compliance** and you’re tired of:
- tribal knowledge living in people’s heads,
- runbooks scattered across wikis and PDFs,
- audits that turn into fire drills,
- “AI demos” that hallucinate and can’t be operated…

…this portfolio shows the exact engineering patterns to fix that.

---

## The outcomes you can hire for

### 1) Faster, safer incident resolution
- A **RAG copilot** that answers SOP questions with **citations (doc + page)** and refuses to bluff.
- **Gap logging** turns “unknown / low-confidence” questions into a work queue for improving docs and training.

### 2) Audit-ready change control (without bureaucracy)
- Every meaningful change produces a **Change Packet**: intent, scope, before/after, validation proof, rollback plan.
- The system is built to generate **receipts** automatically and consistently.

### 3) Proven recovery, not “we think backups exist”
- Backup + restore as a first-class deliverable: **restore drills**, logs, and evidence bundles.
- Designed for environments that need repeatability (regulated ops, public sector, critical infrastructure).

### 4) Secure-by-default delivery patterns
- Segmentation mindset, least privilege, and sanitization rules that let you ship in public without leaking.

---

## What I ship (concrete deliverables)

### ✅ RAG Copilot you can operate
- Retrieval with **source traceability**
- Cited responses (doc/page)
- Confidence + refusal behavior
- Gap log loop (unanswered → improve corpus/runbooks)
- Deployment + health checks + logs

### ✅ Ops / Evidence Factory
- Change packets (CP-###)
- Baselines and desired-state snapshots
- Validation evidence (screenshots/log extracts)
- Rollback steps
- Restore drill receipts

### ✅ Secure blueprints for small enterprise & lab-to-prod discipline
- Network segmentation patterns
- Reproducible setup/runbooks
- “Publish slices” (sanitized artifacts for public credibility)

---

## 15‑minute evaluation path

1) **Architecture & decisions (sanitized)**
   - `home-lab-architecture`
   - Look for: clear boundaries, ADRs, runbooks, and security posture.

2) **Runnable product demo**
   - `station-desk-side-chat`
   - Look for: citations, refusal behavior, gap log, and a clean “how to run” experience.

3) **Receipts & repeatability**
   - `ops-evidence-factory`
   - Look for: consistent templates, example change packets, restore drill evidence.

> Private repo `ops-factory` is where real device exports and operational records live.  
> Public repos are **sanitized mirrors of real discipline**—not made-up theatre.

---

## Repo map (what each proves)

- **home-lab-architecture**  
  Sanitized reference architecture + diagrams + ADRs + runbooks  
  **Proves:** systems thinking, decision trails, secure-by-default design

- **station-desk-side-chat**  
  RAG copilot demo with citations + gap log loop  
  **Proves:** productization mindset, operability, safety against hallucination

- **ops-evidence-factory**  
  Templates + example bundles using fake/sanitized data  
  **Proves:** change control, audit-friendly documentation, restore discipline

- **ops-factory (private)**  
  Real change packets, exports, device records, publish-slice pipeline  
  **Proves:** real ops execution (kept private by design)

---

## Why this isn’t a “portfolio repo” — it’s production thinking

- **Evidence-first:** if it can’t be proven, it doesn’t ship.
- **Citations or refusal:** the copilot doesn’t get to improvise SOPs.
- **Operational ergonomics:** runbooks, health checks, failure modes, restore drills.
- **Security posture:** public credibility without public leakage.

---

## Tech surface area (what I’m comfortable owning)

- **Backend / APIs:** FastAPI, Python, auth patterns, structured logging
- **RAG / Data:** embeddings, chunking, metadata, Postgres, vector DB (Qdrant/FAISS patterns)
- **Ops / Delivery:** Docker, CI workflows, IaC patterns (Terraform mindset)
- **Observability:** metrics/logs dashboards (Prometheus/Grafana patterns)
- **Backup / DR:** restic-style backup discipline, retention, restore drills
- **Networking / Security:** VLAN segmentation concepts, firewall/router patterns, least privilege

(Exact stack per org constraints. The portfolio focuses on **patterns and receipts**, not trendy tooling.)

---

## How I plug into an enterprise team

### As an employee (Cloud Ops / SRE / Platform / AI Enablement)
I can own:
- building or hardening an internal ops copilot,
- turning scattered SOPs into a governed knowledge system,
- shipping “evidence bundles” for compliance and reliability,
- making backup/restore provable (not aspirational).

### As a consultant (short engagement)
Typical first deliverables:
- a scoped copilot MVP on your docs (with citations + refusal),
- a change packet system your team can actually follow,
- at least one documented restore drill you can show leadership.

---

## Contact
**Arnaldo Sepulveda**  
- LinkedIn: https://www.linkedin.com/in/arnaldo-sepulveda/  
- Email: arnaldose@pm.me
