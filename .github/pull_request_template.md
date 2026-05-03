# Pull Request Checklist

Use this template for every serious project change.

The goal is to make every pull request easy to review by you, CodeRabbit, and future employers/clients who inspect your workflow.

---

## 1. Summary

```text
What changed in this pull request?
```

---

## 2. Spec Kit Reference

```text
Feature/spec name:
Spec file or issue link:
Task ID:
```

If this is Level 2+ work, the PR should connect back to a specification, technical plan, and task.

---

## 3. Acceptance Criteria

```text
[ ] Acceptance criterion 1
[ ] Acceptance criterion 2
[ ] Acceptance criterion 3
```

---

## 4. What Changed

```text
Files/areas changed:
-
-
-
```

---

## 5. Manual Testing

```text
[ ] Happy path tested
[ ] Invalid input tested
[ ] Empty state tested if relevant
[ ] Loading state tested if relevant
[ ] Error state tested if relevant
[ ] Mobile layout tested if UI changed
[ ] Auth/permission behavior tested if relevant
```

Testing notes:

```text
Describe what you tested and what happened.
```

---

## 6. TestSprite Status

Choose one:

```text
[ ] Not needed for this change
[ ] TestSprite journey planned
[ ] TestSprite journey completed
[ ] TestSprite found issues and they were fixed
[ ] TestSprite found issues that are documented as follow-up work
```

Journey/result notes:

```text
Paste or summarize the TestSprite result here.
```

---

## 7. CodeRabbit Status

```text
[ ] CodeRabbit review requested/expected
[ ] Major issues fixed
[ ] Security issues fixed
[ ] Optional suggestions reviewed
[ ] I understand any accepted CodeRabbit suggestion
```

Notes:

```text
Mention important CodeRabbit comments or decisions.
```

---

## 8. Security Notes

```text
[ ] No secrets exposed
[ ] Auth checks reviewed if relevant
[ ] Database access rules reviewed if relevant
[ ] Input validation reviewed if relevant
[ ] API permissions reviewed if relevant
```

Security notes:

```text
Mention any security concern or reason this change is safe.
```

---

## 9. Screenshots / Demo

For UI changes, add screenshots or a short demo note.

```text
Before:
After:
```

---

## 10. Learning Notes

```text
What did I learn from this change?
What part should I be able to explain in an interview?
```

---

## 11. Final Definition of Done

```text
[ ] The change matches the specification
[ ] The feature works locally
[ ] The code is understandable
[ ] The main user flow is tested
[ ] CodeRabbit major/security issues are resolved
[ ] TestSprite is completed if needed
[ ] Documentation updated if needed
[ ] I can explain what changed and why
```
