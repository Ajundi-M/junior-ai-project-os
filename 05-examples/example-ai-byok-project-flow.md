# Example: AI BYOK Project Flow

Use this example when building apps where users bring their own OpenAI/Gemini API keys.

BYOK means Bring Your Own Key.

---

## Idea

```text
An AI content assistant where users add their own API key and generate content.
```

---

## Project Level

Usually:

```text
Level 2 or Level 3
```

Why?

Because BYOK involves sensitive user API keys.

---

## Recommended Stack

```text
Frontend: Next.js + TypeScript
Backend: FastAPI or secure Next.js server routes
Database/Auth: Supabase
Secret storage: Supabase Vault or secure encrypted storage
Deployment: depends on backend complexity
Planning: Spec Kit required for key storage and AI generation features
Review: CodeRabbit
Testing: TestSprite main BYOK journey
```

---

## Spec Kit Focus

Before Cursor implementation, the specification and plan must clearly answer:

```text
Where does the API key enter the system?
Where is it stored?
Who can access it?
How is it validated?
How is it hidden from the frontend after saving?
How can the user delete or replace it?
What should TestSprite verify after implementation?
```

Do not ask Cursor to build BYOK behavior from a vague prompt. This is security-sensitive work.

---

## Important Security Rules

```text
[ ] API key never exposed in frontend after saving
[ ] Key validated server-side
[ ] Key stored encrypted
[ ] UI only shows masked key
[ ] Key never appears in logs
[ ] User can delete/replace key
[ ] Backend checks authenticated user before using key
```

---

## Main User Journey for TestSprite

```text
User signs up
→ User opens settings
→ User adds API key
→ System validates key
→ UI shows masked key
→ User generates AI result
→ User deletes key
```

---

## Extra Review Needed

Ask AI and CodeRabbit to check:

```text
Can the key leak to frontend?
Can another user access this key?
Can the key appear in logs?
Can failed API calls expose sensitive data?
Can the endpoint be abused?
Does the implementation match the Spec Kit security requirements?
```
