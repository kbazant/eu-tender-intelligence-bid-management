# Architecture Decision Records

## ADR-001 — Dataverse as the system of record

**Decision:** Use Dataverse as the single operational datastore.

**Reason:** Power Apps, Power Automate, and Copilot Studio can operate against the same governed data model without introducing another database.

---

## ADR-002 — Deterministic qualification scoring

**Decision:** Keep the numeric Fit Score deterministic.

**Reason:** Qualification must remain repeatable, explainable, and auditable. Generative AI is used only for interpretation.

---

## ADR-003 — Human-owned Bid / No Bid decision

**Decision:** Copilot Studio cannot record the official decision.

**Reason:** Final Bid / No Bid accountability remains with an authorized human decision maker.

---

## ADR-004 — Minimal Copilot architecture

**Decision:** Use Dataverse knowledge plus one read-only structured Tender retrieval tool.

**Reason:** Knowledge grounding supports interpretation while structured retrieval improves exact Tender filtering and ranking without introducing additional data platforms.
