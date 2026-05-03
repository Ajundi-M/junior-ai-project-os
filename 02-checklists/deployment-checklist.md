# Deployment Checklist

Use this before and after deploying.

---

## Before Deployment

```text
[ ] App builds locally
[ ] Lint/type checks pass if configured
[ ] Required environment variables are known
[ ] .env.example updated
[ ] Database migrations ready
[ ] Production database configured
[ ] Production auth URLs configured
[ ] No debug secrets or test keys in code
[ ] README setup instructions updated
```

---

## After Deployment

```text
[ ] Live URL opens
[ ] Signup/login works if relevant
[ ] Main user journey works
[ ] Database writes work
[ ] File uploads work if relevant
[ ] External API calls work if relevant
[ ] Mobile layout checked
[ ] No obvious console errors
[ ] TestSprite main journey run against deployed app if possible
```

---

## Final Deployment Note

Do not call a project portfolio-ready until the deployed version works, not only the local version.
