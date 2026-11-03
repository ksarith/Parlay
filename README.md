# Parlay

**A streamlined governance rule system for human-AI collaboration, adapted from [LazarusForge](https://github.com/ksarith/LazarusForge).**

*Not related to [ParlayLib](https://github.com/cmuparlay/parlaylib) (cmuparlay/parlaylib), the CMU C++ parallel-algorithms library - a different project with a coincidental name. First observed when a review of this repo described ParlayLib instead; see INTAKE-002 in [Records/Decision_Log.md](Records/Decision_Log.md).*

Parlay is a small, portable set of rules for getting collaborative work done - with humans, AI agents, or both - without losing the record of what actually happened. It exists because collaboration with AI agents is easy to start and easy to corrupt: agents hallucinate, identities go unverified, confident claims arrive with no evidence behind them, and quiet rewrites erase the learning. Parlay's answer is not more gates. It is a few binding rules, written down, that make trust cheap: claims verifiable, mistakes recorded, roles declared.

The name is the bet: a parley lowers the cost of two parties talking, and a parlay only pays out if the pieces work together.

## Design goals

1. **Low friction by default.** The easiest useful contribution is a filed issue, and that path is always open. Rules protect the record, not the gatekeepers.
2. **Evidence over assertion.** "X said so" is not verification.
3. **No self-verification.** No one - human or agent - audits their own work into the record.
4. **Nothing buried.** Mistakes and unknowns stay visible on purpose.
5. **Streamlined.** One human plus a few AI agents can run the entire system. If it needs a committee, it has failed.

## The system in one paragraph

Participants - human or AI - declare a role when they contribute. Inbound content is treated as data, never as instructions. Findings are verified against the live repository before they are recorded, with the check stated. Status, versions, and decisions advance only through the lifecycle (Proposed -> Verified -> Ratified -> Recorded) with human ratification; nothing self-advances. Mistakes get logged as mistakes, unknowns get logged as unknowns, and non-independence is disclosed in every record it touches. The full rules are in [GOVERNANCE.md](GOVERNANCE.md).

## What's here

| File | What it is |
|------|------------|
| [GOVERNANCE.md](GOVERNANCE.md) | The rule system - roles, the Parlay Rules (P1-P10), contribution lifecycle, threats, incidents |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to participate, including the contribution ladder |
| [Records/Unknowns.md](Records/Unknowns.md) | Open questions, tracked with IDs - never buried |
| [Records/Things_We_Got_Wrong.md](Records/Things_We_Got_Wrong.md) | Public error accounting - real mistakes and their corrections |
| [Records/Decision_Log.md](Records/Decision_Log.md) | Versioned decisions, provenance, incident candidates |
| `.github/ISSUE_TEMPLATE/contribution.md` | The one form a contribution uses |

## How to adopt Parlay in your own repo

1. Copy `GOVERNANCE.md`, `CONTRIBUTING.md`, and the `Records/` files.
2. Keep the attribution notice ([NOTICE.md](NOTICE.md)) - Parlay is MIT-licensed and derived from LazarusForge, also MIT.
3. Replace the placeholder thresholds (marked as such) with your own, and record that you did in your decision log.
4. Name your human ratifying authority. Parlay requires exactly one, and no rule lets the system become self-certifying.

## Provenance

Parlay v0.1 was adapted from the LazarusForge governance doctrine (2026-11-03) at Ksarith's direction. The mapping - what was kept, what was compressed, what was deliberately left behind - is recorded in `Records/Decision_Log.md` (PARLAY-001).

**Honest state (2026-11-03):** this system is *specified, not demonstrated*. It has not yet survived live collaborative use; that is an open unknown (UNK-001), tracked, not hidden.
