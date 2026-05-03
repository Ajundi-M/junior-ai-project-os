# Spec Kit Workflow

## 1. What Spec Kit Is

Spec Kit is the specification-driven development layer of this operating system.

It helps you move from:

```text
idea → specification → technical plan → small tasks → implementation
```

Spec Kit makes the specification the source of truth. That means Cursor should implement what the spec and task list say, not a vague idea in your head.

## 2. Why It Matters for a Junior Developer

AI can write code quickly, but fast code is not always correct code.

Spec Kit helps prevent:

- vague prompts
- AI coding before requirements are clear
- accepting code without understanding it
- missing edge cases
- missing acceptance criteria
- creating technical debt

For a junior developer, the biggest benefit is learning. You understand the feature before Cursor writes code, so you are less likely to accept code you cannot explain.

## 3. When to Use Spec Kit

Use Spec Kit based on project level:

```text
Level 1: optional lightweight specification
Level 2: standard
Level 3: required
Level 4: required
```

For Level 1, a short manual version is usually enough.

For Level 2, Level 3, and Level 4, use the full flow for serious features:

```text
Specify → Plan → Tasks → Cursor implementation
```

## 4. Spec Kit Lifecycle

### Specify

The specification explains what should be built.

Include:

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

Good specification question:

```text
What should be true when this feature is finished?
```

### Plan

The technical plan explains how the feature should be built.

Include:

- architecture impact
- frontend changes
- backend/API changes
- database changes
- auth/permissions
- external services
- risks
- testing plan
- deployment notes

Good planning question:

```text
What parts of the system need to change, and why?
```

### Tasks

The task list breaks the plan into small Cursor-ready tasks.

Each task should include:

- small task goal
- affected files
- acceptance criteria
- testing notes
- review notes
- connection back to the spec

Good task question:

```text
Can Cursor implement this in one focused step without guessing?
```

### Implement

Cursor implements one task at a time.

Rules:

- Cursor implements one Spec Kit task at a time.
- Do not change architecture without updating the plan.
- Compare implementation against the spec.
- If the task is vague, stop and clarify before coding.
- If requirements change, update the specification before continuing.

## 5. How Spec Kit Works With AI Tools

Use each tool for a clear role:

```text
ChatGPT = project manager and teacher
Claude = architect/reviewer
Spec Kit = specification, plan, tasks
Cursor = implementation
CodeRabbit = code review
TestSprite = user journey testing
```

Recommended flow:

```text
ChatGPT/Claude clarify the idea
→ Spec Kit creates the specification
→ Spec Kit creates the technical plan
→ Spec Kit creates small tasks
→ Cursor implements one task
→ CodeRabbit reviews the pull request
→ TestSprite validates the user journey
```

## 6. Important Boundary

Spec Kit does not guarantee good code.

You still need:

- self-review
- CodeRabbit
- manual testing
- TestSprite
- security review
- documentation

Spec Kit tells you what should be built. The other quality gates help prove that the built feature is correct, secure, understandable, and ready to show.
