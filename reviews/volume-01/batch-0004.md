# Batch 0004 Audit — Borrowed Roads

Scope: Volume 01, Chapters 31–40, the rolling state files, the Batch 0004 summary, and the Batch 0005 prompt and card. Reviewed against `outline/volume-01.md`, `outline/ending.md`, the bible, and the day map, and answered against the findings in `logs/batch-0004.review.log` (commit `2246caf`). Prose was repaired, not rewritten; no scene was removed, no beat was cut, and the planned plot was not changed.

## What passed

- All ten chapter files exist and are finished prose. Every chapter changes a practical or emotional situation and ends on a decision, discovery, cost, or question. Nothing is an outline or a chapter log.
- Word counts in the summary and `state/current.md` matched `wc -w` exactly, and US spelling is clean manuscript-wide.
- Panel discipline holds: the only two interface blocks in the batch are Chapter 34 and Chapter 39, one per chapter, on approved headings.
- No loan is accepted anywhere in the batch. The Door Memory is refused **as a route and as a loan**, Joon's distinction that the return is *performed* and not *invoked* is on the page, and Niko Senn's Chapter 21 precedent holds from a bus.
- The two counting bases are kept separate and never conflated, and Chapter 32 puts both on the board.
- The possible-Elias voice stays unidentified and wordless, the audio file and the voice stay distinct, and `K-7Q` remains a fact with no meaning attached.
- The crew is still thin (Doss is one ticket and no pair), Tomas is still the only structural person, and no faction, rule, or final enemy was introduced.
- One next-phase prompt only: `workspace/volume-01/batch-0005/PROMPT.md` for Chapters 41–50. There is no `batch-0006` and no premature volume-close prompt.

## Applied fixes — finished prose

1. **Orphan fragment paragraph (Chapter 33).** A single line — `that the room had been waiting for and not waiting for.` — sat alone between blank lines, mid-sentence, after a paragraph that already ended in a full stop. It was a leftover from a trim and was the only stray lowercase paragraph start in the ten chapters. The paragraph above it, *the hall did not behave like a room that had been told a no*, now carries the beat on its own. A triple blank line left by the same trim earlier in the chapter was reduced to one.
2. **The paper count moved four days early (Chapter 33).** Nadi Bell said the count was already twenty-two on Chapter 33's Tuesday, which contradicted Chapter 37 — where twenty-three is the number *since the second day* and the line moves at eleven o'clock on Saturday — and stole the beat the batch card explicitly required, the paper count moving for the first time since the collapse. Every state file records the Chapter 37 version, so the prose was the outlier. Her line is now forward-looking: **twenty-two the first time somebody walks out of that door.** Her argument is untouched and still costs Sable the exchange, and Chapter 37 keeps the beat whole.
3. **Wrong elapsed-time counter, twice in one line (Chapter 40).** Mara dated the unconfirmed nine-meter reading to *the second week* and the last thermal survey to *eight days old*. The reading comes from the Chapter 18 survey on **Wednesday, day four**; Chapter 40 is Monday, **day twenty-three**. The reading is now **unconfirmed since the fourth day**, no thermal camera has been run down there since, and a person alive at nine meters today **has had nineteen days of this**. The Friday entry was structural, to sixty centimeters at the apron, and is not a survey of this reading.
4. **A month that has not happened (Chapter 35).** Elias learned his lesson about other people's decisions *in a corridor in April*. Chapter 5 establishes the collapse in May and the whole volume runs inside that month. The line now reads **a corridor in May**.
5. **Elapsed hours that fit neither reading (Chapter 39).** The chapter opened *the twelve hours between them*, for a chapter running from a 16:00 carry to a 22:14 notice. It is **six hours**.
6. **The refusal contradicted its own record (Chapter 40).** The written refusal logged the offer as received at `23:14 SUNDAY` while Chapter 39 puts the notice at fourteen minutes past ten, and every state file — continuity, character state, chapter summaries, the Batch 0004 summary, the Batch 0005 prompt and card — records **22:14**. The refusal now reads `22:14`, and it is internally consistent with Joon's 22:40 and 23:00 sessions and the channel closing at eleven.
7. **A clock time Chapter 39 does not support (Chapter 40).** The envelope paragraph said the cost of the message *had been said out loud once, at eleven the night before*. In Chapter 39 that conversation sits between the 22:14 notice and the 22:40 session, and eleven o'clock is when the channel closed. The sentence now says *the night before*, keeping the evidence and dropping the invented timestamp.
8. **Forty people in a hall of twenty-two (Chapter 40).** Defensible only if non-residents are in the room, and this manuscript polices that distinction deliberately. The line now reads **a hall with forty people in it and twenty-two of them living here**, which is accurate — Teodor, Bess Ferran, and Gil Trejo all arrived inside the batch — and it states the difference instead of blurring it.

