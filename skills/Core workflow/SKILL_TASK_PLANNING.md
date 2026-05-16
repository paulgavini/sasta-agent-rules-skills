# Skill: Task Planning

## Purpose

This skill allows the agent to break a large or complex education request into manageable phases such as intake, research, drafting, checking, formatting, export and refinement.

## When To Use

Use this skill when a request involves:

- multiple outputs or file types
- curriculum alignment plus drafting
- assessment design plus rubric or marking guide
- research, source evaluation and synthesis
- practical investigations with safety and data analysis
- Word, LMS, spreadsheet or presentation production
- long workflows that need checkpoints or staged completion

Do not use this skill to create a visible plan for simple tasks unless planning will help the user.

## Inputs

- the user's requested deliverable
- audience and year level
- subject, topic and curriculum or SACE context
- required output formats
- deadlines, lesson time or sequence length
- available sources, files, student work or data
- safety, privacy, assessment and platform constraints
- whether the user wants manual checkpoints or automated completion

## Process

1. Restate the task goal in plain language.
2. Identify the final deliverable or deliverables.
3. Split the work into necessary phases only.
4. Put high-risk phases early, such as privacy checks, safety checks, source verification or assessment criteria review.
5. Sequence research before drafting when factual, curriculum, software or current policy accuracy matters.
6. Sequence drafting before formatting unless the output format strongly shapes the content.
7. Add review and quality-control steps for substantial outputs.
8. Identify where progress should be shown to the user.
9. Keep the plan proportional to the task; use a short checklist for simple work and a phased plan for complex work.
10. Update progress records after each completed file or major project artefact.

## Output

For internal planning, use a compact checklist:

```markdown
## Task Plan
- [ ] Intake and constraints
- [ ] Research and source register
- [ ] Draft content
- [ ] Review against rules
- [ ] Format/export
- [ ] Final check
```

For user-facing planning, provide only what helps the user understand the work:

```markdown
I will handle this in three stages:
1. Check the curriculum and constraints.
2. Draft the resource and marking support.
3. Review for classroom use and export formatting.
```

## Quality Criteria

- The plan is short enough to be useful.
- Steps are ordered logically.
- Safety, privacy, assessment and curriculum risks are not left until the end.
- Research and verification occur before claims are drafted.
- The plan names concrete outputs rather than vague activity.
- The agent keeps working after planning unless the user asks for approval first.

## Related Rules

- `rules/Core behaviour/RULE_ROLE_AND_SCOPE.md`
- `rules/Core behaviour/RULE_FOLLOW_USER_CONTEXT.md`
- `rules/Core behaviour/RULE_CLARIFICATION.md`
- `rules/Core behaviour/RULE_NO_UNREQUESTED_EXPANSION.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`
- `rules/AI agent design/RULE_MANUAL_GATE_CHECKS.md`
- `rules/AI agent design/RULE_AUTOMATED_RUN_MODE.md`

## Example User Requests

- `Create a three-week Year 9 electronics unit with assessment and teacher notes.`
- `Turn these student responses into marked feedback and a summary spreadsheet.`
- `Build a SACE Physics practical task, rubric and Word document.`
- `Create an AI-agent skill and rule set for assessment marking.`

## Failure Modes

- Producing a long plan instead of doing the work.
- Planning phases that are unrelated to the requested output.
- Researching after drafting factual or curriculum-specific claims.
- Leaving safety, privacy or assessment integrity until final review.
- Treating a small request as a complex project.

## Completion Checklist

- Is the final deliverable clear?
- Are the phases necessary and proportional?
- Are high-risk checks early in the process?
- Are research, drafting, review and export steps in a sensible order?
- Does the plan support action rather than delay it?

## Sources

- How students learn best: An overview of the evidence — Australian Education Research Organisation — https://www.edresearch.edu.au/research/research-reports/how-students-learn-best-overview-evidence — Accessed 2026-05-16
- Explicit instruction: Practice guide — Australian Education Research Organisation — https://www.edresearch.edu.au/guides-resources/practice-guides/explicit-instruction-practice-guide-full-publication — Accessed 2026-05-16
- Quick guide: plain language — Australian Government Style Manual — https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language — Accessed 2026-05-16
- Australian Framework for Generative Artificial Intelligence (AI) in Schools — Australian Government Department of Education — https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools — Accessed 2026-05-16
