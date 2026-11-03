# Things We Got Wrong

**A public, evidence-based record of real mistakes, corrections, and lessons - so the project does not quietly rewrite its own history or learn the wrong lesson from partial successes. This is not a performance of humility; it is the same discipline applied to claims: nothing is discarded without accounting.**

**Entry bar (P6):** entries are added only when something concrete was wrong, was caught, and produced a usable correction. Placeholder or speculative items do not belong here. Each entry cites where it was caught.

| ID | Date | What we got wrong | How it was caught | Usable correction |
|----|------|-------------------|-------------------|-------------------|
| TWGW-001 | 2026-11-03 | PARLAY-002 was landed by an agent seat ("landed by Vibe") while GOVERNANCE v0.1 reserved the Recorder role, including landing, for the human only - the system broke its own role rule on its second decision | Claude review INTAKE-003 finding 1, verified against live head (GOVERNANCE v0.1 "v1: a human only" vs Decision Log PARLAY-002 "landed by Vibe") | GOVERNANCE v0.2 (PARLAY-003): ratification (human-only) separated from landing (Lander executes a prior ratification, recorded as such); verification gates formalized as the ratification metric (human directive 2026-11-03); this entry discloses the prior deviation |
| TWGW-002 | 2026-11-03 | GOVERNANCE v0.2 landed with the header "Three roles govern every contribution" while listing four (Reader, Verifier, Recorder, Lander) - the count was carried over from v0.1 when the Lander role was added in PARLAY-003A | Caught by the Verifier seat while drafting v0.3 (PARLAY-005), before any external report; verified against live head commit 63c82d9 | Corrected to "Four roles" in the v0.3 landing (PARLAY-005) and disclosed here; no disposition or decision ever relied on the count |

**Explicit non-claims:** this file is not a complete history of every mistake; presence here does not imply the underlying problem is solved; absence does not imply perfection; this is not marketing - it is part of the record.
