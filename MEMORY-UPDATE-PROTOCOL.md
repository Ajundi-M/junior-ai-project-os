# Memory Update Protocol

This file defines how to keep the Junior AI Project OS up to date after every meaningful change.

The goal is simple:

```text
Future chats should always understand the latest version of the system.
```

This protocol prevents the project from getting stuck at an old context.

---

## 1. When to Update Project Memory

Update project memory after any meaningful change.

Meaningful changes include:

```text
[ ] New workflow decision
[ ] New tool added or removed
[ ] New guide added
[ ] New checklist added
[ ] New template added
[ ] New prompt added
[ ] Project structure changed
[ ] Repo-editing preference changed
[ ] Quality gate changed
[ ] Stack strategy changed
[ ] Public/portfolio positioning changed
[ ] Important correction to existing system behavior
```

Tiny typo fixes usually do not need a memory update.

---

## 2. Files That May Need Updating

After meaningful changes, check these files:

```text
[ ] PROJECT-CONTEXT.md
[ ] NEW-CHAT-PROMPT.md
[ ] README.md
[ ] manifest.json
[ ] CHANGELOG.md
[ ] .cursor-instructions.md
```

Not every change requires all files, but every meaningful change should at least consider them.

---

## 3. Required Update Rules

### PROJECT-CONTEXT.md

Update when the change affects:

```text
Project purpose
User background or preferences
Official workflow
Tool roles
Spec Kit / Cursor / CodeRabbit / TestSprite boundaries
Quality gates
Stack strategy
Repo-editing preferences
Important file list
Future direction
```

### NEW-CHAT-PROMPT.md

Update when the change affects what a new chat must know immediately.

Examples:

```text
New essential file
New official workflow step
New repo-editing preference
New tool role
New long-term rule
```

### README.md

Update when the change affects public-facing understanding.

Examples:

```text
New important operating file
New repo structure
New workflow explanation
New public safety rule
New recommended usage path
```

### manifest.json

Update when files, sections, workflows, or system metadata change.

### CHANGELOG.md

Update after every meaningful change.

Use this format:

```text
## YYYY-MM-DD — Short title

Changed:
- 

Why:
- 

Files affected:
- 
```

### .cursor-instructions.md

Update when Cursor behavior rules change.

---

## 4. Standard Post-Change Checklist

After changing the repo, ask:

```text
[ ] Did this change affect future chats?
[ ] Did this change affect how Cursor should work?
[ ] Did this change affect the official workflow?
[ ] Did this change add/remove important files?
[ ] Did this change affect public repo presentation?
[ ] Did I update PROJECT-CONTEXT.md if needed?
[ ] Did I update NEW-CHAT-PROMPT.md if needed?
[ ] Did I update README.md if needed?
[ ] Did I update manifest.json if needed?
[ ] Did I update CHANGELOG.md if needed?
```

---

## 5. Instruction for Future Assistants

When helping with this repo, always follow this rule:

```text
After any meaningful update, keep the project memory updated.
Do not only edit the immediate file.
Check whether PROJECT-CONTEXT.md, NEW-CHAT-PROMPT.md, README.md, manifest.json, CHANGELOG.md, or .cursor-instructions.md also need updates.
```

This keeps every future chat aligned with the latest system.

---

## 6. User Preference

The user wants this repo to be updated continuously.

The system should not freeze at one point in time.

Whenever new ideas, fixes, tools, or workflow decisions are added, the repo should preserve them in the correct memory/navigation files so future chats do not miss the latest context.
