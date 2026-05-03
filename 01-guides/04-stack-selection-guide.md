# Stack Selection Guide

Choose the simplest professional stack that solves the project requirements.

Do not choose technology only because it is popular.

---

## Option A — Next.js + Supabase

Use when:

- app is mostly web UI
- you need auth
- you need database
- backend logic is simple
- you want fast deployment

Good for:

- dashboards
- CRUD apps
- booking systems
- invoice apps
- admin panels
- portfolio SaaS apps

Recommended stack:

```text
Frontend: Next.js + TypeScript
Styling: Tailwind CSS
Auth: Supabase Auth
Database: Supabase PostgreSQL
Storage: Supabase Storage if needed
Deployment: Vercel + Supabase
```

---

## Option B — Next.js + FastAPI + Supabase

Use when:

- you need Python
- you need AI workflows
- you need image/file processing
- you need complex backend logic
- you need external API orchestration
- you need long-running or structured backend services

Good for:

- AI apps
- image generation apps
- document processing apps
- automation tools
- advanced SaaS projects

Recommended stack:

```text
Frontend: Next.js + TypeScript
Backend: FastAPI
Database/Auth: Supabase
Storage: Supabase Storage or object storage
Infrastructure: Docker
Deployment: Vercel frontend + Render/Railway/Fly/VPS backend, or container hosting
```

---

## Option C — Frontend Only

Use when:

- project is simple
- no auth
- no database
- mostly UI or API consumption

Good for:

- landing pages
- small tools
- calculators
- design demos

Recommended stack:

```text
Frontend: Next.js or Vite + React
Styling: Tailwind CSS
Deployment: Vercel or Netlify
```

---

## When to use Docker

Use Docker when:

- project has multiple services
- you use FastAPI
- you need local environment parity
- you want professional backend practice
- deployment uses containers

Avoid Docker when:

- project is very small
- stack is only Next.js + Supabase
- Docker adds complexity without value

---

## Stack Decision Questions

Before choosing stack, answer:

```text
Does the project need authentication?
Does the project need a database?
Does the project need file uploads?
Does the project need AI APIs?
Does the project need Python?
Does the project need background jobs?
Does the project need payments?
Does the project need real-time updates?
Does the project need admin features?
Who will use this project?
Where will it be deployed?
```

---

## Your recommendation

For most serious portfolio projects:

```text
Start with Next.js + TypeScript + Supabase.
Add FastAPI only when the backend needs Python, AI orchestration, image/file processing, or complex business logic.
Use Docker when there is a real backend/multi-service need.
```
