# Skill: Physics Graph Analysis

## Purpose

This skill allows the agent to analyse, explain or teach physics graphs using axis variables, units, slope, area, graph shape, uncertainty and physical interpretation.

## When To Use

Use this skill when the user asks for:

- graph interpretation in physics
- motion graph explanations
- slope or area calculations
- practical graph analysis
- graphing feedback or marking notes
- Tracker or video-analysis graph interpretation
- graph-based SACE Physics support

## Inputs

- graph type or axis labels
- data table, image description or supplied graph details
- year level or SACE stage
- topic and physical context
- units and scale
- whether students need calculation, interpretation or critique
- assessment or reporting requirements

## Process

1. Identify the quantity and unit on each axis.
2. Decide what graph feature matters: point, gradient, area, intercept, shape, trend or scatter.
3. Derive slope or area units from the axes.
4. Connect graph features to physical meaning.
5. Explain signs, direction and reference points where relevant.
6. Check whether a straight-line model or curve interpretation is justified.
7. If data are experimental, discuss scatter, uncertainty, outliers and range limits.
8. Provide student-facing steps if the output is a tutorial.
9. Provide teacher-facing marking or misconception notes if requested.
10. Avoid overclaiming beyond the data or graph context.

## Output

```markdown
# Physics Graph Analysis

## Graph Context

## Axes And Units

## Key Features

## Calculations

## Physical Interpretation

## Data Quality Or Uncertainty

## Common Mistakes
```

Use only the sections that suit the task.

## Quality Criteria

- Axis quantities and units are explicit.
- Slope and area meanings are correct for the graph.
- Units are derived correctly.
- Physical interpretation is clear.
- Data limitations are stated when relevant.
- Student or teacher guidance matches the audience.

## Related Rules

- `rules/Physics/RULE_GRAPH_INTERPRETATION.md`
- `rules/Physics/RULE_PHYSICS_UNITS.md`
- `rules/Physics/RULE_PHYSICS_NOTATION.md`
- `rules/Science/RULE_DATA_AND_UNCERTAINTY.md`
- `skills/Physics/SKILL_TRACKER_VIDEO_ANALYSIS.md`
- `skills/Physics/SKILL_PHYSICS_PRACTICAL_INVESTIGATIONS.md`

## Example User Requests

- `Explain this velocity-time graph.`
- `Write a worksheet on position-time graph gradients.`
- `Analyse this practical graph and identify uncertainty.`
- `Create feedback for students interpreting motion graphs.`

## Failure Modes

- Applying a graph rule without checking axes.
- Ignoring units for gradient or area.
- Confusing distance, displacement, speed and velocity.
- Treating noisy data as a perfect relationship.
- Extrapolating beyond the data without caution.
- Omitting sign or direction.

## Completion Checklist

- Are axes and units identified?
- Is slope or area interpreted correctly?
- Are calculations checked?
- Are signs and graph shape explained?
- Are uncertainty and limits considered?
- Is the explanation pitched correctly?

## Sources

- Position-Time Graphs - The Physics Classroom - https://www.physicsclassroom.com/Teacher-Toolkits/Position-Time-Graphs/Position-Time-Graphs-Complete-ToolKit - Accessed 2026-05-17
- Position vs. Time Graphs - OpenStax Physics - https://openstax.org/books/physics/pages/2-3-position-vs-time-graphs - Accessed 2026-05-17
- Unpacking the terminology - Data and Measurement in VCE Biology - Victorian Curriculum and Assessment Authority - https://www.vcaa.vic.edu.au/curriculum/vce-curriculum/vce-study-designs/biology/unpacking-terminology-data-and-measurement-vce-biology - Accessed 2026-05-17
