# Skill: LMS Ready Output

## Purpose

This skill allows the agent to prepare content that can be copied into a learning management system or school platform with minimal cleanup.

## When To Use

Use this skill when the user asks for:

- Daymap, Frog, Stile or other LMS-ready posts
- student instructions for an online lesson
- parent-facing LMS announcements
- staff-facing school system messages
- assessment instructions for online submission
- copy-and-paste content for a school platform

## Inputs

- target platform if known
- audience: students, parents/carers or staff
- purpose of the post
- due dates, lesson dates or submission instructions
- links, attachments or resources
- required tone and length
- privacy, accessibility or formatting constraints

## Process

1. Identify the platform and audience.
2. Put the main action or message at the start.
3. Use simple headings and short paragraphs.
4. Use bullet points or numbered steps for instructions.
5. Keep formatting simple so it survives copy and paste.
6. Avoid nested tables, complex indentation and fragile Markdown where the LMS may strip formatting.
7. Include due dates, links, attachments and submission instructions where relevant.
8. Use plain language and Australian spelling.
9. Keep student, family and staff privacy in mind.
10. Add a short teacher note only if it should not be pasted to students or families.

## Output

For students:

```markdown
## Today You Will

## What To Do

## What To Submit

## Due
```

For families:

```markdown
## Update

## What Students Need To Do

## How Families Can Help
```

For staff:

```markdown
## Action Required

## Key Details

## Due Date
```

## Quality Criteria

- The post can be copied into an LMS without complex reformatting.
- The audience knows what to do.
- Dates, links and submission instructions are clear.
- The tone matches the audience.
- Sensitive details are not exposed unnecessarily.
- Accessibility is considered.

## Related Rules

- `rules/Communication/RULE_PARENT_FACING_LANGUAGE.md`
- `rules/Communication/RULE_STAFF_FACING_LANGUAGE.md`
- `rules/Lesson design/RULE_STUDENT_FACING_TONE.md`
- `rules/Document output/RULE_EXPORT_READY_STRUCTURE.md`
- `rules/Quality control/RULE_ACCESSIBILITY.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`

## Example User Requests

- `Make this worksheet instruction LMS-ready.`
- `Write a Daymap post for an upcoming assessment.`
- `Create a Stile lesson intro for Year 8 students.`
- `Turn this announcement into a parent-facing LMS update.`

## Failure Modes

- Using complex tables or formatting that will break in the platform.
- Leaving out the action or due date.
- Mixing teacher-only notes into student-facing text.
- Using vague labels such as "complete the work" without saying where or how.
- Including private student information in a broad announcement.

## Completion Checklist

- Is the audience clear?
- Is the main action at the start?
- Are steps, due dates and submissions clear?
- Is formatting copy-safe?
- Is the tone suitable?
- Is privacy protected?

## Sources

- Emails and letters - Australian Government Style Manual - https://www.stylemanual.gov.au/content-types/emails-and-letters - Accessed 2026-05-17
- Quick guide: plain language - Australian Government Style Manual - https://www.stylemanual.gov.au/style-manual-resources/quick-guides/quick-guide-plain-language - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
