# Skill: Video Transcript

## Purpose

This skill allows the agent to create, clean or structure transcripts for video and audio content so they are accessible, readable and useful for students, staff and families.

## When To Use

Use this skill when the user asks for:

- a video transcript
- a transcript clean-up
- captions or transcript notes
- a summary from a transcript
- an accessible version of audio or video content
- lesson video support material

## Inputs

- audio, video, rough transcript or notes
- speaker names or roles
- audience and year level
- whether time markers are required
- whether visual information needs description
- required output format
- privacy, consent or copyright constraints

## Process

1. Preserve the meaning of spoken content.
2. Identify speakers where known.
3. Add time markers when useful for navigation.
4. Include meaningful non-verbal information in square brackets.
5. Add brief visual descriptions where the visual information is needed to understand the content.
6. Use Australian spelling unless quoting exact on-screen text or speech.
7. Correct obvious automated-transcription errors where context supports the correction.
8. Do not invent missing words or speakers.
9. End with `End of transcript` when producing a formal transcript.

## Output

```markdown
# Transcript

[00:00] Speaker:

[00:15] Speaker:

End of transcript
```

Adjust formatting to suit the user's requested destination.

## Quality Criteria

- Dialogue is accurate and readable.
- Speaker changes are clear.
- Important sounds and visual information are included.
- Time markers help navigation without clutter.
- Personal information is not exposed unnecessarily.
- Unclear sections are marked rather than invented.

## Related Rules

- `rules/Quality control/RULE_ACCESSIBILITY.md`
- `rules/Quality control/RULE_PRIVACY_AND_SAFETY.md`
- `rules/Core behaviour/RULE_AUSTRALIAN_LANGUAGE.md`
- `rules/Document output/RULE_EXPORT_READY_STRUCTURE.md`

## Sources

- Requirements and standards for video and audio - Australian Government Style Manual - https://www.stylemanual.gov.au/content-types/video-and-audio/requirements-and-standards-video-and-audio - Accessed 2026-05-17
- Make content accessible - Australian Government Style Manual - https://www.stylemanual.gov.au/accessible-and-inclusive-content/make-content-accessible - Accessed 2026-05-17
