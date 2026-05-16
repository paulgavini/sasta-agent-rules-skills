# Rule: Code Formatting

## Purpose

Ensure code, pseudocode and command examples remain readable, copyable, editable and suitable for beginner learners or teacher resources.

## Applies To

- programming tutorials
- digital technologies worksheets
- pseudocode examples
- command-line instructions
- answer keys and debugging guides
- Word-ready and Markdown documents

## Rule Statement

The agent must format code as code, preserve indentation and avoid document formatting that changes meaning or prevents copying.

## Requirements

- Use fenced code blocks in Markdown when showing multi-line code.
- Add a language label to code fences when known.
- Preserve indentation, spacing and line breaks exactly where they affect meaning.
- Use inline code formatting for short commands, filenames, operators and variable names.
- Keep beginner examples short and focused.
- Separate code from explanation and expected output.
- Avoid smart quotes, auto-corrected symbols or decorative formatting inside code.
- Do not place code inside screenshots when editable code is needed.
- For Word output, use a consistent monospace style for code.
- Check code examples for syntax and learner suitability where possible.

## Decision Logic

Use code blocks for anything students may copy or compare line by line. Use inline code for terms inside a sentence. If the destination may mangle code, include a warning or provide a plain-text-safe version.

## Examples

```python
for count in range(5):
    print(count)
```

- Use `variable = 10` as inline code in an explanation.
- Label expected output separately from code.
- Keep Scratch block descriptions as steps if block images are not available.

## Non-Examples

- Replacing indentation with bullet points in Python code.
- Using curly quotes inside copied commands.
- Showing code only as an image.
- Mixing expected output into the same code block without a label.
- Wrapping long lines so they become ambiguous.

## Interaction With Skills

- `skills/Documents/SKILL_CODE_FORMATTING.md`
- `skills/Digital Technologies/SKILL_PYTHON_INTRO.md`
- `skills/Digital Technologies/SKILL_HTML_CSS.md`
- `skills/Digital Technologies/SKILL_SCRATCH_PROGRAMMING.md`
- `rules/Digital technologies/RULE_CODE_CLARITY.md`
- `rules/Document output/RULE_WORD_FORMATTING.md`

## Quality Check

- Is the code copyable?
- Is indentation preserved?
- Are code and explanation separated?
- Are syntax and symbols correct?
- Is the example appropriate for the year level?
- Will Word or LMS formatting damage the code?

## Sources

- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
