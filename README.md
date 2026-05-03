# Junior Software Engineer AI Project Operating System

This folder is your personal project-building system.

Use it when you start a new software project, especially portfolio, learning, freelance, SaaS, and AI-powered projects.

The goal is to help you build projects that are:

- professional
- secure
- stable
- understandable
- portfolio-ready
- client-trustworthy
- useful for learning
- built with AI support without becoming fully dependent on AI

## How to use this folder in Cursor

Open this folder in Cursor.

Start with:

1. `START-HERE.md`
2. `DAILY-WORKFLOW.md`
3. `NEW-PROJECT-CHECKLIST.md`
4. `01-guides/01-core-philosophy.md`
5. `01-guides/02-project-lifecycle.md`
6. `01-guides/07-spec-kit-workflow.md`
7. `03-templates/project-brief.md`
8. `03-templates/project-constitution.md`

For every new project, copy the templates into your actual project repo and fill them in.

## Daily Operating Files

Use these files often:

```text
DAILY-WORKFLOW.md = what to do when you open Cursor each day
NEW-PROJECT-CHECKLIST.md = how to start a project from zero
.github/pull_request_template.md = how to prepare professional PRs for CodeRabbit/review
.github/ISSUE_TEMPLATE/feature_spec.md = how to start a feature from a Spec Kit issue
```

## Main Workflow

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

## Spec Kit Role

Spec Kit is the specification governance layer of this system.

Use it before coding to define what should be built, plan how to build it, and break the work into small tasks. This prevents vague vibe coding and makes the specification the source of truth.

```text
Spec Kit = before coding specification, planning, and task breakdown
Cursor = implementation of one clear task at a time
CodeRabbit = after-coding pull request review
TestSprite = after-coding user journey QA
```

Spec Kit helps you learn because you understand the feature before accepting AI-generated code. Use the full Spec Kit workflow for Level 2, Level 3, and Level 4 projects. For Level 1 projects, use a lightweight manual version.

Read: `01-guides/07-spec-kit-workflow.md`

## Your default recommendation

For most serious portfolio projects:

```text
Project Level: Level 2 — Professional Portfolio Project
Frontend: Next.js + TypeScript
Styling: Tailwind CSS
Auth/Database: Supabase
Backend: Next.js API routes first
Advanced backend: FastAPI when Python, AI, or complex backend logic is needed
Deployment: Vercel + Supabase for simple apps
Planning: Spec Kit specification, technical plan, and task list
Testing: Manual + important unit/integration tests + TestSprite for main journeys
Review: CodeRabbit on pull requests
Documentation: README + architecture notes + portfolio writeup
GitHub workflow: feature issues + pull request template
```

## Important Rule

AI is your assistant, not your replacement.

After every feature, you must be able to explain:

- what was built
- what files changed
- why the solution works
- how data flows
- what can break
- how you tested it
- how the implementation connects back to the specification
