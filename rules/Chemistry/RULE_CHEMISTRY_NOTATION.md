# Rule: Chemistry Notation

## Purpose

Ensure chemical formulas, equations, ions, states, charges, quantities and symbols are written accurately and remain editable.

## Applies To

- chemical equations
- formulas and ions
- stoichiometry and molar calculations
- reaction rates and equilibrium
- practical investigations
- SACE Chemistry materials
- Word-ready chemistry resources

## Rule Statement

The agent must preserve chemistry notation precisely, including subscripts, superscripts, charges, state symbols and coefficients.

## Requirements

- Use correct element symbols and capitalisation.
- Preserve subscripts in chemical formulas.
- Use superscript-style charge notation where possible, or clear plain text such as `SO4^2-`.
- Distinguish coefficients from subscripts.
- Use state symbols only where known or relevant: `(s)`, `(l)`, `(g)`, `(aq)`.
- Keep reaction arrows clear and consistent.
- Define symbols such as `n`, `m`, `M`, `c`, `V`, `K`, `Q` or `rate` where needed.
- Use SI units and accepted chemistry units consistently.
- Preserve supplied notation from task sheets, formula sheets or SACE materials.
- Avoid image-only formulas when editability is needed.

## Decision Logic

If exact notation affects correctness, prioritise editability and accuracy over visual styling. If the platform cannot render subscripts or superscripts reliably, use a clear plain-text convention and explain it.

## Examples

- `NaCl`, not `Nacl`.
- `Mg(OH)2`, not `MgOH2`.
- `SO4^2-` for sulfate in plain text.
- `2H2 + O2 -> 2H2O`.
- `NaCl(aq) + AgNO3(aq) -> AgCl(s) + NaNO3(aq)`.

## Non-Examples

- Changing `CO2` to `Co2`.
- Treating `2H2O` and `H4O2` as interchangeable.
- Dropping charges from ionic equations.
- Adding `(aq)` to every species without context.
- Using screenshots for formulas that students need to copy.

## Interaction With Skills

- `skills/Chemistry/SKILL_CHEMICAL_EQUATIONS.md`
- `skills/Chemistry/SKILL_CHEMISTRY_WORKED_EXAMPLES.md`
- `skills/Documents/SKILL_EQUATION_FORMATTING.md`
- `rules/Chemistry/RULE_BALANCING_EQUATIONS.md`
- `rules/Equations/RULE_EQUATION_EDITABILITY.md`
- `rules/Equations/RULE_NO_EQUATION_IMAGES.md`

## Quality Check

- Are formulas and element symbols correct?
- Are subscripts, charges and coefficients distinct?
- Are state symbols justified?
- Are variables and units defined?
- Is notation editable and copy-safe?
- Does notation match the supplied course context?

## Sources

- IUPAC Green Book - Quantities, Units, and Symbols in Physical Chemistry - https://iupac.org/what-we-do/books/greenbook/ - Accessed 2026-05-17
- IUPAC Gold Book: chemical reaction equation - https://www.old.goldbook.iupac.org/html/C/C01034.html - Accessed 2026-05-17
- Linear format equations using UnicodeMath and LaTeX in Word - Microsoft Support - https://support.microsoft.com/en-au/office/linear-format-equations-using-unicodemath-and-latex-in-word-2e00618d-b1fd-49d8-8cb4-8d17f25754f8 - Accessed 2026-05-17
