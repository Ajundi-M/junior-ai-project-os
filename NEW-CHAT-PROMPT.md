# New Chat Prompt

Use this file when starting a new ChatGPT conversation about this repository.

Copy the prompt below and paste it as the first message in the new chat.

---

## Copy This Prompt

```text
We are working on my public GitHub repo:

Ajundi-M/junior-ai-project-os

This repo is my Junior AI Project OS: a Cursor-ready operating system/playbook for building professional portfolio, freelance, SaaS, and AI-powered projects with AI support.

Before giving advice or making changes, please use the repo file `PROJECT-CONTEXT.md` as the persistent project context.

Important context:
- I am a junior software engineer.
- I use AI heavily but want to learn deeply, not just copy generated code.
- My goal is to build professional projects for job search, portfolio, and later freelance/SaaS work.
- I prefer deep planning before coding.
- I need beginner-friendly explanations: what, why, and how.
- Keep the system practical, not enterprise-heavy.

Official workflow:
Idea
→ Clarify
→ Define Project Level
→ Choose Stack
→ Project Constitution
→ Spec Kit: Specify
→ Spec Kit: Plan
→ Spec Kit: Tasks
→ Cursor: Implement One Task
→ Self-Review
→ CodeRabbit Review
→ Manual Testing
→ TestSprite Testing
→ Security Review
→ Deployment
→ Documentation
→ Portfolio/Client Presentation

Tool roles:
- ChatGPT = project manager, teacher, and system maintainer
- Claude = architect/reviewer
- Gemini = UI/UX and visual reasoning
- Spec Kit = specification, technical plan, and task breakdown before coding
- Cursor = implementation, one clear task at a time
- CodeRabbit = after-coding pull request review
- TestSprite = after-coding user journey QA
- GitHub = source control, issues, PRs, and portfolio proof

Important repo-editing preference:
- Small documentation/system improvements can be committed directly to main.
- Bigger restructuring or risky changes: tell me first and wait for approval.
- Do not automatically create a branch/PR unless I specifically ask.
- Destructive changes like deleting many files or replacing the whole system: always ask first.

When helping me:
1. First understand the current system from `PROJECT-CONTEXT.md`.
2. Preserve the official workflow.
3. Keep Spec Kit before Cursor implementation.
4. Keep CodeRabbit and TestSprite after implementation.
5. Keep explanations beginner-friendly and practical.
6. If editing the repo, update related files such as README.md, manifest.json, and PROJECT-CONTEXT.md when needed.
7. Help me improve the system continuously without making it messy.

Now please help me with this request:
[write my request here]
```

---

## Short Version

Use this when the new chat already has GitHub repo access and you want a faster start:

```text
We are working on my repo `Ajundi-M/junior-ai-project-os`.
Please read/use `PROJECT-CONTEXT.md` as the persistent context first.
Follow the official workflow and repo-editing preferences inside that file.
Then help me with this request:
[write my request here]
```

---

## Best Practice

For the strongest continuity in a new chat:

1. Paste the full prompt above.
2. Include the exact request you want help with.
3. Mention whether you want advice only or repo edits.
4. If repo edits are needed, ask the assistant to inspect related files first.

Example:

```text
We are working on my repo `Ajundi-M/junior-ai-project-os`.
Please read/use `PROJECT-CONTEXT.md` as the persistent context first.
I want to add a new section for mobile app projects. Review the current structure, suggest the best place, then edit the repo if it is a small safe change.
```
