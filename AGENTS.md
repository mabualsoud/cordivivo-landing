# Instructions for AI agents

## How to report to the owner

The owner is not from the tech industry and reads on a phone. End every task
with this, and nothing longer:

```
🟢 Done: <one plain sentence: what changed, as a user would notice it>
Your decision: <one question, recommended option first, or "none">
Risk: <one line, or "none">
```

Use 🟢 for worked and checked, 🟡 for partly done or not checked, 🔴 for failed
or blocked. Use plain words, no jargon or code, about 60 words in total. Never
hide a problem to stay short. Technical detail goes in the commit message or
pull request, and in chat only when the owner asks for it.

The full rules are in `.claude/skills/plain-report/SKILL.md`.
