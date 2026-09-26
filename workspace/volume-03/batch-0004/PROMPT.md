# Volume 03 — Batch 0004 Writing Prompt

## Assignment

Write **Chapters 131–140** of *The War of Borrowed Gods* as complete finished scenes in chapter order. This is the fourth prose batch of Volume 03, *Four Nights*. Read, in this order, `AGENTS.md`, `NOVEL_SPEC.md`, `outline/series.md`, `outline/ending.md`, `outline/volume-03.md` in full, this prompt, `state/current.md`, `state/continuity.md`'s sections headed *Volume 03 continuity — BATCH 0003 AS WRITTEN* and *BATCH 0002 AS WRITTEN* (prose fact outranks cards), `state/open-threads.md` items 136 onward, `state/character-state.md` *After Chapter 130*, and Chapters 130, 128 and 125 before drafting. Chapter 130 is the state the batch travels from. Chapter 125 is the midpoint and its panel and its refusal are fixed. Chapter 128 holds the regional letter and the two dates.

**Chapters 1–130 are canon. Do not restart, summarise or rewrite them.** Do not edit controller files, workflows, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, or `state/phase-ledger.json`, and do not create a marker file by hand.

**Where this prompt restates canon, source files own it.** `outline/volume-03.md`, `outline/ending.md` and `state/continuity.md` are canonical for day map, locks, counters, ending shape.

## House style

US spelling throughout — *neighborhood, neighbor, organize, recognize, center, color, license, meter, apologizing, traveling, rumor, labeled, favor, artifact, labor, defense, program*. Run this pattern over whole of `chapters/`, not files edited, before claiming clean:

```text
\b(colour|neighbour|organis[a-z]*|recognis[a-z]*|centre|licence|metre|metres|millimetre|millimetres|apologis[a-z]*|travell[a-z]*|rumour|labell[a-z]*|favour[a-z]*|artefact|behaviour[a-z]*|realis[a-z]*|analys[ei][a-z]*|defence|offence|programme|grey|judgement|kerb|storey|tyre|plough|manoeuvr[a-z]*|sceptic[a-z]*|moustache|enrolment|whilst|amongst|speciality|aluminium|armour|counsellor)\b
```

If new British form turns up, add form to pattern same pass. **Run it over the whole of `chapters/`, not the files you edited, and if the result is anything other than zero, the pass that wrote the prose is the pass that fixes it.** This repository has now caught a British form in the pass that wrote it in seven consecutive batches; expect to catch one again and fix it in the same pass.

**Wider narrator-reference scan, and it must include the BARE SINGULARS:**

```text
\b(this|the) (chapter|chapters|batch|batches|volume|volumes|novel|novels|manuscript|manuscripts|story|stories|series|ending|endings)\b
\bpre-canon\b
\bStage [0-9]\b
\bcanon\b
```

Legitimate hits are device/gift uses (vehicle reader, Load Reader), the records-request series, and a bound paper volume on a shelf. **Volume 03 prose must return zero otherwise. An outline label like `Stage 2` is never allowed in the narration — say the cost in the character's own words.** The power state is called **Named Thread** in the outline and is named in the narration only as a proximity, a connection and a cost.

## Calendar — derive every date from day zero Saturday 6 September 2042; day equals chapter less seventeen

| Chapter | Weekday | Day | Date |
| --- | --- | --- | --- |
| 131 | Monday | 114 | 29 Dec |
| 132 | Tuesday | 115 | 30 Dec |
| 133 | Wednesday | 116 | 31 Dec |
| 134 | Thursday | 117 | 1 Jan **THIRD AND LAST INTERFACE NOTICE** |
| 135 | Friday | 118 | 2 Jan **records request near end** |
| 136 | Saturday | 119 | 3 Jan **first January night** |
| 137 | Sunday | 120 | 4 Jan |
| 138 | Monday | 121 | 5 Jan |
| 139 | Tuesday | 122 | 6 Jan **second January night** |
| 140 | Wednesday | 123 | 7 Jan |

**Midpoint was Chapter 125 day 108 and is not this batch. Day 100 was Chapter 117.** **January 1–7 2043 is Thu, Fri, Sat, Sun, Mon, Tue, Wed — verified from day zero, not from a table.** **New Year's Day is not treated as a public holiday in this manuscript's ordinary civic week beyond the fact that the yard runs six days and shuts Sundays: the yard is open Monday 29, Tuesday 30 and Wednesday 31 December, and on Thursday 1 January, and shut Saturday 2, Sunday 3, open Monday 4, Tuesday 5, Wednesday 6.** **No chapter may invent a holiday arrangement to get round any closure, and the closure is shown on a printed notice and not announced.**

**The Tidegate day-run is over.** It ran from Saturday 29 November 2042 to Wednesday 24 December and stood at **twenty-four riding days with two Sundays out of it** — Sundays 14 and 21 December — and he did not ride on Christmas Day, Boxing Day or after. **Any figure for how long he had been going is twenty-four days and the fares are £132, and no chapter may restart the run or grow it.** **Fares are pounds and only pounds: two pounds seventy-five each way, eleven minutes each way, five-fifty a day round trip, and the Tuesday 06:30 depot slot costs an hour of sleep a week for the rest of his life.** **No chapter may put pounds and dollars in one breath.**

