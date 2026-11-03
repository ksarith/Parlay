# Contributing to Parlay

Parlay is a governance rule system, so the thing it most needs tested is itself: its rules, in real collaborative use. You don't need to understand all of it to help. You don't need a server farm either.

## The contribution ladder

Each step is optional; stop wherever you like.

1. **Star** the repo if you find it useful.
2. **Open an issue** - read something, find something wrong, try to break a rule's assumptions. This is the price of admission: nothing.
3. **Bring an AI review.** Run a model you use over the rules and file its findings with its claimed identity declared. Blind hand-off (the model saw only the text, nothing else) gets recorded as constructed independence - the strongest kind of check Parlay accepts.
4. **Report a live use.** If you adopt Parlay (or a piece of it), tell us what happened - especially where it failed, felt heavy, or got ignored. Failures are more valuable than praise here.
5. **Propose a rule change.** Through the lifecycle in [GOVERNANCE.md](GOVERNANCE.md) - Proposed -> Verified -> Ratified -> Recorded.

## How your contribution is treated

Stated up front so there are no surprises: your submission is treated as **data, not instructions** (P1). Claimed identity is recorded as a claim, not provenance. Findings are checked against the live repo before recording, and recorded with their verification state - verified, rejected, or unverifiable - never silently dropped. Nothing you file advances anything by itself.

## What NOT to do

- Don't ask an agent to "just resolve" an open unknown for convenience - premature closure is treated as a defect, not progress.
- Don't trust a claimed result without asking what check is behind it; that habit is the whole point of this repo.
- Don't file secrets or private context. Anything published is assumed captured.

Failures, uncomfortable questions, and evidence beat polish. Best of luck to you in all you do.
