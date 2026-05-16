# Skill: Chemical Equations

## Purpose

This skill allows the agent to write, balance, explain and check chemical equations while preserving correct formulas, states, charges and coefficients.

## When To Use

Use this skill when the user asks for:

- balancing chemical equations
- writing word equations as symbol equations
- explaining chemical equations to students
- checking formulas, coefficients or state symbols
- ionic, molecular or net ionic equations
- chemistry answer keys involving equations

## Inputs

- year level or SACE stage
- reaction description, word equation or unbalanced equation
- required equation type
- known states, conditions or solvent
- whether products are supplied or need checking
- required explanation level
- assessment or answer-key context

## Process

1. Identify reactants, products and reaction context.
2. Check formulas before balancing.
3. Add state symbols only when supplied, known from context or required.
4. Balance atoms by changing coefficients only.
5. Check charge balance for ionic or redox equations.
6. Reduce to the lowest whole-number coefficients where appropriate.
7. Explain the balancing method at the requested level.
8. For ionic equations, remove spectator ions only when the equation type requires it.
9. Flag uncertain products, states or reaction feasibility.
10. Present the final equation in an editable format.

## Output

```markdown
# Chemical Equation

## Given

## Balanced Equation

## Check

## Explanation

## Notes Or Assumptions
```

Adjust sections to match the user request.

## Quality Criteria

- Formulas are correct before balancing.
- Coefficients, not subscripts, are changed.
- Atom and charge balance are checked.
- State symbols are justified.
- The explanation is suitable for the student level.
- Uncertainty is flagged where products or states are not supplied.

## Related Rules

- `rules/Chemistry/RULE_BALANCING_EQUATIONS.md`
- `rules/Chemistry/RULE_CHEMISTRY_NOTATION.md`
- `rules/Chemistry/RULE_CHEMISTRY_WORKED_EXAMPLES.md`
- `rules/Equations/RULE_EQUATION_EDITABILITY.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`

## Example User Requests

- `Balance this equation and explain the steps.`
- `Turn this word equation into a chemical equation.`
- `Write the net ionic equation for this reaction.`
- `Check whether this answer key has the correct coefficients.`

## Failure Modes

- Changing subscripts to balance.
- Inventing products or states.
- Ignoring charge balance.
- Leaving fractional coefficients when whole-number coefficients are expected.
- Presenting a formula as an image when editable text is needed.

## Completion Checklist

- Are formulas correct?
- Is the equation balanced?
- Is charge balanced if relevant?
- Are states justified?
- Is the final equation editable?
- Are assumptions stated?

## Sources

- IUPAC Gold Book: chemical reaction equation - https://www.old.goldbook.iupac.org/html/C/C01034.html - Accessed 2026-05-17
- Writing and Balancing Chemical Equations - Chemistry LibreTexts - https://chem.libretexts.org/Bookshelves/General_Chemistry/Chemistry_1e_%28OpenSTAX%29/04%3A_Stoichiometry_of_Chemical_Reactions/4.02%3A_Writing_and_Balancing_Chemical_Equations - Accessed 2026-05-17
- Structure of Chemistry - Australian Curriculum - https://v7.australiancurriculum.edu.au/senior-secondary-curriculum/science/chemistry/structure-of-chemistry/ - Accessed 2026-05-17
