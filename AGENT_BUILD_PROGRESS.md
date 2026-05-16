# Agent Build Progress

Last updated: 2026-05-17

## Run Settings

- Maximum files drafted this run: All remaining empty or incomplete files, working one at a time
- Current priority: core workflow skills
- Empty or mostly empty files found: 137
- Rule files found: 78
- Skill files found: 59

## Status Key

- Not started
- Researching
- Drafted
- Reviewed
- Needs human review

## Progress Update Protocol

- Update and save this file immediately after each individual rule or skill file is completed.
- Do not wait until the end of a batch to record progress.
- For each completed file, record the file name, status, short summary of content added, sources used, unresolved issues and recommended next action.
- Keep the full inventory tables current, but use the completed-file log as the live per-file record for Markdown preview refreshes.

## Files Completed This Run

| File | Status | Short summary of content added | Sources used | Unresolved issues | Recommended next action |
| --- | --- | --- | --- | --- | --- |
| `rules/Core behaviour/RULE_ROLE_AND_SCOPE.md` | Reviewed | Defined the agent as an education-focused assistant for South Australian secondary teaching work, including scope boundaries, privacy, assessment integrity and teacher judgement. | Australian Framework for Generative AI in Schools; SA DfE AI in schools; AITSL Australian Professional Standards for Teachers; Australian Curriculum general capabilities | May need school-specific AI and data-use policy wording later. | Use as the broad scope anchor when drafting `RULE_NO_UNREQUESTED_EXPANSION.md` and `RULE_FINAL_CLEAN_OUTPUT.md`. |
| `rules/Core behaviour/RULE_FOLLOW_USER_CONTEXT.md` | Reviewed | Added requirements for using supplied year level, subject, curriculum, platform, audience, assessment conditions and formatting constraints before making assumptions. | SA DfE AI in schools; Australian Curriculum general capabilities; AITSL Australian Professional Standards for Teachers; SACE Learning and assessment plans | Needs later alignment with more specific year-level, SACE and no-overteaching rules. | Cross-reference when drafting `SKILL_REQUEST_INTAKE.md`, `RULE_YEAR_LEVEL_APPROPRIATENESS.md` and `RULE_SACE_ALIGNMENT.md`. |
| `rules/Core behaviour/RULE_CLARIFICATION.md` | Reviewed | Added decision logic for when to ask clarifying questions versus proceeding with stated assumptions, especially for safety, privacy, curriculum, platform and assessment risks. | SA DfE AI in schools; Australian Framework for Generative AI in Schools; AITSL Australian Professional Standards for Teachers | Should be checked against the eventual request-intake skill to avoid duplicated guidance. | Use this as the behaviour rule for future intake and planning skills. |
| `rules/Core behaviour/RULE_AUSTRALIAN_LANGUAGE.md` | Reviewed | Added requirements for Australian English spelling, Australian school terminology, plain language, inclusive language and preserving exact software labels where needed. | Australian Government Style Manual: Spelling; Quick guide: plain language; Inclusive language | May need local school style preferences if the school uses a specific dictionary or terminology list. | Apply across all future skills and rules; cross-reference when drafting communication, feedback and LMS-output files. |
| `rules/Core behaviour/RULE_NO_UNREQUESTED_EXPANSION.md` | Reviewed | Added behavioural limits requiring the agent to stay within the requested task and only add safety, privacy, accuracy, accessibility or usability material when justified. | Australian Framework for Generative AI in Schools; Australian Government Style Manual: Quick guide: plain language; SA DfE AI in schools | May overlap with `RULE_ROLE_AND_SCOPE.md` and future `RULE_NO_OVERTEACHING.md`; keep this rule focused on task scope, not curriculum depth. | Use when drafting task-planning, lesson-sequence and output-review skills. |
| `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md` | Reviewed | Added requirements for final deliverables to be complete, coherent, audience-matched, export-friendly and free of unnecessary process commentary. | Australian Government Style Manual: Home; Quick guide: plain language; SACE Performance standards and grades | Will later need tighter alignment with Word, LMS, equation and code-formatting output rules. | Use as a core quality gate when drafting output-review, Word-export and LMS-ready skills. |
| `skills/Core workflow/SKILL_REQUEST_INTAKE.md` | Reviewed | Added an intake workflow for identifying deliverable, audience, year level, subject, platform, constraints, missing information, assumptions and relevant rules or skills. | SA DfE AI in schools; Australian Curriculum general capabilities; SACE Learning and assessment plans; Australian Government Style Manual: Quick guide: plain language | May need adaptation if a future orchestrator file uses a stricter intake schema. | Use before task planning, curriculum alignment, assessment design and marking workflows. |
| `skills/Core workflow/SKILL_TASK_PLANNING.md` | Reviewed | Added a proportional planning workflow for breaking complex requests into intake, research, drafting, checking, formatting, export and refinement phases. | AERO How students learn best; AERO Explicit instruction practice guide; Australian Government Style Manual: Quick guide: plain language; Australian Framework for Generative AI in Schools | May need later alignment with manual gate checks and automated run mode rules. | Use before multi-output resource, assessment, document-production and agent-design workflows. |
| `skills/Core workflow/SKILL_CURRICULUM_ALIGNMENT.md` | Reviewed | Added a curriculum-alignment workflow distinguishing Australian Curriculum elements, SACE requirements, standards evidence and visible alignment formats. | Australian Curriculum content elements; Australian Curriculum general capabilities; SACE Learning and assessment plans; SACE Performance standards and grades | Needs later cross-check with subject-specific SACE Physics and Chemistry alignment skills. | Use before assessment design, rubric design, lesson sequence planning and SACE subject-specific alignment. |
| `skills/Core workflow/SKILL_SOURCE_RESEARCH.md` | Reviewed | Added a source-research workflow for defining research questions, prioritising official sources, recording sources, checking dates and avoiding fabricated citations. | AERO Evidence use in schools; Australian Government Style Manual: Author-date; Australian Framework for Generative AI in Schools | Needs later alignment with source evaluation and citation rules when those files are drafted. | Use before drafting any current, policy, curriculum, safety, software or evidence-informed content. |
| `skills/Core workflow/SKILL_SOURCE_EVALUATION.md` | Reviewed | Added a source-evaluation workflow for judging authority, accuracy, currency, purpose, bias, relevance, age appropriateness and school suitability. | Monash Question your sources; Monash Library Evaluating information; AERO Evidence use in schools | Needs later alignment with source hierarchy and preferred sources rules. | Use after source research and before synthesis or drafting. |
| `skills/Core workflow/SKILL_SYNTHESIS.md` | Reviewed | Added a synthesis workflow for combining user constraints, official requirements, evaluated sources and classroom judgement into coherent practical outputs. | Monash Create your own argument; AERO Evidence use in schools; Australian Government Style Manual: Structuring content | Needs later alignment with source hierarchy, citation and output-review rules. | Use after source research/evaluation and before final clean output for multi-source tasks. |
| `rules/Curriculum/RULE_CURRICULUM_ALIGNMENT.md` | Reviewed | Added a curriculum alignment rule requiring official or supplied sources, correct use of content descriptions, achievement standards, elaborations and general capabilities, and evidence-based mapping. | Australian Curriculum content elements; Australian Curriculum general capabilities; SACE Performance standards and grades | Needs later cross-check against year-level appropriateness and no-overteaching rules. | Use as the general curriculum validity rule before drafting subject-specific alignment rules. |
| `rules/Curriculum/RULE_SACE_ALIGNMENT.md` | Reviewed | Added SACE alignment requirements for subject outlines, LAPs, assessment types, performance standards, stage differences, academic integrity and provisional-use warnings. | SACE Learning and assessment plans; SACE General assessment information; SACE Performance standards and grades; SACE Physics school assessment; SACE Chemistry overview | Subject-specific Physics and Chemistry alignment skills still need current subject-outline detail. | Draft `SKILL_SACE_PHYSICS_ALIGNMENT.md` and `SKILL_SACE_CHEMISTRY_ALIGNMENT.md` later using current subject outlines. |
| `rules/Curriculum/RULE_YEAR_LEVEL_APPROPRIATENESS.md` | Reviewed | Added requirements for matching language, cognitive demand, scaffolding, examples and assessment expectations to the stated year level or SACE stage. | Australian Curriculum content elements; AERO How students learn best; AERO Teach explicitly | Needs later interaction with lesson differentiation and assessment design rules. | Use before drafting lesson design, tutorial, assessment and feedback files. |
| `rules/Curriculum/RULE_NO_OVERTEACHING.md` | Reviewed | Added limits against unnecessary theory, advanced concepts, edge cases and hidden extension expectations beyond the requested learning goal. | AERO How students learn best; AERO Teach explicitly; Australian Government Style Manual: Quick guide: plain language | Needs later cross-check with extension-task and differentiation skills so extension remains optional. | Use as a guardrail for student-facing tutorials, worked examples, lesson plans and assessments. |
| `rules/Research/RULE_SOURCE_HIERARCHY.md` | Reviewed | Added a hierarchy prioritising user-supplied approved material, official sources, professional bodies, research syntheses and reputable explainers. | Monash Evaluating information; Monash Question your sources; AERO Evidence use in schools | Needs later platform-specific source expectations for Microsoft, Scratch, micro:bit and GameMaker files. | Use with all research and citation rules. |
| `rules/Research/RULE_RESEARCH_REQUIRED.md` | Reviewed | Added triggers for mandatory research when information is current, high-stakes, jurisdiction-specific, source-dependent or explicitly requested. | AERO Evidence use in schools; Monash Question your sources; Australian Framework for Generative AI in Schools | Needs later integration with automated run mode and output review rules. | Use before drafting any policy, curriculum, SACE, safety, privacy or software-dependent file. |
| `rules/Research/RULE_PREFERRED_SOURCES.md` | Reviewed | Added preferred source categories for Australian Curriculum, SACE, SA DfE, AERO, AITSL, eSafety, official software documentation and university guidance. | Monash Evaluating information; AERO Evidence use in schools; SA DfE AI in schools | Needs later addition of exact vendor documentation when platform files are drafted. | Use as source selection guidance for all future drafting. |
| `rules/Research/RULE_CITATION_AND_BIBLIOGRAPHY.md` | Reviewed | Added citation and bibliography requirements, project source-list formats, source-register expectations and safeguards against invented citations. | Australian Government Style Manual: Author-date; Monash Evaluating information; Australian Government Style Manual: Quick guide: plain language | Needs later alignment with document-output and bibliography formatting skills. | Use whenever sources are cited or added to `SOURCE_REGISTER.md`. |
| `rules/Research/RULE_THREE_PASS_RESEARCH.md` | Reviewed | Added an orient, verify and synthesise research pattern for source-dependent tasks, including stopping rules and source filtering. | Monash Question your sources; Monash Evaluating information; Monash Create your own argument | Needs later integration with automated run mode and source-research skill variants. | Use for non-trivial research before drafting. |
| `rules/Research/RULE_RESEARCH_SCREEN_OUTPUT.md` | Reviewed | Added guidance for presenting research findings cleanly, separating deliverables from source notes, and avoiding raw search-log clutter. | Australian Government Style Manual: Structuring content; Quick guide: plain language; Author-date | Needs later alignment with final-output and document-export rules. | Use when reporting researched work to the user or writing source sections. |
| `rules/Quality control/RULE_ACCESSIBILITY.md` | Reviewed | Added accessibility requirements for structure, plain language, colour use, links, image descriptions, simple tables and copy-safe formatting. | Australian Government Style Manual: Make content accessible; Quick guide: plain language; Inclusive language | Needs later alignment with document and LMS output skills. | Use before finalising student-facing, LMS-ready, Word-ready and parent-facing resources. |
| `rules/Quality control/RULE_ACCURACY_CHECK.md` | Reviewed | Added requirements for checking facts, calculations, units, code, terminology, curriculum, SACE, policy and source claims before finalising. | SA DfE AI in schools; Australian Framework for Generative AI in Schools; Monash Question your sources | Needs later subject-specific checks for science, chemistry, physics and programming files. | Use as a general verification rule for all output review. |
| `rules/Quality control/RULE_CLASSROOM_REALISM.md` | Reviewed | Added checks for time, equipment, preparation, supervision, platform access, student readiness, evidence collection and marking workload. | AERO How students learn best; AERO Teach explicitly; AITSL Australian Professional Standards for Teachers | Needs later alignment with lesson-sequence, relief-lesson and practical-investigation skills. | Use before drafting or reviewing lesson, assessment and practical activity outputs. |
| `rules/Quality control/RULE_COMPLETENESS_CHECK.md` | Reviewed | Added a final completeness rule for answering all request parts, including required sections, aligned evidence, tracking updates, assumptions and unresolved issues. | Australian Government Style Manual: Structuring content; Quick guide: plain language; Author-date | Needs later pairing with automated output-review checklist rules. | Use before final responses and after file batches. |
| `rules/Quality control/RULE_NO_HALLUCINATED_FILES.md` | Reviewed | Added safeguards against inventing files, paths, sources, edits, screenshots, exports, test results or completed work. | SA DfE AI in schools; Australian Framework for Generative AI in Schools; Monash Question your sources | Needs later integration with automated run mode and document-production workflows. | Use when reporting file work, source lists and verification results. |
| `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md` | Reviewed | Added privacy and safety requirements for personal information, AI tools, anonymisation, practical risk, supervision, academic integrity and policy review. | OAIC Guidance on privacy and AI products; OAIC Guide to securing personal information; SA DfE AI in schools | Needs later subject-specific safety detail for science, electronics and cybersecurity. | Use before drafting tasks involving students, personal data, online tools, practical work or assessment integrity. |
| `rules/Science/RULE_SCIENCE_ACCURACY.md` | Reviewed | Added science accuracy requirements for terminology, evidence, units, models, diagrams, data, conclusions and age-appropriate simplification. | Australian Curriculum Science; Australian Curriculum content elements; AERO Evidence use in schools | Needs later subject-specific chemistry and physics notation/detail checks. | Use before drafting science, chemistry or physics explanations and answer keys. |
| `rules/Science/RULE_PRACTICAL_SAFETY.md` | Reviewed | Added practical safety requirements for hazards, controls, PPE, supervision, disposal, local risk assessment and teacher-facing safety notes. | Science ASSIST; Australian Curriculum Science; AITSL Australian Professional Standards for Teachers | Needs local school risk assessment processes and lab technician practices where available. | Use before any practical investigation or demonstration file. |
| `rules/Science/RULE_VARIABLES_AND_FAIR_TESTING.md` | Reviewed | Added guidance for investigation questions, independent/dependent/controlled variables, fair tests, repeated trials, data tables and non-fair-test inquiry types. | Australian Curriculum Science; ANSTO Science Inquiry Skills; AERO How students learn best | Needs later alignment with practical investigation skills and assessment rubrics. | Use for junior science, chemistry and physics investigation tasks. |
| `rules/Science/RULE_DATA_AND_UNCERTAINTY.md` | Reviewed | Added guidance for units, precision, repeated measurements, anomalous data, graph choice, uncertainty, validity, reliability and evidence-limited conclusions. | Australian Curriculum Science; VCAA Data and Measurement terminology; Australia's measurement system | Needs later alignment with physics graph interpretation and SACE investigation skills. | Use before graphing, data analysis and practical report tasks. |
| `rules/Assessment/RULE_ASSESSMENT_STRUCTURE.md` | Reviewed | Added assessment structure requirements for task purpose, student instructions, evidence, conditions, criteria, integrity and teacher-facing notes. | AITSL Australian Professional Standards for Teachers; SACE Performance standards and grades; Australian Curriculum content elements | Needs later alignment with assessment-task design skill. | Use before drafting assessment tasks and task sheets. |
| `rules/Assessment/RULE_MARKING_EVIDENCE.md` | Reviewed | Added evidence-based marking requirements linking judgements to submitted work, criteria, standards and verification limits. | SACE Performance standards and grades; AITSL Australian Professional Standards for Teachers; SACE Verification of student work | Needs later alignment with student-work marking skill. | Use before marking, feedback and grade explanations. |
| `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md` | Reviewed | Added safeguards against hidden expectations, double penalties, unsupported integrity penalties and non-criterion-based deductions. | AITSL Australian Professional Standards for Teachers; SACE Verifying assessment conditions; Australian Government Style Manual: Make content accessible | Needs later alignment with accommodations and accessibility rules. | Use in marking guides, rubrics and student-work marking. |
| `rules/Assessment/RULE_RUBRIC_A_TO_E.md` | Reviewed | Added A-E rubric requirements for evidence-quality descriptors, task-specific criteria, standards alignment and avoiding invented grade boundaries. | SACE Performance standards and grades; QCAA Standards elaborations; Australian Curriculum content elements | Needs later SACE subject-specific performance standard detail. | Use for graded rubrics and marking guides. |
| `rules/Assessment/RULE_SINGLE_POINT_RUBRIC.md` | Reviewed | Added single-point rubric structure for expected evidence, strengths and next steps, especially for formative feedback. | AITSL Australian Professional Standards for Teachers; Australian Government Style Manual: Quick guide: plain language; Australian Curriculum content elements | Needs later feedback-comments skill integration. | Use for formative rubrics, drafts, peer review and self-assessment. |
| `rules/Assessment/RULE_FEEDBACK_FORMAT.md` | Reviewed | Added feedback format requirements for evidence, learning implication, concise strengths and manageable next steps. | AITSL Australian Professional Standards for Teachers; SACE Performance standards and grades; Australian Government Style Manual: Quick guide: plain language | Needs later communication and report-writing alignment. | Use for feedback comments, marking notes and reports. |
| `rules/Assessment/RULE_YEAR_8_ASSESSMENT.md` | Reviewed | Added Year 8 assessment requirements for curriculum alignment, clear instructions, scaffolding, manageable criteria, evidence requirements and extension separation. | Australian Curriculum content elements; AERO How students learn best; AERO Teach explicitly | Needs later subject-specific Year 8 digital technologies and science examples. | Use when designing or reviewing Year 8 assessment tasks. |
| `skills/Assessment/SKILL_ASSESSMENT_TASK_DESIGN.md` | Reviewed | Added workflow for designing assessment tasks with purpose, framework, evidence, conditions, criteria, integrity and teacher notes. | AITSL Australian Professional Standards for Teachers; SACE Performance standards and grades; Australian Curriculum content elements | Needs later examples for SACE science, Year 8 science and digital technologies. | Use for new assessment task requests. |
| `skills/Assessment/SKILL_RUBRIC_DESIGN.md` | Reviewed | Added workflow for choosing A-E, single-point or checklist rubric formats and writing evidence-based descriptors. | SACE Performance standards and grades; QCAA Standards elaborations; Australian Curriculum content elements | Needs later integration with subject-specific rubric examples. | Use for rubric and success-criteria requests. |
| `skills/Assessment/SKILL_MARKING_GUIDE.md` | Reviewed | Added workflow for expected evidence, marking notes, acceptable alternatives, partial evidence and integrity notes. | SACE Performance standards and grades; SACE Verification of student work; AITSL Australian Professional Standards for Teachers | Needs later answer-key examples for science and programming. | Use for teacher marking guides and answer keys. |
| `skills/Assessment/SKILL_STUDENT_WORK_MARKING.md` | Reviewed | Added workflow for de-identified evidence mapping, provisional judgement, feedback and teacher checks. | SACE Performance standards and grades; SACE Verification of student work; OAIC Guidance on privacy and AI products | Needs later process for batch marking if supplied work is large. | Use when marking or reviewing student work. |
| `skills/Assessment/SKILL_FEEDBACK_COMMENTS.md` | Reviewed | Added workflow for concise evidence-based strengths and next steps, with tone, privacy and audience checks. | AITSL Australian Professional Standards for Teachers; Australian Government Style Manual: Quick guide: plain language; SACE Performance standards and grades | Needs later alignment with communication length rules. | Use for student feedback and rubric comments. |
| `skills/Assessment/SKILL_REPORT_WRITING.md` | Reviewed | Added workflow for parent-facing report comments from supplied evidence, with strength, next step, tone, length and privacy checks. | AITSL Australian Professional Standards for Teachers; Australian Government Style Manual: Quick guide: plain language; Inclusive language | Needs later alignment with parent-facing language and report comment length rules. | Use for report comments and parent-facing achievement summaries. |

