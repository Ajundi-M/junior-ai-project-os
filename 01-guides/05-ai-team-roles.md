# AI Team Roles

Use AI as a team with clear roles.

Do not let every AI do everything.

---

## 1. Project Manager AI

Recommended tool: ChatGPT

Responsibilities:

- understand project idea
- ask clarification questions
- define project level
- create roadmap
- help prepare feature specifications
- maintain the system
- help you stay organized

---

## 2. Architect AI

Recommended tool: ChatGPT or Claude

Responsibilities:

- choose stack
- design architecture
- define database model
- define API structure
- identify security risks
- review scalability
- create project constitution
- review Spec Kit technical plans

---

## 3. UI/UX Designer AI

Recommended tool: Gemini or Claude

Responsibilities:

- page structure
- user flows
- layout ideas
- responsive behavior
- accessibility
- empty/loading/error states
- visual consistency

---

## 4. Specification Tool

Recommended tool: Spec Kit

Responsibilities:

- turn feature ideas into clear specifications
- define acceptance criteria
- document edge cases
- create technical plans
- break work into small implementation tasks
- keep implementation traceable to the specification

Important rule:

```text
Spec Kit happens before Cursor implementation.
```

---

## 5. Implementer AI

Recommended tool: Cursor

Responsibilities:

- write code
- implement one Spec Kit task at a time
- refactor files
- fix errors
- create components
- follow exact task instructions

Important rule:

```text
The implementer should receive small, clear tasks from the Spec Kit task list.
```

---

## 6. Reviewer AI

Recommended tools: Claude, ChatGPT, CodeRabbit

Responsibilities:

- review code quality
- compare code against the specification
- find bugs
- check edge cases
- check security issues
- suggest better structure
- identify missing tests

---

## 7. QA AI

Recommended tool: TestSprite

Responsibilities:

- test main user journeys
- find user-facing bugs
- support regression testing
- create test reports
- simulate realistic flows
- validate acceptance criteria after implementation

---

## 8. Teacher AI

Recommended tool: ChatGPT

Responsibilities:

- explain what was built
- explain files and logic
- explain errors
- connect code back to the specification
- teach concepts
- prepare interview explanations

---

## AI Usage Rule

For every serious feature, use this flow:

```text
ChatGPT/Claude clarifies the idea
→ Spec Kit creates specification, plan, and tasks
→ Cursor implements one task
→ You read and run the code
→ ChatGPT/Claude explains unclear parts
→ CodeRabbit reviews PR
→ TestSprite tests main flow
```
