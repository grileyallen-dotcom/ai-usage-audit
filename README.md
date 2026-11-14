# AI Usage Audit

A private record of how I use AI, where I can improve, and how I've grown. I keep it for two readers: me, so I can spot patterns in my own AI use, and hiring managers, so they can see how I manage AI in practice.

## What this is

Whenever I use AI on a project, I log the moments that show how I'm managing it: a number I checked, a mistake I caught, a limit I set, a decision to change direction. The log covers any project I use AI on. Entries use generic labels (for example, "Project A, a research project") and never name the project, its sources, or its content.

Each entry is a short, dated record of what happened, what the evidence was, and what changed afterward. The log itself is where my growth shows up. This README only explains the method.

## What gets logged

- **Verification:** I checked a number, fact, or claim the AI gave me.
- **Correction:** The AI got something wrong or did something it shouldn't have, and I caught it.
- **Scope or direction change:** I changed what a project covers or how it runs.
- **Approval gate:** The AI stopped to ask before an action, or I gave or withheld approval.
- **Audit:** I reviewed a piece of AI work against evidence and recorded the result.

Routine edits and ordinary decisions are not logged.

## Habits I'm building

These are the practices I've chosen to hold myself and the AI to:
- Check what the AI tells me against a source before I rely on it.
- Require approval before the AI changes files or takes actions that are hard to undo.
- Change direction when the evidence says so, and record why.
- Write down mistakes, mine and the AI's, so I can see whether they repeat.

## How entries are written

The AI drafts and writes log entries directly, through the `/checkpoint` skill. I review them afterward and correct anything wrong. Entries record only what is evidenced. My reasoning appears only in my own words, or as "reasoning not recorded".

This permission covers only the log. Every other change, and every Git commit and push, still needs my approval.

## Contents

- `progress.md`: the dated log
- `audit/LOG.md`: records of audits of AI work
- `AGENTS.md`: the rules AI agents follow in this repository
- `.agents/skills/` and `.claude/skills/`: the `/checkpoint` and audit procedures
