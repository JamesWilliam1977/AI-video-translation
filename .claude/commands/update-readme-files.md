---
name: update-readme-files
description: Workflow command scaffold for update-readme-files in AI-video-translation.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /update-readme-files

Use this workflow when working on **update-readme-files** in `AI-video-translation`.

## Goal

Update documentation in both English and Chinese README files, sometimes with related images or requirements.

## Common Files

- `README.md`
- `README_ENG.md`
- `images/`
- `requirements.txt`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Edit README.md and/or README_ENG.md
- Optionally update/add related images (in images/)
- Optionally update requirements.txt

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.