## Counters — always chapter day less start, never copied

Cliff Marner day 30: **84, 85, 86, 87, 88, 89, 90, 91, 92, 93.** Della and the man behind the wall day 0: **114, 115, 116, 117, 118, 119, 120, 121, 122, 123.** Prefer naming day over printing numeral. Four non-drift figures: hall twenty-two cards twenty-eight people four dark hours; custody twenty-two items; works model 1,140 and 2,900; schedule 697 with 412 RETAINED 285 TRANSITIONAL forty-four inside September outside November dated 2 December footnote Current reading 11 September 2042.

## Working week

Board and Bellwether counter shut Saturdays Sundays. Yard six days, shut Sundays. **Depot Tuesdays and Fridays 06:30; the Tuesday half is his and is used in this batch at Chapter 132; the Friday half is an inventory half, it is on the depot's notice, and it is empty in his week.** No hearing, counter transaction, determination, method officer or board surveyor on a shut day. The yard's closure card still reads `YARD CLOSED 25, 26, 27, 28 DEC · REOPENS 29 DEC` and the cell's door slip still reads `CLOSED 25, 26, 27, 28 DEC · REOPENS MON 29 DEC 09:00`.

**The works' sequence, exactly as printed in Chapter 121, and it is load-bearing and no block may be cleared twice:**

| NIGHT | BLOCK | CREW |
| --- | --- | --- |
| 6 JAN | 14–22 MARLOW ST | 4 |
| 10 JAN | 2–12 RENNARD · 16–18 MURROW | 5 |
| 17 JAN | 14–22 CUTBANK ROW · 31 CUTBANK ROW | 4 |
| 19 JAN | 15–21 RENNARD · 2–12 CUTBANK ROW | 4 |

**The booking is twenty working days, Monday 5 January 2043 to Thursday 5 February 2043, and Nerys Hobbs signs a sheet for every night, and after the fifth of February the board has to come back for money and in her experience does not come back in the same year it has already spent it.** She gave all of this on 24 December, in a room, because she would not have time in January.

**Verification log: near end Friday 2 January 2043 is Chapter 135 and the log either arrives or it does not; far end Friday 16 January 2043 is Chapter 149 and this batch does not reach it. Nobody chases it and nobody in a room asks Joon Park whether it has come.**

## Batch job — 131–140 *Four Nights* per escalation table

The thread repeats its boundary, the band moves, the schedule does not, and the volume's own documentary clock reaches its near end. **Turn: Hollis Vane's professional observation at Chapter 134 is the hinge and the sixth and last institutional pattern — a schedule that records a state has no version history, because no field on it is for when it changed. It is in his own words, once, and nobody else states it and nobody counts an ordinal aloud.**

Non-negotiables:

- **Interface notices exactly three in Volume 03 at 113, 125, 134. This batch spends the last one at 134 and no others. At most one per chapter. 134 is a boundary only: Elias asks the thread to repeat its boundary and the panel returns the boundary and nothing else, and the asking moves the securing band two streets and forty-four addresses change class and the schedule does not change because a schedule records a state. Nobody caused it and no chapter may say who did, may restate it, may extend it, may scale it, and nobody in a room may call it a cause.**
- **Chapter 134's event is larger than Chapter 119's and is not Chapter 119.** Chapter 119 (Wednesday 17 December) was **half a street of softened edge on one morning with no reading taken, no vehicle, no foreman, no drawing and no cause at all**, and it is deliberately smaller and blander. **134 has an innocent action behind it: the asking.** The difference between the two is the whole of 134. **No chapter in this batch mentions, restates, explains or escalates the 17 December softening.**
- **The central distinction spoken once in Chapter 106 is never restated, paraphrased, improved or handed to anybody.** Cut a character's arrival first and a document second, and never the Chapter 106 sentence and never the panel.
- **The Load Reader's five limits are stated in full in Chapter 113 and nowhere else in the volume.** The boundary is in the Chapter 113 panel, once in Elias's mouth to Hobbs, and **once more in Chapter 134 and nowhere else.** A use may show one limit failing and that is the whole permitted method. **No chapter in this batch recites the set.**
- **Sixth pattern at 134, in Hollis Vane's own words, once.** The schedule's missing person-column is the third of five patterns and is **not new and may not be presented as new**. No ordinal counting aloud by any character.
- **`Before I say anything else` may appear at most once in this batch unless a character names it.** It stands in Volume 03 at Chapters 108, 112, 114, 116 and 120 and appears **zero** times in 121–130; the two references in that batch are men naming it as *step four*.
- **Who-benefits is not restated, improved, summarized, put in a room or used as a weapon.** The volume's one permitted carrying-beat is **Chapter 142 and it is not this batch**: Winifred Alagoa refuses her 2031 sheet to a program officer for "verification," in a doorway, to two people, on a reason about her street, with Joon Park absent and the word unsaid. **No batch chapter stages that, and no earlier chapter in Volume 03 stages it either.**
- **The 1998 working log stayed shut.** It came off the top shelf on Boxing Day and went back up on Sunday 28 December unopened and he laid two fingers on the box and nothing came up. **A later batch may open it on a reason with a name against it, or may leave it shut. It may not be opened because a man came home and looked interested.**
- **Choir once at Chapter 148 in a hall, not here.** Mercy Array, Returning Hand, One-Future Compact, Mercy Field, First Choice, permanent anchor, Open Hand not named and not hinted as a plan.
- **Faster nowhere in any sense. Hand-flat-table motif needs a reason and appeared once in Batch 0003. Tidegate addresses out of the residents' file; no move to Ash Street; hall not a second headquarters; cost travel sleep money in that order.**
- **No future Nell, no Door Memory, no branch travel; envelope unsent reason four words; Sector 4C storage not asked; 2003 line, Ninth Ward caretaker, Sycamore vans unmentioned; sealed site unentered, lip not a scene, handset dead; box count unsettled, no number for boxes not in building; out-of-city and fifth Bell copies unmerged.**
- **Romance slow professional voluntary; nothing romantic; no future promises. Nobody inherits anybody.**
- **Released facts with no meaning are not evidence: Sector 4C, nine, 2011, `K-7Q`, the 1998 page, the stamp format. Tarin Voss unfindable by name and that is not a problem to fix.**
- **Rusk and Sable appear only at Chapter 147 and nowhere before. Ferrand if on page says recorded figures only and does not state the distinction. The branch survivors arrive on 11 January in Chapter 147's vicinity and not in this batch, and Volume 03's only question to any of them is what is your name and what is your address.**

