# Project Lifecycle

Use this lifecycle for every project.

## Full Lifecycle

```text
1. Idea
2. Clarify
3. Define Project Level
4. Choose Stack
5. Project Constitution
6. Spec Kit: Specify
7. Spec Kit: Plan
8. Spec Kit: Tasks
9. Cursor: Implement One Task
10. Self-Review
11. CodeRabbit Review
12. Manual Testing
13. TestSprite Testing
14. Security Review
15. Deployment
16. Documentation
17. Portfolio/Client Presentation
```

---

## 1. Idea

Write the idea in simple words.

```text
This project helps [user] do [task] so they can [benefit].
```

---

## 2. Clarify

Ask questions before planning.

Clarify:

- target user
- main problem
- required features
- optional features
- data model
- auth needs
- security needs
- deployment target
- portfolio goal

---

## 3. Define Project Level

Choose one:

- Level 1: Simple Portfolio Project
- Level 2: Professional Portfolio Project
- Level 3: Freelance/Client-Ready Project
- Level 4: SaaS/Product Project

The project level controls how much specification, testing, review, and documentation you need.

---

## 4. Choose Stack

Choose stack based on project needs, not trends.

Ask:

```text
Does this need auth?
Does this need a database?
Does this need Python?
Does this need AI?
Does this need payments?
Does this need file/image processing?
Does this need real-time features?
```

---

## 5. Project Constitution

The constitution defines the rules of the project.

Include:

- code style
- folder structure
- naming rules
- stack rules
- AI usage rules
- Spec Kit rules
- security rules
- testing rules
- documentation rules
- definition of done

---

## 6. Spec Kit: Specify

Write the feature specification before implementation.

Define:

- user goal
- problem
- scope
- out of scope
- expected behavior
- user stories
- acceptance criteria
- edge cases
- data requirements
- security requirements
- UI/UX requirements
- testing requirements

The specification answers: `What should be built?`

---

## 7. Spec Kit: Plan

Create the technical plan from the specification.

Define:

- architecture impact
- frontend changes
- backend/API changes
- database changes
- auth and permission changes
- external services
- risks
- testing plan
- deployment notes

The plan answers: `How should this be built?`

---

## 8. Spec Kit: Tasks

Break the plan into small tasks.

Each task should include:

- goal
- spec reference
- files likely affected
- implementation notes
- acceptance criteria
- testing notes
- review notes

The task list answers: `What should Cursor implement next?`

---

## 9. Cursor: Implement One Task

Build one Spec Kit task at a time.

Implementation loop:

```text
Read spec and plan
→ Understand current task
→ Implement only that task
→ Compare code against acceptance criteria
→ Run locally
→ Fix errors
→ Explain what changed
→ Commit when ready
```

Do not change architecture without updating the plan first.

---

## 10. Self-Review

Before using review tools, review yourself.

Ask:

```text
Does it match the specification?
Does it work?
Is the code readable?
Is there duplicate logic?
Are errors handled?
Are loading states handled?
Are secrets protected?
```

---

## 11. CodeRabbit Review

Open a pull request and let CodeRabbit review it.

Fix:

- major issues
- security issues
- logic issues
- missing test suggestions
- maintainability problems

Do not blindly accept every suggestion. Understand first.

---

## 12. Manual Testing

Manually test the feature like a real user.

Check:

- happy path
- wrong input
- empty data
- slow network/loading
- mobile layout
- refresh page
- logout/login if relevant

Use the acceptance criteria from the specification as your testing checklist.

---

## 13. TestSprite Testing

Use TestSprite for important user journeys after implementation.

Example journeys:

```text
Sign up → Login → Create item → Edit item → Delete item
Login → Configure settings → Save → Reload
Login → Upload file → Process file → View result
```

TestSprite validates that the built feature works for a real user. It does not replace the specification.

---

## 14. Security Review

Check:

- environment variables
- API permissions
- auth checks
- database row-level security
- input validation
- secret exposure
- API abuse/rate limits if needed

---

## 15. Deployment

Before deployment:

- build passes
- env vars configured
- database migrations applied
- app works in production
- no sensitive logs
- main flow tested after deploy

---

## 16. Documentation

Create:

- README
- architecture notes
- setup guide
- feature list
- testing notes
- known limitations
- future improvements

---

## 17. Portfolio/Client Presentation

Prepare:

- live demo
- screenshots
- GitHub repo
- short project summary
- technical summary
- what you learned
- what problems you solved
