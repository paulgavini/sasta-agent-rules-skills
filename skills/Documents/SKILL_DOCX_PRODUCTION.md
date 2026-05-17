# Skill: DOCX Production

## Purpose

This skill allows the agent to prepare classroom, assessment and communication content for Microsoft Word or DOCX production with clean structure, editable text and accessible formatting.

## When To Use

Use this skill when the user asks for:

- a Word document
- DOCX-ready content
- a worksheet, task sheet or lesson plan for Word
- a rubric, marking guide or report-ready document
- content that should later be exported to PDF
- conversion from Markdown or notes into a structured document

## Inputs

- document purpose and audience
- required sections or school template
- student-facing and teacher-facing content
- tables, rubrics, code, equations or images
- source, bibliography or appendix requirements
- page, font, heading or accessibility preferences
- export target such as DOCX, PDF, LMS or print

## Process

1. Confirm whether the user needs an actual DOCX file, Word-ready Markdown, or content to paste into Word.
2. Structure the document with one title and logical headings.
3. Keep text editable; do not turn body text, equations, tables or code into images.
4. Convert all formulae and equations in the produced `.docx` to Word-native OMML.
5. Preserve raw LaTeX or UnicodeMath only as optional labelled source text when the user needs it; do not use raw source as the final equation inside the `.docx`.
6. Use simple lists and tables that can survive Word export.
7. Keep student-facing, teacher-facing, source and appendix sections clearly separated.
8. Format equations, code and tables according to their specific rules.
9. Add image descriptions or alt text notes when images carry meaning.
10. Check accessibility, heading order, link clarity, colour-independent meaning and OMML equation editability.
11. Check that document content matches the user's requested audience and use.
12. State any export, template, accessibility or local formatting checks still needed.

## Output

```markdown
# Document Title

## Purpose Or Context

## Main Content

## Student Instructions

## Teacher Notes

## Tables Or Appendices

## Sources

## Assumptions And Local Checks
```

Adjust sections to the document type. Do not include empty sections unless the user needs placeholders.

## Quality Criteria

- The document has a clear structure.
- Text remains editable.
- Headings and tables are accessible.
- Student and teacher material are separated.
- Code and equations remain copyable or editable.
- Formulae and equations in actual DOCX files are OMML.
- Sources and assumptions are visible where required.
- The output is ready for Word production or clearly states what remains.

## Related Rules

- `rules/Document output/RULE_EXPORT_READY_STRUCTURE.md`
- `rules/Document output/RULE_WORD_FORMATTING.md`
- `rules/Document output/RULE_HEADING_STYLES.md`
- `rules/Document output/RULE_TABLE_STYLE.md`
- `rules/Document output/RULE_NO_FORMATTING_COLLISIONS.md`
- `rules/Quality control/RULE_ACCESSIBILITY.md`

## Example User Requests

- `Create a Word-ready Year 8 worksheet.`
- `Turn this assessment into a DOCX structure.`
- `Make this lesson plan suitable for Word export.`
- `Prepare a rubric and task sheet for a Word document.`

## Failure Modes

- Making a visually attractive document that is hard to edit.
- Using fake headings or layout-only tables.
- Mixing teacher notes into student instructions.
- Losing code indentation or equation editability.
- Leaving formulae as raw LaTeX, UnicodeMath or images in an actual DOCX instead of OMML.
- Omitting sources, assumptions or local checks when required.
- Over-formatting content before the structure is sound.

## Completion Checklist

- Is the required document type clear?
- Are headings logical?
- Is all content editable?
- Are tables, code and equations formatted safely?
- Are all DOCX formulae and equations converted to OMML?
- Are accessibility issues checked?
- Are unresolved export checks stated?

## Sources

- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
