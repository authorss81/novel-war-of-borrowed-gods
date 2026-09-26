# Volume 03 — Volume-Close Prompt

## Assignment

**Volume 03, *The Bellwether Choice*, is complete: Chapters 101–150 are written as finished prose and the volume ended on Saturday 17 January 2043, day 133.** This phase closes the volume. It writes no chapter prose and restarts nothing.

**Chapters 1–150 are canon. Do not restart, summarise in place, or rewrite any of them.** Do not edit controller files, workflows, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, or `state/phase-ledger.json`, and **do not create a marker file by hand.**

**Where this prompt restates canon, the source files own it.** `outline/volume-03.md`, `outline/ending.md` and `state/continuity.md` are canonical for the day map, the locks, the counters and the ending shape. `state/continuity.md`'s **BATCH 0004 AS WRITTEN** and **BATCH 0005 AS WRITTEN** sections record what the prose actually did, and **where a card or an outline line disagrees with an AS WRITTEN section, the AS WRITTEN section wins and the card is defective.** That has happened repeatedly in this repository and this prompt is not an exception to it.

## What this phase is for

Four things, in this order, and nothing else.

**1. Certify the volume's twenty-eight locks against the finished prose, and mean it.** `outline/volume-03.md`'s *What Volume 03 must not do* carries twenty-three items and its *Volume continuity locks* carries five more. Run the checks below and write what came back, with the file and the line, not with a summary of a summary. **A certification that is wrong is worse than a defect, because the next phase inherits the certificate and not the manuscript.**

**2. Reconcile the state files with the prose and with each other.** `state/current.md`, `state/chapter-summaries.md`, `state/continuity.md`, `state/character-state.md`, `state/open-threads.md` and `NOVEL_SPEC.md` were written by five different prose passes. **A figure that appears in a state file is a figure that was right on a day that has passed.** Every one of the batch totals, every per-chapter word count, every counter, and every lock claim is to be re-measured or re-read, not carried forward. If a state file is wrong, fix the state file and say which one and why.

**3. Write the volume's closing record** into `state/continuity.md` as a **Volume 03 closed** section, and one closing paragraph into `state/open-threads.md` numbered from 181, and the Volume 04 handoff. **The Volume 04 handoff carries the standing warnings forward and adds nothing new to the plot.**

**4. Create exactly one prompt: `workspace/volume-04/batch-0001/PROMPT.md`, for Chapters 151–160, *Anchors*.** That is the only next phase this one creates. **Do not create a `batch-0006` in Volume 03, and do not create a Volume 04 batch-0002 prompt, and do not create a Volume 04 volume-close prompt.**

## The checks, run and reported

**House style.** The authoritative pattern, run over **the whole of `chapters/`** and not over the files this phase edits:

```text
\b(colour|neighbour|organis[a-z]*|recognis[a-z]*|centre|licence|metre|metres|millimetre|millimetres|apologis[a-z]*|travell[a-z]*|rumour|labell[a-z]*|favour[a-z]*|artefact|behaviour[a-z]*|realis[a-z]*|analys[ei][a-z]*|defence|offence|programme|grey|judgement|kerb|storey|tyre|plough|manoeuvr[a-z]*|sceptic[a-z]*|moustache|enrolment|whilst|amongst|speciality|aluminium|armour|counsellor)\b
```

**Batch 0005 introduced one British form — `defence` in Chapter 141 — and the writing pass caught and fixed it in the same pass, and re-running the pattern over all of `chapters/` returned zero.** This is the eighth consecutive batch in which the writing pass has caught its own, and the ninth in which it has not. **Expect to find something. The pattern that cannot fail is not a check.** If a British form turns up, fix the prose and widen the pattern in the same pass, and record the form in this phase's record.

**Narrator references to the book**, and the bare singulars, over the whole of `chapters/`:

```text
\b(this|the) (chapter|chapters|batch|batches|volume|volumes|novel|novels|manuscript|manuscripts|story|stories|series|ending|endings)\b
\bpre-canon\b
\bStage [0-9]\b
\bcanon\b
```

Legitimate hits in Volume 03 are the records-request series in Chapter 128 and a bound paper volume in a list of printed columns. **Everything else in Chapters 101–150 must be zero, and if this phase finds one it must be fixed in the prose, not argued about in a state file.**

