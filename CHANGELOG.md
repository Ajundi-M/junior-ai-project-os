# Changelog

Use this file to record meaningful changes to the Junior AI Project OS.

The goal is to keep the project history clear so future chats, Cursor, and the developer can understand what changed and why.

---

## Update Rule

After every meaningful update, add a short entry here.

A meaningful update includes:

```text
New workflow decision
New tool added
New guide/checklist/template/prompt added
Major wording or structure change
Change to repo-editing preferences
Change to project philosophy
Change to quality gates
Change to stack strategy
```

Small typo fixes do not need a changelog entry.

---

## Entry Format

```text
## YYYY-MM-DD — Short title

Changed:
- 

Why:
- 

Files affected:
- 
```

---

## 2026-05-03 — Added persistent context and new-chat continuity

Changed:
- Added `PROJECT-CONTEXT.md` as the persistent memory source for future chats.
- Added `NEW-CHAT-PROMPT.md` as the copy-paste prompt for starting clean future chats.
- Updated README and manifest to reference the new chat workflow.

Why:
- Future chats should not require reexplaining the whole project from the beginning.
- The system needs a durable memory source that stays inside the repo.

Files affected:
- `PROJECT-CONTEXT.md`
- `NEW-CHAT-PROMPT.md`
- `README.md`
- `manifest.json`

---

## 2026-05-03 — Added GitHub workflow and public polish

Changed:
- Added pull request template.
- Added feature issue template.
- Added daily workflow guide.
- Added new project checklist.
- Added publication checklist.
- Added MIT license.
- Polished README for public/portfolio presentation.

Why:
- The repo is public and should look intentional, professional, and safe to share.
- GitHub issues and pull requests should support the Spec Kit workflow.

Files affected:
- `.github/pull_request_template.md`
- `.github/ISSUE_TEMPLATE/feature_spec.md`
- `DAILY-WORKFLOW.md`
- `NEW-PROJECT-CHECKLIST.md`
- `PUBLICATION-CHECKLIST.md`
- `LICENSE`
- `README.md`
- `manifest.json`

---

## 2026-05-03 — Added continuous memory update protocol

Changed:
- Created this changelog.
- Added the rule that meaningful future updates should also update project memory and related navigation files.

Why:
- The system should not get stuck at an old state.
- Future chats should always inherit the latest decisions, workflows, and repo structure.

Files affected:
- `CHANGELOG.md`
