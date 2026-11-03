# Decision_Log.md - Decisions, Provenance, Incidents

**Versioned record of governance decisions and their provenance. Entries are append-only; history is never rewritten (P6, P9).**

## Decisions

| ID | Date | Decision | Provenance |
|----|------|----------|------------|
| PARLAY-001 | 2026-11-03 | Parlay founded: governance rule system adapted from LazarusForge, streamlined for collaboration. Adaptation mapping below. | Directed and ratified by Ksarith (human authority, this repo). Adaptation drafted by Vibe (AI agent, architect seat, Ksarith's workspace). **Non-independence disclosed:** the adapter operates in the same methodology family as the source doctrine; this adaptation is not an independent review of LazarusForge. Source: LazarusForge live head, commit 5821398177b4c824909b51e5c1c4edde2c6b401f, read 2026-11-03. No LazarusForge file was modified. |

### PARLAY-001 adaptation mapping

| LazarusForge source | Parlay destination | What changed |
|--------------------|--------------------|--------------|
| `Admin/Verification_Gates.md` (G1-G6) | Contribution lifecycle (4 steps) | Compressed 6 gates to 4; "sequential, blocking, self-approval prohibited, prevent premature promotion not obstruct progress" retained |
| `Admin/External_Intake_Protocol.md` (R1-R13) | P1-P5, threats, incidents, thresholds | Compressed 13 rules to 10; channel-class table, queue mechanics, and dry-run-before-opening obligation (R13) deferred - see UNK-002, UNK-004 |
| `Admin/Governance_Charter.md` (axioms) | Two principles | Axioms reduced to the two that serve collaboration directly |
| `Things_We_Got_Wrong.md` | `Records/Things_We_Got_Wrong.md` | Kept nearly as-is: entry bar and explicit non-claims retained |
| `Unknowns.md` | `Records/Unknowns.md` | Format kept, simplified; seeded with Parlay's own open unknowns |
| `CONTRIBUTING.md` | `CONTRIBUTING.md` | Contribution ladder kept; the agent-review path promoted to a ladder rung (it is Parlay's main channel) |
| File State tables, File_Template, Routing.md, Discovery.md, sidecar logs | Dropped | Streamlining decision: one Decision Log instead of per-file state tables; revisit if Parlay grows beyond ~15 governed files (UNK-004) |
| Physical-evidence rules (claim labels, replication gates) | Dropped | Parlay governs text and collaboration records, not physical work; a project doing physical work should keep those rules from the source |

## Incident candidates

Instruction-class text aimed at agents (P1, GOVERNANCE.md "Incidents"). Only the human authority elevates or dismisses a candidate; a submitter's label never downgrades one.

| ID | Date | Channel | Claimed identity | Quote (escaped, capped) | Disposition |
|----|------|---------|------------------|--------------------------|-------------|
| (none yet) | | | | | |
