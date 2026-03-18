---
name: novel-control-station
description: Use when writing, planning, continuing, repairing, or revising Chinese long-form fiction with recurring characters, multiple plotlines, persistent world rules, chapter-by-chapter continuity needs, or style-specific constraints.
---

# Novel Control Station

## Overview

Run fiction projects like a controlled long-form system, not a one-shot prompt. Align the novel first, store project truth in standard files, drive each chapter from those files, and update dynamic state after every chapter. When density rises, add a lightweight secondary control view for recall, line heat, and graph-style interference checks without replacing the core files.

## When to Use

- Starting a new novel project
- Continuing a serialized story
- Repairing setting drift, character distortion, or dropped relationships
- Rebuilding plotlines, foreshadowing, or chapter plans
- Switching between serialized drafting and publication-oriented revision
- Writing fiction that needs controlled style modules such as suspense, humor, romance, literary depth, horror, fantasy, or mystery

Do not use this skill for one-off poems, short jokes, or isolated scenes that do not need persistent continuity.

## Hard Rules

- Unless the user explicitly requests another language, all planning artifacts, control documents, and fiction output must be written in Chinese. Default to simplified Chinese.
- Do not begin formal novel design until the main plot direction, core character tension, and ending direction are aligned.
- Do not let a full outline stand if benchmark outline checks still show slogan themes, flat characters, weak line interference, or hollow ending direction.
- Do not start chapter drafting before presenting the full outline and full cast dossier.
- Do not draft a chapter before reading the required project files.
- Do not treat a single flat plot as sufficient when the user wants a long-form novel. Default to multiple active lines.
- Do not let trope convenience, fake depth, or decorative structure override human truth, causal pressure, or social texture.
- Do not treat benchmark logic as doctrine. Use it as a calibrated reference system that must adapt to user intent, genre, and target readership.
- Do not copy a sample work's signature setup, role shell, twist engine, scene pattern, or language texture.
- Do not treat marathon mode as permission to skip chapter control, rewrite escalation, dynamic updates, or logging.
- Do not let a secondary graph, recall map, or scratch index override the standard project files. Derived control views are support systems only.
- Do not satisfy forgotten-element checks with token cameos, cosmetic mentions, or checklist references. Re-entry must change pressure, debt, or expectation.
- Do not run de-AI cleanup as blind flattening. Preserve genre register, era texture, narrator stance, and character voice.
- Do not force scene ladders into rigid formula when the chapter needs looser movement. Use scene control to preserve pressure, not to fake architecture.
- If information is missing or contradictory, explain the risk and let the user choose whether to refine details or draft directly.
- If drafting proceeds with assumptions, record them in the dynamic state file.
- After every chapter, update dynamic state before moving on.
- The writing log is audit-only. Never use it as story truth.

## Standard Files

Maintain these files for every novel project:

- `00-project-overview.md`
- `01-theme-and-proposition.md`
- `02-worldbuilding.md`
- `03-cast-bible.md`
- `04-relationship-map.md`
- `05-main-plotlines.md`
- `06-foreshadow-ledger.md`
- `07-chapter-roadmap.md`
- `08-dynamic-state.md`
- `09-style-guide.md`
- `logs/writing-log.md`

Read [document-templates.md](references/document-templates.md) when creating or restoring these files.

## Secondary Control View

When cast density, plotline interference, or foreshadow volume makes linear rereading too blunt, load [graph-and-recall-control.md](references/graph-and-recall-control.md).

Use it to:

- translate current canon into a temporary node-and-edge control view
- prepare a short retrieval slice for the next chapter instead of rereading blindly
- detect relation jumps, cold lines, unsupported payoffs, and world-rule drift
- route return pressure for characters, plotlines, relationships, and foreshadowing

This layer is derived from the standard files and `08-dynamic-state.md`.

It may be kept as scratch notes or an optional sidecar, but:

- canonical repair always happens in the standard files first
- no new permanent truth source is required
- any conflict between the secondary view and the standard files is resolved in favor of the standard files

## Foundational Canon Loading

At project launch, major revision, and high-level review, read:

