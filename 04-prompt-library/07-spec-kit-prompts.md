# Spec Kit Prompts

Use these prompts before Cursor implementation.

## 1. Create Feature Specification

```text
Act as a specification-driven senior product engineer.

Create a feature specification for this project using my Junior Software Engineer AI Project Operating System.

Feature idea:
[paste feature idea]

Before writing the final specification, ask clarification questions if anything is unclear.

The specification must include:
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
- open questions
```

## 2. Review Specification

```text
Review this feature specification.

Check:
- unclear requirements
- missing acceptance criteria
- missing edge cases
- hidden security risks
- data model concerns
- UI/UX gaps
- testing gaps
- scope creep

Give me:
1. Must-fix issues
2. Nice-to-have improvements
3. Clarifying questions
4. Whether it is ready for technical planning
```

## 3. Create Technical Plan

```text
Act as a senior software architect.

Using this feature specification, create a technical implementation plan.

Include:
- architecture impact
- frontend changes
- backend/API changes
- database changes
- auth/permission changes
- external services
- risks
- testing plan
- deployment notes
- task generation notes

Do not write implementation code yet.
```

## 4. Generate Tasks

```text
Using this feature specification and technical plan, generate small implementation tasks.

Rules:
- Each task must be small enough for Cursor to implement in one focused step.
- Each task must connect back to the specification.
- Each task must include affected files, acceptance criteria, testing notes, and review notes.
- Do not combine unrelated work into one task.
- Order the tasks logically.
```

## 5. Cursor Task Prompt from Spec Kit

```text
Implement only this Spec Kit task.

Feature spec reference:
[paste relevant spec section]

Technical plan reference:
[paste relevant plan section]

Task:
[paste task]

Rules:
- Implement only this task.
- Do not add unrelated features.
- Do not change architecture without asking.
- Keep code readable for a junior developer.
- Include loading/error/empty states if relevant.
- Explain changed files.
- Explain how to test the task.
```

## 6. Compare Implementation Against Spec

```text
Compare this implementation against the original feature specification.

Check:
- Does the code satisfy every acceptance criterion?
- Did it add out-of-scope behavior?
- Are edge cases handled?
- Are security requirements met?
- Are tests sufficient?
- What is missing before this feature can be accepted?
```
