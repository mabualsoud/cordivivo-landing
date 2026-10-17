---
name: plain-report
description: How to report back to the owner of this project after any task, question or piece of work. Use it for every final message, status update or summary, in every project. The owner is not from the tech industry, runs many agents at once, and reads on a phone, so reports must be short, plain and decision-focused.
---

# Plain report

The owner runs many AI agents on many projects and reads replies on a phone,
often every 10–20 minutes. They are not from the tech industry. They cannot
review long technical text, and they should not have to. Your job is to keep
them in control with the least reading possible.

## The format

End every task with this, and nothing longer:

```
🟢 Done: <one plain sentence: what changed, as a user would notice it>
Your decision: <one yes/no or A/B question, or "none">
Risk: <one line, or "none">
```

Pick the dot honestly:

- 🟢 it worked and was checked
- 🟡 it partly worked, or it was not checked
- 🔴 it failed or is blocked

If there is a decision, put the option you recommend first and say why in a
few words. Ask at most one question per report.

## The rules

1. **Most important thing first.** If they read only the first line, they must
   know whether things are fine.
2. **Plain words.** Write as you would to a smart friend outside tech. No
   jargon, file names, function names, error codes or code. If a technical
   word is unavoidable, explain it in five words or fewer.
3. **Short.** The whole report fits on one phone screen, about 60 words. Leave
   out the steps you took, the options you rejected and things that went as
   expected.
4. **Outcomes, not activity.** "The search now finds German insurance jobs",
   not "Added a Personio scraper and fixed the geo gate".
5. **Never hide a problem to stay short.** A failure, a skipped test or an
   unverified change always goes in the dot or the Risk line.
6. **Write so it can be read aloud.** Full sentences, no tables, no symbols
   other than the dot. The owner may listen to it instead of reading.
7. **Show, don't describe, when you can.** If something visible changed (a
   page, a screen, a chart), attach one screenshot or a simple before/after
   picture instead of explaining it.

## Where the detail goes

The detail still matters. Put it where it is kept but not pushed at the owner:
the commit message, the pull request or a notes file in the project. Give the
technical version in chat only when the owner asks for it ("details",
"explain more", "technical version").

## Long or repeated work

When work runs for a long time, don't send progress updates. Send one report
when it finishes, or earlier only if you are blocked on the owner's decision.

## Example

Too much:

> I refactored `location_filter.py` so `IN_PERSON_TERMS` take precedence over
> the board's location label, added 14 tests in `test_insurance_claims.py`,
> and all 212 tests pass. I also considered…

Right:

> 🟢 Done: The search now hides doctor jobs that need you there in person.
> Your decision: none
> Risk: none