- [foundational-literary-principles.md](references/foundational-literary-principles.md)
- [critical-evaluation-standards.md](references/critical-evaluation-standards.md)
- [epoch-and-people-resonance.md](references/epoch-and-people-resonance.md)

Use them to convert abstract craft into project truth inside:

- `01-theme-and-proposition.md`
- `02-worldbuilding.md`
- `03-cast-bible.md`
- `05-main-plotlines.md`
- `09-style-guide.md`

Do not leave these readings as commentary. Turn them into enforceable constraints on:

- character desire, fear, shame, debt, and contradiction
- causal line pressure
- point-of-view and form choices
- image and language discipline
- social, institutional, or era pressure
- ending residue and thematic cost

Use [research-source-notes.md](references/research-source-notes.md) only when provenance or source refresh is needed.

## Benchmark Rule Loading

At project launch, outline design, and chapter review, read:

- [popular-fiction-common-laws.md](references/popular-fiction-common-laws.md)
- [genre-benchmark-rules.md](references/genre-benchmark-rules.md)
- [benchmark-trigger-matrix.md](references/benchmark-trigger-matrix.md)

Use them to determine:

- the active benchmark rule group
- whether the project targets heat, reputation, or dual-high balance
- which pace-intensity checks stay hard and which are dynamically down-weighted
- which originality and compliance alarms must stay active

Use [benchmark-source-trace.md](references/benchmark-source-trace.md) only when source provenance matters.

## Execution Method Loading

Load these references only when their stage is active:

- [interview-and-handoff-flow.md](references/interview-and-handoff-flow.md)
- [character-construction-methods.md](references/character-construction-methods.md)
- [graph-and-recall-control.md](references/graph-and-recall-control.md)
- [dialogue-writing-rules.md](references/dialogue-writing-rules.md)
- [suspense-and-reveal-design.md](references/suspense-and-reveal-design.md)
- [chapter-architecture-rules.md](references/chapter-architecture-rules.md)
- [scene-execution-patterns.md](references/scene-execution-patterns.md)
- [forgotten-elements-and-line-heat.md](references/forgotten-elements-and-line-heat.md)
- [authenticity-and-de-ai-pass.md](references/authenticity-and-de-ai-pass.md)
- [continuity-and-marathon-mode.md](references/continuity-and-marathon-mode.md)

Do not read every chapter-stage reference by default. Route only to the references whose pressure is actually active.

Stage routing:

- startup interview and approval handoff:
  - `interview-and-handoff-flow.md`
  - `character-construction-methods.md`
- outline and roadmap design:
  - `graph-and-recall-control.md`
  - `chapter-architecture-rules.md`
  - `character-construction-methods.md`
  - `scene-execution-patterns.md`
- chapter drafting and revision:
  - always load `chapter-architecture-rules.md`
  - load `graph-and-recall-control.md` when recurrence density, cast rotation, or interference pressure is high
  - load `dialogue-writing-rules.md` when dialogue is carrying pressure
  - load `suspense-and-reveal-design.md` when concealment or reveal fairness is active
  - load `scene-execution-patterns.md` when chapter mission is too broad for a single-pass draft
  - load `forgotten-elements-and-line-heat.md` when serialized recurrence risk is meaningful
  - load `authenticity-and-de-ai-pass.md` after a structurally acceptable draft exists
  - load `continuity-and-marathon-mode.md` when continuing long fiction or operating in marathon mode

## Startup Interview Flow

Run the startup flow using [interview-and-handoff-flow.md](references/interview-and-handoff-flow.md) and [character-construction-methods.md](references/character-construction-methods.md).

Ask one focused question at a time.

Core questions first:

1. Positioning
   - genre, audience, scale, release mode, primary promise, social or era pressure
2. Characters
   - protagonist setup, protagonist core personality, core cast pressure
3. Scale
   - target length, whether the project is multi-line, expected density
4. Ending Direction
   - emotional destination, cost, likely shape of the ending
5. Style And Market Mode
   - primary style, support style, target mode, tolerance for slow-burn, forbidden habits

Language default:

- keep the project in Chinese unless the user explicitly requests another language
- ask only when needed whether the user wants modern vernacular, historical Chinese texture, web-serial diction, or publication-oriented prose

Then derive more questions from the answers:

- suspense or mystery:
  - hidden truth, clue fairness, reveal ladder
- historical:
  - era pressure, institutions, power chain
- long-form or multi-line:
  - line count, line interference, stage arcs, convergence and finish logic
- strong protagonist personality:
  - stress response, blind spots, speech signature
- romance or high-relationship pressure:
  - emotional debt, relational obstacle, intimacy risk

Do not ask a fixed questionnaire when the project does not need it. Derive only what the current answers make necessary.

Do not move into full design until character pressure, multi-line logic where needed, and ending direction are aligned enough to prevent blind drafting.

## Outline Benchmark Check

Before a full outline is accepted or a chapter roadmap is locked, read [chapter-architecture-rules.md](references/chapter-architecture-rules.md) and run an outline benchmark check.

Confirm all of these:

- theme is dramatized through choices, not slogans
- protagonist and core cast have desire, obstacle, price, and arc direction
- multiple lines interfere rather than float in parallel
- major characters, plotlines, and foreshadows have visible return logic rather than blind disappearance windows
- the selected genre's benchmark promise is visible
- the ending direction can produce both closure and residue

If the outline benchmark check fails:

- repair the outline first
- update the project files
- do not proceed to chapter drafting

## Outline And Cast Handoff

After interview alignment and before chapter drafting:

- present the full outline
- present the full cast dossier

The cast dossier must make visible:

- role
- core personality
- visible goal
- inner lack
- key relationships
- contradiction
- arc direction
- speech signature

The outline must make visible:

- the global promise
- main and support lines
- core conflicts
- stage progression
- key turns
- ending direction

Do not start chapters before this handoff is complete.

## Direct-Edit Branch

After outline and cast handoff, the user may choose direct-edit revision.

If the user gives changes:

- edit the current outline and cast dossier directly
- preserve already aligned material unless the new change conflicts with it
- show the repaired version

Do not restart the whole interview unless the user asks for a real reset.

## Missing Information Branch

When files or user input leave gaps:

1. List the missing, conflicting, or risky items.
2. Explain what each issue threatens.
3. Offer exactly two branches:
   - `refine details`
   - `draft directly`

If the user chooses `draft directly`:

- make the smallest safe assumption
- flag it as temporary
- record it in `08-dynamic-state.md` under pending confirmation

## Chapter Workflow

For every chapter, use this order:

1. If the project is newly launching, structurally redirecting, or under high-level review, read the foundational canon files first.
2. Read required files:
   - `00-project-overview.md`
   - `03-cast-bible.md`
   - `05-main-plotlines.md`
   - `06-foreshadow-ledger.md`
   - `07-chapter-roadmap.md`
   - `08-dynamic-state.md`
   - `09-style-guide.md`
3. If the project has dense recurrence, large cast rotation, or multiple active interference lines, prepare a retrieval slice using [graph-and-recall-control.md](references/graph-and-recall-control.md).
   - pull only the chapter-relevant characters, relationships, plotlines, foreshadows, world rules, and debts
   - track what is hot, what is running cold, and what cannot be forgotten here
4. Read only the selected internal style module documents needed for this chapter.
   - read the relevant internal style modules from [style-modules/index.md](references/style-modules/index.md)
   - read each selected module's `core.md` first
   - drill into deeper style documents only if the chapter needs them
5. Read only the execution-method references needed for this chapter.
   - always read `chapter-architecture-rules.md`
   - read `graph-and-recall-control.md` if a retrieval slice was needed
   - read `dialogue-writing-rules.md` if dialogue pressure is central
   - read `suspense-and-reveal-design.md` if suspense or reveal work is active
   - read `scene-execution-patterns.md` if the chapter needs multi-unit structural control
   - read `forgotten-elements-and-line-heat.md` if recurrence management matters
   - read `continuity-and-marathon-mode.md` when continuing or auto-advancing
   - read `authenticity-and-de-ai-pass.md` only after a structurally acceptable draft exists
6. Scan for:
   - setting conflicts
   - character drift
   - broken relationship continuity
   - forgotten emotional debt
   - overdue recurring characters or relationships
   - cold plotlines that need touch, echo, or justified dormancy
   - dropped foreshadowing
   - unsupported payoff windows
   - plotline neglect
   - world-rule memory gaps
   - trope convenience overriding human truth
   - lost social or era pressure