## Applied fixes — state files

9. **Thread 4 of `state/open-threads.md` restated a survey that never happened.** It dated the nine-meter reading to *eight days before Chapter 36*, which is day twelve, and no thermal survey ran then. The thread now names the **Chapter 18 survey on Wednesday, day four** and says the reading is **nineteen days old as of Chapter 40**.
10. **Thread 19 heading carried a number that is not in the book** — *the hundred-and-ninety-day problem*. It now reads **The ninety-day clock and the stamp in the ground**, which is what the thread is about.
11. **Niko Senn's departure day was wrong in three files.** `state/continuity.md`, `state/character-state.md`, and the Batch 0005 prompt all placed it on *Chapter 37's Sunday*. Chapter 37 is **Saturday**: he says it out loud at four that afternoon, the record is updated at ten past five, and he travels on the **Sunday** after it — day twenty-two, the same Sunday as Chapter 39. All three files now separate the Saturday decision from the Sunday journey, and the continuity entry states the invariant so a later chapter cannot move the count again.
12. **`state/current.md` claimed a verification that had not happened.** It said *every elapsed-time phrase in Chapters 31–40 has now been checked against the day map*; the review found three that had not been. The sentence is replaced by the record of what is now true — the count is twenty-three through Chapter 36 and moves on Chapter 37's Saturday, the nine-meter reading is unconfirmed since day four, the notice and the refusal both read 22:14 — plus a separate entry for the mechanical repairs. The earlier writer corrections in that paragraph are unchanged and still accurate.
13. **Word-count figures across four files were invalidated by this pass.** The trims and repairs net the batch to **25,271 words** (Chapter 33 to 2,870, Chapter 40 to 1,987). `state/current.md`, the Batch 0004 summary, the Batch 0005 prompt, and the Batch 0005 card all now carry the measured figures, and the card and the prompt are back in step as their own header requires.

## Applied fixes — next-phase handoff

14. **The Batch 0005 prompt pointed the next writer at a file that does not exist.** It listed `outline/batches/volume-01-batch-0004.md`; that card was never written, because the batch-0003 writer did not produce it. The read list now names `outline/batches/volume-01-batch-0005.md`, the Batch 0004 prompt, and the Batch 0004 summary, and says in the same sentence that the missing card does not exist and that the finished chapters are the record for that batch. `state/current.md` carries the same note and tells a later phase not to reconstruct a card for a finished batch.
15. **The Batch 0005 prompt named the wrong departure day** — see item 11 — and its Batch 0004 length claim, now corrected, was the only remaining divergence from the canonical card.

## Controller-owned items left for the operator

- `state/phase-ledger.json` was not edited, and no `.done` or `.blocked` marker was created by hand.
- `workspace/volume-01/batch-0003/.done` and `workspace/volume-01/batch-0004/.done` are both still absent, because a writer never writes a marker. `scripts/novel_runner.sh` selects the first sorted `workspace` prompt directory without one, so it will re-dispatch Batch 0003 or Batch 0004 rather than Batch 0005 until the completed directories are stamped. This is controller or operator action and is flagged in `state/current.md`. If a completed batch is dispatched anyway, the instruction there stands: make one small accurate state edit and do not touch chapter prose.

## Files changed in this pass

`chapters/volume-01/chapter-0033.md`, `chapter-0035.md`, `chapter-0039.md`, `chapter-0040.md`; `state/current.md`, `state/continuity.md`, `state/character-state.md`, `state/open-threads.md`; `workspace/volume-01/batch-0004/SUMMARY.md`; `workspace/volume-01/batch-0005/PROMPT.md`; `outline/batches/volume-01-batch-0005.md`. No outline, bible, ending, series, or volume file was edited, and the planned ending is unchanged.
