# Security Checklist

Use this for every project.

---

## Secrets

```text
[ ] No API keys in frontend code
[ ] No service role keys exposed
[ ] No secrets committed to GitHub
[ ] .env files ignored by Git
[ ] .env.example exists with fake values
[ ] Production secrets configured in hosting platform
```

---

## Authentication

```text
[ ] Protected pages require login
[ ] Backend/API checks authenticated user
[ ] User can only access their own data
[ ] Logout works
[ ] Session refresh works if needed
```

---

## Database

```text
[ ] Row Level Security enabled if using Supabase
[ ] Tables have clear ownership rules
[ ] Insert/update/delete policies are reviewed
[ ] Sensitive fields are not returned to client
[ ] Migrations are version controlled
```

---

## API

```text
[ ] API validates input
[ ] API handles errors safely
[ ] API does not leak stack traces
[ ] API checks permissions
[ ] Rate limiting considered for public/AI endpoints
```

---

## BYOK / User API Keys

Use this when users provide their own OpenAI, Gemini, or other API keys.

```text
[ ] Raw API key never reaches frontend after saving
[ ] Key is validated server-side before saving
[ ] Key is encrypted or stored in a secret manager
[ ] UI only shows masked key
[ ] Logs never contain the key
[ ] User can delete/rotate the key
```

---

## Final Security Question

Before showing the project publicly, ask:

```text
If someone malicious signs up, what can they access, abuse, or break?
```
