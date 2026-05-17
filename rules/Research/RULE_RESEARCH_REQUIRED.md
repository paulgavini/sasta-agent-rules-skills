# Rule: Research Required

## Purpose

Define when the agent must research before drafting, editing or advising, so that current, high-stakes or source-dependent claims are not produced from memory alone.

## Applies To

- curriculum, SACE, policy and assessment requirements
- safety, privacy, cybersecurity and AI-use guidance
- software, platform and technical instructions
- science accuracy checks and practical investigation advice
- source-based summaries, bibliographies and evidence-informed teaching claims
- any request where the user explicitly asks for research, sources or verification

## Rule Statement

The agent must research reputable sources before making claims that are current, high-stakes, jurisdiction-specific, source-dependent or explicitly requested to be researched.

## Requirements

- Research when the user asks for sources, current information, latest requirements or verification.
- Research official sources before drafting curriculum, SACE, policy, software or safety content.
- Research when information may have changed since prior knowledge.
- Research when a claim could affect assessment validity, student safety, privacy, legal compliance or school policy.
- Use supplied documents first when the user provides them as the authority.
- Keep research proportional to the risk and complexity of the task.
- Record sources in `SOURCE_REGISTER.md` when they support a completed rule or skill file.
- Do not fabricate sources, URLs, access dates or source claims.
- If research is not possible, state the limitation and mark the output as needing source verification.

## Decision Logic

Research is required when any of these apply:

- the user explicitly says to research, check, verify, cite or use sources
- the answer depends on current curriculum, SACE, policy or software behaviour
- the output will be used for assessment, safety or privacy decisions
- the topic is specialised, disputed or outside common stable knowledge
- a source will be listed in the file or source register

Research may be light when the task is a low-risk rewrite, format cleanup or generic teaching structure that does not depend on current facts.

## Examples

- Research before drafting a SACE Chemistry assessment task.
- Research official documentation before writing DB Browser for SQLite, SQLite, Excel or Power BI instructions.
- Research reputable sources before adding cybersecurity advice for students.
- Use the supplied school rubric as the authority when marking student work.

## Non-Examples

- Inventing a curriculum code because the topic sounds familiar.
- Citing a source that was not checked.
- Relying on memory for current SACE assessment requirements.
- Using research as an excuse to add irrelevant material to a simple rewrite.
- Recording a source in `SOURCE_REGISTER.md` without using it.

## Interaction With Skills

- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`
- `skills/Core workflow/SKILL_SOURCE_EVALUATION.md`
- `skills/Core workflow/SKILL_SYNTHESIS.md`
- `skills/Quality control/SKILL_OUTPUT_REVIEW.md`
- `skills/Quality control/SKILL_SAFETY_AND_RISK_CHECK.md`

## Quality Check

- Was research required for this task?
- Were official or authoritative sources checked first?
- Was the amount of research proportional?
- Are sources recorded where required?
- Are unsupported claims removed or marked for verification?
- Are limits and uncertainty visible where needed?

## Sources

- Evidence use in schools national snapshot: Summary of findings - Australian Education Research Organisation - https://www.edresearch.edu.au/summaries-explainers/research-summaries/evidence-use-schools-national-snapshot-summary - Accessed 2026-05-17
- Question your sources - Monash University - https://www.monash.edu/student-academic-success/sharpen-your-thinking/critical-thinking/question-your-sources - Accessed 2026-05-17
- Australian Framework for Generative Artificial Intelligence (AI) in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
