# Agents For Science, Physics, Chemistry, Electronics, Digital Technologies, IT, Robotics And Data Analysis For SASTA Members

This repository is building a Markdown rule and skill library for an education-focused AI assistant that supports South Australian secondary teaching work.

The current build emphasises Australian spelling, South Australian school context, Australian Curriculum and SACE alignment, assessment integrity, privacy, accessibility, classroom realism and evidence-informed teaching practice.

## Current Status

Progress is tracked in [AGENT_BUILD_PROGRESS.md](AGENT_BUILD_PROGRESS.md). Sources are tracked in [SOURCE_REGISTER.md](SOURCE_REGISTER.md).

As at 2026-05-17, the drafted foundation covers:

- core behaviour rules
- core workflow skills
- curriculum and SACE alignment rules
- research and citation rules
- quality-control rules
- science investigation and safety rules
- assessment rules
- assessment workflow skills
- lesson-design, communication, document-output and equation rules and skills
- physics, chemistry, digital technologies, electronics, media, platform and AI agent design rules and skills

All rule and skill files recorded in the current build inventory have AI-reviewed drafts. Remaining work is now consistency review, source-register tidying, local school policy alignment and human review before production use.

## Repository Structure

```text
rules/
  Core behaviour/
  Curriculum/
  Research/
  Quality control/
  Science/
  Assessment/
  ...

skills/
  Core workflow/
  Assessment/
  Chemistry/
  Digital Technologies/
  Documents/
  Lesson design/
  Physics/
  ...
```

Rules define standing constraints and quality gates. Skills define repeatable workflows for producing a particular kind of output.

## Completed Foundations

### Core Behaviour

The core behaviour rules define the assistant's scope, user-context handling, clarification behaviour, Australian English, output cleanliness and limits on unrequested expansion.

### Core Workflow

The completed workflow skills cover request intake, task planning, curriculum alignment, source research, source evaluation and synthesis.

### Curriculum And SACE

Curriculum rules distinguish Australian Curriculum elements, SACE requirements, year-level appropriateness and the need to avoid overteaching. They require alignment to official or supplied criteria rather than invented curriculum links.

### Research And Sources

Research rules require reputable sources where appropriate, define preferred source categories, establish a source hierarchy, and set expectations for citations, bibliography entries and concise research reporting.

### Quality Control

Quality-control rules cover accessibility, accuracy checks, classroom realism, completeness, privacy and safety, and avoiding hallucinated files, paths, sources or verification results.

### Science

Science rules cover science accuracy, practical safety, variables and fair testing, and data and uncertainty. These are intended to support future chemistry, physics and practical-investigation skills.

### Assessment

Assessment rules and skills now cover task design, evidence-based marking, fair penalties, A-E rubrics, single-point rubrics, feedback comments, report writing and Year 8 assessment design.

## Source Practice

The project records sources in [SOURCE_REGISTER.md](SOURCE_REGISTER.md). Preferred sources include:

- Australian Curriculum, Assessment and Reporting Authority
- SACE Board of South Australia
- South Australian Department for Education
- Australian Institute for Teaching and School Leadership
- Australian Education Research Organisation
- Australian Government Style Manual
- Office of the Australian Information Commissioner
- Australian school science and measurement sources where relevant
- official software documentation for platform-specific files
- DB Browser for SQLite and SQLite documentation for database-development tasks
- Microsoft Support and Microsoft Learn for Excel, Power Query and Power BI workflows

Sources should not be fabricated. Source claims should be linked to the files that use them.

## Drafting Conventions

- Use Australian spelling.
- Preserve existing meaningful content.
- Do not rename, move or delete files unless explicitly asked.
- Research reputable sources before drafting current, policy, curriculum, safety, software or evidence-informed content.
- Update `AGENT_BUILD_PROGRESS.md` and `SOURCE_REGISTER.md` after completing files.
- Treat `Reviewed` as an AI self-reviewed draft. Human approval or production sign-off must be recorded separately if a human review process is introduced.
- When producing actual Word `.docx` files, convert all formulae and equations to Word-native OMML. Raw LaTeX or UnicodeMath may be preserved as labelled source text, but it is not the final equation format for DOCX output.

## Using The Rules And Skills

The `.md` files in this repository are written so they can be used as prompt context for Codex, ChatGPT or another AI assistant. They do not require a special runtime by themselves; the main requirement is that the assistant can read the relevant files or that you paste the relevant content into the conversation.

### In Codex With A Project Folder

When this repository is open as a Codex workspace, ask Codex to use the relevant rules and skills before completing the task.

Example:

```text
Use the rules and skills in this project to create a Year 8 Science assessment task on fair testing.
Apply the assessment, curriculum, science, privacy and output-review rules.
```

Codex can then inspect files such as:

- `skills/Core workflow/SKILL_REQUEST_INTAKE.md`
- `skills/Core workflow/SKILL_TASK_PLANNING.md`
- `skills/Assessment/SKILL_ASSESSMENT_TASK_DESIGN.md`
- `rules/Assessment/RULE_ASSESSMENT_STRUCTURE.md`
- `rules/Curriculum/RULE_YEAR_LEVEL_APPROPRIATENESS.md`
- `rules/Science/RULE_VARIABLES_AND_FAIR_TESTING.md`

For larger tasks, ask Codex to first identify which rules and skills apply, then draft the output.

Example:

```text
Before drafting, identify the relevant rule and skill files in this repository.
Then use them to design the task, rubric and teacher notes.
```

### In Codex Without A Project Folder

