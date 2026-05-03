# Example: Level 2 SaaS Dashboard Flow

This example shows how to apply the system to a serious portfolio project.

---

## Idea

```text
A simple SaaS dashboard that helps freelancers track clients, invoices, and payment status.
```

---

## Project Level

```text
Level 2 - Professional Portfolio Project
```

Reason:

- good for job portfolio
- includes auth, database, dashboard UI
- shows full-stack ability
- not too complex like a real SaaS product

---

## Stack

```text
Frontend: Next.js + TypeScript
Styling: Tailwind CSS
Auth: Supabase Auth
Database: Supabase PostgreSQL
Deployment: Vercel + Supabase
Planning: Spec Kit specification, technical plan, and task list
Review: CodeRabbit
Testing: Manual + important tests + TestSprite main journey
```

---

## Main Features

```text
1. Signup/login
2. Dashboard overview
3. Client CRUD
4. Invoice CRUD
5. Payment status tracking
6. Basic charts
7. Settings page
```

---

## Spec Kit Step

Before Cursor implementation, create:

```text
1. A feature specification for each serious feature
2. A technical plan for how the feature changes the app
3. Small Cursor-ready tasks connected to the spec
```

Example:

```text
Client CRUD
→ Spec Kit: specify client behavior, acceptance criteria, edge cases, and security rules
→ Spec Kit: plan pages, components, API/database changes, and testing
→ Spec Kit: generate CLIENT-01, CLIENT-02, CLIENT-03 tasks
→ Cursor: implement one task at a time
```

---

## Main User Journey for TestSprite

```text
User signs up
→ User logs in
→ User creates a client
→ User creates an invoice for that client
→ User marks invoice as paid
→ Dashboard updates total paid amount
```

---

## Example Phases

```text
Phase 1: Project setup and constitution
Phase 2: Spec Kit planning for auth and dashboard foundation
Phase 3: Supabase auth tasks
Phase 4: Dashboard layout tasks
Phase 5: Spec Kit planning for client management
Phase 6: Client management tasks
Phase 7: Invoice management tasks
Phase 8: Dashboard metrics tasks
Phase 9: Testing, review, deployment, and documentation
```

---

## Example Definition of Done

```text
[ ] Level 2 features have specs, plans, and task lists
[ ] Auth works
[ ] User can only see own clients/invoices
[ ] Dashboard works on mobile
[ ] Empty states exist
[ ] Input validation exists
[ ] CodeRabbit review completed
[ ] TestSprite main journey passes
[ ] README and portfolio writeup completed
```
