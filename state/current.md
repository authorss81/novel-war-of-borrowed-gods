# Current State

Current phase: Volume 01, Batch 0002 complete and audited; Batch 0003 prose phase is next

Next active batch: Volume 01, Batch 0003 (Chapters 21–30)

Current volume: 1

Current batch: 3 (next; Batch 0002 complete)

Last completed chapter: 20

Last batch summary: `workspace/volume-01/batch-0002/SUMMARY.md`

Batch 0002 result: Chapters 11–20 are complete as finished prose and have been through a review and correction pass. Four days in the Cinder Quarter turned the Kestrel question from *is a re-entry safe?* into *who decides which honest record becomes the official one?* The team did not re-enter the tunnel. It produced a three-column page separating unsafe, shifted, and physically absent; read the `MNT-4C-17` relay card once; took a graphite impression of a mechanical fault tape that rang at 05:17:11 and 05:24:40; proved the 05:24 classification was prepared inside the sector; learned that the credential holder’s name was discarded in the 2035 renumbering; confirmed Nadi Bell’s family and shuttle from a relative’s memory; took a local vote that split authority across five names and gave Elias no sole command; watched a neighbor refuse Halla Dren’s request on the record; and stopped a survey on a pre-written number, with Elias the one who called it. The correction pass fixed two year-and-day arithmetic errors, one unmarked clock jump, and the mixed house spelling; it added no plot and removed no scene.

Active threats: the altered service door, unsafe and of unproven physical status; one confirmed living person behind the wall and one unconfirmed thermal reading; a 2031 repair pour and a buried paired node under the west apron; a void 210 metres from the clinic; a provisional classification and a day-four review board; Sable’s 2019 and 2029 casualty arguments, which are real; the possibility that the Office’s sealed data node becomes the only version of the survey; and Perry Dunne’s unmoved Friday.

Active promises: the first Still Hand loan is complete and unavailable; Elias is at Stage 1 with persistent left-hand numbness and no summonable power; the five-name stop plan and the five-signature promise are on the hall wall; Ansel Duarte’s success condition is a conversation and not an extraction; Mara’s condition is no medic on the line; the shaft Halla Dren asked them not to name is not named, and the request and the refusal are printed in order; Nell’s signal is still incomplete, her carrier matches the 05:17 route entry, and Elias’s reply is still unsent and now lives in his notebook. The service door’s three states and the lower service corridor’s separate existence are both on file: the door is unproven as to absence, and the corridor is the element Chapter 25 must find gone.

Current relationship pressure: Elias and Mara remain professional partners in a slow trust built on conduct. She dictated the full loan record into a document the Office has countersigned; he asked a reporter on the record that he does not know which account becomes official, in front of four other people who had already spoken for their own domains; and he accepted both her refusal to put a medic on the line and a nineteen-year-old survivor’s redefinition of the mission. Nothing romantic has occurred and no future version has promised either of them anything.

Current power state: **Stage 1: First Witness.** No loan has been accepted anywhere in Volume 01 since the Still Hand returned at the third wheel. Halla Dren answered with `No loan offered` and gave no gift; her request was refused and recorded, and she was not asked twice. The Cinder Quarter refuge is batteries, lamps, seam glass in a wooden frame, analog maps, and mechanical barriers on a feeder the residents can cut, under consent cards that can be withdrawn with no reason. It is not a shared-load circuit and not a new stage.

Phase handoff: Batch 0002 prose and manuscript state are complete. `workspace/volume-01/batch-0003/PROMPT.md` is the only next-phase prompt and holds Chapters 21–30; its cards live in canonical form at `outline/batches/volume-01-batch-0003.md`, and the two must be changed together. There is no `batch-0004`.

Marker situation, stated accurately: `workspace/volume-01/batch-0002/.done` does **not** exist on disk, because a writer never writes a marker and the controller only stamps the directory it actually selected. `scripts/novel_runner.sh` picks the first `PROMPT.md` under `workspace` in sorted order whose directory has neither `.done` nor `.blocked`, so **batch-0002 still sorts ahead of batch-0003** and is the correct next dispatch. The runner does `touch "$phase_dir/.done"` when a run finishes, so the next tick after that reaches batch-0003. Both batch-0001 and batch-0002 prompts now carry a re-dispatch banner that forbids rewriting finished chapters, and the batch-0002 audit is at `reviews/volume-01/batch-0002.md`. If a completed batch prompt is dispatched again anyway, make one small accurate state edit and do not touch chapter prose.

Controller-owned files were not edited by the writer or by the review. `state/phase-ledger.json` is owned by the controller, and only the controller writes `.done`, `.blocked`, and `.deferred` markers. Do not create one by hand.

Chapter length: Batch 0002 finished at 28,159 words across ten chapters (2,358–3,524 each) after a review pass removed roughly 2,000 words of restatement and a correction pass settled the prose's spelling on US forms. The 1,700–2,400 target was exceeded in nine of the ten chapters; Chapter 13, at 2,358, is inside it. The overage is concentrated in three-hander scenes (Chapters 16, 18, 19) that cannot honestly be cut to 2,400, and Chapters 13, 12, and 15 sit closest to the target. Batch 0003 should aim at 1,800–2,400 so a ten-chapter batch lands nearer 20,000–24,000 words, while still allowing one long chapter where a complete scene cannot honestly be cut shorter.

Day map: the collapse and Chapters 1–10 are a Saturday; Sunday is Chapters 11–13 and the 1600 transfer that opens 14; Monday is the rest of 14 and the 7 p.m. vote in 15; Tuesday is 16; Tuesday night is 17; Wednesday is 18–19 with the ninety-six-hour hold accepted on Wednesday afternoon; and Thursday is 20. The review board sits on the hold's fourth day, the following Saturday, and Perry Dunne's Friday — asked for in Chapter 15 — falls inside the hold, on its third day. Prefer day-relative language and consult `state/continuity.md` before naming a weekday.

House style: US spelling, matching the bible and the outlines — *neighborhood*, *neighbor*, *organize*, *recognize*, *center*, *color*. The Batch 0002 prose was normalized onto this in the review pass, and the batch-0003 prompt and cards are written to it. Do not reintroduce mixed forms.

Controller-owned files were not edited by the writer or by the review.
