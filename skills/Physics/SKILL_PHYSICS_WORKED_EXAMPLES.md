# Skill: Physics Worked Examples

## Purpose

This skill allows the agent to create clear physics worked examples that show method, units, reasoning and interpretation at a suitable level for the students.

## When To Use

Use this skill when the user asks for:

- a physics worked example
- a step-by-step solution
- a student-facing explanation of a calculation
- an answer key for physics questions
- SACE Physics skills and applications support
- motion, force, energy, electricity, waves or graph calculations

## Inputs

- year level or SACE stage
- topic and formula or principle
- question, data, diagram or graph
- required notation or formula sheet
- expected student prior knowledge
- whether output is student-facing or teacher-facing
- required precision, significant figures or unit convention

## Process

1. Identify the physical situation and what the question asks for.
2. List known quantities and the unknown where this supports learning.
3. Choose the relevant model, formula, graph rule or conservation principle.
4. Define symbols if students may not know them.
5. Rearrange the formula before substitution if needed.
6. Substitute values with units.
7. Calculate carefully and check units.
8. Interpret the result in context, including direction, sign and reasonableness.
9. Add a common mistake or check only if it helps the learner.
10. Keep the working concise enough for the requested audience.

## Output

```markdown
# Worked Example

## Question

## Known Values

## Formula Or Principle

## Working

## Answer

## Check Or Interpretation
```

Adjust headings to match the user's requested format.

## Quality Criteria

- The method is visible.
- Units and conversions are correct.
- Notation is consistent.
- The answer is interpreted physically.
- The explanation matches the student level.
- The output avoids unnecessary advanced theory.

## Related Rules

- `rules/Physics/RULE_PHYSICS_WORKED_EXAMPLES.md`
- `rules/Physics/RULE_PHYSICS_UNITS.md`
- `rules/Physics/RULE_PHYSICS_NOTATION.md`
- `rules/Equations/RULE_UNITS_IN_EQUATIONS.md`
- `rules/Lesson design/RULE_SCAFFOLDED_INSTRUCTION.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`

## Example User Requests

- `Write a worked example for F = ma.`
- `Show students how to calculate velocity from a distance-time graph.`
- `Create a SACE-style answer key for this physics question.`
- `Explain this energy calculation step by step.`

## Failure Modes

- Giving the answer without the reasoning path.
- Omitting units or conversions.
- Using inconsistent symbols.
- Overexplaining with theory not needed for the problem.
- Ignoring direction or sign.
- Claiming SACE alignment without checking supplied or current SACE material.

## Completion Checklist

- Is the question being answered?
- Are knowns, unknowns and formulas clear?
- Are units correct throughout?
- Is the answer physically interpreted?
- Is the level appropriate?
- Are assumptions or verification gaps stated?

## Sources

- Teach explicitly - Australian Education Research Organisation - https://www.edresearch.edu.au/guides-resources/practice-guides/teach-explicitly - Accessed 2026-05-17
- How students learn best: An overview of the evidence - Australian Education Research Organisation - https://www.edresearch.edu.au/research/research-reports/how-students-learn-best-overview-evidence - Accessed 2026-05-17
- Overview - Physics - SACE Board of South Australia - https://www.sace.sa.edu.au/web/physics - Accessed 2026-05-17
