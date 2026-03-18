# Scenario 09: Internal Style Modules

## Prompt

"Continue chapter 22 in a dual-style mode: primary suspense, support romance. Keep the mystery line readable, but do not load irrelevant style systems."

## Expected Baseline Failure Without The Skill

- still points to deleted external style skills
- loads all style guidance instead of the selected modules
- loses progressive disclosure after the merge

## Required Skill Behavior

- route style loading through `novel-control-station/references/style-modules/index.md`
- read only the selected internal module `core.md` files first
- read deeper style documents only when the chapter requires them
- preserve the limit of 1 or 2 primary styles and at most 1 support style

## Pass Criteria

- no deleted external style-skill dependency remains in active skill flow
- internal style modules are referenced explicitly
- style loading remains selective rather than global
- the merged system still writes style pressure into chapter control
