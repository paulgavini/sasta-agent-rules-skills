# Rule: Equation Editability

## Purpose

Ensure equations and formulae remain editable, reusable and suitable for Word, Markdown, LMS or assessment contexts.

## Applies To

- science and mathematics worksheets
- physics and chemistry worked examples
- Word-ready and DOCX outputs
- answer keys and marking guides
- equation-heavy tutorials
- formulae in tables or explanations

## Rule Statement

The agent must preserve equations in editable form rather than flattening them into images or ambiguous plain text. When producing an actual Word `.docx`, all equations and formulae must be converted to Word-native Office Math Markup Language (OMML).

## Requirements

- Use editable equation formats when the user needs Word, DOCX, revision or future modification.
- When creating or exporting an actual `.docx`, convert every equation and each formula to OMML so it opens as a native Word equation.
- Do not leave LaTeX, UnicodeMath, plain-text fractions or equation images as the final equation format inside a produced `.docx` unless the user explicitly asks to preserve raw source as an additional reference.
- If providing Word-ready Markdown rather than an actual `.docx`, preserve the source equation and state that the DOCX production step must convert it to OMML.
- Preserve subscripts, superscripts, fractions, Greek letters, operators and brackets.
- Keep variable names and units visually distinct.
- Use display equations for multi-step or central formulae.
- Use inline equations only when they remain readable.
- Avoid screenshots or image-based equations unless the user explicitly asks for a visual only.
- For Word-ready draft output, note whether the source equation is intended for Word equation editor, UnicodeMath or LaTeX conversion before OMML production.
- For final DOCX output, verify or flag whether the equation is actually stored as OMML rather than merely displayed as text.
- Check that copied equation text will not be damaged by smart punctuation or auto-formatting.
- Flag any conversion uncertainty rather than promising perfect Word rendering.
- Keep equations age-appropriate and aligned with the task.

## Decision Logic

If students or teachers need to edit, copy, assess or adapt the equation, keep it editable. If producing DOCX, the editable target is OMML. If a platform cannot preserve a complex equation, provide a simpler text-safe version and state the limitation.

## Examples

- `F = ma`
- `v = d / t`
- `E_k = \frac{1}{2}mv^2`
- Word-ready note: `Convert this equation to OMML in the DOCX production step.`

## Non-Examples

- Pasting an equation as an image into a worksheet.
- Delivering a DOCX where equations remain as raw LaTeX text instead of OMML.
- Replacing a fraction with ambiguous text such as `1/2mv^2` without spacing or explanation.
- Changing chemical subscripts during formatting.
- Claiming Word conversion is verified when it was not checked.

## Interaction With Skills

- `skills/Documents/SKILL_EQUATION_FORMATTING.md`
- `skills/Documents/SKILL_DOCX_PRODUCTION.md`
- `skills/Physics/SKILL_PHYSICS_WORKED_EXAMPLES.md`
- `skills/Chemistry/SKILL_CHEMICAL_EQUATIONS.md`
- `rules/Equations/RULE_LATEX_PRESERVATION.md`
- `rules/Equations/RULE_NO_EQUATION_IMAGES.md`

## Quality Check

- Is the equation editable?
- If producing DOCX, is every equation stored as OMML?
- Are symbols, subscripts and superscripts preserved?
- Is the intended Word or Markdown format clear?
- Are units and variables distinct?
- Are conversion limits stated?
- Is the notation suitable for the audience?

## Sources

- Linear format equations using UnicodeMath and LaTeX in Word - Microsoft Support - https://support.microsoft.com/en-au/office/linear-format-equations-using-unicodemath-and-latex-in-word-2e00618d-b1fd-49d8-8cb4-8d17f25754f8 - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
- Office Open XML Math elements - Microsoft Learn - https://learn.microsoft.com/en-us/openspecs/office_standards/ms-oe376/83056bdc-cabe-41b4-9b4c-6e7c6bd1edc7 - Accessed 2026-05-17
- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
- Australia's measurement system - Department of Industry, Science and Resources - https://www.industry.gov.au/national-measurement-institute/australias-measurement-system - Accessed 2026-05-17
