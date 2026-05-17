# Rule: Debugging Explanation

## Purpose

Ensure debugging guidance helps students diagnose, explain and fix problems methodically rather than guessing or replacing the whole program.

## Applies To

- programming tutorials
- debugging worksheets
- code review comments
- teacher answer keys
- student support responses
- Scratch, micro:bit, Python, JavaScript, GameMaker and web-coding tasks

## Rule Statement

The agent must explain debugging as a structured process of comparing expected behaviour with actual behaviour, isolating causes and testing one change at a time.

## Requirements

- Start with the intended behaviour of the program.
- Ask or state what actually happens when the program runs.
- Separate syntax errors, runtime errors and logic errors where appropriate.
- Encourage students to read error messages carefully and identify the relevant line or block.
- Use small test cases to reproduce the problem.
- Change one thing at a time and retest.
- Explain why a fix works, not only what to change.
- Preserve student code where possible instead of replacing it with a full new solution.
- For block-based environments, refer to events, block order, conditions, broadcasts, variables and sprite/object state.
- For text-based code, preserve indentation and exact symbols.
- Avoid shaming language; frame errors as useful evidence.
- In assessment contexts, provide diagnostic prompts before giving direct fixes.

## Decision Logic

If the student needs learning support, guide them through predict, run, compare, locate, fix and retest. If the user asks for a teacher answer key, include likely causes and corrected code. If the task is summative or student-owned, give hints and diagnostic questions unless the user explicitly requests teacher-facing correction.

## Examples

- "Expected: the score increases by 1 when the sprite touches the coin. Actual: it increases many times. Check whether the sprites remain touching across several frames."
- "The error message points to line 4. Look at the indentation under the `if` statement."
- "Test with `age = 12`, `age = 18` and `age = 20` before changing the condition."

## Non-Examples

- Rewriting a student's whole program when one condition is wrong.
- Saying "the code is broken" without explaining what evidence shows the fault.
- Treating all errors as syntax errors.
- Suggesting several fixes at once and making it impossible to know which one worked.
- Ignoring expected behaviour and debugging only by appearance.

## Interaction With Skills

- `rules/Digital technologies/RULE_BEGINNER_PROGRAMMING.md`
- `rules/Digital technologies/RULE_CODE_CLARITY.md`
- `rules/Digital technologies/RULE_PSEUDOCODE_FIRST.md`
- `skills/Digital Technologies/SKILL_PYTHON_INTRO.md`
- `skills/Digital Technologies/SKILL_SCRATCH_PROGRAMMING.md`
- `skills/Digital Technologies/SKILL_GAMEMAKER_GML.md`

## Quality Check

- Is the expected behaviour stated?
- Is the actual behaviour or error message used as evidence?
- Are students guided to isolate the cause?
- Is only one change tested at a time?
- Does the explanation say why the fix works?
- Is the help appropriate for the assessment context?

## Sources

- Technologies - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/curriculum-information/understand-this-learning-area/technologies - Accessed 2026-05-17
- Programming - Digital Technologies Hub - https://www.digitaltechnologieshub.edu.au/media/3nikb2aw/programming_a3_web_f-2.pdf - Accessed 2026-05-17
- Implementation - Grok Academy - https://grokacademy.org/a/curriculum/implementation/ - Accessed 2026-05-17
- Teach explicitly - Australian Education Research Organisation - https://www.edresearch.edu.au/guides-resources/practice-guides/teach-explicitly - Accessed 2026-05-17
