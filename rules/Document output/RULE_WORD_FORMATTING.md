# Rule: Word Formatting

## Purpose

Ensure content intended for Microsoft Word is simple, editable, accessible and resistant to formatting breakage.

## Applies To

- DOCX production
- Word-ready Markdown
- worksheets and task sheets
- reports and parent-facing documents
- assessment documents and rubrics
- teacher notes and lesson plans

## Rule Statement

The agent must prefer editable Word-native structure and simple formatting over fragile visual layout.

## Requirements

- Use built-in heading styles when producing or preparing Word documents.
- Keep body text as editable text, not images.
- Use simple tables with header rows where tables are necessary.
- Avoid text boxes, floating shapes, decorative WordArt and layout-only tables unless explicitly required.
- Keep fonts, spacing and styles consistent.
- Use clear link text rather than raw URLs where the destination is known and the format allows it.
- Include alt text or image descriptions when images carry meaning.
- Avoid placing essential information only in headers, footers or decorative elements.
- Preserve equations, code and tables in editable forms where possible.
- When producing an actual `.docx`, convert all formulae and equations to Word-native OMML.
- Do not leave raw LaTeX, raw UnicodeMath, screenshots or ambiguous plain-text equations as the final formulae format in a produced `.docx`.
- Run or recommend accessibility checks when producing final Word documents.

## Decision Logic

If the user needs a Word file, prioritise editability, accessibility and OMML equations. If the user only needs content to paste into Word, use clean Markdown that maps naturally to Word headings, lists and tables, and mark equations that must become OMML during DOCX production.

## Examples

- Use heading levels for title and sections.
- Keep a rubric as an editable table.
- Convert physics formulae to OMML when producing the DOCX file.
- Put instructions in normal paragraphs and lists.
- Add a short image description after a diagram if alt text cannot be embedded.

## Non-Examples

- Exporting worksheet text as a screenshot.
- Using a table only to align two blocks of text.
- Manually styling headings with bold and large font instead of heading styles.
- Putting key instructions inside a footer.
- Using coloured text as the only sign of required work.
- Producing a DOCX with equation screenshots or raw LaTeX where Word-native OMML equations are required.

## Interaction With Skills

- `skills/Documents/SKILL_DOCX_PRODUCTION.md`
- `skills/Documents/SKILL_WORD_EXPORT_FORMATTING.md`
- `skills/Documents/SKILL_TABLE_FORMATTING.md`
- `rules/Document output/RULE_HEADING_STYLES.md`
- `rules/Document output/RULE_NO_FORMATTING_COLLISIONS.md`
- `rules/Quality control/RULE_ACCESSIBILITY.md`

## Quality Check

- Is the content editable in Word?
- Are formulae and equations in DOCX output converted to OMML?
- Are headings, tables and lists Word-friendly?
- Are styles consistent?
- Are images and links accessible?
- Is essential information in the main document body?
- Are fragile layout features avoided?

## Sources

- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Create more accessible Word documents - Microsoft Support - https://support.microsoft.com/en-us/office/create-more-accessible-word-documents-0b2ca649-69a5-4d3b-9ff5-a56e6611d194 - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
