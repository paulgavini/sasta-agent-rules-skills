# Rule: No Formatting Collisions

## Purpose

Prevent formatting choices from breaking readability, accessibility, export, copy-paste behaviour or later editing.

## Applies To

- Word-ready output
- DOCX production
- Markdown intended for conversion
- LMS-ready resources
- tables, rubrics and worksheets
- documents containing code, equations or images

## Rule Statement

The agent must avoid combining formatting features in ways that create confusing, inaccessible or fragile documents.

## Requirements

- Do not use multiple formatting cues when one clear structure is enough.
- Avoid combining tables, text boxes, images and manual spacing to force layout.
- Do not use colour as the only marker of meaning.
- Avoid excessive bold, italics, capitals, underlining and highlighting.
- Keep headings, lists, tables, code and equations structurally distinct.
- Do not put long paragraphs inside narrow table cells.
- Avoid nesting lists so deeply that copy-paste becomes unclear.
- Keep code blocks and equations away from auto-formatting that changes symbols.
- For actual DOCX output, convert formulae and equations to OMML rather than relying on pasted source text that Word might auto-format incorrectly.
- Check that teacher notes, student instructions and source notes do not blend together.
- Prefer simple structures that survive export to Word, PDF or LMS.

## Decision Logic

If the formatting makes content harder to scan, copy, edit or convert, simplify it. If the user requests a specific visual style, apply it only after preserving structure, accessibility and editability.

## Examples

- Use a heading plus a short list instead of a shaded text box.
- Use one simple rubric table instead of nested tables.
- Label `Extension` in text rather than relying only on colour.
- Keep code in a code block separate from explanatory bullets.

## Non-Examples

- A heading inside a table cell used as the main document structure.
- Red text as the only sign that a task is optional.
- A worksheet with text boxes, tables and manual spaces controlling all layout.
- Code pasted into proportional font with smart punctuation.
- A dense rubric with merged cells, colour coding and long paragraphs.

## Interaction With Skills

- `skills/Documents/SKILL_DOCX_PRODUCTION.md`
- `skills/Documents/SKILL_WORD_EXPORT_FORMATTING.md`
- `skills/Documents/SKILL_TABLE_FORMATTING.md`
- `skills/Documents/SKILL_CODE_FORMATTING.md`
- `rules/Document output/RULE_EXPORT_READY_STRUCTURE.md`
- `rules/Quality control/RULE_ACCESSIBILITY.md`

## Quality Check

- Is structure doing the work instead of decoration?
- Can the document be copied and edited cleanly?
- Are colour-only meanings avoided?
- Are tables, code and equations distinct?
- If producing DOCX, are formulae and equations OMML?
- Are student and teacher sections visually and structurally separate?
- Will export or conversion preserve meaning?

## Sources

- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
- Tables - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content/tables - Accessed 2026-05-17
- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
