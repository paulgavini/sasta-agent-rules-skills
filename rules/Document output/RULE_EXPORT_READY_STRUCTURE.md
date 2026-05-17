# Rule: Export Ready Structure

## Purpose

Ensure Markdown, Word-ready and document-ready outputs have a clean structure that can be copied, exported or converted without avoidable rework.

## Applies To

- Word-ready resources
- DOCX production
- worksheets and task sheets
- lesson plans and teacher notes
- assessment documents and rubrics
- Markdown intended for conversion
- LMS content that may be pasted into documents

## Rule Statement

The agent must structure document outputs with clear headings, logical order, simple blocks and minimal formatting assumptions so the content remains usable across Markdown, Word and exported formats.

## Requirements

- Use a clear title and predictable section order.
- Use headings to show structure rather than bold text alone.
- Keep paragraphs short and scannable.
- Use lists, tables and callouts only when they make the content easier to use.
- Avoid nested tables, text boxes, decorative layout tricks or fragile formatting.
- Keep teacher-facing and student-facing sections clearly labelled.
- Place instructions, evidence, criteria and notes in separate sections where relevant.
- Ensure sources, assumptions and local checks are included when required.
- Avoid relying on colour, spacing or visual position as the only meaning.
- Leave output clean enough for copy-paste into Word, Google Docs or LMS.
- When the destination is an actual DOCX file, structure equation content so formulae can be converted to OMML and do not rely on images or plain-text approximations.

## Decision Logic

If the user asks for a document, task sheet, worksheet or export-ready output, prioritise structure over visual decoration. If the destination is unknown, use simple Markdown headings and tables that can survive conversion.

## Examples

- Use `# Title`, `## Student Instructions`, `## What To Submit`, `## Teacher Notes`.
- Put a rubric in a simple table with clear column headings.
- Put source notes at the end under `## Sources`.
- Use labelled assumptions rather than hidden notes in parentheses.

## Non-Examples

- A worksheet made from large unlabelled blocks of text.
- Using bold lines as fake headings throughout a document.
- Relying on coloured text to signal required versus extension work.
- Putting teacher notes inside student instructions without labels.
- Using tables only to force page layout.

## Interaction With Skills

- `skills/Documents/SKILL_DOCX_PRODUCTION.md`
- `skills/Documents/SKILL_EQUATION_FORMATTING.md`
- `skills/Documents/SKILL_WORD_EXPORT_FORMATTING.md`
- `skills/Lesson design/SKILL_STUDENT_FACING_TUTORIAL.md`
- `skills/Assessment/SKILL_ASSESSMENT_TASK_DESIGN.md`
- `rules/Document output/RULE_HEADING_STYLES.md`
- `rules/Quality control/RULE_COMPLETENESS_CHECK.md`

## Quality Check

- Is the document structure obvious?
- Are headings real and logically ordered?
- Can the output be copied or converted cleanly?
- Are student and teacher sections separated?
- Are tables used only where they help?
- Are sources and assumptions easy to find?

## Sources

- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
