# Volume 03 — Batch 0003 Writing Prompt

## Assignment

Write **Chapters 121–130** of *The War of Borrowed Gods* as complete finished scenes in chapter order. This is the third prose batch of Volume 03, *The List*. Read, in this order, `AGENTS.md`, `NOVEL_SPEC.md`, `outline/series.md`, `outline/ending.md`, `outline/volume-03.md` in full, this prompt, `state/current.md`, `state/continuity.md`'s sections headed *Volume 03 continuity — BATCH 0001 AS WRITTEN* and *Volume 03 continuity — BATCH 0002 AS WRITTEN* (prose fact outranks cards), `state/open-threads.md` items 128 onward, `state/character-state.md` *After Chapter 120*, and Chapters 120, 118 and 113 before drafting. Chapter 120 is the state the batch travels from. Chapter 113 is the only interface notice spent. Chapter 118 holds the corridor lie and the Board query.

**Chapters 1–120 are canon. Do not restart, summarise or rewrite them.** Do not edit controller files, workflows, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, or `state/phase-ledger.json`, and do not create a marker file by hand.

**Where this prompt restates canon, source files own it.** `outline/volume-03.md`, `outline/ending.md` and `state/continuity.md` are canonical for day map, locks, counters, ending shape.

## House style

US spelling throughout — *neighborhood, neighbor, organize, recognize, center, color, license, meter, apologizing, traveling, rumor, labeled, favor, artifact, labor, defense, program*. Run this pattern over whole of `chapters/`, not files edited, before claiming clean:

```text
\b(colour|neighbour|organis[a-z]*|recognis[a-z]*|centre|licence|metre|metres|millimetre|millimetres|apologis[a-z]*|travell[a-z]*|rumour|labell[a-z]*|favour[a-z]*|artefact|behaviour[a-z]*|realis[a-z]*|analys[ei][a-z]*|defence|offence|programme|grey|judgement|kerb|storey|tyre|plough|manoeuvr[a-z]*|sceptic[a-z]*|moustache|enrolment|whilst|amongst|speciality|aluminium|armour|counsellor)\b
```

If new British form turns up, add form to pattern same pass. **Run it over the whole of `chapters/`, not the files you edited, and if the result is anything other than zero, the pass that wrote the prose is the pass that fixes it.**

**Wider narrator-reference scan, and it must include the BARE SINGULARS.** The plurals-only list missed `this chapter`, `the chapter did not let him off`, `this batch's`, `the first batch` and `pre-canon` in Batch 0002, and missed `Stage 2` in Chapter 119 entirely, and then two state files certified the scan clean. Use all of:

```text
\b(this|the) (chapter|chapters|batch|batches|volume|volumes|novel|novels|manuscript|manuscripts|story|stories|series|ending|endings)\b
\bpre-canon\b
\bStage [0-9]\b
\bcanon\b
```

Legitimate hits are device/gift uses (vehicle reader, Load Reader), the records-request series, and a bound paper volume on a shelf. **Volume 03 prose must return zero otherwise, and an outline label like `Stage 2` is never allowed in the narration — say the cost in the character's own words instead.** A power-system stage is a planning term, not a thing a narrator can know.

## Calendar — derive every date from day zero Saturday 6 September 2042; day equals chapter less seventeen

| Chapter | Weekday | Day | Date |
| --- | --- | --- | --- |
| 121 | Friday | 104 | 19 Dec |
| 122 | Saturday | 105 | 20 Dec |
| 123 | Sunday | 106 | 21 Dec |
| 124 | Monday | 107 | 22 Dec |
| 125 | Tuesday | 108 | 23 Dec MIDPOINT |
| 126 | Wednesday | 109 | 24 Dec |
| 127 | Thursday | 110 | 25 Dec |
| 128 | Friday | 111 | 26 Dec |
| 129 | Saturday | 112 | 27 Dec |
| 130 | Sunday | 113 | 28 Dec |

Midpoint is Chapter 125 day 108; do not confuse with Volume 02 Chapter 75 day 58. Day 100 was Chapter 117.

**The Tidegate day-run is fixed and is derived, not chosen: it started on Saturday the twenty-ninth of November and Chapter 120 is its nineteenth day.** Three canon chapters establish it and all three agree — `chapter-0105.md` (3 December) has Alagoa say *five days running*, `chapter-0107.md` (5 December) says *seven days*, `chapter-0108.md` (6 December) says *eight days*. **Any figure you write for how long he has been going must come out of that start date, not out of a previous chapter's prose.** Run day 11 is Chapter 111, 12 is 112, 13 is 113, 14 is 114, 15 is 115 (and Sunday the fourteenth of December is the day off), 16 is 117, 17 is 118, 18 is 119, 19 is 120. **Chapter 114 says *fourteen days running* and Chapter 116 says *fifteen days, and this is the day off*.** A prior pass had 6 December as the start, which contradicted three chapters of Batch 0001.

