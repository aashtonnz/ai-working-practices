# Style guide

Version 1, 18 Oct 2026.

How a project looks, feels and communicates with the people who use it: apps, websites, documents, emails (including automated ones), notifications, confirmations and error messages.

**External only.** This guide applies only to what people outside the project see: users, customers and the public, including public documentation and READMEs. It does not apply in any way to communication among the people working on the project, including the AI. Task boards, commit messages, internal notes and conversations follow their own conventions.

**Entirely optional.** A project may follow this guide, adapt it, or ignore it completely. A project that already has its own look and voice doesn't necessarily need to change it.

## Look and feel

Clean, simple and calm. Utilitarian, in that the interface serves the task and gets out of the way, but still human, never cold. Never loud, busy or cluttered.

When in doubt, follow these, in order:

1. The project's own style note, if it has one.
2. This guide.
3. On a native Apple or Android app, that platform's own guidelines (Apple's Human Interface Guidelines, Google's Material Design).
4. Otherwise, [shadcn/ui](https://ui.shadcn.com), the default reference for typefaces, type sizes, spacing, colour and components such as buttons and forms.

Outside the web (emails, documents, slides), follow whatever is consistent with the project as a whole.

Whatever else applies, keep things usable by people with disabilities, such as low vision, colour blindness or not using a mouse. The usual standard is level AA of the Web Content Accessibility Guidelines (WCAG). Nothing above overrides this.

**Define styles by role, once.** Type sizes, spacing and other styles are defined by role ("title", "caption", "body", "small gap") in one place. Every element uses a role, never a hand-picked value. A change alters the role, so everything with that role changes together, or deliberately adds a new role. Whenever the design changes, check for one-off values.

## Communication

- Plain words, short sentences. Say what happens next in every message, confirmation and error.
- Own mistakes, never blame the reader, and thank people for corrections.
- Never imply a person did what software did.
- Professional first, warmth second. No pleasantries that waste the reader's time, no emoji or exclamation marks in system text.
- Describe, don't sell. Claim less than you deliver.
- No completeness claims ("every", "all", "any") unless literally true.
- Concrete nouns and numbers over abstract claims.
- Keep what exists separate from what's planned, and label plans as plans.
- Everything a user sees is about the user. The builders' inner monologue stays in internal docs.
- One name for one thing: call each feature, button or idea the same thing everywhere.

## Project style note

A project may keep a note of its own style choices, of any length, wherever its material lives (for example `STYLE.md`, or a section in the project's instructions). How much of this guide it uses, if any, is up to the project.

```markdown
# Style

Follows: style guide v1 (ai-working-practices), if used

Tone: ...
Spelling: ...
Typeface: ...
Colours: ...
Logo and imagery: ...
```
