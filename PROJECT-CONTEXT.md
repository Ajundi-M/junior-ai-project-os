# Project Context: Junior AI Project OS

Use this file as the persistent context for future ChatGPT/Cursor conversations about this repo.

When starting a new chat about this project, paste or reference this file first so the assistant understands the full system goal, decisions, rules, and current direction.

---

## 1. Project Identity

Repository:

```text
Ajundi-M/junior-ai-project-os
```

Project name:

```text
Junior Software Engineer AI Project Operating System
```

Purpose:

```text
A Cursor-ready operating system/playbook that helps a junior software engineer build professional software projects with AI support.
```

Target user:

```text
A junior software engineer who uses AI heavily and wants to build professional portfolio, freelance, SaaS, and AI-powered projects while learning deeply.
```

---

## 2. User Background

The user is a junior software engineer.

Current skill level:

```text
Good but not perfect: JavaScript, TypeScript, Python, SQL, Docker
Can understand: Next.js, FastAPI, Supabase, deployment concepts, AI workflows
Needs more practice: frontend, security, testing, UI/UX, project planning
Still relies on AI for many implementation steps
```

Main goals:

```text
Build strong projects for first software engineering job search
Create portfolio projects that employers can trust
Create freelance-ready projects later
Learn what, why, and how while building
Avoid blind AI coding
Build stable, professional, secure, documented projects
```

Preferred working style:

```text
Deep planning before coding
Beginner-friendly explanations
Detailed step-by-step systems
Flexible stack selection depending on project needs
Quality is priority, but cost matters
```

---

## 3. Core Philosophy

The system should help the user build and learn at the same time.

Main principles:

```text
Understand before building
Clarify before planning
Specify before implementation
Plan before coding
Break work into small tasks
Cursor implements one task at a time
Review before moving forward
Test before deployment
Document before showing
Use AI as a team, not magic
Never accept AI code blindly
Every project must teach something
```

Important learning rule:

```text
After every feature, the user must be able to explain:
- what was built
- what files changed
- why the solution works
- how data flows
- what can break
- how it was tested
- how the implementation connects back to the specification
```

---

## 4. Official System Workflow

Use this workflow for every serious project:

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

---

## 5. Project Levels

The system uses levels to avoid underbuilding or overbuilding.

```text
Level 1: Simple Portfolio Project
Level 2: Professional Portfolio Project
Level 3: Freelance/Client-Ready Project
Level 4: SaaS/Product Project
```

Default recommendation:

```text
Use Level 2 for most serious job-search portfolio projects.
```

Spec Kit expectation:

```text
Level 1: optional lightweight/manual specification
Level 2: standard for serious features
Level 3: required
Level 4: required
```

---

## 6. Tool Roles

Use AI/tools as a structured team:

```text
ChatGPT = project manager, teacher, system maintainer
Claude = architect, reviewer, complex reasoning
Gemini = UI/UX, visual reasoning, frontend feedback
Spec Kit = specification, technical plan, task breakdown
Cursor = implementation environment
CodeRabbit = pull request review gate
TestSprite = user journey and QA gate
GitHub = source control, issues, PRs, portfolio proof
```

Important tool boundaries:

```text
Spec Kit happens before implementation.
Cursor implements one clear task at a time.
CodeRabbit reviews code after implementation.
TestSprite validates user journeys after implementation.
```

---

## 7. Spec Kit Role

Spec Kit is the specification governance layer of the system.

Purpose:

```text
Prevent vague AI coding
Make the specification the source of truth
Force features through specify → plan → tasks → implementation
Help the user understand the feature before accepting generated code
Keep implementation traceable to requirements
```

Spec Kit lifecycle:

```text
Specify: define what should be built
Plan: define how it should be built
Tasks: break the plan into small implementation steps
Implement: Cursor implements one task at a time
```

Spec Kit does not replace:

```text
Self-review
CodeRabbit
Manual testing
TestSprite
Security review
Documentation
```

---

## 8. Default Stack Strategy

Do not force one stack for every project.

Choose the simplest professional stack that solves the project requirements.

Recommended defaults:

