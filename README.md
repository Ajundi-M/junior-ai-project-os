# Junior AI Project OS

A practical, Cursor-ready operating system for building professional software projects with AI support.

This repository is a personal developer playbook designed for a junior software engineer who wants to build portfolio, freelance, SaaS, and AI-powered projects with stronger planning, better quality gates, and deeper learning.

It combines specification-driven development, AI-assisted implementation, code review, testing, documentation, and portfolio presentation into one repeatable workflow.

---

## Why This Repo Exists

Modern AI tools can generate code quickly, but speed alone does not create professional software.

This system exists to prevent common AI-assisted development problems:

- starting to code before requirements are clear
- accepting AI-generated code without understanding it
- building features without acceptance criteria
- skipping security, testing, and documentation
- creating projects that work locally but are not portfolio-ready
- relying on AI as magic instead of using it as a structured engineering assistant

The goal is simple:

```text
Build professional projects while learning how professional software is planned, implemented, reviewed, tested, documented, and presented.
```

---

## Who This Is For

This repo is especially useful for:

- junior software engineers
- self-taught developers
- students building portfolio projects
- developers using Cursor, ChatGPT, Claude, Gemini, CodeRabbit, and TestSprite
- developers who want a clear system for AI-assisted project work
- developers who prefer deep planning before coding

It is not meant to be an enterprise-heavy framework. It is a practical operating system for building better projects step by step.

---

## What This Demonstrates

For employers, clients, or reviewers, this repo demonstrates that the developer cares about:

- requirements clarification
- specification-first thinking
- architecture planning
- task decomposition
- secure development habits
- testing and QA
- pull request review
- documentation
- continuous learning
- professional project presentation

---

## Core Workflow

Use this workflow for serious projects:

```text
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
```

The key idea is that implementation should not begin from a vague prompt. Serious features should move through specification, technical planning, and small task generation before Cursor writes code.

---

## Tool Roles

```text
ChatGPT = project manager, teacher, and system maintainer
Claude = architect, reviewer, and complex reasoning partner
Gemini = UI/UX and visual reasoning assistant
Spec Kit = specification, technical plan, and task breakdown
Cursor = implementation environment
CodeRabbit = pull request review gate
TestSprite = user journey and QA testing gate
GitHub = source control, issues, pull requests, and portfolio proof
```

Important boundary:

```text
Spec Kit happens before coding.
Cursor implements one clear task at a time.
CodeRabbit reviews after coding.
TestSprite validates user journeys after coding.
```

---

## Project Levels

The system uses project levels to avoid underbuilding or overbuilding.

```text
Level 1 = Simple Portfolio Project
Level 2 = Professional Portfolio Project
Level 3 = Freelance/Client-Ready Project
Level 4 = SaaS/Product Project
```

Recommended default:

```text
Use Level 2 for serious job-search portfolio projects.
```

Spec Kit usage:

```text
Level 1 = optional lightweight specification
Level 2 = standard for serious features
Level 3 = required
Level 4 = required
```

---

## Recommended Default Stack

The stack is flexible and should be chosen based on project requirements.

Common defaults:

```text
Most portfolio web apps:
Next.js + TypeScript + Tailwind CSS + Supabase

Advanced AI/backend/data/file/image projects:
Next.js + TypeScript + FastAPI + Supabase + Docker

Simple frontend-only projects:
Next.js or Vite + React + Tailwind CSS
```

Main principle:

```text
Choose the simplest professional stack that solves the project requirements.
```

---

## How to Use This Repo in Cursor

Open this repository in Cursor.

Start with:

1. `START-HERE.md`
2. `PROJECT-CONTEXT.md`
3. `NEW-CHAT-PROMPT.md`
4. `DAILY-WORKFLOW.md`
5. `NEW-PROJECT-CHECKLIST.md`
6. `01-guides/01-core-philosophy.md`
7. `01-guides/02-project-lifecycle.md`
8. `01-guides/07-spec-kit-workflow.md`
9. `03-templates/project-brief.md`
10. `03-templates/project-constitution.md`

For every new project, copy the relevant templates into the actual project repository and fill them in.

---

## Starting a New Chat About This Repo

Use `NEW-CHAT-PROMPT.md` when starting a fresh ChatGPT conversation.