## Rule Files

| File | Status | Sources used | Notes |
| --- | --- | --- | --- |
| `rules/AI agent design/RULE_AGENT_FILE_STRUCTURE.md` | Not started |  |  |
| `rules/AI agent design/RULE_AUTOMATED_RUN_MODE.md` | Not started |  |  |
| `rules/AI agent design/RULE_MANUAL_GATE_CHECKS.md` | Not started |  |  |
| `rules/AI agent design/RULE_ORCHESTRATOR_CONTROL.md` | Not started |  |  |
| `rules/AI agent design/RULE_OUTPUT_REVIEW_CHECKLIST.md` | Not started |  |  |
| `rules/AI agent design/RULE_SKILL_RULE_SEPARATION.md` | Not started |  |  |
| `rules/Assessment/RULE_ASSESSMENT_STRUCTURE.md` | Reviewed | AITSL Australian Professional Standards for Teachers; SACE Performance standards and grades; Australian Curriculum content elements | Completed this run. |
| `rules/Assessment/RULE_FEEDBACK_FORMAT.md` | Reviewed | AITSL Australian Professional Standards for Teachers; SACE Performance standards and grades; Australian Government Style Manual: Quick guide: plain language | Completed this run. |
| `rules/Assessment/RULE_MARKING_EVIDENCE.md` | Reviewed | SACE Performance standards and grades; AITSL Australian Professional Standards for Teachers; SACE Verification of student work | Completed this run. |
| `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md` | Reviewed | AITSL Australian Professional Standards for Teachers; SACE Verifying assessment conditions; Australian Government Style Manual: Make content accessible | Completed this run. |
| `rules/Assessment/RULE_RUBRIC_A_TO_E.md` | Reviewed | SACE Performance standards and grades; QCAA Standards elaborations; Australian Curriculum content elements | Completed this run. |
| `rules/Assessment/RULE_SINGLE_POINT_RUBRIC.md` | Reviewed | AITSL Australian Professional Standards for Teachers; Australian Government Style Manual: Quick guide: plain language; Australian Curriculum content elements | Completed this run. |
| `rules/Assessment/RULE_YEAR_8_ASSESSMENT.md` | Reviewed | Australian Curriculum content elements; AERO How students learn best; AERO Teach explicitly | Completed this run. |
| `rules/Chemistry/RULE_BALANCING_EQUATIONS.md` | Not started |  |  |
| `rules/Chemistry/RULE_CHEMISTRY_NOTATION.md` | Not started |  |  |
| `rules/Chemistry/RULE_CHEMISTRY_WORKED_EXAMPLES.md` | Not started |  |  |
| `rules/Communication/RULE_EMAIL_PROFESSIONAL_TONE.md` | Not started |  |  |
| `rules/Communication/RULE_PARENT_FACING_LANGUAGE.md` | Not started |  |  |
| `rules/Communication/RULE_STAFF_FACING_LANGUAGE.md` | Not started |  |  |
| `rules/Communication/RULE_STUDENT_COMMENT_LENGTH.md` | Not started |  |  |
| `rules/Core behaviour/RULE_AUSTRALIAN_LANGUAGE.md` | Reviewed | Australian Government Style Manual: Spelling; Quick guide: plain language; Inclusive language | Completed this run. |
| `rules/Core behaviour/RULE_CLARIFICATION.md` | Reviewed | Australian Framework for Generative AI in Schools; SA DfE AI in schools; AITSL Australian Professional Standards for Teachers | Completed this run. |
| `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md` | Reviewed | Australian Government Style Manual: Home; Quick guide: plain language; SACE Performance standards and grades | Completed this run. |
| `rules/Core behaviour/RULE_FOLLOW_USER_CONTEXT.md` | Reviewed | SA DfE AI in schools; Australian Curriculum general capabilities; AITSL Australian Professional Standards for Teachers; SACE Learning and assessment plans | Completed this run. |
| `rules/Core behaviour/RULE_NO_UNREQUESTED_EXPANSION.md` | Reviewed | Australian Framework for Generative AI in Schools; Australian Government Style Manual: Quick guide: plain language; SA DfE AI in schools | Completed this run. |
| `rules/Core behaviour/RULE_ROLE_AND_SCOPE.md` | Reviewed | Australian Framework for Generative AI in Schools; SA DfE AI in schools; AITSL Australian Professional Standards for Teachers; Australian Curriculum general capabilities | Completed this run. |
| `rules/Curriculum/RULE_CURRICULUM_ALIGNMENT.md` | Reviewed | Australian Curriculum content elements; Australian Curriculum general capabilities; SACE Performance standards and grades | Completed this run. |
| `rules/Curriculum/RULE_NO_OVERTEACHING.md` | Reviewed | AERO How students learn best; AERO Teach explicitly; Australian Government Style Manual: Quick guide: plain language | Completed this run. |
| `rules/Curriculum/RULE_SACE_ALIGNMENT.md` | Reviewed | SACE Learning and assessment plans; SACE General assessment information; SACE Performance standards and grades; SACE Physics school assessment; SACE Chemistry overview | Completed this run. |
| `rules/Curriculum/RULE_YEAR_LEVEL_APPROPRIATENESS.md` | Reviewed | Australian Curriculum content elements; AERO How students learn best; AERO Teach explicitly | Completed this run. |
| `rules/Digital technologies/RULE_BEGINNER_PROGRAMMING.md` | Not started |  |  |
| `rules/Digital technologies/RULE_CODE_CLARITY.md` | Not started |  |  |
| `rules/Digital technologies/RULE_DATA_ETHICS.md` | Not started |  |  |
| `rules/Digital technologies/RULE_DEBUGGING_EXPLANATION.md` | Not started |  |  |
| `rules/Digital technologies/RULE_DEVICE_CONSTRAINTS.md` | Not started |  |  |
| `rules/Digital technologies/RULE_PSEUDOCODE_FIRST.md` | Not started |  |  |
| `rules/Document output/RULE_CODE_FORMATTING.md` | Not started |  |  |
| `rules/Document output/RULE_EXPORT_READY_STRUCTURE.md` | Not started |  |  |
| `rules/Document output/RULE_HEADING_STYLES.md` | Not started |  |  |
| `rules/Document output/RULE_NO_FORMATTING_COLLISIONS.md` | Not started |  |  |
| `rules/Document output/RULE_TABLE_STYLE.md` | Not started |  |  |
| `rules/Document output/RULE_WORD_FORMATTING.md` | Not started |  |  |
| `rules/Equations/RULE_EQUATION_EDITABILITY.md` | Not started |  |  |
| `rules/Equations/RULE_LATEX_PRESERVATION.md` | Not started |  |  |
| `rules/Equations/RULE_NO_EQUATION_IMAGES.md` | Not started |  |  |
| `rules/Equations/RULE_UNITS_IN_EQUATIONS.md` | Not started |  |  |
| `rules/Lesson design/RULE_COMMON_MISTAKES.md` | Not started |  |  |
| `rules/Lesson design/RULE_DIFFERENTIATION.md` | Not started |  |  |
| `rules/Lesson design/RULE_LEARNING_INTENTIONS_SUCCESS_CRITERIA.md` | Not started |  |  |
| `rules/Lesson design/RULE_SCAFFOLDED_INSTRUCTION.md` | Not started |  |  |
| `rules/Lesson design/RULE_STUDENT_FACING_TONE.md` | Not started |  |  |
| `rules/Lesson design/RULE_TEACHER_FACING_TONE.md` | Not started |  |  |
| `rules/Physics/RULE_GRAPH_INTERPRETATION.md` | Not started |  |  |
| `rules/Physics/RULE_PHYSICS_NOTATION.md` | Not started |  |  |
| `rules/Physics/RULE_PHYSICS_UNITS.md` | Not started |  |  |
| `rules/Physics/RULE_PHYSICS_WORKED_EXAMPLES.md` | Not started |  |  |
| `rules/Platforms/RULE_EXCEL_ONLINE_CONTEXT.md` | Not started |  |  |
| `rules/Platforms/RULE_FROG_STILE_DAYMAP.md` | Not started |  |  |
| `rules/Platforms/RULE_GAMEMAKER_CONTEXT.md` | Not started |  |  |
| `rules/Platforms/RULE_MICROBIT_CONTEXT.md` | Not started |  |  |
| `rules/Platforms/RULE_POWER_BI_ONLINE_CONTEXT.md` | Not started |  |  |
| `rules/Platforms/RULE_SCRATCH_CONTEXT.md` | Not started |  |  |
| `rules/Quality control/RULE_ACCESSIBILITY.md` | Reviewed | Australian Government Style Manual: Make content accessible; Quick guide: plain language; Inclusive language | Completed this run. |
| `rules/Quality control/RULE_ACCURACY_CHECK.md` | Reviewed | SA DfE AI in schools; Australian Framework for Generative AI in Schools; Monash Question your sources | Completed this run. |
| `rules/Quality control/RULE_CLASSROOM_REALISM.md` | Reviewed | AERO How students learn best; AERO Teach explicitly; AITSL Australian Professional Standards for Teachers | Completed this run. |
| `rules/Quality control/RULE_COMPLETENESS_CHECK.md` | Reviewed | Australian Government Style Manual: Structuring content; Quick guide: plain language; Author-date | Completed this run. |
| `rules/Quality control/RULE_NO_HALLUCINATED_FILES.md` | Reviewed | SA DfE AI in schools; Australian Framework for Generative AI in Schools; Monash Question your sources | Completed this run. |
| `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md` | Reviewed | OAIC Guidance on privacy and AI products; OAIC Guide to securing personal information; SA DfE AI in schools | Completed this run. |
| `rules/Research/RULE_CITATION_AND_BIBLIOGRAPHY.md` | Reviewed | Australian Government Style Manual: Author-date; Monash Evaluating information; Australian Government Style Manual: Quick guide: plain language | Completed this run. |
| `rules/Research/RULE_PREFERRED_SOURCES.md` | Reviewed | Monash Evaluating information; AERO Evidence use in schools; SA DfE AI in schools | Completed this run. |
| `rules/Research/RULE_RESEARCH_REQUIRED.md` | Reviewed | AERO Evidence use in schools; Monash Question your sources; Australian Framework for Generative AI in Schools | Completed this run. |
| `rules/Research/RULE_RESEARCH_SCREEN_OUTPUT.md` | Reviewed | Australian Government Style Manual: Structuring content; Quick guide: plain language; Author-date | Completed this run. |
| `rules/Research/RULE_SOURCE_HIERARCHY.md` | Reviewed | Monash Evaluating information; Monash Question your sources; AERO Evidence use in schools | Completed this run. |
| `rules/Research/RULE_THREE_PASS_RESEARCH.md` | Reviewed | Monash Question your sources; Monash Evaluating information; Monash Create your own argument | Completed this run. |
| `rules/Science/RULE_DATA_AND_UNCERTAINTY.md` | Reviewed | Australian Curriculum Science; VCAA Data and Measurement terminology; Australia's measurement system | Completed this run. |
| `rules/Science/RULE_PRACTICAL_SAFETY.md` | Reviewed | Science ASSIST; Australian Curriculum Science; AITSL Australian Professional Standards for Teachers | Completed this run. |
| `rules/Science/RULE_SCIENCE_ACCURACY.md` | Reviewed | Australian Curriculum Science; Australian Curriculum content elements; AERO Evidence use in schools | Completed this run. |
| `rules/Science/RULE_VARIABLES_AND_FAIR_TESTING.md` | Reviewed | Australian Curriculum Science; ANSTO Science Inquiry Skills; AERO How students learn best | Completed this run. |

