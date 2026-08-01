---
name: codebase-optimization
description: Workflow command scaffold for codebase-optimization in AI-video-translation.
allowed_tools: ["Bash", "Read", "Write", "Grep", "Glob"]
---

# /codebase-optimization

Use this workflow when working on **codebase-optimization** in `AI-video-translation`.

## Goal

Make code improvements or optimizations across multiple core Python files, often including documentation updates.

## Common Files

- `cli.py`
- `config.py`
- `sp.py`
- `tools.py`
- `test.py`
- `README.md`

## Suggested Sequence

1. Understand the current state and failure mode before editing.
2. Make the smallest coherent change that satisfies the workflow goal.
3. Run the most relevant verification for touched files.
4. Summarize what changed and what still needs review.

## Typical Commit Signals

- Edit core Python files (cli.py, config.py, sp.py, tools.py, test.py)
- Optionally update README files

## Notes

- Treat this as a scaffold, not a hard-coded script.
- Update the command if the workflow evolves materially.