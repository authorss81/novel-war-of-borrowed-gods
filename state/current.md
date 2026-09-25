# Current State

Current phase: phase-002-batch-plan

Next active batch: Volume 01, Batch 0002 (Chapters 11–20)

Current volume: 1

Current batch: 2 (next active; Batch 0001 complete)

Last completed chapter: 10

Last batch summary: `workspace/volume-01/batch-0001/SUMMARY.md`

Batch 0001 result: Chapters 1–10 are complete as finished prose. Groups A and B brought sixteen people to the first refuge; Group C brought the paper count to twenty-three. The Civic Spine’s empty-Car-3 report, the service-door route mismatch, Nadi’s missing digital family row, two deeper heat signatures, and the pre-collapse `MNT-4C-17` route-entry clue remain active.

Active threats: Kestrel’s unstable seam; the damaged and index-missing service-door aftermath; two deeper heat signatures; the damaged service route and unstable civic record; Sable’s premature equipment-failure classification; the unresolved second author code; the unidentified possible-Elias voice; and the possibility that the Office will seal the site or seize the original records.

Active promises: Elias’s first bounded Still Hand loan is complete; his left-hand numbness and fine-control loss remain. The present-day branch-crossed Nell signal remains partial and agency-bearing. Nadi’s family contact, shuttle number, and missing digital row are preserved. The `MNT-4C-17` code and Sable’s 05:24 timestamp must be compared before a re-entry decision.

Current relationship pressure: Elias and Mara remain professional partners, not romantic partners. Mara’s consent covers present treatment and repair; future Mara’s consent is separate. Elias has begun disclosure, delegation, and smaller promises, but his habit of carrying decisions alone is not solved. Their continued collaboration is based on changed conduct and a shared refusal to turn a future voice into a tool.

Current power state: Elias is at **Stage 1: First Witness**. The Still Hand ended automatically when the maintenance trolley’s third wheel stopped; no supernatural capacity remains. He can recognize a future echo’s warning or refusal near an active seam, but cannot reopen the loan, summon Still Hand, or treat a branch memory as a command. The Cinder Quarter prototype refuge is a physical/civic tool made from batteries, lamps, seam glass, analog maps, and barriers, not a shared-load circuit.

Phase handoff: Batch 0001 prose and manuscript state are complete, and `reviews/volume-01/batch-0001.md` records the batch audit. The next writer should begin with `workspace/volume-01/batch-0002/PROMPT.md`, which lists the beats already played in Chapters 1–10 so they are advanced rather than repeated. The same chapter cards now also exist in canonical card form at `outline/batches/volume-01-batch-0002.md`; keep the two in agreement.

Chapter length baseline: Batch 0001 measured 1,288–1,948 words per chapter, 16,014 words across ten chapters. That is a complete scene at the low end rather than a padded one, so the batch 0002 target was set deliberately to 1,700–2,400 words for an ordinary chapter, with longer only where a scene cannot honestly be cut shorter. This is a measured budget for the batch timeout, not a revision of Chapters 1–10. Do not re-expand finished prose to hit a number, and do not report a batch as short without counting words.

Re-dispatch guard: this prompt has already been satisfied. If the Batch 0001 writer prompt is dispatched again, do not write or rewrite Chapters 1–10. Both batch prompts carry completion banners that forbid rewriting finished chapters.

Controller-owned files were not edited by the writer or by the reviewer. `state/phase-ledger.json` still shows `phase-002-batch-plan` as `planned`, and the controller writes every `.done` marker; a writer never creates one. Read the marker situation accurately: `workspace/phase-000-bootstrap/.done`, `workspace/phase-001-outline/.done`, and `workspace/phase-002-batch-plan/.done` are present on disk, but `workspace/volume-01/batch-0001/.done` is still absent, because Batch 0001 was created inside the phase-002 run and the controller only stamps the phase directory it actually selected. The runner selects the first `workspace/**/PROMPT.md` whose directory lacks `.done` or `.blocked`, so it still selects `batch-0001` before `batch-0002`. The current dispatch has selected it, which means the controller will write its `.done` when this run completes and the next tick will reach Batch 0002. The residual risk is a future dispatch of `batch-0001` that produces no file changes at all: the runner would defer before it stamps the marker, and `.deferred` does not divert selection. If that ever happens, make one small, accurate state edit here rather than stopping with an empty diff, and do not touch chapter prose.
