# CP2 Teacher Grading Guide

Checkpoint 2 uses a **60 automatic + 40 teacher = 100 total** model.

The automatic grader checks observable Git/GitHub evidence. The teacher scores reasoning and work quality from the student's open Pull Request and the `submission.md` stored on that Pull Request's **head/source branch**. Do not grade the starter copy of `submission.md` on `main`.

## Teacher rubric — 40 points

| Category | Points | What to look for |
|---|---:|---|
| Branch safety | 10 | Student understands why feature work should not be done directly on `main` and followed the required branch workflow. |
| Git workflow explanation | 10 | Student correctly explains staging, committing, and pushing, using appropriate Git terminology. |
| Pull Request understanding | 10 | Student explains what a Pull Request does and why it is different from a local commit or remote push. |
| Reflection & work quality | 10 | Reflection is specific; commit/PR work is clear, intentional, and not merely copied or empty. |

## Fixed grading comment

The bot posts this template directly in the student's Pull Request:

```text
/manual-grade
Branch safety: 0/10
Git workflow explanation: 0/10
Pull Request understanding: 0/10
Reflection & work quality: 0/10

Feedback:
Write concise feedback here.
```

Replace the category scores and feedback, then post the comment. The workflow calculates the teacher subtotal and final score automatically.

A short-form override is also supported:

```text
/manual-grade 36
```

Use the fixed four-category template for normal grading so students can see exactly where points were earned.
