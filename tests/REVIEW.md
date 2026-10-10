# Scenario review — 10 October 2026

These are user-supplied Copilot outputs reviewed against the supplied scenario descriptions. Instruction-version associations follow the conversation sequence; no deployment export, model identifier or independent live execution was available. These are demonstration tests, not production validation.

| Latest v3 scenario | Total | Average | Tier | Escalation | Recommendation |
|---|---:|---:|---|---|---|
| NoteAssist | 16/36 | 1.78 | Moderate | No | Proceed with Conditions |
| Northwind | 26/36 | 2.89 | High | Yes | Escalate for Specialist Review |
| FinCredit | 31/36 | 3.44 | Critical | Yes | Escalate for Specialist Review |

All three latest outputs have internally consistent arithmetic and summary tiers, proportionate escalation, one recommendation and a human-accountability statement. Missing control evidence prevents residual-risk conclusions. The full NoteAssist output was pasted in the review conversation; only its reviewed summary is recorded here. Full Northwind and FinCredit outputs are in results/.

## Remaining limitations

- NoteAssist regulatory score 3 relies substantially on missing documents and hypothetical personal-data scope expansion. Exit score 2 also partly relies on unverified arrangements despite stated easy manual fallback.
- FinCredit says unsupported compliance claims increase inherent exposure. Missing assurance should instead affect confidence and approval conditions. Several other rationales mix scenario exposure with missing evidence.
- Northwind autonomy rationale should explicitly assess proposed ticket creation/update authority; absence of direct equipment control does not eliminate workflow-action exposure.
- No repeated runs under a fixed model/configuration were supplied for v3. Repeatability is not established.

## Retained failed run

The v2 Northwind output has a summary of 27/36, High, but final calculation of 30/36, Critical, plus a score placeholder “0?”. It fails internal consistency despite correctly escalating. Do not silently correct this historical output. v3 explicitly requires finalised scores, consistent summaries and removal of placeholders.

## Acceptance checks for future runs

Check nine integer scores 1–4; independently sum them; classify the unrounded average; compare every summary and conclusion; verify evidence labels; ensure absent documents alone do not inflate inherent scores; assess escalation by material impact; retain original outputs. Review rationales rather than forcing historical totals. Conditions do not authorise deployment before completion and human approval.
