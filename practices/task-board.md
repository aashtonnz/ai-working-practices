# Task board

Version 1.2, 18 Oct 2026.

One short living document showing what is being done now, what is next, and what is waiting on the person, kept wherever the project's material lives: a file in a repository or folder (for example `TASKS.md`), a document in a chat tool's project, or a shared document. The AI reads it when it starts work and keeps it up to date. Where it can't write there, it gives the updated board for you to save. It works like a text kanban board that a person can scan in a minute and an AI can read at the start of every conversation.

## The rules, and why

1. **Every task has a permanent ID** (T-01, T-02, ...). Numbers are never reused, and a new task takes the next free number wherever it sits in the order. When a task is dropped or merged, note its ID as retired in one line.
   *Why:* commits, notes and conversations can point at "T-14", the reference survives reordering, and a missing number is never a mystery.
2. **Doing holds at most three tasks.**
   *Why:* more than three in progress usually means none of them is moving.
3. **Next is in order and short, about ten tasks at most.** A longer plan goes in its own file (for example `PLAN.md`), by phase, and the board shows only the next steps. The plan holds each task's full description; the board gives it one line.
   *Why:* the board is for what happens next, not the whole roadmap, and keeping the detail in one place stops the two drifting apart.
4. **Waiting on you is its own section.** Anything that needs the person's decision, approval or action goes here, dated, saying exactly what is needed, with a suggested answer when there is one.
   *Why:* requests buried inside other tasks are easy to miss, and work stalls silently.
5. **Gates are listed as tasks.** A gate is a checkpoint question whose answer decides whether the plan continues as it is ("Is it fast enough? If not, rethink before building more"). When a gate is passed, record the answer under Done.
   *Why:* it makes "stop and rethink" a planned step rather than an afterthought.
6. **Tasks take days, not weeks.** Split anything bigger.
   *Why:* small tasks show real progress and surface problems early.
7. **Done shows evidence.** Each finished task has a one-line result, a link to its output (a file, commit, document or page) and the date.
   *Why:* "done" becomes something anyone can check, not just a claim.
8. **Keep it short.** Move Done items older than about two weeks to an archive file (for example `TASKS-archive.md`), unchanged. Aim for the board to fit on a screen or two.
   *Why:* a board that cannot be scanned quickly stops being read.
9. **Update it in the same change as the work, and date it.** The board carries a "last updated" date, with the time zone. If it is found out of date, fix it before anything else.
   *Why:* a stale board misleads both the person and the next AI session.
10. **Decisions go in a decision log, not on the board.** Record significant choices separately, one dated line each, and link to them from tasks where useful.
    *Why:* the board changes daily; decisions need to stay findable.
11. **Standing priorities, if any, go in a few lines at the top.**
    *Why:* they apply to every task, so they belong where every reader starts.
12. **Ideas wait in Later.** "Later / ideas" holds things worth doing someday. An idea gets an ID when it is scheduled into Next.
    *Why:* good ideas have a home without crowding the plan.

## Template

```markdown
# Tasks

Last updated: YYYY-MM-DD (time zone)
Follows: task board v1.2 (ai-working-practices)

Standing priorities:
- ...

## Doing (at most 3)
- T-07: what it is. Status or next step.

## Waiting on you
- T-12: exactly what is needed, and the suggested answer. Raised YYYY-MM-DD.

## Next (in order, at most about 10)
- T-08: what it is.
- Gate A: the question. If no: what happens instead.
- T-09: what it is.

## Later / ideas
- An idea, in a line.

## Done (last two weeks, newest first)
- T-05: the result, in one line. [link to output](...) YYYY-MM-DD.
```
