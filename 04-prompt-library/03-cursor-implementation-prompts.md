# Cursor Implementation Prompts

Use these prompts in Cursor.

---

## Implement One Spec Kit Task

```text
Implement only this Spec Kit task.

Use the Spec Kit task as the source of truth.
Do not implement if the task is vague.
Ask for the spec or technical plan if missing.

Feature spec reference:
[paste relevant spec section]

Technical plan reference:
[paste relevant plan section]

Task:
[paste task]

Rules:
- Implement only this task.
- Do not implement unrelated features.
- Do not add new libraries unless necessary.
- Do not change architecture without asking.
- Keep code simple and readable for a junior developer.
- Follow the existing project structure.
- Add error/loading/empty states if relevant.
- Keep code changes traceable to the spec.
- Explain what files you changed and why.
- Explain how to test the task.
```

---

## Implement One Task

```text
Implement only this task.

Task:
[paste task]

Rules:
- Do not implement unrelated features.
- Do not add new libraries unless necessary.
- Keep code simple and readable.
- Follow the existing project structure.
- Add error/loading/empty states if relevant.
- Explain what files you changed and why.

If this is Level 2+ work and no Spec Kit spec/plan/task exists, ask for it before implementing.
```

---

## Debug Error

```text
I got this error:

[paste error]

Please:
1. Explain what the error means in simple language.
2. Identify the likely cause.
3. Propose the smallest safe fix.
4. Apply the fix only to the necessary files.
5. Explain how I can verify it works.
```

---

## Refactor Safely

```text
Refactor this code safely.

Goals:
- improve readability
- reduce duplication
- keep behavior the same
- avoid unnecessary architecture changes

Before changing behavior, compare against the Spec Kit specification or ask for it if missing.

After refactoring, explain:
- what changed
- why it is better
- how to test that nothing broke
```