**Interface notices.** Exactly three in the whole of Volume 03, and no more: **113 accepted, 125 refused, 134 a boundary with three empty fields.** `grep` for `Loan offered` across `chapters/volume-03/` and confirm the count is three and the fields are as recorded. **There is no fourth and this phase may not invent one, describe one, forecast one, or put one in a quotation.**

**`Choir` and `faster`.** `Choir` appears **once in the whole manuscript**, in Chapter 148, in Ferrand's mouth, and nowhere else. `faster` appears nowhere in Volume 03. `Stage 2` appears nowhere in the narration.

**Word counts.** Re-measure Chapters 101–150 with `wc -w` and report the per-chapter figures and the five batch totals. **The sum of the per-chapter figures is the figure of record.** The `cat | wc -w` artifact — the last chapter of a batch with no trailing newline losing one token to the first chapter of the next — is pre-existing and is not to be "fixed" by editing a chapter's last line.

**Counters.** Cliff Marner is the chapter's day number less thirty; Della Marner and the man behind the wall are the chapter's own day number; and a day number is a chapter number less seventeen. Spot-check at least Chapters 101, 117, 125, 140 and 150 by deriving, not by reading a state file.

**The four readings.** Occasion 1, 11 September 2042, 06:40, issued 08:10. Occasion 2, 29 November 2042, 06:15, issued out of the cell 1 December 09:40. **Occasion 3 does not exist and there is a ruled line in the log that says so.** Occasion 4, 1 January 2043, street shut 06:20, reader on the alignment 07:15, off it 07:50, output on the trestle about 10:45, check box signed. Ref `BWP/TG/4SD/2042` on all three. **Chapter 138 is the only chapter in the volume in which all four dates are read out in one breath, by the engineer, in ninety seconds, to a man with a folder.** The second reading is the one taken on 29 November and **the word December may not be used for it.**

**The four non-drift figures.** Hall: twenty-two resident cards, twenty-eight people, four dark hours a night, and the headcount does not move anywhere in Volume 03. Custody schedule: twenty-two items, and nothing renumbered and no twenty-third or twenty-fourth. Works board's model: 1,140 addresses and 2,900 residents, adjusted twice. Retention Schedule: 697 rows, 412 `RETAINED`, 285 `TRANSITIONAL`, dated 2 December 1942, footnote `Current reading: 11 September 2042`, and **forty-four addresses inside the September band and outside the December one.** The December printed tally `IF ACTIONED — TRANSITIONAL 241 · RETAINED 456` is wrong and is not crossed out. The 41-against-39 arithmetic for 3 to 27 Sallow Court is unclosed and is not closed here.

**No door total.** A range of numbers is a street and a card is a door, and a flat has a door and does not have a number on the street. **The eight printed works' blocks come to fifty-one street-facing door numbers inclusive, not ninety-one, and the *ninety and something* of Chapter 121 is the works' own count of doors including flats.** **No chapter in Volume 03 prints a door total and this phase may not put one in a state file either.**

**Money.** Pounds only in Tidegate: two pounds seventy-five each way, eleven minutes each way, five-fifty a day round trip. **The Tidegate day-run is over — it ran from Saturday 29 November 1942 to Wednesday 24 December, stood at twenty-four riding days with two Sundays out of it, and the fares are £132, and no chapter restarts or grows it and no chapter prints a cumulative figure.** The one exception is Winifred Alagoa's school exercise book, **bought for two dollars, which is her own purchase in her own mouth, and it may not share a sentence with a pound.** The depot's slots are Tuesdays and Fridays 06:30, the Friday half is an inventory half and is on the notice and empty in his week, and the letter of 9 January 2043 moves the Friday hose certification to Thursdays, says the slots will not be held twice, and gives nothing else and takes nothing away.

## The locks, item by item, with the file and the line

For each of the twenty-eight, report **held**, or **not held**, with a file and a line. The ones most likely to have drifted, and the ones to check hardest:

- **The three questions on the Ash Street wall** are not taken down, added to or answered; the second half of the oldest is still a bracket with nothing under it; the nineteenth of November is still the only date; the wall is full; nobody builds another wall; and the four minutes and the lamp vote are in Petar Lisk's book on the page after 22 November and not on the board.
- **The answer to *who benefits* is not restated, improved, summarized, put in a room, or used as a weapon.** The volume's one permitted beat is **conduct and not speech** and it is Chapter 142: Alagoa refusing a verification card in her own doorway, to two people, on a reason about her street, with Joon Park absent and nobody in the chapter saying the word. **No other chapter in Volume 03 stages a refusal to hand over a document in a doorway, and no earlier chapter stages Alagoa refusing anybody in a doorway at all** — except Chapter 102, which shuts a door on him and then opens it four inches for the draught, and which is named here as the thing that is not a counterexample.
- **The central distinction, spoken once in Chapter 106, in Tomas Vale's own mouth, on Ash Street, with Joon Park writing it down, is not restated, paraphrased, improved, handed to anybody, or given a synonym in a second character's mouth.** A repair pass found it restated twice in Volume 03, both times in the borrowed form *none of the three is the same quantity*, and both were rewritten in place. **The word *quantity* does not appear anywhere in Chapters 101–150.** A chapter that needs a second pass at the mechanism cuts a character's arrival first and a document second, and never the panel and never the Chapter 106 sentence.
- **The Load Reader's five limits are stated in full once, in the Chapter 113 panel, and nowhere else.** The boundary is in that panel, once in Elias's mouth to Hobbs on 11 December, and once in the Chapter 134 panel. **No chapter recites the set. A use may show one limit failing and that is the whole permitted method.**
- **The sixth institutional pattern is spent once, in Hollis Vane's own words at Chapter 134, about his own trade, and there is no seventh.** No narrator, no Elias and no character states it, names an ordinal, or counts the patterns aloud.
- **`Before I say anything else` stands at five chapters — 108, 112, 114, 116, 120 — and appears zero times in Chapters 121–150.**
- **The 1998 working log stayed shut**, a name went on Petar Lisk's second list in his mother's hand from 2029, and no box was opened. **A later batch may open that box on the reason and may not open it because a man came home and looked interested.** Volume 03 is over, so the box stays shut and the question is Volume 08's.
- **Tomas Vale is not asked, not consulted, not offered, unknowing lender branch, not softened and not a villain**, and his eight pages are a method and not a confession and are not evidence and are in no proceeding. He does not appear in Chapters 131–150. **Ferrand's independently written method is connected to Tomas's pages by resemblance only, and no chapter connects them by anything else.**
- **Nell**: four fragments, no location, degraded; the Door Memory is closed and its return was performed; **the envelope is unsent and the reason is four words; no future Nell offer is scheduled and none may be invented; no branch travel.**
- **Halla Dren is not asked again.** The 2003 line, the Ninth Ward caretaker, the Sycamore vans and the sealed-site lip are unmentioned. **Sector 4C, nine, 2011, `K-7Q`, the 1998 page and the stamp format are released facts with no meaning and are not used as evidence.** **Tarin Voss is unfindable by name and that is not a problem to fix.** **Perpetua Oyelaran is a wound and not a clock and the volume describes the wall and does not re-narrate her name.** **The man behind the wall is unwritten at his own request, one hundred and thirty-three days in as of Chapter 150, and nobody goes to a lip and nobody calls the dead handset line.**
- **Released facts with no meaning are not evidence.** A 2038 pour with a hairline crack nobody is allowed to touch stands. A form in a drawer since August stands. The out-of-city copy and the fifth Bell copy are two objects and are never merged, and the box count is still unsettled — **count the garage, never the road.**
- **The hand goes flat on a table in this manuscript as a named motif and nowhere else**, and a new instance needs a reason.
- **Nothing romantic happens; no future version of Elias or of Mara promises them anything; nobody inherits anybody; the four-minute practice is a practice and not a courtesy.** The word *faster* is absent from the volume in any sense.
- **No new supernatural species, no new loan mechanic, and no system rule that Volumes 01 and 02 did not establish.**
- **The saved site is not entered, the loading lip is not a scene, and the handset is dead.**
- **Faster nowhere in any sense; Tidegate addresses out of the residents' file; no move to Ash Street; the hall on Ash Street is not a second headquarters; the cost of going to Tidegate is paid in travel, then sleep, then money, in that order.**

## The ending shape, confirmed against `outline/ending.md`

**Volume 03 is a mid-series volume and `outline/ending.md` is the whole series' ending, so nothing in it is spent here.** Confirm and record that Volume 03 has introduced none of it: **the Mercy Array, the Returning Hand, the One-Future Compact, Mercy Field, the First Choice, the permanent anchor and the Open Hand are not named anywhere in Chapters 101–150 and are not hinted at as a plan, and `Choir` is spoken once, by Ferrand, in a hall, at Chapter 148, and the movement's structure, membership, origin and history are not explained in this volume.** **Ferrand is the volume's antagonist and the series' first named political opponent, and he is a man with a program and not a voice, and about two hundred people in a hall believed him, and that is the volume's last state.**

