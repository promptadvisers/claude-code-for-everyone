# Anatomy of a skill

A skill is a small folder containing a text guide called SKILL.md.

- The top settings use YAML: labels and values between --- markers. The name gives the short command name; the description helps identify when to use it.
- The body uses Markdown: headings, lists and written instructions.
- Examples and references can be included as optional supporting files.

You can ask Claude to draft the file. You do not need to memorize YAML.

## Shortened teaching example

```markdown
---
name: meeting-to-work
description: Use for meeting follow-up.
---

# Steps
1. Read the meeting.
2. Keep agreed tasks; flag unknowns.
3. Cite the source for each task.
```

The full tested meeting skill is in demos/02-meeting-board/reusable-skill/.claude/skills/meeting-to-work/SKILL.md. Use that full skill for the course exercise.

Choose it explicitly with /meeting-to-work, or describe a matching task. Verify that the intended skill loaded.

Reference: https://code.claude.com/docs/en/skills
