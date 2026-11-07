# Fresh-eyes review

Version 1, 7 Nov 2026.

Before a significant piece of work leaves the author's hands, or becomes the foundation for much more, someone who did not do it reviews it, starting from the work itself rather than from the author's account of it. The reviewer can be a separate AI agent, a new conversation or a person. Suits work where an undetected error would spread or be costly, such as analysis, data, code others depend on, or a document going out; small or routine work rarely needs one.

## The rules, and why

1. **Review at the points where an error would become expensive to undo: before the work is shipped, published or sent, and at a milestone where much further work will rest on it.** Not after every task.
   *Why:* errors compound. A mistake found at that point costs one fix; found later, it costs everything built on it since.
2. **The reviewer starts from the work and its sources, not from the author's summaries or conclusions.** Give the goal, the material and any rules the work must meet; leave out what the author believes is right or wrong with it, beyond naming things that are already known to be odd.
   *Why:* a reviewer handed the author's conclusions tends to confirm them, and the author's summary is where their blind spots are.
3. **Ask for findings ranked by seriousness, each with its evidence and marked as confirmed or suspected, plus what was checked and found correct, and what could not be checked and why.**
   *Why:* evidence lets each finding be checked quickly; the lists of what was found correct and what was not checked show how far the review can be trusted.
4. **Check each finding before acting on it. Each fix gets its own task, and where it can, a check that fails before the fix and passes after.**
   *Why:* reviewers are wrong too, and a fix without a failing check may not fix anything.
5. **Record the review and what came of it, including findings set aside and why, and tell the person the outcome.**
   *Why:* it shows what has been checked, and stops the same question being raised again.

## Template

A brief for the reviewer:

```markdown
Review [the work] before [what it will be used for]. Work only from [the material, files or sources]; do not trust any summary of it, including [the author's notes], as correct.
Rules the work must meet: [scope, constraints].
Look especially for: [kinds of error that matter here]. Known oddities to explain if you can: [any].
You may: [read, run, query]. You may not: [change, send, publish].
Report, most serious first: what is wrong, the evidence, how much it affects, a suggested fix and a check that would show it fixed; mark each confirmed or suspected. Then list what you checked and found correct, and what you could not check and why.
```
