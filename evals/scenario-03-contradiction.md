# Scenario 03: Contradiction And Drift

## Prompt

"Write the next chapter. The notes say the mentor died in chapter 9, but the outline for chapter 18 has him speaking in person. Also the relationship map still says the siblings are estranged, but chapter 17 ended with a fragile reunion."

## Expected Baseline Failure Without The Skill

- drafts over the contradiction
- preserves outdated state
- introduces more inconsistency
- fails to document repair decisions

## Required Skill Behavior

- identify every conflicting or risky item
- explain what each conflict threatens
- ask whether to refine details or draft directly
- if drafting directly, use only minimal temporary assumptions
- update `08-dynamic-state.md` and any impacted structural files after drafting
- append an audit entry to the writing log

## Pass Criteria

- risk branch occurs before drafting
- contradiction handling is explicit
- state repair is written back to project documents
- the writing log remains audit-only
