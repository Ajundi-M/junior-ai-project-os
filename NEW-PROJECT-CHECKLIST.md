# New Project Checklist

Use this checklist when starting a new project from zero.

The goal is to move from idea to first implementation task without skipping planning, security, testing, or documentation.

---

## 1. Project Purpose

Choose the project purpose:

```text
[ ] Learning
[ ] Portfolio
[ ] Freelance/client
[ ] SaaS/product idea
```

Write the idea:

```text
This project helps [user] do [task] so they can [benefit].
```

---

## 2. Project Level

Choose one:

```text
[ ] Level 1 — Simple Portfolio Project
[ ] Level 2 — Professional Portfolio Project
[ ] Level 3 — Freelance/Client-Ready Project
[ ] Level 4 — SaaS/Product Project
```

Recommended default for serious job-search projects:

```text
Level 2 — Professional Portfolio Project
```

---

## 3. Clarification Questions

Answer before planning:

```text
Who is the target user?
What problem does the project solve?
What are the main features?
What is out of scope for version 1?
Does it need authentication?
Does it need a database?
Does it store sensitive data?
Does it use external APIs or AI?
Where will it be deployed?
What should an employer/client notice?
```

---

## 4. Stack Decision

Choose the simplest professional stack that fits the project.

Common choices:

```text
[ ] Next.js + Supabase
[ ] Next.js + FastAPI + Supabase
[ ] Frontend-only app
[ ] Other, with explanation
```

Decision notes:

```text
Frontend:
Backend:
Database:
Auth:
Storage:
Deployment:
Testing:
Review tools:
Specification workflow:
```

---

## 5. Create Project Documents

Copy these templates into the new project:

```text
[ ] 03-templates/project-brief.md
[ ] 03-templates/project-constitution.md
[ ] 03-templates/architecture-plan.md
[ ] 03-templates/spec-kit-feature-spec.md
[ ] 03-templates/spec-kit-technical-plan.md
[ ] 03-templates/spec-kit-task-list.md
[ ] 03-templates/task-breakdown.md
[ ] 03-templates/portfolio-writeup.md
```

Suggested project docs folder:

```text
docs/
  project-brief.md
  project-constitution.md
  architecture-plan.md
  specs/
  plans/
  tasks/
  testing-notes.md
  portfolio-writeup.md
```

---

## 6. Project Constitution

Before coding, complete the constitution:

```text
[ ] Stack rules defined
[ ] Code quality rules defined
[ ] AI usage rules defined
[ ] Spec Kit rules defined
[ ] Security rules defined
[ ] Testing rules defined
[ ] Documentation rules defined
[ ] Definition of done defined
```

---

## 7. First Spec Kit Feature

Choose the smallest useful first feature.

Usually this is one of:

```text
[ ] Project setup
[ ] Auth setup
[ ] Main layout
[ ] First database model
[ ] First CRUD feature
[ ] First AI/API integration
```

Create:

```text
[ ] Feature specification
[ ] Technical plan
[ ] Small task list
```

---

## 8. First Cursor Task

Before asking Cursor to code:

```text
[ ] Task is small
[ ] Task has acceptance criteria
[ ] Task has testing notes
[ ] Task has likely affected files
[ ] Task connects to the specification
[ ] You know how to verify it
```

---

## 9. GitHub Setup

For a serious project:

```text
[ ] Git repository created
[ ] README started
[ ] .gitignore exists
[ ] .env.example exists if environment variables are needed
[ ] PR template copied or created
[ ] Feature issue template copied or created
[ ] First issue created from feature spec
```

---

## 10. First Definition of Done

The first feature is complete only when:

```text
[ ] It matches the specification
[ ] It works locally
[ ] Manual test passes
[ ] Code is understandable
[ ] No private values are exposed
[ ] Documentation updated if needed
[ ] CodeRabbit reviewed if PR was opened
[ ] TestSprite used if it affects main user journey
[ ] You can explain what changed and why
```
