# Project Levels

Not every project needs the same complexity.

Use levels to avoid underbuilding or overbuilding.

---

## Level 1 — Simple Portfolio Project

Use for:

- learning
- simple demos
- small portfolio apps

Examples:

- todo app
- notes app
- weather dashboard
- simple blog
- small calculator/tool

Required:

- clean UI
- responsive layout
- basic functionality
- README
- live demo
- manual testing

Spec Kit expectation:

```text
Optional lightweight specification.
```

For Level 1, you can write a short manual spec with the goal, scope, acceptance criteria, and testing notes.

Optional:

- auth
- database
- unit tests

---

## Level 2 — Professional Portfolio Project

This is your recommended default for serious job-search projects.

Use for:

- portfolio projects
- job applications
- GitHub showcase
- serious learning

Examples:

- SaaS dashboard
- CRM mini-app
- invoice manager
- booking system
- AI content tool
- analytics dashboard

Required:

- Spec Kit specification for serious features
- Spec Kit technical plan before implementation
- Spec Kit task list before Cursor coding
- clean professional UI
- responsive design
- auth if user data exists
- database if persistent data exists
- input validation
- loading states
- error states
- empty states
- basic security review
- manual testing
- important unit/integration tests
- TestSprite main journey testing
- CodeRabbit PR review
- README
- architecture notes
- deployed demo
- screenshots
- portfolio writeup

Spec Kit expectation:

```text
Standard for serious features.
```

---

## Level 3 — Freelance/Client-Ready Project

Use for:

- client work
- freelance delivery
- business users

Required:

- everything in Level 2
- Spec Kit required for features and changes
- stronger auth rules
- role-based access if needed
- better error handling
- better logging
- deployment guide
- client handoff document
- more complete testing
- backup/export thinking
- maintenance notes

Spec Kit expectation:

```text
Required.
```

---

## Level 4 — SaaS/Product Project

Use for:

- serious product ideas
- paid SaaS
- public launch

Required:

- everything in Level 3
- Spec Kit required for product features, migrations, and risky changes
- payments if needed
- admin dashboard
- user settings
- email notifications if needed
- monitoring
- rate limiting
- privacy/legal pages
- CI/CD
- scalability plan
- stronger security review

Spec Kit expectation:

```text
Required.
```

---

## Your default

For your next serious projects:

```text
Use Level 2 unless the project is intentionally small or client/product ready.
Use Spec Kit for Level 2+ features before asking Cursor to implement.
```
