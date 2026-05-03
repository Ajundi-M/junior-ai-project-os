# Daily Workflow

Use this file when you open Cursor and want to continue working without getting lost.

The goal is to keep your daily work focused, professional, and connected to the system.

---

## 1. Start of Session

Before coding, answer:

```text
What project am I working on?
What feature am I working on?
What project level is it?
What is the current Spec Kit task?
```

Checklist:

```text
[ ] I opened the correct project folder
[ ] I know the current feature
[ ] I know the project level
[ ] I found the related specification
[ ] I found the related technical plan
[ ] I found the current task
```

---

## 2. Choose One Task

Do not work on many tasks at the same time.

Choose one small task from the Spec Kit task list.

A good task should have:

```text
[ ] Clear goal
[ ] Spec reference
[ ] Likely affected files
[ ] Acceptance criteria
[ ] Testing notes
[ ] Review notes
```

If the task is vague, stop and clarify before using Cursor.

---

## 3. Implementation Rule

Cursor should implement only one Spec Kit task at a time.

Before implementation, confirm:

```text
[ ] I understand the feature specification
[ ] I understand the technical plan
[ ] I understand the current task
[ ] I know what should not be changed
[ ] I know how to test the task
```

---

## 4. Run and Read the Code

After Cursor makes changes:

```text
[ ] Read the changed files
[ ] Ask for explanation of unclear code
[ ] Run the app locally
[ ] Check for terminal errors
[ ] Check for browser console errors
[ ] Confirm the behavior matches the specification
```

Do not accept code you cannot explain.

---

## 5. Manual Test

Use the acceptance criteria from the specification.

Checklist:

```text
[ ] Happy path works
[ ] Invalid input is handled
[ ] Empty state works if relevant
[ ] Loading state works if relevant
[ ] Error state works if relevant
[ ] Mobile layout works if UI changed
[ ] Auth or permission behavior works if relevant
```

---

## 6. Self-Review

Ask:

```text
Does this match the specification?
Did implementation add anything out of scope?
Is the code readable?
Are private values protected?
Are errors handled?
Is the feature testable?
```

---

## 7. Commit and Pull Request

For serious work, open a pull request and use the repository PR template.

Checklist:

```text
[ ] PR links to spec or task
[ ] Acceptance criteria included
[ ] Manual testing documented
[ ] Security notes added if relevant
[ ] CodeRabbit review checked
[ ] Major or security issues fixed
```

---

## 8. TestSprite

Use TestSprite for important user journeys.

Checklist:

```text
[ ] Journey is based on the specification
[ ] TestSprite run completed if needed
[ ] Failures reviewed
[ ] Critical issues fixed
[ ] Main flow re-tested
```

---

## 9. End of Session Notes

Before stopping, write short notes:

```text
What I finished:
What is still broken:
What I should do next:
What I learned:
What I need to ask AI later:
```

This helps you restart faster next time.
