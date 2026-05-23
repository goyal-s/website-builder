# Project Journal Team Skill + Documentation Bootstrap

## Decisions locked in

| Question | Your choice |
|----------|-------------|
| Skill location | **Cursor Team skill** — authored in repo at `.cursor/skills/project-journal/`, committed to GitHub; team members get it when they open the repo. If your org uses Cursor Dashboard → Team Skills, upload/copy from there after commit. |
| Versioning | **Semver in `docs/VERSION`** — patch bump on each journal update; minor bump on milestones (GitHub push, Vercel deploy, first production release). |

---

## Part 1 — The Team skill (write this first)

Create `.cursor/skills/project-journal/SKILL.md` with workflow rules for timestamped docs, TOC, mermaid, semver, CHANGELOG, release notes, and next actions.

---

## Part 2 — Bootstrap docs for website-builder

Backfill actions A001–A007 in `docs/project_journal.md`. Set `docs/VERSION` to `0.2.1`.

---

## Part 3 — Cursor Team publishing note

After committing `.cursor/skills/project-journal/`:

1. **Automatic for repo collaborators:** skill is available via project skills when the repo is opened.
2. **Org-wide Team Skills (if enabled):** Cursor Dashboard → Team → Skills → add from repo path or paste `SKILL.md` content.

---

## Execution order

1. Write `.cursor/skills/project-journal/SKILL.md` + `templates.md`
2. Create `docs/` files + root `CHANGELOG.md` with backfilled actions
3. Set `docs/VERSION` to `0.2.1`
4. Commit and push to GitHub

No Vercel work in this phase — that stays in `next_actions.md`.

See full plan details in Cursor plans or `docs/project_journal.md` after bootstrap.