If the files are not available in the workspace, copy the relevant rule and skill Markdown into the prompt before the task.

Use this order:

1. Paste the most relevant skill file.
2. Paste any required rule files.
3. Add your teaching task or request.
4. Ask the assistant to follow the pasted instructions.

Example:

```text
Use the following local rules and skill as operating instructions for this task.

[paste SKILL_ASSESSMENT_TASK_DESIGN.md]
[paste RULE_ASSESSMENT_STRUCTURE.md]
[paste RULE_YEAR_LEVEL_APPROPRIATENESS.md]

Now create a Year 8 assessment task on ...
```

Keep the pasted set small. For most tasks, one skill and three to six rules is enough.

### In ChatGPT Online With Project Files

If using ChatGPT Projects or another online workspace that supports project files, upload the repository or the relevant `rules/`, `skills/`, `AGENT_BUILD_PROGRESS.md` and `SOURCE_REGISTER.md` files.

Then give an instruction such as:

```text
Use the uploaded rule and skill Markdown files as project instructions.
For each education task, choose the relevant skill workflow and apply the related rules.
If current curriculum, SACE, safety, policy or software details are needed, research reputable sources and cite them.
Use Australian spelling.
```

For best results, name the files you want used when the task is specific.

Example:

```text
Use SKILL_FEEDBACK_COMMENTS.md, RULE_FEEDBACK_FORMAT.md,
RULE_MARKING_EVIDENCE.md and RULE_NO_UNFAIR_PENALTY.md.
Write concise feedback for the following Year 8 Science responses.
```

### In ChatGPT Online Without Project Files

If you are using a normal chat without uploaded files, paste a compact selection of rules and skills into the conversation. Start with the skill that matches the task, then add only the rules that matter.

Useful starter combinations:

- Assessment task: `SKILL_ASSESSMENT_TASK_DESIGN.md`, `RULE_ASSESSMENT_STRUCTURE.md`, `RULE_CURRICULUM_ALIGNMENT.md`, `RULE_YEAR_LEVEL_APPROPRIATENESS.md`
- Rubric: `SKILL_RUBRIC_DESIGN.md`, `RULE_RUBRIC_A_TO_E.md`, `RULE_SINGLE_POINT_RUBRIC.md`, `RULE_MARKING_EVIDENCE.md`
- Feedback: `SKILL_FEEDBACK_COMMENTS.md`, `RULE_FEEDBACK_FORMAT.md`, `RULE_MARKING_EVIDENCE.md`, `RULE_NO_UNFAIR_PENALTY.md`
- Research-informed drafting: `SKILL_SOURCE_RESEARCH.md`, `SKILL_SOURCE_EVALUATION.md`, `SKILL_SYNTHESIS.md`, `RULE_SOURCE_HIERARCHY.md`
- Science practical: `RULE_PRACTICAL_SAFETY.md`, `RULE_VARIABLES_AND_FAIR_TESTING.md`, `RULE_DATA_AND_UNCERTAINTY.md`, `RULE_PRIVACY_AND_SAFETY.md`
- Database development: `SKILL_DATABASES.md`, `SKILL_EXCEL_ONLINE.md`, `SKILL_POWER_BI.md`, `RULE_DEVICE_CONSTRAINTS.md`, `RULE_DATA_ETHICS.md`
- Word documents with formulae: `SKILL_DOCX_PRODUCTION.md`, `SKILL_EQUATION_FORMATTING.md`, `RULE_EQUATION_EDITABILITY.md`, `RULE_NO_EQUATION_IMAGES.md`, `RULE_WORD_FORMATTING.md`

Example:

```text
I am going to paste one skill and several rules. Treat them as instructions.
After reading them, create the requested output and briefly list which pasted files you used.
```

### Choosing Files For A Task

Use the skill file for the output type and rule files for the constraints.

Examples:

- To create something: choose a skill.
- To check quality: choose quality-control rules.
- To align to curriculum: choose curriculum rules.
- To design or mark assessment: choose assessment skills and rules.
- To write for students, parents or staff: choose communication and language rules.
- To handle current facts, sources or policy: choose research rules.

If unsure, start with:

- `skills/Core workflow/SKILL_REQUEST_INTAKE.md`
- `skills/Core workflow/SKILL_TASK_PLANNING.md`
- `skills/Core workflow/SKILL_SOURCE_RESEARCH.md`
- `rules/Core behaviour/RULE_FOLLOW_USER_CONTEXT.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`

### Suggested Prompt Pattern

```text
Use the relevant Markdown rules and skills from this repository.

Task:
[describe the teaching task]

Context:
- Year level:
- Subject:
- Audience:
- Platform or format:
- Assessment conditions:
- Sources or curriculum text supplied:

Process:
1. Identify which rule and skill files apply.
2. Research reputable sources if required.
3. Draft the output.
4. Check it against the rules.
5. Provide the final clean output plus a short source note if sources were used.
```

## Recommended Next Work

The current recommended next work is:

1. Tidy `SOURCE_REGISTER.md` and the source-summary bullets in `AGENT_BUILD_PROGRESS.md` for duplicate entries and encoding artefacts.
2. Add local school policy sources before live deployment, especially for AI use, student data, LMS posting, assessment integrity and practical safety.
3. Run human review for files that will be treated as policy, production guidance or school-wide operating instructions.

## Human Review Notes

The drafted files are structured and source-informed, but `Reviewed` means AI self-reviewed. They should still receive human review before being treated as final policy or production guidance. Local school policies, current SACE subject outlines, platform constraints and school-approved assessment practices override or refine the general rules here when they apply.
