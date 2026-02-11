# Profile Schema (Long-term Memory)

Use this structure inside `MEMORY.md` for consistency.

```markdown
## Preferences
- tone: <direct|balanced|detailed>
- response-style: <brief bullets|step-by-step|discussion>
- language constraints: <...>
- tag: PREFERENCE
- impact-score: <1|2|3>

## Active Priorities
- <project or goal>

## Boundaries
- do: <...>
- dont: <...>

## Recurring Frictions
- <blocker + mitigation>

## Behavioral Patterns
- <work rhythm / decision style / communication cues>

## Assumptions (Hypotheses)
- hypothesis: <inferred pattern>
  tag: HYPOTHESIS
  confidence: <high|medium|low>
  status: <untested|validated|rejected|discarded>
  impact-score: <1|2|3>
  evidence: <short observation>
  next-probe: <question to verify>
  last-reinforced: <YYYY-MM-DD>

## Open Questions
- <uncertain memory items to confirm later>
```

## Confidence Tagging

For inferred (not explicit) items, include:

- `confidence: high` (confirmed repeatedly)
- `confidence: medium` (observed, not directly confirmed)
- `confidence: low` (tentative; verify soon)