Confirm the volume's concrete resolution against `outline/volume-03.md`: **the district survives on the reading and not on the list, and the people who evacuate it are Tidegate people, and Elias Rook is a pair of hands in a corridor.** The Retention Schedule is withdrawn and replaced by a second schedule four times longer, assembled in eleven days by about two hundred people writing their own address on it by hand, with a column headed for a name and a line that reads `cannot be reached at this address — see sheet`. **The securing band is not withdrawn, the pilot authorization is not withdrawn, and the reading keeps running.** **Three branch survivors are given names in a system and addresses on a sheet and are not asked what they want.** **The program keeps its field record: the pilot has never lost anybody in the field, that is true, and it stays true, and it is going to be in every document about this for forty years.**

## State files to write

- `state/continuity.md` — a **Volume 03 closed** section after the BATCH 0005 AS WRITTEN section: the measured result, the lock audit, the divergences from the cards recorded rather than papered over, the corrections this phase applied, and the measured state of every figure in the volume.
- `state/open-threads.md` — one closing paragraph numbered from **181**, carrying the standing warnings into Volume 04 with nothing added to the plot.
- `state/current.md` — the head paragraph, the next active phase, the length paragraph, the house-style paragraph and the phase handoff, all pointing at the Volume 04 Batch 0001 prompt.
- `state/character-state.md` — leave *After Chapter 150* alone; it is the volume's last character record. **If a character's state in it is contradicted by the prose, fix that paragraph and say so.**
- `state/chapter-summaries.md` — leave Chapters 101–150 alone and verify that each of the fifty has a summary and that the summaries agree with the prose on the days and the counters.
- `NOVEL_SPEC.md` — Status, and the volume count.

## The one prompt to create

**`workspace/volume-04/batch-0001/PROMPT.md`, for Chapters 151–160, *Anchors*, days 134–143, Monday 18 January to Wednesday 27 January 1943.** Day zero is Saturday 6 September 1942, so **day 134 is Monday 18 January 1943** and day 143 is Wednesday the twenty-seventh. That prompt must be written from `outline/series.md`, `outline/volume-04.md` if it exists, `NOVEL_SPEC.md`, `state/current.md`, `state/continuity.md`, `state/open-threads.md` and `state/character-state.md` *After Chapter 150*, and it must say, in terms:

- **The volume's last chapter, Chapter 150, is the state the batch travels from,** and its closing image — a depot, a nail, an exercise book, four dark hours, a wall with three questions and no room — is the state, not a summary of the state.
- **What Volume 04 inherits and must not resolve, rescale or explain:** the band moved and the schedule has been withdrawn and nobody caused it; the two times, 06:10 and 07:15, on the inside back cover of a notebook with nothing written between them, unremarked by every character and every narrator in Volume 03; the eleven on Rennard Street and the day book that has the failure in it; the four dead at Sallow Court, two on a nail and two in a margin; the three branch survivors entered in a book and asked nothing; **the two named dates, the second of January and the sixteenth, both Fridays, both said in rooms and never to be said sooner unless somebody asks in a room**; the booking closing on Thursday 5 February; **the night of Monday 19 January, day 135, which is Volume 04's first night and which no Volume 03 chapter staged, booked, referred to as a night to come, or put on anything**; and **about two hundred people in a church hall who believed a man who is not wrong, which is the volume's last condition and Volume 04's first problem.**
- **The house-style pattern, the narrator-reference scan, and the fact that the writer of the prose is the writer of the check.**
- **The counters derive from the chapter's own day number and are never copied forward.**

**Do not create anything else.** No `batch-0006` in Volume 03, no Volume 04 `batch-0002` prompt, no Volume 04 volume-close prompt, no second next phase, and **no marker file by hand.**

## What must not happen in this phase

No chapter prose is written, restarted, summarised in place or rewritten. No scene is replaced. No day in Volume 03 moves. No figure is invented to make a state file agree. **No planned ending is changed, and no new final enemy is introduced** — the final external conflict is fixed in `outline/ending.md` and is Volume 19's, and the full origin is established in the Mercy Line records, Tomas Vale's testimony, Anika Rao's investigation, Sable Arden's policy history and the Returning Hand's own documents, which are not Volume 03's and not Volume 04's.