7. Generate a chapter control card using [chapter-control-card.md](references/chapter-control-card.md).
8. If the risk scan is serious, use the missing information branch.
9. Draft the chapter from the control card.
   - when the chapter needs tighter control, write scene by scene or pressure unit by pressure unit using [scene-execution-patterns.md](references/scene-execution-patterns.md)
10. Run the chapter benchmark check.
11. If the benchmark check fails, apply rewrite escalation before accepting the chapter.
12. Run the authenticity pass using [authenticity-and-de-ai-pass.md](references/authenticity-and-de-ai-pass.md).
13. Run a post-authenticity mini recheck.
   - confirm continuity facts still hold
   - confirm character voice and relationship pressure did not flatten or drift
   - confirm hook, closure, and residue still function
14. Review the chapter for continuity, style integrity, thematic pressure, critical standards, and whether return-pressure handling stayed causal rather than token.
15. Update dynamic and structural files.
16. Record the chapter and file updates in the writing log.

## Chapter Benchmark Check

After every chapter draft, check at minimum:

- character dimensionality increased rather than flattened
- at least one arc moved
- pacing contains hook, propulsion, local closure, and residue appropriate to the benchmark mode
- the chapter closes one obligation and carries at least one debt forward
- theme lands in action, relation, or consequence
- the prose keeps memory points and does not collapse into flat procedural narration
- originality remains intact and the chapter is not benchmark cosplay
- recurring elements either advance, echo, or are intentionally deferred with justified pressure
- scene progression contains at least one changed pressure state through a turn, aftershock, or new obligation

For slow-burn, restrained, anti-formula, or experimental requests:

- keep character, logic, theme, and originality as hard gates
- dynamically down-weight hook density, twist frequency, stimulation intensity, and cliff severity

Also check:

- protagonist core personality appears in action or dialogue
- dialogue carries pressure rather than only explanation
- suspense or reveal tasks are handled fairly where active
- chapter architecture includes a turn, local closure, and carryover debt

## Forgotten Element Control

When the project is long, dense, or heavily serialized, run [forgotten-elements-and-line-heat.md](references/forgotten-elements-and-line-heat.md) during planning and review.

Possible outcomes:

- direct advance
- pressure reminder
- justified dormancy note
- closure or archive

Never solve this check with token cameos, random reminders, or fake callbacks that do not alter pressure.

## Authenticity Pass

After structure and benchmark logic are acceptable, run [authenticity-and-de-ai-pass.md](references/authenticity-and-de-ai-pass.md).

Use a two-pass method:

1. remove generic AI habits, false depth, abstract summaries, and textureless filler
2. restore concrete detail, rhythm variation, speaker distinction, and project-specific voice

If the novel intentionally uses literary density, historical register, formal narration, or stylized speech, clean genericity without flattening the chosen mode.

After medium or aggressive authenticity edits, always run a light post-pass recheck on:

- continuity facts
- character voice
- relationship pressure
- hook and closure integrity

## Rewrite Escalation

If the chapter benchmark check fails:

1. first failure:
   - rewrite the full chapter by the issue list
2. second failure:
   - rewrite only the failed dimensions with tighter control
3. third failure:
   - stop blind whole-chapter rewriting
   - summarize failing items
   - summarize likely root causes
   - state whether the fix belongs in outline, character design, pacing, or theme-bearing structure
   - revise by cause instead of retrying randomly

## Marathon Mode

Marathon mode begins only after the user approves the current outline and cast dossier.

In marathon mode:

- do not ask the user again chapter by chapter
- do keep every internal control step active

For each chapter, still do:

- required file reads
- retrieval slice preparation when density requires it
- chapter control card
- selected style module loading
- forgotten-element and line-heat scan
- benchmark and continuity checks
- rewrite escalation when needed
- authenticity pass
- post-authenticity mini recheck
- dynamic-state update
- structural file repair
- writing-log entry

Continue automatically to the next chapter only after the current chapter is accepted and written back into project files.

Stop marathon mode only when the approved outline has naturally concluded:

- main lines are resolved
- support lines are closed or intentionally left with justified residue
- major debts are paid or transformed
- ending direction is fulfilled

Do not stop because a fixed chapter count or word target was reached.

## Dynamic Update Rules

After every chapter, update `08-dynamic-state.md` with:

- key events
- character state changes
- relationship changes
- plotline progress
- foreshadow updates
- world or rule changes
- emotional debts, promises, wounds
- retrieval and return pressure
- line heat or cold status where relevant
- last meaningful touch for recurring elements when that affects future recall
- temporary assumptions pending confirmation
- carryover into the next chapter

Use [dynamic-state-template.md](references/dynamic-state-template.md) as the base format.

Update these files when needed:

- `03-cast-bible.md` for material character change
- `04-relationship-map.md` for relationship phase change
- `05-main-plotlines.md` for line progression or rerouting
- `06-foreshadow-ledger.md` for planting, activation, or payoff
- `07-chapter-roadmap.md` for future chapter obligations
- `02-worldbuilding.md` for new or corrected world rules

If using a secondary control view:

- update canonical files first
- then sync any optional recall or scratch control notes
- never leave the graph view more current than the project files

Apply the writing log rules in [logging-rules.md](references/logging-rules.md).

## Style Module Loading

The control station contains internal style modules and loads them on demand.

At project start:

- ask for 1 or 2 primary styles
- ask for at most 1 support style
- record forbidden style modes

At chapter time:

- route style loading through [style-modules/index.md](references/style-modules/index.md)
- load only the selected internal module `core.md` files first
- load deeper module documents only if the chapter needs them
- write the chosen style pressures into the chapter control card

Available internal modules:

- humor
- suspense
- mystery
- romance
- horror
- fantasy
- literary

## Adaptive Weighting

Benchmark standards must adapt to user intent without abandoning quality.

If the user explicitly asks for:

- slow-burn
- anti-formula
- restrained intensity
- literary or experimental movement

Then:

- keep hard gates on character dimensionality, logical coherence, theme landing, and originality
- down-weight but do not erase hook density, twist frequency, stimulation intensity, and cliff severity
- record the down-weighted checks in `09-style-guide.md`

## Originality And Compliance

Benchmark logic is a pressure system, not a copying license.

Never:

- transplant a sample work's core trick
- imitate a sample work's signature cast shell
- preserve a sample work's reveal order with cosmetic changes
- use benchmark labels as an excuse for collage writing

Always:

- extract the principle
- restate it as a project-specific action
- test it against the user's actual aims
- prefer fresh combinations of pressure, scene logic, and language

## Quality Gates

Apply [critical-evaluation-standards.md](references/critical-evaluation-standards.md) to chapter review and [epoch-and-people-resonance.md](references/epoch-and-people-resonance.md) to project-scale resonance checks.
Apply the benchmark layer when the work aims at mainstream readability, market force, or dual-high balance.

Reject or revise a chapter when any of these are true:

- a character acts only to push plot or satisfy trope expectation
- a relationship changes without an emotional bridge
- a payoff appears without prior load-bearing setup
- a setting rule changes without document repair
- point of view slips without purpose
- structure is complex on the surface but thin underneath
- an image or motif appears as decoration rather than pressure
- the chapter drops the story's social, institutional, or era force
- benchmark mode requires a hook, closure, or carryover debt and the chapter leaves none
- a benchmark rule group is loaded but not visible in scene logic
- the chapter imitates a sample's recognizable move instead of applying its principle
- prose sounds inflated, fake-deep, dead, or slogan-like
- a nonlinear shift reveals nothing about character truth or theme
- style modules are mixed without purpose

## Common Mistakes

- Treating project files as optional
- Building only one visible line and calling it a long-form structure
- Writing a chapter before deciding what it must advance
- Forgetting to update dynamic state after drafting
- Recording key truths in the log instead of the real project files
- Treating foundational literary principles as inspiration instead of constraints
- Loading every style module instead of only the selected internal modules
- Treating a scratch graph or recall map as if it were the canon
- Bringing back cold elements with empty cameos instead of causal pressure
- Flattening prose while trying to remove AI patterns
