# Skill: Chemistry Worked Examples

## Purpose

This skill allows the agent to create chemistry worked examples that show chemical reasoning, equations, units, mole relationships and final interpretation clearly.

## When To Use

Use this skill when the user asks for:

- chemistry worked examples
- step-by-step stoichiometry
- mole, mass, concentration or volume calculations
- reaction rates calculations
- equilibrium, acids and bases or redox support
- answer keys for chemistry questions
- SACE Chemistry skills and applications support

## Inputs

- year level or SACE stage
- topic and question
- given data and required answer
- formula sheet, equation or supplied convention
- whether equations need balancing first
- required precision or significant figures
- student-facing or teacher-facing audience

## Process

1. Identify the chemistry concept or calculation type.
2. Check chemical formulas and balance equations before using ratios.
3. List known quantities and what is being found where useful.
4. State the relevant relationship, such as `n = m / M` or `c = n / V`.
5. Substitute values with units.
6. Use mole ratios from the balanced equation where relevant.
7. Convert units before calculation where needed.
8. Calculate and check reasonableness.
9. Interpret the answer in the chemical context.
10. Add common mistakes only when they support learning.

## Output

```markdown
# Worked Example

## Question

## Chemical Relationship

## Working

## Answer

## Check Or Interpretation
```

Adjust headings to suit the task.

## Quality Criteria

- Chemical notation is accurate.
- Equations are balanced before ratios are used.
- Units and conversions are correct.
- Reasoning is visible.
- The answer is interpreted in context.
- The level matches the learner.

## Related Rules

- `rules/Chemistry/RULE_CHEMISTRY_WORKED_EXAMPLES.md`
- `rules/Chemistry/RULE_BALANCING_EQUATIONS.md`
- `rules/Chemistry/RULE_CHEMISTRY_NOTATION.md`
- `rules/Equations/RULE_UNITS_IN_EQUATIONS.md`
- `rules/Lesson design/RULE_SCAFFOLDED_INSTRUCTION.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`

## Example User Requests

- `Write a worked example for mole-to-mass stoichiometry.`
- `Explain this concentration calculation step by step.`
- `Create a SACE Chemistry answer key for this rates question.`
- `Show students how to use mole ratios from a balanced equation.`

## Failure Modes

- Using an unbalanced equation.
- Omitting units or conversions.
- Confusing mass, amount and concentration.
- Treating formulas as flexible text.
- Overloading a simple calculation with advanced theory.

## Completion Checklist

- Is the chemical relationship correct?
- Is notation accurate?
- Are equations balanced where needed?
- Are units handled correctly?
- Is the answer interpreted?
- Are assumptions visible?

## Sources

- Writing and Balancing Chemical Equations - Chemistry LibreTexts - https://chem.libretexts.org/Bookshelves/General_Chemistry/Chemistry_1e_%28OpenSTAX%29/04%3A_Stoichiometry_of_Chemical_Reactions/4.02%3A_Writing_and_Balancing_Chemical_Equations - Accessed 2026-05-17
- Teach explicitly - Australian Education Research Organisation - https://www.edresearch.edu.au/guides-resources/practice-guides/teach-explicitly - Accessed 2026-05-17
- Overview - Chemistry - SACE Board of South Australia - https://www.sace.sa.edu.au/web/chemistry - Accessed 2026-05-17
