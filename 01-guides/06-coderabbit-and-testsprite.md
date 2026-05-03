# CodeRabbit and TestSprite in the System

CodeRabbit and TestSprite are professional quality gates.

They are not replacements for your own understanding.

---

## Relationship with Spec Kit

Spec Kit, CodeRabbit, and TestSprite work together, but they happen at different times.

```text
Spec Kit = specification, technical plan, and task breakdown before coding
Cursor = implementation of one task at a time
CodeRabbit = pull request code review after coding
TestSprite = user journey QA after implementation
```

Spec Kit defines what should be true. CodeRabbit checks code quality. TestSprite checks whether the built user journey works.

---

## CodeRabbit

Use CodeRabbit as the pull request review gate.

### When to use it

Use CodeRabbit after:

- a feature is implemented
- the app runs locally
- you have committed the changes
- you open a pull request

### What CodeRabbit helps with

- code quality
- maintainability
- possible bugs
- missing tests
- security concerns
- PR summaries
- review suggestions

### CodeRabbit workflow

```text
Finish Spec Kit task or feature
→ Run local app
→ Self-review against the spec
→ Commit changes
→ Open pull request
→ Let CodeRabbit review
→ Fix major/security/logic issues
→ Ask AI to explain unclear comments
→ Merge only when acceptable
```

### How to treat CodeRabbit comments

Fix immediately:

- security issues
- broken logic
- missing validation
- obvious bugs
- major maintainability problems

Think before accepting:

- style preferences
- large refactors
- suggestions that change architecture
- suggestions you do not understand

Never do this:

```text
Accept all suggestions blindly.
```

---

## TestSprite

Use TestSprite as the user journey and QA testing gate.

### When to use it

Use TestSprite after:

- the feature works locally
- manual testing passes
- the main flow is ready to verify

### What TestSprite helps with

- end-to-end testing
- user journey simulation
- regression testing
- frontend/backend behavior checks
- bug reports
- visual/user-facing issues

### TestSprite workflow

```text
Finish feature
→ Manual test using acceptance criteria
→ Define main user journey from the spec
→ Run TestSprite
→ Review failures
→ Fix bugs
→ Re-run critical tests
→ Accept feature
```

### Good journeys to test

```text
Sign up → Login → Create item → Edit item → Delete item
Login → Update settings → Refresh page → Confirm saved state
Login → Upload file → Process file → View result
Login → Configure AI key → Validate key → Generate result
```

---

## Required by project level

```text
Level 1: Optional
Level 2: Recommended/standard for serious portfolio projects
Level 3: Required
Level 4: Required
```

---

## Final rule

A feature is not done until:

```text
The implementation matches the specification.
CodeRabbit has no unresolved major/security issues.
TestSprite passes the main user journey when relevant.
You understand what was changed.
```