## Skill Files

| File | Status | Sources used | Notes |
| --- | --- | --- | --- |
| `skills/Assessment/SKILL_ASSESSMENT_TASK_DESIGN.md` | Reviewed | AITSL Australian Professional Standards for Teachers; SACE Performance standards and grades; Australian Curriculum content elements | Completed this run. |
| `skills/Assessment/SKILL_FEEDBACK_COMMENTS.md` | Reviewed | AITSL Australian Professional Standards for Teachers; Australian Government Style Manual: Quick guide: plain language; SACE Performance standards and grades | Completed this run. |
| `skills/Assessment/SKILL_MARKING_GUIDE.md` | Reviewed | SACE Performance standards and grades; SACE Verification of student work; AITSL Australian Professional Standards for Teachers | Completed this run. |
| `skills/Assessment/SKILL_REPORT_WRITING.md` | Reviewed | AITSL Australian Professional Standards for Teachers; Australian Government Style Manual: Quick guide: plain language; Inclusive language | Completed this run. |
| `skills/Assessment/SKILL_RUBRIC_DESIGN.md` | Reviewed | SACE Performance standards and grades; QCAA Standards elaborations; Australian Curriculum content elements | Completed this run. |
| `skills/Assessment/SKILL_STUDENT_WORK_MARKING.md` | Reviewed | SACE Performance standards and grades; SACE Verification of student work; OAIC Guidance on privacy and AI products | Completed this run. |
| `skills/Chemistry/SKILL_CHEMICAL_EQUATIONS.md` | Not started |  |  |
| `skills/Chemistry/SKILL_CHEMISTRY_PRACTICAL_INVESTIGATIONS.md` | Not started |  |  |
| `skills/Chemistry/SKILL_CHEMISTRY_WORKED_EXAMPLES.md` | Not started |  |  |
| `skills/Chemistry/SKILL_REACTION_RATES.md` | Not started |  |  |
| `skills/Chemistry/SKILL_SACE_CHEMISTRY_ALIGNMENT.md` | Not started |  |  |
| `skills/Core workflow/SKILL_CURRICULUM_ALIGNMENT.md` | Reviewed | Australian Curriculum content elements; Australian Curriculum general capabilities; SACE Learning and assessment plans; SACE Performance standards and grades | Completed this run. |
| `skills/Core workflow/SKILL_REQUEST_INTAKE.md` | Reviewed | SA DfE AI in schools; Australian Curriculum general capabilities; SACE Learning and assessment plans; Australian Government Style Manual: Quick guide: plain language | Completed this run. |
| `skills/Core workflow/SKILL_SOURCE_EVALUATION.md` | Reviewed | Monash Question your sources; Monash Library Evaluating information; AERO Evidence use in schools | Completed this run. |
| `skills/Core workflow/SKILL_SOURCE_RESEARCH.md` | Reviewed | AERO Evidence use in schools; Australian Government Style Manual: Author-date; Australian Framework for Generative AI in Schools | Completed this run. |
| `skills/Core workflow/SKILL_SYNTHESIS.md` | Reviewed | Monash Create your own argument; AERO Evidence use in schools; Australian Government Style Manual: Structuring content | Completed this run. |
| `skills/Core workflow/SKILL_TASK_PLANNING.md` | Reviewed | AERO How students learn best; AERO Explicit instruction practice guide; Australian Government Style Manual: Quick guide: plain language; Australian Framework for Generative AI in Schools | Completed this run. |
| `skills/Digital Technologies/SKILL_CYBERSECURITY_CONTEXTS.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_DATA_ANALYSIS.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_DATABASES.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_EXCEL_ONLINE.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_GAMEMAKER_GML.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_HTML_CSS.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_POWER_BI.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_PYTHON_INTRO.md` | Not started |  |  |
| `skills/Digital Technologies/SKILL_SCRATCH_PROGRAMMING.md` | Not started |  |  |
| `skills/Documents/SKILL_CODE_FORMATTING.md` | Not started |  |  |
| `skills/Documents/SKILL_DOCX_PRODUCTION.md` | Not started |  |  |
| `skills/Documents/SKILL_EQUATION_FORMATTING.md` | Not started |  |  |
| `skills/Documents/SKILL_TABLE_FORMATTING.md` | Not started |  |  |
| `skills/Documents/SKILL_WORD_EXPORT_FORMATTING.md` | Not started |  |  |
| `skills/Electronics/SKILL_ELECTRONICS_CIRCUITS.md` | Not started |  |  |
| `skills/Electronics/SKILL_MICROBIT_PROGRAMMING.md` | Not started |  |  |
| `skills/Electronics/SKILL_ROBOTICS_PROGRAMMING.md` | Not started |  |  |
| `skills/Electronics/SKILL_SENSOR_SYSTEMS.md` | Not started |  |  |
| `skills/LMS and school systems/SKILL_LMS_READY_OUTPUT.md` | Not started |  |  |
| `skills/LMS and school systems/SKILL_PARENT_COMMUNICATION.md` | Not started |  |  |
| `skills/LMS and school systems/SKILL_STAFF_COMMUNICATION.md` | Not started |  |  |
| `skills/Lesson design/SKILL_DIFFERENTIATION.md` | Not started |  |  |
| `skills/Lesson design/SKILL_EXTENSION_TASKS.md` | Not started |  |  |
| `skills/Lesson design/SKILL_LESSON_SEQUENCE_PLANNING.md` | Not started |  |  |
| `skills/Lesson design/SKILL_RELIEF_LESSON.md` | Not started |  |  |
| `skills/Lesson design/SKILL_STUDENT_FACING_TUTORIAL.md` | Not started |  |  |
| `skills/Lesson design/SKILL_TEACHER_NOTES.md` | Not started |  |  |
| `skills/Media/SKILL_AI_VOICEOVER_SCRIPT.md` | Not started |  |  |
| `skills/Media/SKILL_SCREEN_RECORDING_TUTORIAL.md` | Not started |  |  |
| `skills/Media/SKILL_VIDEO_TRANSCRIPT.md` | Not started |  |  |
| `skills/PD and leadership/SKILL_AI_AGENT_DESIGN.md` | Not started |  |  |
| `skills/PD and leadership/SKILL_PD_SESSION_DESIGN.md` | Not started |  |  |
| `skills/PD and leadership/SKILL_PRESENTATION_PLANNING.md` | Not started |  |  |
| `skills/PD and leadership/SKILL_RULESET_DEVELOPMENT.md` | Not started |  |  |
| `skills/Physics/SKILL_PHYSICS_GRAPH_ANALYSIS.md` | Not started |  |  |
| `skills/Physics/SKILL_PHYSICS_PRACTICAL_INVESTIGATIONS.md` | Not started |  |  |
| `skills/Physics/SKILL_PHYSICS_WORKED_EXAMPLES.md` | Not started |  |  |
| `skills/Physics/SKILL_SACE_PHYSICS_ALIGNMENT.md` | Not started |  |  |
| `skills/Physics/SKILL_TRACKER_VIDEO_ANALYSIS.md` | Not started |  |  |
| `skills/Quality control/SKILL_CLASSROOM_IMPLEMENTATION_CHECK.md` | Not started |  |  |
| `skills/Quality control/SKILL_OUTPUT_REVIEW.md` | Not started |  |  |
| `skills/Quality control/SKILL_SAFETY_AND_RISK_CHECK.md` | Not started |  |  |

