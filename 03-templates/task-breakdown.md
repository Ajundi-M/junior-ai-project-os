# Task Breakdown Template

Use this lightweight template for Level 1 projects or very small changes.

For Level 2, Level 3, and Level 4 features, prefer `03-templates/spec-kit-task-list.md` so every task connects back to a written specification and technical plan.

---

## Phase Name

Example:

```text
Phase 1: Project Setup
Phase 2: Auth
Phase 3: Dashboard
Phase 4: Core Feature
Phase 5: Testing and Deployment
```

---

## Task Template

```text
Task ID:
Task name:
Goal:
Spec reference if available:
Files likely affected:
Detailed instructions:
Acceptance criteria:
Manual testing:
Automated testing:
Review notes:
Learning notes:
```

---

## Task Rules

```text
[ ] Task is small enough for one focused Cursor step
[ ] Task has a clear goal
[ ] Task has acceptance criteria
[ ] Task explains how to test it
[ ] Task does not combine unrelated work
```

---

## Example Task

```text
Task ID: AUTH-01
Task name: Create login page UI

Goal:
Create a responsive login page with email/password inputs and clear validation messages.

Spec reference if available:
Login feature UI/UX requirements.

Files likely affected:
- app/login/page.tsx
- components/auth/login-form.tsx

Acceptance criteria:
- Page is responsive
- Email and password fields exist
- Submit button exists
- Empty input validation exists
- Loading state exists
- Error message area exists

Manual testing:
- Visit /login
- Submit empty form
- Submit invalid email
- Check mobile layout

Review notes:
- Keep component small
- Do not connect Supabase yet
```
