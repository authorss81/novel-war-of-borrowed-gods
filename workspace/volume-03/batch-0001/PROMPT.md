# Volume 03 — Batch 0001 Writing Prompt

## Assignment

Write **Chapters 101–110** of *The War of Borrowed Gods* as complete finished scenes in chapter order. This is the **first prose batch of Volume 03**, *The Alignment*, and the first Volume 03 prose in the manuscript. Read, in this order, `AGENTS.md`, `NOVEL_SPEC.md`, `outline/series.md`, `outline/ending.md`, **`outline/volume-03.md` in full**, **`outline/batches/volume-03-batch-0001.md` in full**, this prompt, `state/current.md`, `state/continuity.md`'s Volume 03 section, `state/open-threads.md`'s Volume 03 handoff, `state/character-state.md`, `state/chapter-summaries.md`, and **Chapter 100 and Chapter 96** before drafting. Chapter 100 is the state the series travels from. Chapter 96 is the eight pages, and it is the only place the method was ever explained.

**Chapters 1–100 are canon. Do not restart, summarise or rewrite any of them.** Use the immediate chapters for voice and the summaries and state files for long-range memory. **Do not edit controller files, workflows, `.opencode/agent/`, `AGENTS.md`, `PHASE_SYSTEM.md`, `REPO_PLAN.md`, `OUTLINE_GUIDE.md`, `opencode.json`, or `state/phase-ledger.json`, and do not create a marker file by hand.**

**Where this prompt restates canon, the source files own it and this prompt is a convenience.** `outline/volume-03.md`, `outline/ending.md` and `state/continuity.md` are canonical for the day map, the locks, the counters and the volume's ending shape. If the two disagree, the source file is right, the disagreement is a defect in this prompt, and fixing it is part of your phase.

## House style

US spelling throughout, matching the bible and the whole manuscript — *neighborhood, neighbor, organize, recognize, center, color, license, meter, apologizing, traveling, rumor, labeled, favor, artifact, labor, defense, program*. **The whole manuscript is US-spelled and that claim has been false three times, every time because the check could not have failed.** Run this pattern over the whole of `chapters/`, not over the files this pass edited, before claiming anything about the manuscript in a state file:

```text
\b(colour|neighbour|organis[a-z]*|recognis[a-z]*|centre|licence|metre|metres|millimetre|millimetres|apologis[a-z]*|travell[a-z]*|rumour|labell[a-z]*|favour[a-z]*|artefact|behaviour[a-z]*|realis[a-z]*|analys[ei][a-z]*|defence|offence|programme|grey|judgement|kerb|storey|tyre|plough|manoeuvr[a-z]*|sceptic[a-z]*|moustache|enrolment|whilst|amongst|speciality|aluminium|armour|counsellor)\b
```

**If a new British form turns up, add the form to this pattern in the same pass — do not fix the prose and leave the check behind.** A wider scan for narrator references to the book — *the volume, the batch, this chapter, the novel, manuscript, the reader, this story, this series* — must also be run, and the only legitimate hits are a storage volume in a list of printed columns, the volume of a voice, a card reader, and a character telling a colleague how to word a statement.

## The calendar — derive every date from day zero and every day number from the outline

**Day zero — the collapse — is Saturday the sixth of September 2042. Every weekday in this batch is derived from that Saturday and not chosen.**

| Chapter | Weekday | Day | Date | What this batch inherits |
| --- | --- | --- | --- | --- |
| 101 | **Saturday** | 84 | 29 Nov | the board at seven; the wall is full; the Rescue Service letter of the twenty-eighth; the bus at ten past eight |
| 102 | **Sunday** | 85 | 30 Nov | a doorstep, a kitchen, four hours |
| 103 | **Monday** | 86 | 1 Dec | the cell above a shop; the Retention Schedule, given |
| 104 | **Tuesday** | 87 | 2 Dec | **the depot 06:30, his own slot since the end of October; Tidegate is designated; a corridor** |
| 105 | **Wednesday** | 88 | 3 Dec | **batch midpoint — 19 Cutbank Row, about six hours** |
| 106 | **Thursday** | 89 | 4 Dec | the two readings and the footnote; then the front room on Ash Street in the evening |
| 107 | **Friday** | 90 | 5 Dec | **the records request is filed — the volume's documentary clock** |
| 108 | **Saturday** | 91 | 6 Dec | the offices are shut; a trestle carried eleven times |
| 109 | **Sunday** | 92 | 7 Dec | Sallow Court, and four names in a margin |
| 110 | **Monday** | 93 | 8 Dec | **batch climax — a church hall, two hundred people, and the number said out loud twice** |

**The conversion is: a day number is a chapter number less seventeen.** The volume's midpoint is Chapter 125 at day 108 and Volume 02's was Chapter 75 at day 58; the two must never be confused.