## Sources Used So Far

- Spelling — Australian Government Style Manual — used in `RULE_AUSTRALIAN_LANGUAGE.md`.
- Home — Australian Government Style Manual — used in `RULE_FINAL_CLEAN_OUTPUT.md`.
- How students learn best: An overview of the evidence — Australian Education Research Organisation — used in `SKILL_TASK_PLANNING.md`, `RULE_YEAR_LEVEL_APPROPRIATENESS.md` and `RULE_NO_OVERTEACHING.md`.
- Teach explicitly - Australian Education Research Organisation - used in `RULE_YEAR_LEVEL_APPROPRIATENESS.md` and `RULE_NO_OVERTEACHING.md`.
- Make content accessible - Australian Government Style Manual - used in `RULE_ACCESSIBILITY.md`.
- Explicit instruction: Practice guide — Australian Education Research Organisation — used in `SKILL_TASK_PLANNING.md`.
- Evidence use in schools national snapshot: Summary of findings — Australian Education Research Organisation — used in `SKILL_SOURCE_RESEARCH.md`, `SKILL_SOURCE_EVALUATION.md`, `SKILL_SYNTHESIS.md`, `RULE_SOURCE_HIERARCHY.md`, `RULE_RESEARCH_REQUIRED.md` and `RULE_PREFERRED_SOURCES.md`.
- Create your own argument - Monash University - used in `SKILL_SYNTHESIS.md` and `RULE_THREE_PASS_RESEARCH.md`.
- Structuring content - Australian Government Style Manual - used in `SKILL_SYNTHESIS.md`, `RULE_RESEARCH_SCREEN_OUTPUT.md` and `RULE_COMPLETENESS_CHECK.md`.
- Question your sources — Monash University — used in `SKILL_SOURCE_EVALUATION.md`, `RULE_SOURCE_HIERARCHY.md`, `RULE_RESEARCH_REQUIRED.md`, `RULE_THREE_PASS_RESEARCH.md`, `RULE_ACCURACY_CHECK.md` and `RULE_NO_HALLUCINATED_FILES.md`.
- Evaluating information — Monash University Library — used in `SKILL_SOURCE_EVALUATION.md`, `RULE_SOURCE_HIERARCHY.md`, `RULE_PREFERRED_SOURCES.md`, `RULE_CITATION_AND_BIBLIOGRAPHY.md` and `RULE_THREE_PASS_RESEARCH.md`.
- About the curriculum content elements — Australian Curriculum — used in `SKILL_CURRICULUM_ALIGNMENT.md`, `RULE_CURRICULUM_ALIGNMENT.md`, `RULE_YEAR_LEVEL_APPROPRIATENESS.md`, `RULE_ASSESSMENT_STRUCTURE.md`, `RULE_RUBRIC_A_TO_E.md`, `RULE_SINGLE_POINT_RUBRIC.md`, `RULE_YEAR_8_ASSESSMENT.md`, `SKILL_ASSESSMENT_TASK_DESIGN.md` and `SKILL_RUBRIC_DESIGN.md`.
- Science - Australian Curriculum - used in `RULE_SCIENCE_ACCURACY.md`, `RULE_PRACTICAL_SAFETY.md`, `RULE_VARIABLES_AND_FAIR_TESTING.md` and `RULE_DATA_AND_UNCERTAINTY.md`.
- About Science Assist - Australian Science Teachers Association - used in `RULE_PRACTICAL_SAFETY.md`.
- Science Inquiry Skills - Australian Nuclear Science and Technology Organisation - used in `RULE_VARIABLES_AND_FAIR_TESTING.md`.
- Unpacking the terminology - Data and Measurement in VCE Biology - Victorian Curriculum and Assessment Authority - used in `RULE_DATA_AND_UNCERTAINTY.md`.
- Australia's measurement system - Department of Industry, Science and Resources - used in `RULE_DATA_AND_UNCERTAINTY.md`.
- General assessment information for teachers - SACE Board of South Australia - used in `RULE_SACE_ALIGNMENT.md`.
- Verification of student work - SACE Board of South Australia - used in `RULE_MARKING_EVIDENCE.md`, `SKILL_MARKING_GUIDE.md` and `SKILL_STUDENT_WORK_MARKING.md`.
- Verifying assessment conditions that support learning - SACE Board of South Australia - used in `RULE_NO_UNFAIR_PENALTY.md`.
- Standards elaborations - Queensland Curriculum and Assessment Authority - used in `RULE_RUBRIC_A_TO_E.md`.
- School assessment - Physics - SACE Board of South Australia - used in `RULE_SACE_ALIGNMENT.md`.
- Overview - Chemistry - SACE Board of South Australia - used in `RULE_SACE_ALIGNMENT.md`.
- Quick guide: plain language — Australian Government Style Manual — used in `RULE_AUSTRALIAN_LANGUAGE.md`, `RULE_NO_UNREQUESTED_EXPANSION.md`, `RULE_FINAL_CLEAN_OUTPUT.md`, `SKILL_REQUEST_INTAKE.md`, `SKILL_TASK_PLANNING.md`, `RULE_NO_OVERTEACHING.md`, `RULE_CITATION_AND_BIBLIOGRAPHY.md`, `RULE_RESEARCH_SCREEN_OUTPUT.md`, `RULE_ACCESSIBILITY.md`, `RULE_COMPLETENESS_CHECK.md`, `RULE_SINGLE_POINT_RUBRIC.md`, `RULE_FEEDBACK_FORMAT.md`, `SKILL_FEEDBACK_COMMENTS.md` and `SKILL_REPORT_WRITING.md`.
- Inclusive language — Australian Government Style Manual — used in `RULE_AUSTRALIAN_LANGUAGE.md`, `RULE_ACCESSIBILITY.md` and `SKILL_REPORT_WRITING.md`.
- Author-date — Australian Government Style Manual — used in `SKILL_SOURCE_RESEARCH.md`, `RULE_CITATION_AND_BIBLIOGRAPHY.md`, `RULE_RESEARCH_SCREEN_OUTPUT.md` and `RULE_COMPLETENESS_CHECK.md`.
- Australian Framework for Generative Artificial Intelligence (AI) in Schools — Australian Government Department of Education — used in `RULE_ROLE_AND_SCOPE.md`, `RULE_CLARIFICATION.md`, `RULE_NO_UNREQUESTED_EXPANSION.md`, `SKILL_TASK_PLANNING.md`, `SKILL_SOURCE_RESEARCH.md`, `RULE_RESEARCH_REQUIRED.md`, `RULE_ACCURACY_CHECK.md` and `RULE_NO_HALLUCINATED_FILES.md`.
- Artificial intelligence (AI) in schools - information for parents and carers — South Australian Department for Education — used in `RULE_ROLE_AND_SCOPE.md`, `RULE_FOLLOW_USER_CONTEXT.md`, `RULE_CLARIFICATION.md`, `RULE_NO_UNREQUESTED_EXPANSION.md`, `SKILL_REQUEST_INTAKE.md`, `RULE_PREFERRED_SOURCES.md`, `RULE_ACCURACY_CHECK.md`, `RULE_NO_HALLUCINATED_FILES.md` and `RULE_PRIVACY_AND_SAFETY.md`.
- Guidance on privacy and the use of commercially available AI products - Office of the Australian Information Commissioner - used in `RULE_PRIVACY_AND_SAFETY.md` and `SKILL_STUDENT_WORK_MARKING.md`.
- Guide to securing personal information - Office of the Australian Information Commissioner - used in `RULE_PRIVACY_AND_SAFETY.md`.
- Australian Professional Standards for Teachers — AITSL — used in core behaviour files, `RULE_CLASSROOM_REALISM.md`, `RULE_ASSESSMENT_STRUCTURE.md`, `RULE_MARKING_EVIDENCE.md`, `RULE_NO_UNFAIR_PENALTY.md`, `RULE_SINGLE_POINT_RUBRIC.md`, `RULE_FEEDBACK_FORMAT.md`, `SKILL_ASSESSMENT_TASK_DESIGN.md`, `SKILL_MARKING_GUIDE.md`, `SKILL_FEEDBACK_COMMENTS.md` and `SKILL_REPORT_WRITING.md`.
- General capabilities — Australian Curriculum — used in `RULE_ROLE_AND_SCOPE.md`, `RULE_FOLLOW_USER_CONTEXT.md`, `SKILL_REQUEST_INTAKE.md`, `SKILL_CURRICULUM_ALIGNMENT.md` and `RULE_CURRICULUM_ALIGNMENT.md`.
- Learning and assessment plans - Stage 1 and Stage 2 — SACE Board of South Australia — used in `RULE_FOLLOW_USER_CONTEXT.md` and `RULE_SACE_ALIGNMENT.md`.
- Learning and assessment plans — SACE Board of South Australia — used in `SKILL_REQUEST_INTAKE.md` and `SKILL_CURRICULUM_ALIGNMENT.md`.
- Performance standards and grades — SACE Board of South Australia — used in `RULE_FINAL_CLEAN_OUTPUT.md`, `SKILL_CURRICULUM_ALIGNMENT.md`, `RULE_CURRICULUM_ALIGNMENT.md`, `RULE_SACE_ALIGNMENT.md`, `RULE_ASSESSMENT_STRUCTURE.md`, `RULE_MARKING_EVIDENCE.md`, `RULE_RUBRIC_A_TO_E.md`, `RULE_FEEDBACK_FORMAT.md`, `SKILL_ASSESSMENT_TASK_DESIGN.md`, `SKILL_RUBRIC_DESIGN.md`, `SKILL_MARKING_GUIDE.md`, `SKILL_STUDENT_WORK_MARKING.md` and `SKILL_FEEDBACK_COMMENTS.md`.

