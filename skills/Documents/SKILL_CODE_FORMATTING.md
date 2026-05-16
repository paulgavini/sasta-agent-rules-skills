# Skill: Code Formatting

## Purpose

This skill allows the agent to format code, pseudocode, commands and expected output so they are readable, copyable and suitable for student resources, teacher notes and Word-ready documents.

## When To Use

Use this skill when the user asks for:

- formatted code examples
- programming worksheets or tutorials
- pseudocode for students
- command-line instructions
- debugging guides
- Word-ready code formatting
- cleaning code copied from another source

## Inputs

- programming language or pseudocode style
- year level and learner experience
- target format: Markdown, Word, LMS or print
- code, expected output and explanation
- whether students need to copy, edit or merely read the code
- platform constraints such as Scratch, Python, GameMaker or HTML/CSS

## Process

1. Identify the language and student level.
2. Preserve exact code syntax, indentation, spacing and symbols.
3. Use fenced code blocks for multi-line code in Markdown.
4. Use inline code for variables, filenames, operators and short commands.
5. Add a language label to code fences where known.
6. Separate code, explanation, expected output and student tasks.
7. Avoid smart quotes and auto-corrected punctuation.
8. Keep examples short enough for the intended learner.
9. For Word-ready output, specify monospace formatting and preserve indentation.
10. Check syntax or state what has not been tested.

## Output

````markdown
## Example Code

```python
print("Hello")
```

## What It Does

## Your Turn

## Expected Output
````

Adjust language labels and headings to suit the task.

## Quality Criteria

- Code is copyable.
- Indentation is preserved.
- Explanations do not interrupt the code block.
- Expected output is clearly labelled.
- Examples are appropriate for the learner.
- Syntax and formatting risks are checked.

## Related Rules

- `rules/Document output/RULE_CODE_FORMATTING.md`
- `rules/Document output/RULE_WORD_FORMATTING.md`
- `rules/Digital technologies/RULE_CODE_CLARITY.md`
- `rules/Digital technologies/RULE_BEGINNER_PROGRAMMING.md`
- `rules/Digital technologies/RULE_PSEUDOCODE_FIRST.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`

## Example User Requests

- `Format this Python code for a worksheet.`
- `Make this pseudocode student-friendly.`
- `Put this command sequence into a Word-ready format.`
- `Separate the expected output from the code.`

## Failure Modes

- Breaking indentation.
- Replacing code punctuation with smart punctuation.
- Mixing output and code in one unlabelled block.
- Giving examples too advanced for the year level.
- Presenting untested code as verified.
- Using screenshots where editable code is needed.

## Completion Checklist

- Is the language identified?
- Is syntax preserved?
- Is code separated from explanation?
- Is the example learner-appropriate?
- Is expected output labelled?
- Are testing or verification limits stated?

## Sources

- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
