# Skill: Table Formatting

## Purpose

This skill allows the agent to create, clean or review tables so they are readable, accessible, editable and suitable for Markdown, Word, LMS or spreadsheet-adjacent use.

## When To Use

Use this skill when the user asks for:

- a rubric table
- a lesson sequence table
- a data table template
- a source register or progress table
- a table cleaned for Word or LMS
- converting a dense table into a clearer format
- checking whether a table should be a list instead

## Inputs

- table purpose and audience
- destination format: Markdown, Word, LMS, spreadsheet or print
- required columns or criteria
- expected row count and cell length
- accessibility or width constraints
- whether users will fill in the table
- related rubric, assessment or source-register requirements

## Process

1. Confirm what the table helps users compare, record or decide.
2. Use a list instead if the information is short, sequential or not genuinely tabular.
3. Choose concise column headings.
4. Keep cells short; split dense content into notes below the table if needed.
5. Avoid merged cells, nested tables and blank structural cells.
6. Keep the table narrow enough for the destination.
7. Use consistent wording and grammar across rows.
8. For student fill-in tables, leave enough space or use clear prompts.
9. For rubrics, align rows and columns to evidence students can produce.
10. Check copy-paste and export risks before finalising.

## Output

```markdown
| Column 1 | Column 2 | Column 3 |
| --- | --- | --- |
|  |  |  |
```

Add a short note before or after the table if needed for context, assumptions or use.

## Quality Criteria

- The table has a clear purpose.
- Column headings are meaningful.
- Cell content is concise.
- The table is editable and export-safe.
- Accessibility and width are considered.
- A list is used instead when more appropriate.

## Related Rules

- `rules/Document output/RULE_TABLE_STYLE.md`
- `rules/Document output/RULE_EXPORT_READY_STRUCTURE.md`
- `rules/Document output/RULE_NO_FORMATTING_COLLISIONS.md`
- `rules/Quality control/RULE_ACCESSIBILITY.md`
- `skills/Assessment/SKILL_RUBRIC_DESIGN.md`
- `skills/Lesson design/SKILL_LESSON_SEQUENCE_PLANNING.md`

## Example User Requests

- `Make this rubric table clearer.`
- `Create a data table template for a Year 8 practical.`
- `Turn this lesson sequence into a table.`
- `Clean this source register table.`

## Failure Modes

- Using tables for page layout.
- Creating wide tables that will not fit in Word.
- Putting long paragraphs in every cell.
- Using merged cells that break export.
- Leaving unclear or repeated column headings.
- Making a student table too dense to use.

## Completion Checklist

- Does a table suit the information?
- Are headings clear?
- Is the table simple and narrow enough?
- Are cells concise?
- Are merged and nested cells avoided?
- Is the table ready for the target format?

## Sources

- Tables - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content/tables - Accessed 2026-05-17
- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
