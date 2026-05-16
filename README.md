# SASTA Agents

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

Many subject, platform, document-output, lesson-design, communication and specialist workflow files remain to be drafted.

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

Sources should not be fabricated. Source claims should be linked to the files that use them.

## Drafting Conventions

- Use Australian spelling.
- Preserve existing meaningful content.
- Do not rename, move or delete files unless explicitly asked.
- Research reputable sources before drafting current, policy, curriculum, safety, software or evidence-informed content.
- Update `AGENT_BUILD_PROGRESS.md` and `SOURCE_REGISTER.md` after completing files.
- Treat `Reviewed` as an AI self-reviewed draft unless the project later reserves that status for human review.

## Recommended Next Work

The current recommended next batch is:

1. `rules/Communication/RULE_EMAIL_PROFESSIONAL_TONE.md`
2. `rules/Communication/RULE_PARENT_FACING_LANGUAGE.md`
3. `rules/Communication/RULE_STAFF_FACING_LANGUAGE.md`

Likely upcoming clusters after communication include:

- lesson-design rules and skills
- document-output and Word/LMS formatting rules
- chemistry and physics subject rules
- digital technologies and platform-specific rules
- quality-control workflow skills
- AI agent design rules

## Human Review Notes

The drafted files are structured and source-informed, but they should still receive human review before being treated as final policy or production guidance. In particular, local school policies, current SACE subject outlines, platform constraints and school-approved assessment practices may need to override or refine the general rules here.
