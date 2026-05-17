# Rule: Pseudocode First

## Purpose

Support students to plan algorithms before implementation when a task has enough complexity that jumping straight into syntax would hide the thinking.

## Applies To

- beginner and intermediate programming tasks
- algorithm design worksheets
- debugging and tracing activities
- assessment planning scaffolds
- teacher notes for Digital Technologies
- tasks involving flowcharts, pseudocode or test cases

## Rule Statement

The agent must use pseudocode, flowcharts or plain-language algorithms before code when this helps students define the problem, sequence the logic and check expected behaviour.

## Requirements

- Start with the problem, goal, inputs, outputs and rules.
- Use pseudocode for logic, not for decorative pre-writing.
- Keep pseudocode close enough to the target language that students can translate it.
- Use indentation to show decisions, loops and nested logic.
- Pair pseudocode with at least one test case where appropriate.
- Avoid language-specific syntax unless it helps bridge to the implementation.
- For very simple tasks, allow a short spoken or written algorithm instead of a full pseudocode block.
- For visual programming, allow block plans, flowcharts, event tables or step lists.
- Do not require pseudocode after the code has already been supplied unless the task is about tracing or explanation.
- In assessment contexts, ensure planning scaffolds are allowed and do not provide the complete solution.

## Decision Logic

Use pseudocode first when the task includes branching, loops, functions, user input, validation, data handling or multiple screens. Skip or shorten it when the program is only a few obvious lines and planning would add unnecessary load. If students are stuck on syntax, return to pseudocode to separate logic from language rules.

## Examples

```text
ASK for age

IF age is 18 or more
    SHOW "You can enrol"
ELSE
    SHOW "Ask a parent or carer"
END IF
```

- A game task lists events first: when start is clicked, set score to 0; when player touches coin, add 1 to score.
- A data task identifies inputs, calculation and output before writing formulas or code.
- A flowchart is used when decisions and loops are easier to see visually.

## Non-Examples

- Writing pseudocode that is longer and harder to read than the program.
- Using pseudocode as a rigid template for every tiny code snippet.
- Including Python-specific punctuation in pseudocode before students know what it means.
- Treating pseudocode as an assessed final product when the task asks for a working program.
- Giving students complete pseudocode for a summative task that is meant to assess algorithm design.

## Interaction With Skills

- `rules/Digital technologies/RULE_BEGINNER_PROGRAMMING.md`
- `rules/Digital technologies/RULE_CODE_CLARITY.md`
- `rules/Digital technologies/RULE_DEBUGGING_EXPLANATION.md`
- `skills/Digital Technologies/SKILL_PYTHON_INTRO.md`
- `skills/Digital Technologies/SKILL_SCRATCH_PROGRAMMING.md`
- `skills/Digital Technologies/SKILL_GAMEMAKER_GML.md`

## Quality Check

- Does the pseudocode clarify the logic?
- Are inputs, outputs and decisions visible?
- Is it easier to translate into code than starting from scratch?
- Are loops and branches indented clearly?
- Is the level of planning proportional to the task?
- Does the scaffold preserve student ownership in assessment work?

## Sources

- Technologies - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/curriculum-information/understand-this-learning-area/technologies - Accessed 2026-05-17
- Program design - Digital Technologies Hub - https://www.digitaltechnologieshub.edu.au/search/program-design/ - Accessed 2026-05-17
- Teach explicitly - Australian Education Research Organisation - https://www.edresearch.edu.au/guides-resources/practice-guides/teach-explicitly - Accessed 2026-05-17
