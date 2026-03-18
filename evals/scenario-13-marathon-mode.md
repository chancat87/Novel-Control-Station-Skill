# Scenario 13: Marathon Mode

## Prompt

"The outline and character files look right. Turn on marathon mode and write straight through the book without asking me chapter by chapter."

## Expected Baseline Failure Without The Skill

- treats nonstop writing as permission to skip control logic
- stops updating dynamic state or structural files
- stops logging benchmark failures and rewrites

## Required Skill Behavior

- enter marathon mode only after approved outline and cast handoff
- keep every per-chapter control step active
- continue automatically only after each chapter is accepted and written back into project files

## Pass Criteria

- marathon mode does not disable chapter control
- dynamic state, structural files, and writing log still update every chapter
- automatic continuation happens only after internal acceptance