**Fares are pounds and only pounds in this batch: two pounds seventy-five each way, eleven minutes each way, five-fifty a day round trip.** Chapter 112 has twelve days and sixty-six pounds, Chapter 115 fifteen days and eighty-two pounds fifty, Chapter 117 sixteen days and about eighty-eight pounds. **No chapter may put pounds and dollars in one breath.** Volume 01 Chapter 35 and Volume 02 Chapter 71 have dollars and always will; the volume's fare rate is in pounds and a cumulative figure must match it.

## Counters — always chapter day less start, never copied forward

Cliff Marner day 30: **74,75,76,77,78,79,80,81,82,83**. Della and man behind wall day 0: **104,105,106,107,108,109,110,111,112,113.** Prefer naming day over printing numeral. Four non-drift figures: hall twenty-two cards twenty-eight people four dark hours; custody twenty-two items; works model 1,140 and 2,900; schedule 697 with 412 RETAINED 285 TRANSITIONAL forty-four inside September outside November dated 2 December footnote Current reading 11 September 2042.

## Working week

Board and Bellwether counter shut Saturdays Sundays. Yard six days, shut Sundays. Depot Tuesdays Fridays 06:30, Tuesday his. No hearing counter determination office on shut day. Friday 19 Dec and Friday 26 Dec depot inventory halves on notice empty in his week. Verification log near 2 Jan far 16 Jan neither received chased nor asked after in room.

**Christmas and Boxing Day fall inside this batch and the ordinary civic closures stand. Derived from day zero, not chosen: Thursday 25 December 2042 (day 110, Chapter 127) is Christmas Day and Friday 26 December 2042 (day 111, Chapter 128) is Boxing Day. The only Sunday in this batch's day range of 19–28 December is the twenty-first (day 106, Chapter 123), and Chapter 123 has him not cross the cut that day for exactly that reason.** The Havenport Tidal Board, the Bellwether cell's public counter, the hearing room and the determination office are **shut on both days**, exactly as they are on any Saturday and Sunday, and **the works yard is shut on the four days printed on its own card — 25, 26, 27 and 28 December — four days, not five and not six.** **No hearing, no counter transaction, no determination, no yard, no method officer and no board surveyor on either day, and no chapter may treat either date as an ordinary working day or invent a special holiday arrangement to get round it.** A reader who knows when Christmas is will check this, and the notice on the yard gate and the sheet on the board are where a closure is shown rather than announced. **The depot runs Tuesdays and Fridays; the Friday halves in this batch are the nineteenth and the twenty-sixth, and the twenty-sixth is the inventory half, on the notice, empty in his week — the same as every other Friday in the run, and not a cancellation. The twenty-fifth is a Thursday and is not a depot day at all.** Elapsed counters still advance on the days nothing happens: day 110 is 80 days out for Cliff and 110 days in for Della and the man behind the wall, and a chapter that happens in a room at Ash Street can still carry them.

## Batch job — 121–130 *The List* per escalation table

Final clearances made survivable with future physician hands; Elias asks question boundary forbids. **Turn: Chapter 125 future Mara refuses, complete with reason, consistent with standing refusals, not outage. Eleven hurt in January clearance; refusal not villain, Elias is. Promise made Chapter 122 makes refusal payoff not rupture.**

Non-negotiables:

