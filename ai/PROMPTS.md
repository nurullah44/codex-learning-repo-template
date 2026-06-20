# Reusable Prompts

## Ticket

```text
Help me turn this idea into a small verifiable ticket. Do not plan implementation yet.

Idea:
```

## Research Questions

```text
We are preparing objective research.

Given this ticket, generate neutral research questions. Do not propose a solution.
For each question, say why it matters and what evidence would answer it.
```

## Objective Research

```text
Research mode. Read only. Do not edit files.

Answer these questions with file references. Separate facts from assumptions.
Do not propose implementation.
```

## Design Discussion

```text
Using the ticket and research, explain 2-3 possible approaches.

For each approach include how it works, tradeoffs, risks, and test strategy.
Recommend one, but do not write code or a final plan yet.
```

## Vertical Plan

```text
Create a vertical implementation outline.

Use a tracer bullet first. Each slice must include:
- change
- verification
- rollback or stop condition

Keep slices small enough that I can understand each one.
```

## One Slice

```text
Implement only the approved slice.

Before editing, restate:
- files likely touched
- exact change
- verification command or manual check

After verification, stop and explain the next decision.
```

## Review

```text
Review this change against the ticket and acceptance criteria.

Findings first. Focus on incorrect behavior, missed criteria, regression risk,
missing tests, and unnecessary complexity.
```
