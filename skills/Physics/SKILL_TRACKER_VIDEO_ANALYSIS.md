# Skill: Tracker Video Analysis

## Purpose

This skill allows the agent to support physics video-analysis tasks by planning, explaining or reviewing data collection, graph interpretation and uncertainty for Tracker-style motion analysis.

## When To Use

Use this skill when the user asks for:

- Tracker video analysis guidance
- motion analysis from video
- a video-analysis worksheet
- interpreting position-time or velocity-time graphs from video
- practical notes for filming motion
- troubleshooting physics video data

## Inputs

- year level or SACE stage
- motion or phenomenon being analysed
- software context, if supplied
- video setup: camera, scale, frame rate, angle and motion path
- quantities to measure
- graph or data output
- assessment or practical report requirements
- equipment and safety constraints

## Process

1. Clarify the motion and the quantity students need to analyse.
2. Identify setup needs: fixed camera, visible scale, stable reference point and suitable frame rate.
3. State assumptions if the video setup is not supplied.
4. Guide students to collect only the data needed for the learning goal.
5. Connect software outputs to physics quantities, not just button clicks.
6. Interpret position-time, velocity-time or acceleration-time graphs using axis labels and units.
7. Discuss data quality issues such as parallax, tracking error, frame choice, calibration and noisy velocity data.
8. Include safety and classroom practicality notes for filming.
9. Provide student-facing steps or teacher-facing notes depending on the request.
10. Avoid claiming precision that the video setup cannot support.

## Output

```markdown
# Tracker Video Analysis

## Aim

## Video Setup

## Data Collection

## Graphs To Produce

## Analysis Questions

## Uncertainty And Limitations

## Teacher Notes
```

Adjust headings to suit the user's software, platform and lesson format.

## Quality Criteria

- The setup supports the intended measurement.
- Scale, frame rate and reference point are considered.
- Graph interpretation uses axes and units.
- Limitations and uncertainty are visible.
- Instructions are realistic for the classroom.
- Software steps do not replace physics reasoning.

## Related Rules

- `rules/Physics/RULE_GRAPH_INTERPRETATION.md`
- `rules/Physics/RULE_PHYSICS_UNITS.md`
- `rules/Science/RULE_DATA_AND_UNCERTAINTY.md`
- `skills/Physics/SKILL_PHYSICS_GRAPH_ANALYSIS.md`
- `skills/Physics/SKILL_PHYSICS_PRACTICAL_INVESTIGATIONS.md`
- `rules/Quality control/RULE_CLASSROOM_REALISM.md`

## Example User Requests

- `Create a Tracker worksheet for projectile motion.`
- `Explain how students should interpret a velocity-time graph from video.`
- `Write teacher notes for a video analysis practical.`
- `Troubleshoot noisy Tracker data for a ramp investigation.`

## Failure Modes

- Treating software output as automatically accurate.
- Omitting scale or calibration.
- Ignoring parallax and camera angle.
- Focusing on button-click instructions without physics interpretation.
- Overclaiming precision from low-quality video.
- Forgetting safety and classroom setup constraints.

## Completion Checklist

- Is the video setup clear?
- Are measured quantities and units defined?
- Are graphs interpreted physically?
- Are uncertainty and limitations included?
- Are software and classroom assumptions stated?
- Is the task suitable for the students?

## Sources

- Position-Time Graphs - The Physics Classroom - https://www.physicsclassroom.com/Teacher-Toolkits/Position-Time-Graphs/Position-Time-Graphs-Complete-ToolKit - Accessed 2026-05-17
- Unpacking the terminology - Data and Measurement in VCE Biology - Victorian Curriculum and Assessment Authority - https://www.vcaa.vic.edu.au/curriculum/vce-curriculum/vce-study-designs/biology/unpacking-terminology-data-and-measurement-vce-biology - Accessed 2026-05-17
- Science Inquiry Skills - Australian Nuclear Science and Technology Organisation - https://www.ansto.gov.au/education/think-science-bringing-science-skills-together/science-inquiry-skills - Accessed 2026-05-17
