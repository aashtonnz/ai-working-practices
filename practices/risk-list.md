# Risk list

Version 1.1, 20 Oct 2026.

A short living document listing the biggest things that could stop the work, each with what could be done about it and the cheapest early test that would show whether that will work. Kept wherever the project's material lives (for example `docs/risks.md`) and linked from the task board. Suits projects with real uncertainty, such as new technology, research or anything that might not work; small or routine projects rarely need one.

## The rules, and why

1. **Rank by concern and keep it short, about ten risks.** Each risk has a permanent ID and a short name, as tasks do on the task board (for example, R-3: Battery life), and its place in the list shows its rank.
   *Why:* a long list hides the few risks that matter, and "R-3" still points at the same risk after re-ranking, where "risk 3" would not.
2. **For each risk: why it matters, what we can likely do, and the cheapest early test, or why none is needed.**
   *Why:* a risk without a test is only a worry; with one, it becomes work that settles it.
3. **Every early test is a task on the board, and the risk names it.**
   *Why:* tests listed only here are never done; this is one of the "commitments listed elsewhere" the task board says must point to their tasks.
4. **Review it when finishing a significant piece of work, and date it.**
   *Why:* results change which risks matter.
5. **When a risk is settled, say how, in one line, rather than deleting it.**
   *Why:* it shows what has been tested, and stops the same worry being raised again.

## Template

```markdown
# Risks

Last updated: YYYY-MM-DD (time zone)
Follows: risk list v1.1 (ai-working-practices)

## R-1: The risk, in a few words
**Why it matters.** ...
**What we can likely do.** ...
**Early test.** ... (T-12)

## Settled
- R-2: The risk: how it was settled, in one line. YYYY-MM-DD.
```