- **Interface notices exactly three in Volume 03 at 113, 125, 134. This batch spends one at 125 and no others. At most one per chapter.** 113 spent. 134 boundary-only later.
- **Chapter 122 bilateral practice milestone and not before:** before gift tell other one — not gift, that you are going to ask — four-minute rule silence means no. Mara asks once in room with witnesses as in Volume 01; second asking is joke and cost. Do not start before 122; 113 must not have been version of it.
- **Chapter 125 panel fixed in outline/volume-03.md:** Loan offered Mara Okafor twenty-one years ahead, Still Hand, keep one living body from failing while another carries/repairs, boundary do not use hand on anybody on list nor to make schedule come out right, return when last one out of building and you say out loud it is last one. Refused with reason using three of four standing refusals, in words said before acted on, in room. Program headings SECURED SUBJECT / SUBJECT HELD may appear only from 125 preparation; panel still says Still Hand. Present Mara does not consent for her nor defend her: nobody inherits me. Not romance.
- **Thread stays proximity Chapters 121–124; no second thread lender upgrade mechanic.** Stage cost: aftermath easier to identify not undo; changed future may alter thread.
- **Central distinction spoken once Chapter 106 never restated paraphrased improved handed.** Cut arrival then document before panel if second pass needed.
- **The Load Reader's five limits are stated in full in Chapter 113 and nowhere else in the volume so far**, and the boundary is in the Chapter 113 panel and once in Elias's mouth to Hobbs the same afternoon. **Do not recite the limits again.** A use may show one of them failing — a stair that still shakes, a reading nobody can check, an hour of wrong-load sight that cannot be willed — and that is the whole permitted method. If a chapter needs a second pass at the mechanism, cut a character's arrival first and a document second, and never the panel and never the Chapter 106 sentence.
- **"Before I say anything else" is a tic with a name — step four — and it is now in four chapters of Batch 0002 only: 112 where it is introduced, 114 where Anum names it, 116 where Elias names it, 120 where Rusk performs it and Joon Park notices.** It is a good instrument at that density and a formula at eight. **It may appear at most once in this batch unless a character names it.**
- **Sixth pattern Hollis Vane Chapter 134 own words only.** Schedule missing person-column is third of five not new. No ordinal counting aloud.
- **Wall three questions untouched bracket empty 19 Nov only date full nobody builds; Perpetua wound not clock not named cheaply; who-benefits not restated put in room weaponized — Chapter 142 doorway conduct reserved (Alagoa refuses sheet to program officer to two people doorway street reason, Joon absent, word unsaid). No batch chapter stages that.**
- **Choir once Chapter 148 Ferrand hall; not spoken written leafleted here. Mercy Array Returning Hand Compact Mercy Field First Choice anchor Open Hand not named hinted as plan.**
- **Faster nowhere any sense. Hand-flat-table motif needs reason. Tidegate addresses out of residents file; no move to Ash Street; hall not second HQ; cost travel sleep money order.**
- **No future Nell Door Memory branch travel; envelope unsent reason four words; Sector 4C storage not asked; 2003 line Ninth Ward caretaker Sycamore vans unmentioned; sealed site unentered lip not scene handset dead; box count unsettled no number for boxes not in building; out-of-city and fifth Bell copies unmerged.**
- **Romance slow professional voluntary; nothing romantic; no future promises.**
- **Released facts no meaning not evidence: Sector 4C nine 2011 K-7Q 1998 page stamp format; Tarin Voss unfindable by name not problem not fixed.**
- **Rusk appears only 120 and 147 in volume; no room here. Sable sentence Chapter 147 only; not here. Ferrand figures only recorded ones if on page; does not state distinction.**

## Inherited live threads for this batch

- Thread proximity danger continues; terrible use not done not absolved.
- Chemist Marden Row out mid-Jan sixty; Mara clinical administrative; moral point Ferrand 148.
- Four names margin and fading hand; named from margin in January (142) not here; four-day rule spent.
- Folder delivered; **reclassification tally is now printed in Chapter 117 as `IF ACTIONED — TRANSITIONAL 241 · RETAINED 456` against the schedule's 285 and 412 out of 697, and the difference of forty-four is derivable by the reader**; no character says either number in a room; next occasion January unfixed.
- Board query copy in Meridian; Rusk read dislikes cannot say in office.
- Corridor lie about Hobbs kept out of book; Hobbs shut-door fact request still no form.
- **Reading changed 17 Dec nobody caused; thread can move before use. THIS IS NOT CHAPTER 134 AND MAY NOT BE SCALED INTO IT.** Chapter 119's event is **half a street of softened edge on one morning, with no reading taken, no vehicle, no foreman, no drawing and no cause**, and it is deliberately smaller and blander than what Chapter 134 must be: **an innocent use of the thread — asking a lender to repeat a boundary — moving the band two streets, forty-four addresses changing class, and the schedule not changing because a schedule records a state.** Do not restate, extend, repeat or escalate the Chapter 119 softening anywhere in this batch, and do not have anybody in a room call it a cause. Nobody caused it and no chapter may say who did.
- Alagoa Saturday bollard Sallow last; 41 vs 39 gap never closed.
- Second reading 29 Nov program calls second Ferrand November; never December again; band two streets schedule unmoved unrebuilt.

## Character changes required

- Elias: asks forbidden question at 125 nine pages villain not softened; keeps left limitation every scene; loses cover of bilateral promise he helped make.
- Mara: four refusals intact; present refuses future anger/gratitude; relationship climax not romance.
- Tomas: not asked not offer unknowing lender branch; not softened villain.
- Joon: date public six weeks; only we-do-not-know-that voice; not functionary narrator.
- Ferrand if on page: recorded figures only.

## Length

Ten chapters 1,800–2,400 each, total 20,000–24,000. Cut beat never add. Exposition risk is midpoint justification; use nine pages of asking not speech about asking.

## State files afterwards

Update `state/current.md`, `state/chapter-summaries.md`, `state/continuity.md` (new BATCH 0003 AS WRITTEN with every new name street form figure before prose uses next), `state/character-state.md` (After Chapter 130), `state/open-threads.md` (next items), `NOVEL_SPEC.md` Status, `workspace/volume-03/batch-0003/SUMMARY.md`. Create exactly one next prompt `workspace/volume-03/batch-0004/PROMPT.md`. No other prompt no marker.
