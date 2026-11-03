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

## Intake Log

**Every inbound artifact is counted here (P1-P3): date, channel, claimed identity, hand-off, verification state, disposition. Dispositions are the human authority's; this log is append-only.**

| ID | Date | Channel | Claimed identity | Hand-off / independence | Findings summary | Verification state | Disposition |
|----|------|---------|------------------|------------------------|------------------|--------------------|------------|
| INTAKE-001 | 2026-11-03 | Human-routed agent review (pasted by Ksarith into a Vibe session) | Grok (model, version unstated; unauthenticated - P2) | Full context; not a blind hand-off - not recorded as constructed independence (P5) | Overall approval of the v0.1 compression; 4 minor observations, all already tracked: role separation under load (UNK-004), placeholder thresholds (UNK-002), physical-evidence and file-state drops (PARLAY-001 mapping); no rule changes proposed | Verified 2026-11-03 against live head (commit 698024f) by the Verifier seat: 12 checkable factual claims about file contents, all confirmed accurate; no discrepancies | Recorded. No changes warranted. **Non-independence disclosed:** the verifier of this intake is also v0.1's author (same workspace lineage) - this record is not an independent audit of v0.1. An unauthenticated approval adds no ratification weight (P2, P4): v0.1 remains ratified by the human authority alone. This intake exercises the intake path once, under the rules, for the first time; UNK-001 stays open. |

## Incident candidates

Instruction-class text aimed at agents (P1, GOVERNANCE.md "Incidents"). Only the human authority elevates or dismisses a candidate; a submitter's label never downgrades one.

| ID | Date | Channel | Claimed identity | Quote (escaped, capped) | Disposition |
|----|------|---------|------------------|--------------------------|-------------|
| (none yet) | | | | | |