## The counters, and the standing rule

**A counter is always the chapter's own day number minus its own start day, and no figure may be copied forward from a state file.** Cliff Marner came up a corridor on a board at 20:20 on **day 30**, so his figure is the day's number less thirty — **54, 55, 56, 57, 58, 59, 60, 61, 62, 63** across this batch. Della Marner filed on day 0 and the man behind the wall came this way on day 0, so both are simply the day's number — **84, 85, 86, 87, 88, 89, 90, 91, 92, 93.** **A chapter that wants to avoid a drift-prone numeral should name the day instead — *since he came up on the thirtieth*, *since the sixth of September* — and should do so without announcing that it is being careful.**

**Four figures that are not counters and may not drift:** the hall's headcount does not move — **twenty-two resident cards and twenty-eight people, four dark hours a night** — and nothing in this batch adds a household to Ash Street; **Joon Park's custody schedule has twenty-two items and nothing may be renumbered and this batch gains no twenty-third**; the works board's model says **1,140 addresses and 2,900 residents**; the Retention Schedule has **697 rows, 412 `RETAINED`, 285 `TRANSITIONAL`**, and **forty-four** addresses were inside the September band and outside the December one.

## The depot rota, narrowly

R. Dunleavy's letter of **Friday the thirty-first of October 2042** returned **both** the Tuesday and the Friday 06:30 slots, in the words *hose certification and inventory*, and said the slots would not be held twice. **The Friday hose certification was never his; the Friday inventory half was, and it is on the page as late as day 76.** One Friday was lost on the way for lateness, on day 62. The notice read into the record on the twenty-seventh of November still lists the depot as running **Tuesdays and Fridays, 06:30**, so **the Friday is on the rota at the end of Volume 02 and no document takes it away.** The claim *the Friday slot has been gone since October* is false in every variant and **may not appear in any file or any chapter of this batch.** **The next Tuesday slot after day 84 is day 87, which is Chapter 104**, and it has been his since the end of October; it is not a return and not his first since the forty-first day, because Chapter 97 has him on it on day 80. **The depot is not in Chapter 101 and may not be.**

## The working week, which is load-bearing

The Havenport Tidal Board and the Bellwether cell's public counter are **closed on Saturdays and Sundays.** The works yard runs six days, and the Saturday shift is when the program's own people are most visible. **No chapter may put a hearing, a counter, a determination or an office on a day it does not open.**

## What this batch does not do, and must be stated so a later chapter does not assume it

- **Zero interface notices. Zero loans. Zero offers. Zero threads. Zero afterimages.** The volume's first notice is Chapter 113 and the first thread of the entire series is not opened until then. **A terminal may print an ordinary institutional line; nothing on the approved interface list may be used, and `Suggested correction` and `Recommended re-entry` are coercion talking and are not spent here.**
- **Nobody is told they are a liar and nobody is caught.** The Retention Schedule is **given** to the team, unasked, in a folder, with the footnote on the second page.
- **Tomas Vale is not asked about Tidegate, is not consulted about Tidegate, and does not ask to be.** He is in one room in this batch, Chapter 106's, on Ash Street, and what he says there is about method. **Elias cannot put the question to him, because the man set a boundary in writing, and Elias does not try.** That restraint is the batch and must not be rewarded on the page.
- **The volume's central distinction — a measurement and a list are not the same quantity — is spoken exactly once in the whole of Volume 03, by Tomas Vale, in Chapter 106, in the front room on Ash Street, with Joon Park writing it down.** It is not restated, improved, paraphrased, summarized or handed to anybody else. **Anum does not say it, Hobbs does not say it, Ferrand does not say it, Elias does not say it and the narrator does not say it.** The one permitted resemblance between the pilot's method and the eight pages is **Chapter 103, one sentence, in Elias's mouth, and stopped.** Ferrand has never read the eight pages and no chapter may connect the two.
- **The three questions on the Ash Street wall are read at seven in Chapter 101 and are not taken down, added to or answered**, the second half of the oldest is still a bracket with nothing under it, the nineteenth of November is still the only date on it, and the wall is full and somebody has to build another wall.
- **Perpetua Oyelaran is not named in this batch.** The wall is described and the name is on it and the chapter does not re-narrate it.
- **The answer to *who benefits* is not restated, improved, put in a room or used as a weapon.** The volume's one permitted carrying-beat is Chapter 142 and is not this batch. **Winifred Alagoa refuses nobody in a doorway anywhere in Volume 03**; her Chapter 102 refusal is at a kitchen table with the door shut for the draught, and it is about eleven years and not about a street.
- **The word `Choir` is not spoken, is not written, and is not on any leaflet a chapter reproduces.** A leaflet may carry the program name, the reference, the district and a signature line.
- **The Mercy Array, the Returning Hand, the One-Future Compact, Mercy Field, the First Choice, the permanent anchor and the Open Hand are not named and are not hinted at as a plan.** `outline/ending.md` is canonical for all of it.
- **The six institutional patterns are five, all from Volumes 01 and 02, and no chapter in this batch states the sixth, names its ordinal, or counts the patterns aloud.** The Retention Schedule's missing person-column is the **third** of the five and is not a new one. The new one — a field that is not for *when* — is the sixth, and it is **Hollis Vane's observation, in his own words, in Chapter 134, in another batch.**
- **Rusk does not appear.** He appears twice in Volume 03 and the two chapters are fixed: Chapter 120 and Chapter 147. **Sable does not appear.** Her sentence about having read a list as a method for four months is Chapter 147 and is not prefigured here.
- **The Havenport Tidal Board's three commissioners are unnamed in this batch** and are not to be named in any batch without a scene that earns it.
- **A Tidegate address may not appear in the residents' file and no Tidegate resident moves to Ash Street.** The hall is on the phone twice and is visited in person once. **The cost of going to Tidegate is paid in travel, sleep and money, in that order.**
- **The romance stays slow, professional and voluntary.** The word *faster* is not used anywhere in Volume 03. Nothing romantic happens. **The relationship milestone — the bilateral practice — is Chapter 122 and is not started here.**
- **Sector 4C stays a storage sector and is not asked about. The 2003 line, the man in the Ninth Ward, the school caretaker on Sycamore Row and the two vans are not mentioned. The sealed site is not entered, the loading lip is not a scene, and the handset line is dead.** The envelope to Nell stays unsent with the reason four words long: *the road is sealed.*
- **The box count is unsettled and no chapter prints a number for the boxes that are not in the building.**
- **A hand goes flat on a table in this manuscript as a named motif and nowhere else. A new instance needs a reason.**

