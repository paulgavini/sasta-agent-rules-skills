# Rule: Code Clarity

## Purpose

Ensure code examples are readable, teachable and suitable for students who need to understand, trace, modify and test programs.

## Applies To

- programming tutorials
- worked examples
- debugging activities
- starter code
- answer keys
- teacher notes
- code snippets in Word, LMS or Markdown resources

## Rule Statement

The agent must write and present code for clarity before cleverness, using readable names, consistent structure and learner-appropriate comments.

## Requirements

- Use meaningful names for variables, functions, sprites, objects, files and controls.
- Keep examples short enough for students to trace.
- Introduce one main programming idea at a time unless the user asks for an integrated project.
- Use consistent indentation, spacing and layout.
- Prefer direct, readable logic over compact or advanced syntax for beginners.
- Separate setup, processing and output where this helps comprehension.
- Add comments only where they explain purpose, intent or a non-obvious step.
- Avoid comments that merely repeat the code.
- Avoid unexplained libraries, frameworks, APIs or hidden files.
- Show expected output separately from code.
- Preserve exact syntax in fenced code blocks or other copy-safe formats.
- Match style conventions to the language or platform being used.

## Decision Logic

If code is for students, optimise for reading, tracing and modifying. If code is for teacher automation or production use, still keep naming and structure clear, but allow more advanced patterns when they reduce real complexity. If a concise language feature would confuse the stated audience, use the more explicit version.

## Examples

```python
score = 0

if answer == "A":
    score = score + 1

print("Score:", score)
```

- Use `player_score` rather than `ps` in beginner code.
- Use a short comment such as `# Check whether the player found the key` before a decision block.
- In Scratch instructions, name sprites and broadcasts clearly, such as `message: game over`, rather than `message1`.

## Non-Examples

- Using one-letter variable names in a beginner example without a reason.
- Compressing several ideas into one clever line.
- Including comments like `# add 1` above `score = score + 1`.
- Mixing code and expected output in the same code block.
- Using inconsistent indentation or unexplained helper functions.

## Interaction With Skills

- `rules/Digital technologies/RULE_BEGINNER_PROGRAMMING.md`
- `rules/Digital technologies/RULE_PSEUDOCODE_FIRST.md`
- `rules/Digital technologies/RULE_DEBUGGING_EXPLANATION.md`
- `rules/Document output/RULE_CODE_FORMATTING.md`
- `skills/Digital Technologies/SKILL_PYTHON_INTRO.md`
- `skills/Digital Technologies/SKILL_HTML_CSS.md`
- `skills/Digital Technologies/SKILL_GAMEMAKER_GML.md`

## Quality Check

- Can a student explain what each major line does?
- Are names meaningful and consistent?
- Is the code formatted so indentation and syntax are preserved?
- Are comments purposeful rather than noisy?
- Has advanced syntax been removed or explained?
- Is the expected behaviour or output visible?

## Sources

- PEP 8 - Style Guide for Python Code - Python Software Foundation - https://peps.python.org/pep-0008/ - Accessed 2026-05-17
- Technologies - Australian Curriculum, Assessment and Reporting Authority - https://www.australiancurriculum.edu.au/curriculum-information/understand-this-learning-area/technologies - Accessed 2026-05-17
- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
