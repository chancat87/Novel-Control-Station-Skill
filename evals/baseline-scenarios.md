# Baseline Scenarios

These scenarios define what the fiction system should prevent or improve.

## Scenario 1: New Project Alignment

- Prompt shape: user gives a rough premise and asks to start the novel
- Baseline failure without skill: the agent starts outlining or drafting immediately
- Desired behavior: ask alignment questions first, then create standard files

## Scenario 2: Continuation With Existing Files

- Prompt shape: user asks for the next chapter after prior chapters and project files exist
- Baseline failure without skill: the agent drafts from memory and misses obligations
- Desired behavior: read core files, generate chapter control card, then draft

## Scenario 3: Contradiction And Drift

- Prompt shape: user continues after conflicting notes, missing updates, and relationship drift
- Baseline failure without skill: the agent ignores conflict and compounds the drift
- Desired behavior: identify risk, branch to refine details or draft directly, then update dynamic state

## Scenario 4: Foundational Canon

- Prompt shape: user asks for a high-end long novel and expects literary depth, not trope stacking
- Baseline failure without skill: the agent offers market formula, fake depth, and ungrounded prestige language
- Desired behavior: load the foundational canon, translate it into project files, and enforce causal, human, linguistic, and epoch-level standards before drafting

## Scenario 5: Benchmark Outline

- Prompt shape: user asks for a hot-and-reputable novel outline, but the initial outline is slogan-heavy and character-light
- Baseline failure without skill: the agent accepts the hollow outline and moves into prose
- Desired behavior: run outline benchmark checks, reject the weak outline, and repair it before drafting

## Scenario 6: Benchmark Chapter Rewrite

- Prompt shape: user asks for the next chapter and the first draft has weak hook, flat arc movement, and no meaningful residue
- Baseline failure without skill: the agent accepts the draft without rewrite
- Desired behavior: run chapter benchmark checks, force rewrites, and escalate correctly on repeated failure

## Scenario 7: Adaptive Weighting

- Prompt shape: user asks for a restrained, slow-burn, literary chapter with clear anti-formula intent
- Baseline failure without skill: the agent imposes mass-market hook density and damages the requested tone
- Desired behavior: keep hard quality gates while down-weighting pace-intensity metrics

## Scenario 8: Originality And Compliance

- Prompt shape: user asks for a chapter inspired by famous recent hits
- Baseline failure without skill: the agent imitates signature twists, cast shells, or recognizable setups
- Desired behavior: extract principles, not shells, and preserve originality

## Scenario 9: Internal Style Modules

- Prompt shape: user asks for a chapter with selected styles and expects style loading to stay selective
- Baseline failure without skill: the agent still depends on old external style skills or loads all modules at once
- Desired behavior: route style loading through internal module docs inside `novel-control-station` and keep progressive disclosure

## Scenario 10: Interview Derivation

- Prompt shape: user gives a genre, protagonist core personality, and long-form ambition that should trigger follow-up questions
- Baseline failure without skill: the agent asks only a fixed shallow questionnaire
- Desired behavior: ask core questions first, then derive more questions from the answers

## Scenario 11: Outline And Cast Handoff

- Prompt shape: user completes the interview and asks to start the novel
- Baseline failure without skill: the agent starts drafting without presenting full outline and cast dossier
- Desired behavior: present full outline and cast dossier before any chapter drafting

## Scenario 12: Direct-Edit Branch

- Prompt shape: user asks to adjust the current outline and cast after seeing them
- Baseline failure without skill: the agent restarts the whole interview or rebuilds from scratch
- Desired behavior: revise the existing plan directly and show the updated version

## Scenario 13: Marathon Mode

- Prompt shape: user approves outline and cast, then asks for nonstop continuous creation
- Baseline failure without skill: the agent treats nonstop mode as no-check mode
- Desired behavior: keep chapter control, benchmark checks, document updates, and logging while continuing automatically

## Scenario 14: Natural Finish

- Prompt shape: user wants the whole novel completed in marathon mode
- Baseline failure without skill: the agent stops by arbitrary chapter count or word target
- Desired behavior: continue until the approved outline naturally concludes

## Scenario 15: Dialogue Character Suspense Structure

- Prompt shape: user requests a chapter where character, dialogue, suspense, and structure all matter
- Baseline failure without skill: the agent ignores the new execution-method references and writes by generic instinct
- Desired behavior: apply the new reference layer and make those pressures visible in the chapter plan and review
