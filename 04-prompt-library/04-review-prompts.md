# Review Prompts

Use these before and after CodeRabbit.

---

## Self-Review with AI

```text
Act as a senior code reviewer.

Review this feature/code for:
- correctness
- readability
- maintainability
- edge cases
- error handling
- loading/empty states
- security
- missing tests

Give me:
1. Major issues
2. Minor issues
3. Suggested improvements
4. Questions I should answer before merging
```

---

## Compare Code Against Specification

```text
Compare this implementation against the original feature specification.

Check:
- Does the code satisfy every acceptance criterion?
- Did it add out-of-scope behavior?
- Are edge cases handled?
- Are security requirements met?
- Are loading, empty, error, mobile, and accessibility states handled if required?
- Are tests sufficient for the project level?
- What is missing before this feature can be accepted?

Give me:
1. Must-fix issues
2. Nice-to-have improvements
3. Missing tests
4. Whether the feature is ready for CodeRabbit and TestSprite
```

---

## Explain CodeRabbit Comments

```text
CodeRabbit gave me these comments:

[paste comments]

Please explain:
1. What each comment means in beginner-friendly language.
2. Which comments are important.
3. Which comments are optional.
4. How to fix the important ones.
5. Whether any suggestion could be risky.
```

---

## Final Feature Acceptance Review

```text
Use my Definition of Done checklist and the feature specification.

Tell me whether this feature is ready to accept.

Check:
- specification match
- functionality
- code quality
- security
- testing
- documentation
- CodeRabbit issues
- TestSprite results
- whether I can explain the feature
```