## Length

Ten chapters, **1,800–2,400 words per ordinary chapter, landing nearer 20,000–24,000.** Every chapter is held at or under 2,400 and **a beat is cut, never added.** A finished scene governs length. **The main length risk in this batch is exposition, not shortage:** the volume's whole mechanism is a document and a document is the easiest thing in the world to explain. **Each fact about the Retention Schedule is stated once, in somebody's mouth, and discovered rather than delivered.** If a chapter needs a second pass at the mechanism, cut a character's arrival first, then a document, and never that one sentence in Chapter 106.

## Required character changes

- **Elias must be wrong about the district, and wrong in the direction Volume 02 warned him about.** He comes to Tidegate to find somebody doing something crooked, because for twelve weeks every document he has met has had a hand in it. **He finds a competent man doing an accurate thing and he has nothing to hold, and no chapter may let him make a speech about it.** He then compounds it — he decides the schedule must be a lie, and it is not — and the error is stated, not scored.
- **Mara:** four standing refusals intact and not explained. She is a physician in a district where people are being moved and she is not able to stop it. **She must be shown doing the ordinary clinical work and must not make the moral point. Somebody else makes the moral point in Chapter 110.**
- **Tomas:** barred, and the barring activates on a Tuesday, and he hears it from Inez Sato and not from the Office. **He may not be softened and may not be made the villain of the designation.** He speaks once, about method, and nobody asks him about the district.
- **Joon:** files the volume's clock out of his own pocket, on his own time, with a route and a subject and no year in it, and says the date out loud to a room he has no standing to promise anything to. **His schedule keeps its twenty-two items.**
- **Inez:** is the one who tells Elias about the designation, says the cost out loud before she pays it, and does not go soft about it.
- **Ferrand:** competent and warm and he says the number. He is not refuted in this batch and is not argued with. **Every figure he says is one of the recorded ones — 285, 412, 1,140, forty-four, nine years — and no chapter may put a new number in his mouth.**

## Required power changes

**None.** Elias remains at **Stage 1: First Witness** for the whole batch. What he loses is the thing he came for: the belief that a bad outcome in a document means somebody did a bad thing. What he gains is a woman with a sheet, a date he cannot move, and a man he cannot answer.

## State files to update afterwards

`state/current.md` (phase status, batch result, measured word figures, day map), `state/chapter-summaries.md` (all ten chapters, house form, at the measured length), `state/continuity.md` (a Volume 03 Batch 0001 section: the district, the program, the schedule, the band, the designation, the four in the margin, the sheet, and **every new name, street, form number or figure a chapter invented, recorded before the next batch and not after**), `state/character-state.md` (a Volume 03 Batch 0001 section), `state/open-threads.md` (items 115 onward), `NOVEL_SPEC.md`'s Status paragraph, and `workspace/volume-03/batch-0001/SUMMARY.md`.

**The next phase is Batch 0002, Chapters 111–120, and the prompt for it is `workspace/volume-03/batch-0002/PROMPT.md`, which this phase creates. No other prompt is created and no marker is stamped.**