That file contains a copy-paste prompt that tells the new chat to use `PROJECT-CONTEXT.md` as the persistent memory source for this project.

Recommended flow:

```text
Open NEW-CHAT-PROMPT.md
→ Copy the full prompt or short version
→ Paste it into a new ChatGPT chat
→ Add your new request at the end
```

This keeps future chats clean while preserving the important context from this project.

---

## Repository Structure

```text
.
├── START-HERE.md
├── PROJECT-CONTEXT.md
├── NEW-CHAT-PROMPT.md
├── DAILY-WORKFLOW.md
├── NEW-PROJECT-CHECKLIST.md
├── PUBLICATION-CHECKLIST.md
├── 01-guides/
├── 02-checklists/
├── 03-templates/
├── 04-prompt-library/
├── 05-examples/
├── .github/
├── .cursor-instructions.md
├── manifest.json
└── LICENSE
```

---

## Important Operating Files

```text
START-HERE.md = first file to read
PROJECT-CONTEXT.md = persistent context for future AI chats
NEW-CHAT-PROMPT.md = copy-paste prompt for starting clean future chats
DAILY-WORKFLOW.md = what to do when opening Cursor each day
NEW-PROJECT-CHECKLIST.md = how to start a project from zero
PUBLICATION-CHECKLIST.md = safety/professional checklist before sharing publicly
.cursor-instructions.md = guidance for Cursor behavior
manifest.json = machine-readable overview of the system
```

---

## Guides

```text
01-guides/01-core-philosophy.md
01-guides/02-project-lifecycle.md
01-guides/03-project-levels.md
01-guides/04-stack-selection-guide.md
01-guides/05-ai-team-roles.md
01-guides/06-coderabbit-and-testsprite.md
01-guides/07-spec-kit-workflow.md
```

---

## Checklists

```text
02-checklists/definition-of-done.md
02-checklists/security-checklist.md
02-checklists/testing-checklist.md
02-checklists/spec-kit-checklist.md
02-checklists/deployment-checklist.md
02-checklists/documentation-checklist.md
```

---

## Templates

```text
03-templates/project-brief.md
03-templates/project-constitution.md
03-templates/architecture-plan.md
03-templates/spec-kit-feature-spec.md
03-templates/spec-kit-technical-plan.md
03-templates/spec-kit-task-list.md
03-templates/task-breakdown.md
03-templates/portfolio-writeup.md
```

---

## Prompt Library

```text
04-prompt-library/01-project-manager-prompts.md
04-prompt-library/02-architect-prompts.md
04-prompt-library/03-cursor-implementation-prompts.md
04-prompt-library/04-review-prompts.md
04-prompt-library/05-testing-prompts.md
04-prompt-library/06-learning-prompts.md
04-prompt-library/07-spec-kit-prompts.md
```

---

## GitHub Workflow Files

```text
.github/pull_request_template.md
.github/ISSUE_TEMPLATE/feature_spec.md
```

These files help connect the system to real GitHub workflows:

```text
Feature issue → Spec Kit specification → technical plan → task list → Cursor implementation → PR → CodeRabbit → TestSprite → merge/showcase
```

---

## Definition of Done

A serious feature is not done until:

```text
[ ] It has a clear specification if Level 2+
[ ] It has a technical plan if Level 2+
[ ] It was broken into small tasks before implementation
[ ] It works locally
[ ] It matches the acceptance criteria
[ ] The code is understandable
[ ] Inputs are validated
[ ] Loading, empty, and error states exist if needed
[ ] Mobile layout works if relevant
[ ] Auth/database permissions are correct if relevant
[ ] No secrets are exposed
[ ] Manual testing passes
[ ] CodeRabbit major/security issues are resolved or consciously rejected
[ ] TestSprite main journey passes if relevant
[ ] Documentation is updated if needed
[ ] The developer can explain what changed and why
```

---

## Public Repo Safety

This repository is intended to be public and portfolio-friendly.

Do not commit:

- API keys
- tokens
- passwords
- private client information
- private project links
- sensitive personal notes
- raw messy drafts that should remain private

Use this public repo as the polished version of the operating system. Keep private experiments and personal notes elsewhere.

---

## License

This project is licensed under the MIT License. See `LICENSE` for details.