## Unresolved Questions

- Confirm whether these rules should explicitly name local school platforms such as Frog OS, Stile and Daymap in every relevant file, or only in platform/output-specific files.
- Confirm whether SACE alignment files should privilege the current SACE subject outlines over general SACE policy sources when both apply.
- Confirm whether the project should use `Reviewed` for AI self-reviewed drafts, or reserve it for human-reviewed content.

## Duplication Or Overlap Concerns

- `RULE_ROLE_AND_SCOPE.md` and `RULE_NO_UNREQUESTED_EXPANSION.md` overlap around scope boundaries. Keep `ROLE_AND_SCOPE` broad and reserve detailed anti-expansion behaviour for `NO_UNREQUESTED_EXPANSION`.
- `RULE_FOLLOW_USER_CONTEXT.md`, `RULE_YEAR_LEVEL_APPROPRIATENESS.md`, and `RULE_NO_OVERTEACHING.md` will overlap. Keep `FOLLOW_USER_CONTEXT` as the general context-order rule and put curriculum depth control in the later files.
- `RULE_CLARIFICATION.md` and `SKILL_REQUEST_INTAKE.md` will overlap. Keep the rule focused on when to ask; make the skill focused on how to gather and organise missing information.

## Recommended Next Batch

1. `rules/Communication/RULE_EMAIL_PROFESSIONAL_TONE.md`
2. `rules/Communication/RULE_PARENT_FACING_LANGUAGE.md`
3. `rules/Communication/RULE_STAFF_FACING_LANGUAGE.md`
