# AGENTS.md

Guidance for AI coding assistants (Claude Code, Gemini CLI, Codex, Cursor, and others) working in this repository. This is the single source of truth — `CLAUDE.md`, `GEMINI.md`, and `VIBECODERS.md` defer to this document.

## Repository Purpose

This is a **GitHub practice workbook for authors** — not a prose project and not a software project. Writers (often AI-assisted) clone or fork it to practice the Git workflow: branches, commits, pull requests. The Markdown files inside are *scaffolding* — they give the writer something small and low-stakes to edit so the Git mechanics have a subject.

There is no build, no tests, no package manager, no code to run. The value delivered to the user is confidence with Git, not polished prose.

## Content Architecture

Two folders, both designed as easy edit targets:

- **`ai-isms/`** (`triplets.md`, `metaphors.md`) — catalogs of common AI-writing patterns. Each file ends with a "How to contribute" section that walks the writer through fork → edit → commit → PR. The contribution instructions *are* the lesson; the examples are the subject matter.
- **`prompts/`** (`brainstorming-prompts.md`, `revision-prompts.md`) — numbered prompt starters. Same role: a list the writer can safely extend with one new numbered item to practice a commit.

Both files use `<details>` collapsibles so they render cleanly on github.com. Preserve that structure when editing — the GitHub rendering is part of the pedagogy.

## Operating Contract

Your job is to support the writer's Git practice, not to polish the content.

- Help the writer make one small, focused change at a time so it maps cleanly to a commit.
- Explain the Git step you're about to take (branch, commit, push, PR) before doing it, especially for first-timers.
- Suggest clear commit messages in the style already used: `Add [example]`, `Update [file]`, `Revise [section]`, `Refine [X]`.
- When the writer does edit content, preserve their voice and make minimal changes — this isn't a venue for rewrites.
- Don't strip every triplet or metaphor. The `ai-isms/` files explicitly warn against that — the point is to flag the *generic* ones while keeping rhythm.
- Flag common AI-writing patterns only if the writer asks; otherwise leave their prose alone.
- Don't bulk-expand the example files. One new entry at a time is the practice pattern.
- Match each file's existing format when adding entries — short examples with no per-line commentary in `ai-isms/`; single-axis constraints in `prompts/`.
- When opening a PR, fill in [`.github/pull_request_template.md`](.github/pull_request_template.md) (What / Why / Feedback) rather than replacing it with free-form prose — the structure is part of the lesson.
- If the writer isn't sure what to work on, point them at the repo's `good first issue` tab before inventing a task.

## Tip: Translate Git into Writer Terms

Writers already know how documents work. When explaining a GitHub action, anchor it to the document-editing concept they already use. Reach for this mapping before you reach for jargon.

| GitHub Term | Document Editing Equivalent | Short Definition |
|---|---|---|
| **Repository (Repo)** | Project folder | The top-level folder containing all files and their revision history. |
| **Commit** | Save version | A timestamped save point recording what changed and who changed it. |
| **Branch** | Separate draft | A parallel version you can edit freely without affecting the main one. |
| **Merge** | Combine versions | Applying changes from one branch into another. |
| **Pull Request (PR)** | Request for review | Proposed changes submitted for acceptance, like sending a draft to an editor. |
| **Fork** | Copy to your account | A personal copy of someone else's repo, separate from the original. |
| **Push** | Upload changes | Sending your local commits to the remote repo on GitHub. |
| **Pull** | Download & merge | Pulling the latest remote changes down into your local copy. |
| **Clone** | Download working copy | Making a local copy of a repo that stays linked to the remote. |
| **Issue** | Task / comment thread | A discussion thread for a task, bug, or suggestion on the repo. |

Source: [Glossary of IT terms](https://github.com/AlgorithmAlchemy/Glossary-of-IT-terms).

Use whichever column the writer is already comfortable with, and don't assume they've seen the GitHub term before.
