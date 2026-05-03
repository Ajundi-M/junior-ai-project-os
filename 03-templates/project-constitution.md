# Project Constitution Template

The constitution defines the rules of the project.

Do not start implementation before this is complete.

---

## 1. Project Rules

```text
Project name:
Project level:
Project purpose:
Target user:
```

---

## 2. Stack Rules

```text
Frontend:
Backend:
Database:
Auth:
Storage:
Deployment:
Testing:
Review tools:
Specification tool: Spec Kit
```

---

## 3. Code Quality Rules

```text
[ ] Use TypeScript where possible
[ ] Use clear names
[ ] Keep components small
[ ] Avoid duplicate logic
[ ] Separate UI from business logic
[ ] Handle errors clearly
[ ] Add comments only when helpful
```

---

## 4. AI Usage Rules

```text
[ ] AI must ask clarification questions before planning
[ ] AI must produce small tasks
[ ] AI must explain major decisions
[ ] Cursor implements one task at a time
[ ] I must understand code before accepting it
[ ] AI must not introduce new libraries without approval
```

---

## 5. Spec Kit Rules

```text
[ ] Level 2+ features require written specification
[ ] Level 2+ features require technical plan before implementation
[ ] Implementation tasks must be generated from the plan
[ ] Cursor must implement one task at a time
[ ] Code changes must be traceable back to the specification
[ ] If requirements change, update the spec before continuing
```

---

## 6. Security Rules

```text
[ ] No secrets in frontend
[ ] No secrets committed to GitHub
[ ] Auth required for private pages
[ ] User can only access their own data
[ ] API validates input
[ ] Database access rules reviewed
```

---

## 7. Testing Rules

```text
[ ] Manual testing for every feature
[ ] Testing should use acceptance criteria from the specification
[ ] Unit/integration tests for important logic
[ ] TestSprite for main user journeys
[ ] CodeRabbit review before merge
```

---

## 8. Documentation Rules

```text
[ ] README must stay updated
[ ] Architecture notes must exist
[ ] Important decisions must be documented
[ ] Known limitations must be documented
```

---

## 9. Definition of Done

A feature is done only when:

```text
[ ] It matches the specification
[ ] It works locally
[ ] It is reviewed
[ ] It is tested
[ ] It is documented if needed
[ ] I can explain it
```