## Inherited live threads for this batch

- Thread proximity danger continues; the terrible use is not done and not absolved.
- Chemist Marden Row out mid-January, about sixty people; Mara clinical and administrative; the moral point is Ferrand's at 148 and not hers.
- Four names in a margin and on a fading hand; **to be named from the margin in January at Chapter 142 with Alagoa asked first, and Joon does not think she will say yes.** Not named here.
- Reclassification tally printed in Chapter 117 as `IF ACTIONED — TRANSITIONAL 241 · RETAINED 456` against 285 and 412 out of 697; the forty-four is derivable by the reader; no character says either number in a room; the next occasion is the fourth reading, January, date not fixed inside the contractor's window.
- Board query copy in Meridian; Rusk read it and dislikes it and cannot say so in his office.
- Corridor lie about Hobbs kept out of the counter book; the shut-door fact request still has no form.
- **The eleven: Rhoda Mistry's ballpoint list, Peart's eleven signed works cards, a ladder out instead of a carry, and nobody hurt on 23 December. Eleven people are hurt in the January clearance because the hands were not there, and the refusal is not the villain of that and Elias is.** **This batch may not put anybody on a stair in these ten chapters, and may not stage the injuries; those are Chapters 141 and after.**
- **The hand lamp, in his coat, not on the residents' file, not on a pad, not in a book, not near the power budget, £2.10 to run.** It may be used and it may not become the building's.
- **Four January dates he had in his coat on 27 December and did not give to a woman at a bollard.** A later chapter may have somebody else find a gap; he may not hand them over retroactively as a present.
- Alagoa Saturday bollard; 41 vs 39 gap never closed; second reading is the one taken 29 November and is never called December.

## Character changes required

- **Elias:** asks the boundary to be repeated at 134 and the asking is what moves the ground, and nobody caused it, and he has to live inside that. Keeps the left limitation in every scene. Does not get the gift, does not get a girl, does not get an ending. Has told a room in December that he will be on four nights with a lamp and is now on them.
- **Mara:** four refusals intact; she is not the moral point; her chapter 125 refusal is not revisited as a wound and is not softened.
- **Tomas:** not asked, not consulted, not offered, unknowing lender branch, not softened, not a villain.
- **Joon:** the two dates are public and he refuses to say them sooner; the only we-do-not-know-that voice; not a narrator; the four names stay where the woman put them.
- **Inez:** two standing refusals current; the hall is not a headquarters; a lamp on a table gets voted on.
- **Ferrand if on page:** recorded figures only.

## Length

Ten chapters 1,800–2,400 each, total 20,000–24,000. **Cut beat never add.** The exposition risk is the mechanism, and the defense is the prompt's own: cut a character's arrival first and a document second, and never the panel and never the Chapter 106 sentence.

## State files afterwards

Update `state/current.md`, `state/chapter-summaries.md`, `state/continuity.md` (new BATCH 0004 AS WRITTEN with every new name street form figure before prose uses next), `state/character-state.md` (After Chapter 140), `state/open-threads.md` (next items), `NOVEL_SPEC.md` Status, `workspace/volume-03/batch-0004/SUMMARY.md`. **Chapters 141–150 remain, so create exactly one next prompt `workspace/volume-03/batch-0005/PROMPT.md` and no other. No marker.**
