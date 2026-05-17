# Skill: Word Export Formatting

## Purpose

This skill allows the agent to prepare Markdown or drafted content so it exports cleanly to Microsoft Word, Google Docs, PDF or LMS without avoidable formatting damage.

## When To Use

Use this skill when the user asks for:

- Word-ready formatting
- content suitable for export
- Markdown that will become a document
- clean headings, tables, lists or page-ready structure
- fixing formatting before DOCX or PDF production
- making a document easier to edit after export

## Inputs

- source content or draft
- target format: Word, DOCX, PDF, Google Docs, LMS or print
- required school template or style preferences
- tables, equations, code, images or links
- audience and document purpose
- accessibility or copy-paste requirements

## Process

1. Identify the export target and likely conversion risks.
2. Convert fake headings into real Markdown heading structure.
3. Simplify layout-dependent structures such as nested tables, text boxes or manual spacing.
4. Keep lists, tables, code blocks and equations structurally distinct.
5. If exporting to an actual `.docx`, convert all formulae and equations to Word-native OMML.
6. If preparing Word-ready Markdown only, preserve equation source and clearly mark that DOCX production must convert it to OMML.
7. Shorten or split tables that are too wide for the destination.
8. Use clear link text and avoid bare URLs unless the user needs them.
9. Add image descriptions or alt text notes for meaningful images.
10. Check that required versus extension work is labelled in text, not colour alone.
11. Preserve exact code, equations, units and technical notation.
12. Report any formatting features that still need checking inside Word, including OMML conversion if not verified.

## Output

```markdown
# Export-Ready Version

## Formatting Notes

## Content

## Checks Still Needed In Word
```

For simple tasks, return only the cleaned content plus brief notes.

## Quality Criteria

- Content has a stable heading hierarchy.
- Formatting is simple enough to survive export.
- Tables, code and equations remain editable.
- DOCX formulae and equations are OMML.
- Accessibility risks are reduced.
- Visual styling does not carry meaning alone.
- Remaining Word-specific checks are explicit.

## Related Rules

- `rules/Document output/RULE_EXPORT_READY_STRUCTURE.md`
- `rules/Document output/RULE_WORD_FORMATTING.md`
- `rules/Document output/RULE_HEADING_STYLES.md`
- `rules/Document output/RULE_TABLE_STYLE.md`
- `rules/Document output/RULE_NO_FORMATTING_COLLISIONS.md`
- `rules/Equations/RULE_EQUATION_EDITABILITY.md`

## Example User Requests

- `Make this Markdown Word-ready.`
- `Clean this worksheet before I export it to PDF.`
- `Fix the heading and table structure for Word.`
- `Prepare this rubric for copying into Google Docs.`

## Failure Modes

- Optimising for screen appearance while breaking editability.
- Leaving fake headings and layout-only tables.
- Losing code indentation during formatting.
- Using colour as the only signal.
- Failing to mention checks that must happen in Word itself.
- Exporting to DOCX while leaving formulae as images, raw LaTeX or raw UnicodeMath instead of OMML.

## Completion Checklist

- Is the target export format clear?
- Are headings structural?
- Are layout risks simplified?
- Are tables, code and equations preserved?
- If producing DOCX, are formulae and equations converted to OMML?
- Are accessibility issues checked?
- Are Word-only checks listed?

## Sources

- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Create more accessible Word documents - Microsoft Support - https://support.microsoft.com/en-us/office/create-more-accessible-word-documents-0b2ca649-69a5-4d3b-9ff5-a56e6611d194 - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
