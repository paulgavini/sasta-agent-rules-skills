# Skill: Synthesis

## Purpose

This skill allows the agent to combine user-provided material, researched sources, curriculum requirements and practical teaching judgement into a coherent, accurate and usable output.

## When To Use

Use this skill when the user asks for:

- a summary that combines several sources or documents
- a teaching resource based on research, policy or curriculum material
- a comparison, recommendation or decision from multiple inputs
- a rewritten resource that preserves key ideas while improving structure
- an assessment, rubric, lesson sequence or guide that must integrate standards and classroom needs
- a final output after source research and source evaluation

## Inputs

- user request and intended deliverable
- audience, year level, subject and platform
- supplied notes, files, examples or source material
- researched sources and source-evaluation notes
- curriculum, SACE, school or assessment constraints
- required tone, length, format and citation expectations
- uncertainties, conflicts or gaps identified during research

## Process

1. Restate the synthesis goal in one sentence before drafting.
2. Sort inputs into:
   - required user constraints
   - official curriculum, SACE, policy or software requirements
   - research evidence or reputable guidance
   - teacher-generated or classroom-context evidence
   - examples, preferences and optional ideas
3. Keep high-authority and user-supplied constraints visible while drafting.
4. Identify agreements, tensions, gaps and limits across sources before combining them.
5. Do not average incompatible claims or hide uncertainty by smoothing sources together.
6. Preserve the meaning of source material while using original wording unless a short quotation is necessary and permitted.
7. Convert source ideas into practical teaching, assessment or workflow decisions.
8. Remove duplicated points, weak evidence and off-task material.
9. Structure the final output so the user can act on it quickly.
10. Add citations, source notes, assumptions or limitations only where they are useful or requested.

## Output

For research-to-draft synthesis:

```markdown
## Synthesised Direction
- Main decision:
- Source basis:
- Classroom implication:
- Limits or assumptions:
```

For a final resource, produce the requested deliverable first and place source notes or assumptions after the resource unless the user requested a visible evidence map.

For conflicting sources:

```markdown
## Source Tension
| Issue | Source positions | Resolution for this output |
| --- | --- | --- |
```

## Quality Criteria

- The final output answers the user's actual request.
- Source material is integrated, not pasted together.
- Official or high-authority sources drive decisions where policy, curriculum, assessment or safety matters.
- The synthesis distinguishes evidence, interpretation and practical recommendation.
- Unsupported claims, invented citations and vague appeals to research are removed.
- The result is concise, coherent and suitable for the intended audience.

## Related Rules

- `rules/Core behaviour/RULE_FOLLOW_USER_CONTEXT.md`
- `rules/Core behaviour/RULE_NO_UNREQUESTED_EXPANSION.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`
- `rules/Research/RULE_SOURCE_HIERARCHY.md`
- `rules/Research/RULE_CITATION_AND_BIBLIOGRAPHY.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`
- `rules/Quality control/RULE_COMPLETENESS_CHECK.md`

## Example User Requests

- `Turn these research notes into a teacher-facing summary.`
- `Combine these curriculum points into a Year 8 assessment task.`
- `Use these sources to create a short parent explanation.`
- `Compare these approaches and recommend the best one for my class.`

## Failure Modes

- Creating a patchwork of source excerpts rather than a coherent new output.
- Treating all sources as equally authoritative.
- Hiding contradictions or uncertainty.
- Adding unsupported claims because they sound plausible.
- Losing the user's format, audience or classroom constraints while synthesising.
- Overloading a practical resource with unnecessary research explanation.

## Completion Checklist

- Has the synthesis goal been identified?
- Have source types and authority levels been distinguished?
- Are conflicts, gaps or uncertainties handled honestly?
- Does the output preserve the user's required constraints?
- Is the final structure easy to scan and use?
- Are sources or assumptions included only where useful?

## Sources

- Create your own argument - Monash University - https://www.monash.edu/student-academic-success/sharpen-your-thinking/critical-thinking/create-argument - Accessed 2026-05-17
- Evidence use in schools national snapshot: Summary of findings - Australian Education Research Organisation - https://www.edresearch.edu.au/summaries-explainers/research-summaries/evidence-use-schools-national-snapshot-summary - Accessed 2026-05-17
- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
