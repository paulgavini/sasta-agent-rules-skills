# Rule: LaTeX Preservation

## Purpose

Ensure LaTeX or LaTeX-like equation text supplied by the user is preserved accurately unless the user explicitly asks for conversion.

## Applies To

- equations in Markdown
- Word equation preparation
- DOCX production where LaTeX source must become OMML
- physics and chemistry formulae
- worked examples
- assessment materials
- source files containing LaTeX notation

## Rule Statement

The agent must not casually rewrite, simplify or "prettify" LaTeX in ways that change mathematical meaning or break future conversion.

## Requirements

- Preserve user-supplied LaTeX exactly when editability or conversion matters.
- When the final output is an actual `.docx`, use the preserved LaTeX only as source material and convert the final Word equation to OMML.
- If the user needs the raw LaTeX retained, include it as labelled source text in addition to the OMML equation, not instead of the OMML equation.
- Keep braces, commands, subscripts, superscripts, fractions, arrays and alignment syntax intact.
- Do not replace LaTeX commands with approximate plain text unless requested.
- Do not convert LaTeX to an image.
- If changing notation for clarity, explain the change or keep the original alongside the converted form.
- Use fenced code blocks or inline code when showing raw LaTeX.
- Use rendered-style explanation only when it does not replace the raw source needed by the user.
- Flag Word compatibility limits for advanced LaTeX commands.
- Flag any LaTeX-to-OMML conversion uncertainty before claiming the DOCX equation is final.
- Avoid mixing UnicodeMath and LaTeX in one equation unless the user requests it.
- Check that Markdown escaping does not hide or alter backslashes.

## Decision Logic

If the user supplies LaTeX, assume it is meaningful source text. Preserve it first, then provide converted or student-friendly versions separately if helpful. For final DOCX production, the converted equation must be OMML.

## Examples

- Preserve raw: `E_k = \frac{1}{2}mv^2`
- Preserve raw: `CO_2`
- Provide both raw and display explanation if requested.
- Note: `Check this in Word's equation editor if using LaTeX input.`
- DOCX note: `Raw LaTeX is preserved as source; the inserted Word equation must be OMML.`

## Non-Examples

- Changing `\frac{1}{2}` to `1/2` in a final equation without reason.
- Removing braces around exponents.
- Turning LaTeX into a screenshot.
- Replacing `\Delta` with `D` because it is easier to type.
- Claiming all LaTeX commands work in Word.
- Treating raw LaTeX text as the final equation in a produced DOCX.

## Interaction With Skills

- `skills/Documents/SKILL_EQUATION_FORMATTING.md`
- `rules/Equations/RULE_EQUATION_EDITABILITY.md`
- `rules/Equations/RULE_NO_EQUATION_IMAGES.md`
- `rules/Document output/RULE_CODE_FORMATTING.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`

## Quality Check

- Is the original LaTeX preserved?
- Are commands, braces and symbols intact?
- Are conversions clearly labelled?
- If producing DOCX, has LaTeX been converted to OMML?
- Are Word compatibility limits stated?
- Are Markdown code spans or fences used where needed?
- Has mathematical meaning been preserved?

## Sources

- Linear format equations using UnicodeMath and LaTeX in Word - Microsoft Support - https://support.microsoft.com/en-au/office/linear-format-equations-using-unicodemath-and-latex-in-word-2e00618d-b1fd-49d8-8cb4-8d17f25754f8 - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Make your Word documents accessible to people with disabilities - Microsoft Support - https://support.microsoft.com/en-us/office/make-your-word-documents-accessible-to-people-with-disabilities-d9bf3683-87ac-47ea-b91a-78dcacb3c66d - Accessed 2026-05-17
