# Skill: Safety And Risk Check

## Purpose

This skill allows the agent to review outputs for safety, privacy, practical risk, online risk, assessment integrity and local approval needs before they are used with students, staff or families.

## When To Use

Use this skill when the user asks for:

- a safety or risk review
- checking a practical investigation
- reviewing AI, privacy or student data risks
- checking online, software, cybersecurity or platform activities
- reviewing assessment integrity risks
- identifying local policy or approval checks
- making a lesson, task or communication safer to use

## Inputs

- draft activity, task, message, resource or workflow
- audience and year level
- subject, platform, equipment or materials
- whether students, staff or families are identifiable
- type of data, media or student work involved
- supervision, room, PPE, device or internet constraints
- assessment conditions and integrity requirements
- supplied school policy, risk assessment or approval requirements

## Process

1. Identify the risk domain: practical safety, privacy, online safety, AI use, assessment integrity, wellbeing, equipment or local policy.
2. Check whether personal or sensitive information is necessary; remove, anonymise or generalise where possible.
3. Check whether a public AI tool, online service or platform is being asked to handle student data or identifying media.
4. Check practical hazards such as chemicals, heat, electricity, sharp tools, movement, biological materials, outdoor work or specialist equipment.
5. Check supervision, PPE, room setup, disposal, emergency and local risk assessment needs.
6. Check assessment integrity, including unauthorised assistance, hidden criteria, unfair conditions or unverifiable student work.
7. Replace unsafe or high-risk instructions with safer alternatives where possible.
8. State what the teacher or school must verify before use.
9. Avoid giving detailed procedural advice for high-risk activities without current, local and specialist safety confirmation.
10. Keep the final risk notes clear, proportionate and usable.

## Output

```markdown
# Safety And Risk Check

## Overall Risk Level

## Key Risks

## Required Controls

## Privacy And Data Notes

## Assessment Integrity Notes

## Safer Alternatives

## Local Checks Before Use
```

Use cautious language when the output needs local approval or specialist advice.

## Quality Criteria

- Risks are specific to the actual task.
- Personal information is minimised.
- Practical safety controls are proportionate and visible.
- AI, platform and online risks are considered.
- Assessment integrity is protected.
- Local approval needs are clearly flagged.
- The check avoids pretending to replace school risk assessment processes.

## Related Rules

- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Quality control/RULE_ACCURACY_CHECK.md`
- `rules/Science/RULE_PRACTICAL_SAFETY.md`
- `rules/Assessment/RULE_MARKING_EVIDENCE.md`
- `rules/Assessment/RULE_NO_UNFAIR_PENALTY.md`
- `rules/Digital technologies/RULE_DATA_ETHICS.md`

## Example User Requests

- `Check this chemistry practical for safety risks.`
- `Review this AI activity for privacy issues.`
- `Make this online research task safer.`
- `Check this assessment task for integrity risks.`

## Failure Modes

- Treating safety notes as a replacement for school risk assessment.
- Ignoring personal information in examples or prompts.
- Recommending public AI tools for identifiable student data.
- Giving practical instructions without supervision, PPE or local checks.
- Overstating certainty when risk depends on school context.
- Removing useful learning instead of proposing safer alternatives.

## Completion Checklist

- Are the main risks identified?
- Is personal information minimised?
- Are supervision, PPE, equipment and local checks stated?
- Are AI, online and platform risks considered?
- Is assessment integrity protected?
- Are safer alternatives offered where useful?

## Sources

- Guidance on privacy and the use of commercially available AI products - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/guidance-on-privacy-and-the-use-of-commercially-available-ai-products - Accessed 2026-05-17
- Guide to securing personal information - Office of the Australian Information Commissioner - https://www.oaic.gov.au/privacy/privacy-guidance-for-organisations-and-government-agencies/handling-personal-information/guide-to-securing-personal-information - Accessed 2026-05-17
- About Science Assist - Australian Science Teachers Association - https://asta.edu.au/scienceassist/about-assist/ - Accessed 2026-05-17
