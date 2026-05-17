# Skill: Equation Formatting

## Purpose

This skill allows the agent to format equations, formulae, units and mathematical working so they remain editable, readable and suitable for Word, Markdown, science resources and assessment materials.

## When To Use

Use this skill when the user asks for:

- formatted equations
- Word-ready maths or science formulae
- DOCX equations that must be stored as OMML
- LaTeX or UnicodeMath preservation
- worked examples with equations
- units in calculations
- avoiding equation images
- cleaning equation formatting for worksheets or answer keys

## Inputs

- subject and year level
- destination format: Markdown, Word, DOCX, PDF, LMS or print
- equations, formulae or worked examples
- required notation, units and symbols
- whether equations must be editable in Word
- whether LaTeX, UnicodeMath or plain text is preferred
- assessment or answer-key requirements

## Process

1. Identify the target format and whether equations must be editable.
2. Use text, LaTeX, UnicodeMath or Word-native equation syntax rather than equation images where possible.
3. If the target is an actual `.docx`, convert every equation and each formula to Word-native OMML.
4. If the target is Word-ready Markdown only, preserve the source equation and add a clear note that DOCX production must convert it to OMML.
5. Preserve original mathematical meaning, symbols, subscripts, superscripts and operators.
6. Keep units visible and separate from variable symbols.
7. Use SI units and Australian measurement conventions unless the user supplies another standard.
8. In worked examples, show enough steps for the year level without overcomplicating the solution.
9. Keep equations aligned or separated clearly when multiple lines are needed.
10. Label variables and define symbols where students need them.
11. Check calculations, units and notation before finalising.
12. Verify or flag Word-specific OMML conversion checks, especially for LaTeX or UnicodeMath source.

## Output

```markdown
## Formula

`v = d / t`

where:

- `v` = speed in metres per second (`m/s`)
- `d` = distance in metres (`m`)
- `t` = time in seconds (`s`)

## Worked Example
```

For Word-ready draft work, provide the equation text and note the intended conversion path. For actual DOCX production, insert the equation as OMML.

## Quality Criteria

- Equations remain editable where required.
- DOCX equations are converted to OMML.
- Mathematical meaning is preserved.
- Units are correct and visible.
- Variables are defined for students.
- Working is age-appropriate.
- Word or export limitations are stated.

## Related Rules

- `rules/Equations/RULE_EQUATION_EDITABILITY.md`
- `rules/Equations/RULE_LATEX_PRESERVATION.md`
- `rules/Equations/RULE_NO_EQUATION_IMAGES.md`
- `rules/Equations/RULE_UNITS_IN_EQUATIONS.md`
- `rules/Document output/RULE_WORD_FORMATTING.md`
- `rules/Science/RULE_DATA_AND_UNCERTAINTY.md`

## Example User Requests

- `Format these formulae for Word.`
- `Make this physics worked example editable.`
- `Preserve the LaTeX in this worksheet.`
- `Check the units in these equations.`

## Failure Modes

- Turning equations into images when editability is needed.
- Changing subscripts, superscripts or operators during formatting.
- Omitting units from substituted values.
- Mixing variable names and units ambiguously.
- Presenting Word conversion as guaranteed without checking.
- Producing a DOCX where formulae remain raw LaTeX, UnicodeMath or images instead of OMML.
- Adding advanced notation beyond the requested year level.

## Completion Checklist

- Is the target equation format clear?
- Are equations editable or copyable as required?
- If producing DOCX, are equations converted to OMML?
- Are symbols and units preserved?
- Are calculations checked?
- Are variables defined where needed?
- Are conversion limitations flagged?

## Sources

- Linear format equations using UnicodeMath and LaTeX in Word - Microsoft Support - https://support.microsoft.com/en-au/office/linear-format-equations-using-unicodemath-and-latex-in-word-2e00618d-b1fd-49d8-8cb4-8d17f25754f8 - Accessed 2026-05-17
- Editing equations created using Microsoft Equation Editor - Microsoft Support - https://support.microsoft.com/en-us/office/editing-equations-created-using-microsoft-equation-editor-08a44b8c-ae15-41a7-bc15-7239890c0cec - Accessed 2026-05-17
- Office Open XML Math elements - Microsoft Learn - https://learn.microsoft.com/en-us/openspecs/office_standards/ms-oe376/83056bdc-cabe-41b4-9b4c-6e7c6bd1edc7 - Accessed 2026-05-17
- Australia's measurement system - Department of Industry, Science and Resources - https://www.industry.gov.au/national-measurement-institute/australias-measurement-system - Accessed 2026-05-17
- SI Units - National Institute of Standards and Technology - https://www.nist.gov/pml/weights-and-measures/metric-si/si-units - Accessed 2026-05-17
