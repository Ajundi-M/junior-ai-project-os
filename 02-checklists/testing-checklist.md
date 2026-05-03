# Testing Checklist

Testing protects your project from bugs and gives employers/clients trust.

---

## Manual Testing

For every feature:

```text
[ ] Happy path works
[ ] Wrong input handled
[ ] Empty state handled
[ ] Loading state handled
[ ] Error state handled
[ ] Mobile layout works
[ ] Refresh page still works
[ ] Auth behavior works if relevant
```

---

## Unit Testing

Use for:

- utility functions
- validation logic
- formatting logic
- calculations
- prompt construction
- business rules

Checklist:

```text
[ ] Important pure functions tested
[ ] Edge cases tested
[ ] Invalid input tested
```

---

## Integration Testing

Use for:

- API + database
- auth flow
- external API interaction
- backend service logic

Checklist:

```text
[ ] Important API routes tested
[ ] Database operations tested
[ ] Auth permission checks tested
[ ] Error responses tested
```

---

## TestSprite Testing

Use for user journeys.

Checklist:

```text
[ ] Main journey defined
[ ] TestSprite run completed
[ ] Failures reviewed
[ ] Critical bugs fixed
[ ] Main journey re-tested
[ ] Test results saved or summarized
```

---

## Recommended by Project Level

```text
Level 1: Manual testing
Level 2: Manual + important unit/integration + TestSprite main journey
Level 3: Manual + unit + integration + TestSprite critical journeys
Level 4: Full testing strategy + regression testing + monitoring
```
