# Skill: SACE Physics Alignment

## Purpose

This skill allows the agent to align Physics resources, tasks and advice to SACE Physics requirements using current SACE sources or user-supplied subject material.

## When To Use

Use this skill when the user asks for:

- SACE Physics alignment
- Stage 1 or Stage 2 Physics task support
- investigations folio guidance
- skills and applications task design
- subject outline or LAP alignment
- performance standards or assessment evidence mapping
- SACE Physics teacher notes

## Inputs

- SACE stage and assessment type
- task, resource or lesson to align
- current SACE Physics subject outline or supplied school material if available
- LAP, assessment conditions or school requirements
- topic, evidence and student output
- performance standards or criteria supplied by the user
- moderation, verification or integrity constraints

## Process

1. Confirm whether the task is Stage 1 or Stage 2 Physics.
2. Check current SACE Physics pages or supplied subject-outline/LAP material before making specific claims.
3. Treat the current supplied or official Physics subject outline as the primary authority for Physics-specific content, assessment types, weightings, criteria and performance standards; use general SACE policy sources for LAP, integrity, moderation and verification processes.
4. Identify the assessment type, such as investigations folio or skills and applications task.
5. Map the resource to evidence students must produce.
6. Keep assessment conditions and verification requirements visible.
7. Use current SACE terminology where it is supplied or verified.
8. Avoid inventing performance-standard wording, weightings or task requirements.
9. Flag when the school LAP or current subject outline must be checked.
10. Add teacher-facing alignment notes without cluttering student-facing instructions.
11. Keep the output usable for planning, moderation or classroom implementation.

## Output

```markdown
# SACE Physics Alignment

## Stage And Assessment Type

## Source Checked

## Intended Evidence

## Alignment Notes

## Assessment Integrity Notes

## LAP Or Local Checks
```

Use the user's supplied template when provided.

## Quality Criteria

- Stage and assessment type are clear.
- SACE claims are sourced or flagged for checking.
- Evidence aligns with the task.
- Assessment integrity and verification are considered.
- LAP and local checks are visible.
- Student-facing and teacher-facing notes are separated.

## Related Rules

- `rules/Curriculum/RULE_SACE_ALIGNMENT.md`
- `rules/Assessment/RULE_ASSESSMENT_STRUCTURE.md`
- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Physics/RULE_PHYSICS_UNITS.md`
- `rules/Physics/RULE_PHYSICS_NOTATION.md`
- `skills/Core workflow/SKILL_CURRICULUM_ALIGNMENT.md`

## Example User Requests

- `Align this Stage 2 Physics practical to SACE.`
- `Check whether this task fits a Physics investigations folio.`
- `Write SACE Physics teacher notes for this assessment.`
- `Map this lesson sequence to SACE Physics evidence.`

## Failure Modes

- Inventing SACE requirements from memory.
- Mixing Stage 1 and Stage 2 expectations.
- Claiming LAP compliance without checking the LAP.
- Hiding assessment integrity conditions from the teacher.
- Using general physics alignment when SACE-specific alignment was requested.
- Adding performance-standard wording not supplied or verified.

## Completion Checklist

- Is the SACE stage clear?
- Has the relevant SACE or supplied source been checked?
- Is assessment type identified?
- Is required evidence clear?
- Are integrity and local checks visible?
- Are unverifiable claims avoided?

## Sources

- Overview - Physics - SACE Board of South Australia - https://www.sace.sa.edu.au/web/physics - Accessed 2026-05-17
- School assessment - Physics - SACE Board of South Australia - https://www.sace.sa.edu.au/web/physics/school-assessment - Accessed 2026-05-17
- Learning and assessment plans - Stage 1 and Stage 2 - SACE Board of South Australia - https://www.sace.sa.edu.au/coordinating/admin/information-sheets/57 - Accessed 2026-05-17
