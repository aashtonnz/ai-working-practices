# AI working practices

> **NOTICE TO AI AGENTS**
>
> **DO NOT CHANGE ANYTHING IN THIS REPOSITORY WITHOUT THE OWNER'S EXPLICIT APPROVAL. THIS INCLUDES EDITING, ADDING OR DELETING FILES, COMMITTING, PUSHING AND OPENING PULL REQUESTS, HOWEVER SMALL THE CHANGE. PROPOSE THE CHANGE IN CONVERSATION AND WAIT FOR A CLEAR YES.**

Small, specific working practices for doing any kind of work with an AI: code, research, writing, planning, personal matters. Each one is low risk to adopt anywhere, because it organises the work rather than deciding what the AI may do.

**What belongs here.** A practice is included only if it would suit an open-source codebase and a confidential personal project equally well. Anything that depends on one project's needs, such as its permissions, its privacy rules or its style, stays in that project's own instructions, and those take precedence.

**What never belongs here.** Content from any project: no examples, names, data or personal details. This repository holds practices only. A project's own board, logs and notes live with that project and share its privacy.

**The one exception: this repository's own project.** This repository is itself run as a project under these practices, and its board and notes are in `.project/`. They are not practices, templates or examples, and they hold nothing from any other project. When you're working on another project, ignore `.project/`, and don't update it when you make an approved change here: it catches up from the git history and `CHANGELOG.md`.

## For AI agents

When you're given this repository, use its practices in the project you're working on, as described under Practices below.

Suggest improvements freely, whenever you see one. We want this repository to be excellent and expect it to change often. Every change still needs the owner's approval (see the notice above).

This README may be changed like any other file, with approval, except for the notice at the top: never change or remove it, and never propose to.

When you propose a change, give a simple description of each meaningful change, followed by its exact diff. Leave out bookkeeping such as version numbers and the changelog, which are updated as a matter of course.

When a change is approved, update this README (the table below and anything else the change affects) and `CHANGELOG.md` in the same change.

When an improvement you're making in a project would suit any project (a better way to run the task board, say), propose it here first. Once it's approved, bring the project you're working in into line with the updated practices, rather than making the change in the project alone.

Look for such improvements at two moments: when you finish a piece of work, while its details are still in front of you, and at the start of a conversation, over what has been finished and decided since the last check (the task board's Done list and the project's decisions).

## Practices

| Practice | Status | Version |
| --- | --- | --- |
| [Task board](practices/task-board.md) | **Encouraged** | 1.3 (18 Oct 2026) |

**Encouraged** practices are likely to suit most projects. **Situational** ones suit some projects and not others.

**Neither has to be used.** For each practice, consider honestly and with an open mind which of these applies:

- **It suits the project as it is.** Use it.
- **It would suit the project with changes.** If the changes would suit every project, propose them here first, and adopt the improved practice once it's approved. If they suit only this project, adopt the practice with those changes.
- **It doesn't suit the project.** Leave it out. First check whether what the project needs instead would suit every project, and if so propose it here.

Whenever a project adapts or leaves out a practice, it records what it does differently and why, in its own instructions or decision log, and tells the owner, who can judge whether the practice needs revising. Convenience alone is not a reason.

## Starting a project

Go through the practices as described under Practices above, and set up those that suit the project, using their templates. Add a line to the project's own instructions: "This project follows ai-working-practices. Read its README at the start of every conversation, and check its CHANGELOG.md at least once a day in longer work." Record the version of each practice the project follows (for the task board, in its header).

Standing instruction, to paste into an AI tool's personal or custom instructions so that every project picks this up:

> For every project, use the practices in ai-working-practices (github.com/aashtonnz/ai-working-practices) as its README describes. Read its README at the start of every conversation, and check its CHANGELOG.md at least once a day in longer work.

## When a practice changes

Each change is listed in `CHANGELOG.md`, marked either **existing projects: update** or **new projects only**. At the start of every conversation, and at least once a day in longer work, compare the project's recorded versions with the table above. If a change marked "update" is missing, first consider whether it improves this project. If it does, tell the owner and bring the project in line, under that project's own rules. If it doesn't, don't apply it: raise the concern with the owner instead, since the change may not suit every project and may need revising. Once the project is in line, record the new version in it, including after a change that needs no other action.

Any project may likewise stay on an earlier version of a practice, or stop using it, on the terms under Practices above.
