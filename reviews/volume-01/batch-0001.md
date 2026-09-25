# Batch 0001 Audit — The Ninety Seconds

Scope: Volume 01, Chapters 1–10, the rolling state files, and the Batch 0002 prompt. Reviewed against `outline/volume-01.md`, `outline/ending.md`, the bible, and the batch cards. This file records two passes. The first list below is the initial pass; the second-pass list records a later read that found four prose defects and three process defects. In both passes, completed prose was repaired, not rewritten, and the planned plot was not changed.

## Applied fixes

1. **Record contradiction narrowed (Chapter 9).** The closing line claimed the terminal said none of the twenty-three had been there, which overstated the discrepancy. Seven members of Group C were never in Car 3. The line now separates the fifteen who rode in Car 3 from the seven who were behind the wall, so the contradiction stays exactly as wide as the evidence Batch 0002 has to resolve.
2. **Crossing order corrected (Chapter 3).** Tarin was wheeled through first, but the tally read as though he crossed last. The count now ends at fifteen with Tarin’s name read first, matching Chapter 4’s procession.
3. **"Still Hand" introduced (Chapter 2).** The Chapter 7 usage had no prior appearance in prose. The offer panel now carries a `Gift name` field and Elias reads it aloud, so the term is grounded at the loan.
4. **Injury description corrected (`state/chapter-summaries.md`).** Only Tarin was pinned by the steel handrail; the other fourteen were inside the buckled carriage.
5. **Unsent note described accurately (`state/open-threads.md`, `state/character-state.md`, `state/continuity.md`, chapter summaries).** Elias tore out his reply to Nell and did not send it. The state now says so, so the next batch cannot assume Nell received or answered it.
6. **Batch 0002 prompt reconciled with played beats.** The Chapter 16 card no longer re-runs the Chapter 9 handover and discovery; it now starts from the established contact, shuttle number, and missing digital row, and advances to a relative’s confirmation and a broker refusal. The Chapter 13 card no longer re-discovers `MNT-4C-17`, and the Chapter 18 card forbids re-staging future Mara’s Chapter 9 refusal.
7. **Phase prompts guarded against a duplicate run.** `workspace/phase-002-batch-plan/PROMPT.md` and `workspace/volume-01/batch-0001/PROMPT.md` carry completion status banners, and the phase prompt no longer orders a writer to update `state/phase-ledger.json`.
8. **Status header refreshed (`NOVEL_SPEC.md`).** The spec no longer claims that no prose exists.

## Second-pass review and applied fixes

A second read of Chapters 1–10 and the handoff found four prose defects and three process defects. The chapter repairs were surgical: no scene, beat, or planned plot was rewritten.

1. **Injury contradicted inside one scene (Chapter 4).** A medic said the left grip was gone, offered to test the other hand, and then put the pen in Elias’s *right* hand; he dropped it, and she called that hand fine. The beat read as a right-hand deficit and contradicted `state/character-state.md`, `state/continuity.md`, and Chapters 7, 9, and 10, which all localize the cost to the left hand. The medic now tests the right hand, finds it sound, then sets the pen in the left and lets go of his wrist. Both of her original judgements survive — fine enough to climb stairs, not fine enough to pretend — and the left-hand loss is now demonstrated rather than stated.
2. **Ambiguous exchange in the record-precision scene (Chapter 4).** “Write with your left hand” / “I do” could not be read as a sincere offer, and Elias’s reply did not establish that he writes with his right, which is what he does everywhere else in the chapter. The line is now “Say when it goes” / “I already did,” which also pays off the medic’s new instruction that he report when the hand fails and hand the job to someone else.
3. **Dangling introduction (Chapter 1).** A second woman in “a rescue technician’s orange strip” was placed behind the carriage glass, never named, never placed in any group, and never appearing again. If she was a trapped rescuer she is a continuity hole; if she was set dressing she should not be a character. The identified role is gone, and the beat is kept as an unidentified figure with both palms on the glass that does not react when Elias calls, which also sets up the knock at the end of the chapter. The rescue count is untouched.
4. **Premature count (Chapter 9).** “The seven people from the alcove” appeared before Ansel and his two companions had crossed; only five were out. The line now reads “two of the seven were still out of sight,” which is exact at that moment and does not pre-spend the count that lands later in the chapter.
5. **Chapter length was never audited.** The batch total was 16,014 words across ten chapters (1,288–1,948 each), and the first pass listed seven checks without counting words. Chapters 1–10 are complete scenes rather than padded ones, so they were not re-expanded. The measured baseline is now recorded in `state/current.md`, and the Batch 0002 target was set deliberately to 1,700–2,400 words for an ordinary chapter, with longer allowed only where a scene cannot honestly be cut shorter. That is a budget the batch timeout can actually absorb. The audit list below now includes the length check so the omission does not repeat.
6. **The re-dispatch risk was described backwards.** The state file said phase selection “should no longer land on the completed batch” in the same paragraph that correctly recorded the missing marker. It still selects `batch-0001`, because the controller only stamps the phase directory it selected, and Batch 0001 was created inside the phase-002 run. The current dispatch has selected it, so the controller will stamp its `.done` at completion; the remaining hazard is a future selection of `batch-0001` that produces no diff, because the runner would defer before stamping and `.deferred` does not divert selection. `state/current.md` now says this plainly and instructs a re-dispatched writer to make one small accurate state edit rather than stopping with an empty diff.
7. **Card file missing (`outline/batches/volume-01-batch-0002.md`).** Batch 0002’s cards existed only inside the workspace prompt, so `outline/batches/` was not accumulating as the documented layout expects. The cards are now also in canonical card form, derived from the prompt without changing a single beat, and the two files are bound to each other by a note in the prompt.

### Checks that passed

- All ten chapter files exist and are finished prose, each with a changed situation and a completed beat.
- Zero exact duplicate paragraphs and zero cross-chapter repeated sentences across the batch.
- Three interface panels total, one per chapter, all using the approved terminology headings.
- One next-phase prompt only: `workspace/volume-01/batch-0002/PROMPT.md` for Chapters 11–20, no `batch-0003`.
- The Still Hand loan closes on the trolley’s third wheel and cannot be reopened, extended, or retried.
- Elias remains at Stage 1: First Witness with persistent left-hand numbness and no summonable power.
- The terminal route and report contradiction is preserved as a discrepancy, not resolved.
- The Cinder Quarter refuge stays a physical and civic tool with recorded consent and withdrawal.
- Volume locks hold: no Mercy Array origin, no First Silence cause, no Returning Hand, Choir, or Compact reveal; Nell unresolved; Elias and Mara professional partners.

## Controller-owned items left for the operator

- `state/phase-ledger.json` still lists `phase-002-batch-plan` as `planned` with zero attempts. Only the controller may mark a phase done.
- `workspace/volume-01/batch-0001/.done` is still absent, and phase selection takes the first `workspace/*/PROMPT.md` directory without one, so it selects the finished batch before Batch 0002. The controller stamps the marker for the phase it ran, and it has run this one, so the marker should appear when the current dispatch completes. If `batch-0001` is ever selected again, the run must produce a file change or the runner will defer before stamping; see the re-dispatch instruction in `state/current.md`. Only the controller writes `.done` and `.blocked`.
