# Batch 0001 Audit — The Ninety Seconds

Scope: Volume 01, Chapters 1–10, the rolling state files, and the Batch 0002 prompt. Reviewed against `outline/volume-01.md`, `outline/ending.md`, the bible, and the batch cards. Findings and applied fixes are listed below; completed prose was repaired, not rewritten.

## Applied fixes

1. **Record contradiction narrowed (Chapter 9).** The closing line claimed the terminal said none of the twenty-three had been there, which overstated the discrepancy. Seven members of Group C were never in Car 3. The line now separates the fifteen who rode in Car 3 from the seven who were behind the wall, so the contradiction stays exactly as wide as the evidence Batch 0002 has to resolve.
2. **Crossing order corrected (Chapter 3).** Tarin was wheeled through first, but the tally read as though he crossed last. The count now ends at fifteen with Tarin’s name read first, matching Chapter 4’s procession.
3. **"Still Hand" introduced (Chapter 2).** The Chapter 7 usage had no prior appearance in prose. The offer panel now carries a `Gift name` field and Elias reads it aloud, so the term is grounded at the loan.
4. **Injury description corrected (`state/chapter-summaries.md`).** Only Tarin was pinned by the steel handrail; the other fourteen were inside the buckled carriage.
5. **Unsent note described accurately (`state/open-threads.md`, `state/character-state.md`, `state/continuity.md`, chapter summaries).** Elias tore out his reply to Nell and did not send it. The state now says so, so the next batch cannot assume Nell received or answered it.
6. **Batch 0002 prompt reconciled with played beats.** The Chapter 16 card no longer re-runs the Chapter 9 handover and discovery; it now starts from the established contact, shuttle number, and missing digital row, and advances to a relative’s confirmation and a broker refusal. The Chapter 13 card no longer re-discovers `MNT-4C-17`, and the Chapter 18 card forbids re-staging future Mara’s Chapter 9 refusal.
7. **Phase prompts guarded against a duplicate run.** `workspace/phase-002-batch-plan/PROMPT.md` and `workspace/volume-01/batch-0001/PROMPT.md` carry completion status banners, and the phase prompt no longer orders a writer to update `state/phase-ledger.json`.
8. **Status header refreshed (`NOVEL_SPEC.md`).** The spec no longer claims that no prose exists.

## Controller-owned items left for the operator

- `state/phase-ledger.json` still lists `phase-002-batch-plan` as `planned` with zero attempts. Only the controller may mark a phase done.
- Neither `workspace/phase-002-batch-plan/` nor `workspace/volume-01/batch-0001/` has a `.done` marker, and phase selection takes the first `workspace/*/PROMPT.md` without one. Phase selection would therefore land on a finished batch unless the controller writes the markers. The prompt banners make a re-dispatch harmless to the prose, but the markers are the controller’s to create.

## Checks that passed

- One next-phase prompt only: `workspace/volume-01/batch-0002/PROMPT.md` for Chapters 11–20, no `batch-0003`.
- The Still Hand loan closes on the trolley’s third wheel and cannot be reopened, extended, or retried.
- Elias remains at Stage 1: First Witness with persistent left-hand numbness and no summonable power.
- The terminal route and report contradiction is preserved as a discrepancy, not resolved.
- The Cinder Quarter refuge stays a physical and civic tool with recorded consent and withdrawal.
- Volume locks hold: no Mercy Array origin, no First Silence cause, no Returning Hand, Choir, or Compact reveal; Nell unresolved; Elias and Mara professional partners.
