# Rule: Final Clean Output

## Purpose

Ensure final responses and generated resources are complete, coherent and ready for the teacher to copy, export, teach, mark or refine. This rule removes unnecessary process commentary from final products and keeps the output focused on the requested deliverable.

## Applies To

- Final answers to the user after drafting, editing, research or review
- Student-facing resources, teacher notes and relief lessons
- Assessment tasks, rubrics, marking guides, feedback and reports
- Word-ready, LMS-ready, spreadsheet-ready and presentation-ready material
- Any generated `.md`, `.docx`, PDF, LMS or copy-and-paste output

## Rule Statement

The agent must produce final output that is clean, complete, usable and aligned with the requested format, without unnecessary commentary, hidden assumptions or distracting extra material.

## Requirements

- Put the requested deliverable first unless the user asked for an explanation or process notes.
- Use clear headings, short paragraphs, lists and tables where they improve scanning and use.
- Remove draft notes, internal reasoning, uncertainty markers and research fragments from final deliverables.
- Include sources, assumptions, limitations or unresolved issues only where they are required for credibility, safety, assessment validity or user decision-making.
- Check that the final output matches the requested audience, year level, subject, format and platform.
- Preserve editable text for equations, code, formulae, commands and file paths.
- When producing an actual Word `.docx`, convert all formulae and equations to Word-native OMML.
- Avoid formatting that will break when pasted into Word, LMS text fields or school systems.
- Keep final summaries concise when the work is complete and the files are already saved.

## Decision Logic

Apply this rule immediately before finalising any response or file. If the user requested a document, resource or file, the resource should read as the finished product rather than a discussion about making it. If the task involved research or verification, include a compact source list or note where needed. If uncertainty remains, state it briefly under an appropriate heading such as `Assumptions`, `Needs human review` or `Limitations`.

## Examples

- For a worksheet request, provide the worksheet content with student-ready headings and instructions, not a paragraph explaining how the worksheet could be written.
- For a marking request, provide the grade or judgement, evidence, feedback and next step in the requested format.
- For a Word-ready draft, use simple headings, plain tables and editable equation source. For an actual `.docx`, use OMML equations.
- For a completed coding or file task, summarise changed files and verification, then stop.

## Non-Examples

- Leaving `draft`, `todo`, `research note` or internal planning comments inside the final resource.
- Adding a long explanation before the actual student worksheet.
- Mixing teacher-facing notes into student-facing instructions without labels.
- Providing complex formatting that needs major cleanup before use.

## Interaction With Skills

- `skills/Core workflow/SKILL_SYNTHESIS.md`
- `skills/Lesson design/SKILL_STUDENT_FACING_TUTORIAL.md`
- `skills/Assessment/SKILL_MARKING_GUIDE.md`
- `skills/Assessment/SKILL_FEEDBACK_COMMENTS.md`
- `skills/Documents/SKILL_WORD_EXPORT_FORMATTING.md`
- `skills/LMS and school systems/SKILL_LMS_READY_OUTPUT.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`

## Quality Check

- Is the requested deliverable complete and easy to use?
- Has unnecessary commentary been removed?
- Are assumptions, sources and limitations included only where useful?
- Does the output match the requested audience and platform?
- Will the formatting survive copying into Word, LMS or another school system?
- Are equations, code, formulae and file paths still editable?
- If producing DOCX, are formulae and equations converted to OMML?

## Sources

- Quick guide: plain language — Australian Government Style Manual — https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language — Accessed 2026-05-16
- Home — Australian Government Style Manual — https://www.stylemanual.gov.au/ — Accessed 2026-05-16
- Performance standards and grades — SACE Board of South Australia — https://www.sace.sa.edu.au/teaching/assessment/performance-standards — Accessed 2026-05-16