```text
Most portfolio web apps:
Next.js + TypeScript + Tailwind CSS + Supabase

Advanced AI/backend/data/file/image projects:
Next.js + TypeScript + FastAPI + Supabase + Docker

Simple frontend-only projects:
Next.js or Vite + React + Tailwind CSS
```

Use FastAPI when:

```text
Python is needed
AI orchestration is complex
Image/file/document processing is needed
Backend logic is complex
External API orchestration is important
```

Use Docker when:

```text
The project has multiple services
FastAPI is used
Environment parity matters
Container deployment is planned
```

---

## 9. Quality Gates

Feature Definition of Done:

```text
Feature has clear specification if Level 2+
Feature has technical plan if Level 2+
Feature was broken into small tasks before implementation
Feature works locally
Code is readable
Inputs are validated
Loading/empty/error states exist if needed
Mobile layout works if relevant
Auth/database permissions are correct if relevant
No secrets are exposed
Manual testing passes
Important tests added if needed
CodeRabbit major/security issues fixed or consciously rejected
TestSprite main journey passes if relevant
Documentation updated if needed
User can explain what changed and why
```

Project Definition of Done:

```text
Main features completed
App deployed
Main user journeys work in production
README completed
Architecture notes completed
Setup instructions completed
Screenshots added
Demo account added if useful
Known limitations documented
Future improvements documented
Security checklist completed
Testing checklist completed
CodeRabbit has no unresolved critical issues
TestSprite validates main user journeys
Portfolio writeup completed
```

---

## 10. GitHub Workflow Preferences

For this repository:

```text
Small documentation/system improvements → commit directly to main
Bigger restructuring or risky changes → tell the user first and wait for approval
Do not automatically create a branch/PR unless the user specifically asks
Destructive changes like deleting many files or replacing the whole system → always ask first
```

The user gave approval for ongoing edits to this repo when requested in chat, with the safety boundary above.

---

## 11. Important Repo Files

Start here:

```text
README.md
START-HERE.md
DAILY-WORKFLOW.md
NEW-PROJECT-CHECKLIST.md
PROJECT-CONTEXT.md
```

Core guides:

```text
01-guides/01-core-philosophy.md
01-guides/02-project-lifecycle.md
01-guides/03-project-levels.md
01-guides/04-stack-selection-guide.md
01-guides/05-ai-team-roles.md
01-guides/06-coderabbit-and-testsprite.md
01-guides/07-spec-kit-workflow.md
```

Core checklists:

```text
02-checklists/definition-of-done.md
02-checklists/security-checklist.md
02-checklists/testing-checklist.md
02-checklists/spec-kit-checklist.md
02-checklists/deployment-checklist.md
02-checklists/documentation-checklist.md
```

Core templates:

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

Prompt library:

```text
04-prompt-library/01-project-manager-prompts.md
04-prompt-library/02-architect-prompts.md
04-prompt-library/03-cursor-implementation-prompts.md
04-prompt-library/04-review-prompts.md
04-prompt-library/05-testing-prompts.md
04-prompt-library/06-learning-prompts.md
04-prompt-library/07-spec-kit-prompts.md
```

GitHub workflow:

```text
.github/pull_request_template.md
.github/ISSUE_TEMPLATE/feature_spec.md
```

---

## 12. How Future Chats Should Start

When starting a new chat about this system, the user can say:

```text
We are working on my Junior AI Project OS repo: Ajundi-M/junior-ai-project-os.
Please read/use PROJECT-CONTEXT.md as the persistent context before suggesting changes.
```

The assistant should then:

```text
1. Read PROJECT-CONTEXT.md if repo access is available.
2. Follow the official workflow and tool boundaries.
3. Preserve beginner-friendly language.
4. Avoid enterprise-heavy complexity unless the user asks.
5. Treat Spec Kit as before-coding governance.
6. Treat CodeRabbit and TestSprite as after-coding quality gates.
7. For risky repo changes, tell the user first and wait for approval.
```

---

## 13. Current Direction

The project should be updated continuously as the user learns better workflows, tools, and practices.

Future improvements may include:

```text
More example project flows
More project-type-specific playbooks
Better security review templates
More testing strategy examples
Interview explanation templates
Portfolio case study templates
Spec Kit examples for real projects
Cursor rules for specific stacks
```

Keep the system practical, clear, and useful inside Cursor.
