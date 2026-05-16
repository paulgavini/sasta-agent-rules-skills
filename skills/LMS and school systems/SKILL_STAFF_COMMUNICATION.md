# Skill: Staff Communication

## Purpose

This skill allows the agent to draft clear and efficient staff-facing communication for school colleagues, teams, leaders and support staff.

## When To Use

Use this skill when the user asks for:

- staff emails
- meeting agendas or follow-up notes
- relief teacher notes
- team updates
- moderation reminders
- requests for action or information
- staff-facing LMS or intranet posts

## Inputs

- audience and role group
- purpose of the message
- decisions, updates or actions required
- dates, deadlines, owners and links
- student or class information that must be included
- tone and format
- privacy or sensitivity constraints

## Process

1. Identify whether the message is an action request, update, agenda, note or record.
2. Put the purpose or action near the start.
3. Use headings or bullet points for multiple items.
4. Include deadlines, owners, locations, links and attachments where relevant.
5. Keep the tone collegial and practical.
6. Minimise student, family or staff personal information.
7. Distinguish confirmed information from assumptions.
8. Remove unnecessary background.
9. Make the message easy to scan.
10. Flag sensitive or high-stakes content for leadership review where appropriate.

## Output

For email:

```markdown
Subject:

Hi team,

Purpose:

Action required:

Key details:

Thanks,
[Name]
```

For meeting notes:

```markdown
## Purpose
## Decisions
## Actions
| Action | Owner | Due |
| --- | --- | --- |
```

## Quality Criteria

- Staff can quickly see what they need to know or do.
- The tone is professional and collegial.
- Dates, owners and actions are clear.
- Sensitive information is minimised.
- The format suits the communication channel.
- Australian spelling is used.

## Related Rules

- `rules/Communication/RULE_STAFF_FACING_LANGUAGE.md`
- `rules/Communication/RULE_EMAIL_PROFESSIONAL_TONE.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Quality control/RULE_CLASSROOM_REALISM.md`
- `rules/Core behaviour/RULE_FINAL_CLEAN_OUTPUT.md`

## Example User Requests

- `Write a staff email asking teachers to bring assessment samples to moderation.`
- `Create relief teacher notes for this lesson.`
- `Turn these dot points into a clear team update.`
- `Write a follow-up email after a faculty meeting.`

## Failure Modes

- Hiding the action in a long paragraph.
- Sharing student details more broadly than needed.
- Using a frustrated or blaming tone.
- Missing owners, dates or next steps.
- Treating assumptions as confirmed facts.

## Completion Checklist

- Is the communication type clear?
- Is the required action visible?
- Are dates, owners and details included?
- Is the tone collegial?
- Is privacy protected?
- Is the message easy to scan?

## Sources

- Emails and letters - Australian Government Style Manual - https://www.stylemanual.gov.au/content-types/emails-and-letters - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Australian Professional Standards for Teachers - Australian Institute for Teaching and School Leadership - https://aitsl.edu.au/docs/default-source/teach-documents/australian-professional-standards-for-teachers - Accessed 2026-05-17
