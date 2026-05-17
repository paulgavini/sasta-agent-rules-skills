# Rule: Output Review Checklist

## Purpose

Provide a final quality gate for agent-generated files, instructions and user-facing outputs before they are treated as complete.

## Applies To

- rule and skill files
- AI agent specifications
- source and progress registers
- teacher-facing, student-facing, parent-facing and staff-facing outputs
- code, data, document and LMS-ready deliverables

## Rule Statement

The agent must review outputs for scope, accuracy, source support, privacy, safety, accessibility, formatting and completion before reporting them as done.

## Requirements

- Check that the output answers the user's actual request and does not drift into unrelated expansion.
- Check that factual, technical, curriculum and policy claims are supported by reputable sources or clearly labelled as assumptions.
- Check that source titles, organisations, URLs and access dates are real and recorded where required.
- Check for Australian spelling, clear language and audience-appropriate terminology.
- Check for privacy risks, personal information, assessment-integrity risks and unsafe instructions.
- Check that examples and non-examples match the rule or skill purpose.
- Check that formatting is consistent with nearby completed files.
- Check that links, paths and file names are stable and correctly typed.
- Check that unresolved issues and recommended next actions are recorded in `AGENT_BUILD_PROGRESS.md` where relevant.
- Do not mark a file complete if sources are missing, content is only a stub or the file conflicts with user constraints.

## Decision Logic

Before finalising a file, review it against the checklist. If the issue is minor and can be fixed within scope, fix it. If the issue needs human judgement, local policy or unavailable information, record the unresolved issue and make the output a draft, template or reviewed AI draft as appropriate. If the issue undermines accuracy, safety or source integrity, do not report the file as complete until corrected.

## Examples

- Replace US spelling with Australian spelling unless preserving a source title or software label.
- Add a missing source-register row after citing a new official source.
- Flag that local school policy is needed before using an AI agent with identifiable student data.
- Correct a rule that duplicates a skill procedure instead of defining always-on behaviour.

## Non-Examples

- Marking a placeholder file as complete.
- Reporting that all sources were used when a source was only searched but not relied on.
- Ignoring broken file paths in related-rule links.
- Leaving a privacy-risk example in a student-facing resource.

## Interaction With Skills

- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`
- `skills/Quality control/SKILL_SAFETY_AND_RISK_CHECK.md`
- `skills/Core workflow/SKILL_SOURCE_EVALUATION.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`

## Quality Check

- Is the output complete for the requested purpose?
- Are sources real, suitable and registered?
- Is the file internally consistent and formatted like the rest of the project?
- Are privacy, safety and assessment issues handled?
- Are unresolved issues recorded honestly?

## Sources

- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- OWASP Top 10 for Large Language Model Applications - OWASP Foundation - https://owasp.org/www-project-top-10-for-large-language-model-applications/ - Accessed 2026-05-17
- AI Risk Management Framework - National Institute of Standards and Technology - https://www.nist.gov/itl/ai-risk-management-framework - Accessed 2026-05-17
