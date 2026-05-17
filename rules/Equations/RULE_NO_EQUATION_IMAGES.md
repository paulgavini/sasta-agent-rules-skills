# Rule: No Equation Images

## Purpose

Prevent equations from being delivered as images when editable, searchable or accessible text is needed.

## Applies To

- Word and DOCX documents
- worksheets and task sheets
- answer keys and worked examples
- LMS posts
- science, maths, chemistry and physics resources
- accessibility review

## Rule Statement

The agent must not use equation images as the default format for formulae or worked examples. Equations should be text-based, editable and accessible wherever possible.

## Requirements

- Use editable text, LaTeX, UnicodeMath or Word-native equations before considering images.
- When producing an actual Word `.docx`, convert formulae and equations to Word-native OMML rather than using equation images or raw source text as the final equation.
- Do not replace an editable equation with a screenshot.
- Do not embed important mathematical content only in an image without text equivalent.
- If an image is unavoidable, include the equation text and a description nearby.
- Keep variables, units and symbol definitions in text.
- Avoid image-based equations in assessment materials where students or teachers need to copy, edit or verify them.
- Preserve raw equation source when exporting or converting.
- Keep raw equation source only as an optional labelled reference in DOCX outputs; the working equation itself must be OMML.
- Flag platform limits if LMS or Word cannot render a complex equation cleanly.
- Use simple text-safe equations when that is more reliable for the destination.
- Check accessibility before finalising equation-heavy resources.

## Decision Logic

Use an equation image only when the user explicitly wants a visual or the target platform cannot render the equation any other way. Even then, provide editable source text alongside it. For DOCX production, prefer OMML and treat images as exceptional supporting visuals only.

## Examples

- Provide `v = d / t` as text, not an image.
- Provide raw LaTeX plus a note for Word conversion.
- Produce a DOCX with native OMML equations.
- Add `Alt text: kinetic energy equals one half times mass times velocity squared` if an image is unavoidable.

## Non-Examples

- A worksheet where every equation is a screenshot.
- A formula image with no text equivalent.
- An answer key that cannot be edited because equations are flattened.
- A PDF-only equation pasted into Word with no source.
- A DOCX where formulae are screenshots or raw LaTeX instead of OMML.

## Interaction With Skills

- `skills/Documents/SKILL_EQUATION_FORMATTING.md`
- `skills/Documents/SKILL_DOCX_PRODUCTION.md`
- `rules/Equations/RULE_EQUATION_EDITABILITY.md`
- `rules/Equations/RULE_LATEX_PRESERVATION.md`
- `rules/Document output/RULE_WORD_FORMATTING.md`
- `rules/Quality control/RULE_ACCESSIBILITY.md`

## Quality Check

- Is the equation available as editable text?
- If producing DOCX, is the equation converted to OMML?
- Is any image supported by text equivalent?
- Are variables and units searchable and copyable?
- Is the format suitable for Word or LMS?
- Are accessibility needs met?
- Are platform limitations stated?

## Sources

- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Linear format equations using UnicodeMath and LaTeX in Word - Microsoft Support - https://support.microsoft.com/en-au/office/linear-format-equations-using-unicodemath-and-latex-in-word-2e00618d-b1fd-49d8-8cb4-8d17f25754f8 - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
