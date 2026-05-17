# Rule: Agent File Structure

## Purpose

Keep agent rules, skills and progress files organised so a human can inspect, reuse and maintain the system without guessing what each file controls.

## Applies To

- agent instruction repositories
- rule and skill libraries
- progress registers and source registers
- custom GPT, Codex-style and school workflow agent designs
- any generated or edited Markdown file that changes agent behaviour

## Rule Statement

The agent must preserve a clear file structure in which each file has one primary purpose, meaningful existing content is retained, and behaviour-critical material is easy to locate.

## Requirements

- Do not rename, move or delete files unless the user explicitly requests that action.
- Keep rule files in rule folders and skill files in skill folders.
- Use the existing folder and naming conventions before introducing any new structure.
- Give each file one clear behavioural purpose.
- Preserve meaningful existing content when expanding an empty, partial or older draft file.
- Use predictable headings such as `Purpose`, `Applies To`, `Rule Statement`, `Requirements`, `Decision Logic`, `Examples`, `Non-Examples`, `Interaction With Skills`, `Quality Check` and `Sources` for rule files unless the local pattern differs.
- Record source use in both the completed file and `SOURCE_REGISTER.md`.
- Record completion status in `AGENT_BUILD_PROGRESS.md` immediately after the file is completed.
- Avoid duplicating the same full rule across several files; cross-reference related files instead.
- Keep file paths stable in references so they remain usable in Codex, ChatGPT project folders and GitHub.

## Decision Logic

If the user asks to add or complete agent guidance, first look for an existing file that matches the purpose. If one exists, update that file while preserving its useful content. If no matching file exists and the user has not asked for new files, do not create one without a clear reason. If a file belongs to a different category, keep the current file focused and reference the related file instead of copying large blocks of guidance.

## Examples

- Put always-on behaviour such as privacy, source checking or output review in a rule file.
- Put repeatable task procedures such as source research, assessment drafting or transcript creation in a skill file.
- Update `SOURCE_REGISTER.md` when a new source supports a completed rule.
- Keep `AGENT_BUILD_PROGRESS.md` as the live build ledger rather than scattering status notes across many files.

## Non-Examples

- Moving a rule into a skill folder because it contains procedural language.
- Creating a new file when an empty placeholder already exists.
- Overwriting a partly drafted file without preserving usable material.
- Referring to a source in a file but not adding it to the source register.

## Interaction With Skills

- `skills/PD and leadership/SKILL_RULESET_DEVELOPMENT.md`
- `skills/PD and leadership/SKILL_AI_AGENT_DESIGN.md`
- `rules/AI agent design/RULE_SKILL_RULE_SEPARATION.md`
- `rules/AI agent design/RULE_OUTPUT_REVIEW_CHECKLIST.md`

## Quality Check

- Is the file in the right folder for its purpose?
- Does the file have one clear role?
- Has existing meaningful content been preserved?
- Are related rules or skills referenced instead of duplicated?
- Are progress and source registers updated?

## Sources

- Agents - OpenAI Agents SDK - https://openai.github.io/openai-agents-python/agents/ - Accessed 2026-05-17
- Australian Framework for Generative Artificial Intelligence in Schools - Australian Government Department of Education - https://www.education.gov.au/schooling/resources/australian-framework-generative-artificial-intelligence-ai-schools - Accessed 2026-05-17
- Structuring content - Australian Government Style Manual - https://www.stylemanual.gov.au/structuring-content - Accessed 2026-05-17
