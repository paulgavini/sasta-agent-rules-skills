# Rule: Accessibility

## Purpose

Ensure generated resources are usable by students, teachers and families with diverse language, literacy, disability, technology and access needs.

## Applies To

- student-facing worksheets, tutorials and LMS posts
- teacher notes, assessment tasks and rubrics
- tables, diagrams, links, images and multimedia instructions
- Word-ready, LMS-ready and screen-readable output
- parent, carer and staff communication

## Rule Statement

The agent must create accessible, inclusive and readable content by default, and must avoid formatting or language choices that create unnecessary barriers.

## Requirements

- Use clear headings, logical order and short sections.
- Use plain language unless technical vocabulary is required for learning.
- Define essential technical terms when students need them.
- Avoid relying on colour alone to convey meaning.
- Use meaningful link text rather than bare URLs where the format allows.
- Provide alt text or text descriptions when images or diagrams are essential.
- Keep tables simple, with clear headers and no unnecessary merged-cell complexity.
- Avoid dense blocks of text in student-facing materials.
- Preserve editable text for equations, code, formulae and instructions.
- For actual DOCX output, use Word-native OMML for formulae and equations so they remain editable Word equations.
- Consider low-bandwidth, small-screen, printed and LMS-copy contexts where relevant.

## Decision Logic

If an accessibility choice could slightly lengthen the output but make it more usable, choose accessibility. If the user asks for a format that may create barriers, keep the requested format but reduce avoidable barriers. If a student-facing output includes images, colour coding, audio or video, provide an equivalent text pathway where practical.

## Examples

- A worksheet uses clear task headings and step-by-step instructions.
- A graph activity describes what students should inspect rather than saying only "look at the red line".
- A rubric table has concise descriptors and clear criterion names.
- A video task includes a transcript or key prompts when needed.

## Non-Examples

- Using colour alone to indicate correct and incorrect answers.
- Writing long unbroken paragraphs for junior students.
- Creating complex tables that will not paste cleanly into Word or an LMS.
- Using vague link text such as `click here`.
- Providing an image of an equation instead of editable equation text or OMML in a DOCX.

## Interaction With Skills

- `skills/Documents/SKILL_DOCX_PRODUCTION.md`
- `skills/Documents/SKILL_TABLE_FORMATTING.md`
- `skills/LMS and school systems/SKILL_LMS_READY_OUTPUT.md`
- `skills/Lesson design/SKILL_STUDENT_FACING_TUTORIAL.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`

## Quality Check

- Is the structure easy to navigate?
- Is the language clear for the audience?
- Are tables, links, images and colour use accessible?
- Can the content be copied into Word or an LMS without major loss?
- Are essential visual or media elements described in text?
- Are equations, code and formulae editable?
- If producing DOCX, are formulae and equations OMML rather than images or raw source text?

## Sources

- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Inclusive language - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/inclusive-language - Accessed 2026-05-17
