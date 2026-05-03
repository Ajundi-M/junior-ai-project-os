# Example Spec Kit Feature Flow

Example feature: add client management to a freelance invoice dashboard.

## 1. Feature Idea

```text
Add client management so a freelancer can save clients and reuse them when creating invoices.
```

## 2. Mini Specification

Feature name:

```text
Client Management
```

Project level:

```text
Level 2 — Professional Portfolio Project
```

User goal:

```text
As a freelancer, I want to add and manage clients so I can create invoices faster and keep client details organized.
```

In scope:

- view client list
- add client
- edit client
- delete client only when safe
- show loading, empty, and error states
- require login
- make sure users only see their own clients

Out of scope:

- importing clients from CSV
- client portal login
- advanced CRM notes
- email automation

Acceptance criteria:

```text
[ ] Logged-in user can see their own clients
[ ] Logged-in user can create a client with name and email
[ ] Client email is validated
[ ] User can edit client details
[ ] User can delete a client when allowed
[ ] Empty state appears when no clients exist
[ ] Loading and error states are visible when needed
[ ] Mobile layout is usable
[ ] User cannot access another user's clients
```

Edge cases:

- no clients yet
- invalid email
- duplicate client name
- slow network
- database error
- user logs out while on the page

Testing requirements:

- manually test create, edit, delete, empty state, and mobile layout
- add validation tests if validation logic is separate
- run a TestSprite journey for client creation and editing

## 3. Technical Plan Summary

Frontend changes:

```text
Add a clients page, client list component, client form component, and empty/error/loading states.
```

Backend/API changes:

```text
Add authenticated client create, read, update, and delete behavior using the existing backend pattern.
```

Database changes:

```text
Create a clients table with user ownership, name, email, optional phone, optional notes, created_at, and updated_at.
```

Auth and security:

```text
Only logged-in users can manage clients. A user can only access rows where user_id matches their account.
```

Risks:

```text
The biggest risk is leaking one user's client data to another user. Review auth checks and database rules carefully.
```

## 4. Task List

```text
Task ID: CLIENT-01
Task name: Create clients database model
Goal: Add the clients table and ownership rules.
Spec reference: Data requirements and security requirements.
Acceptance criteria: Table exists, user ownership is enforced, migrations are documented.
Testing notes: Confirm user cannot read another user's clients.
```

```text
Task ID: CLIENT-02
Task name: Build client list page UI
Goal: Create the clients page with loading, empty, and error states.
Spec reference: UI/UX requirements.
Acceptance criteria: Page is responsive and displays the correct states.
Testing notes: Open page with no clients, many clients, and simulated error.
```

```text
Task ID: CLIENT-03
Task name: Add create client form
Goal: Let a logged-in user create a client.
Spec reference: Expected behavior and acceptance criteria.
Acceptance criteria: Name is required, email is validated, successful save updates the list.
Testing notes: Submit empty form, invalid email, and valid client.
```

```text
Task ID: CLIENT-04
Task name: Add edit and delete behavior
Goal: Let a user update or delete their own clients.
Spec reference: Expected behavior, edge cases, and security requirements.
Acceptance criteria: Edit works, delete confirms intent, user cannot affect another user's clients.
Testing notes: Edit a client, delete a client, check permission behavior.
```

## 5. Cursor Implementation Instruction Example

```text
Implement only this Spec Kit task.

Feature spec reference:
Client Management acceptance criteria: logged-in user can create a client with name and email; email is validated; loading/error states are handled.

Technical plan reference:
Use the existing authenticated backend pattern. Do not add a new state management library.

Task:
CLIENT-03 — Add create client form.

Rules:
- Implement only this task.
- Do not add edit/delete behavior yet.
- Keep code readable for a junior developer.
- Include validation, loading, and error states.
- Explain changed files and how to test.
```

## 6. CodeRabbit Review Step

After the task or feature is implemented:

```text
Open a pull request and let CodeRabbit review the changes.
Focus on security, validation, data ownership, duplicated logic, and missing tests.
Do not blindly accept suggestions that change architecture. Ask AI to explain comments you do not understand.
```

## 7. TestSprite Journey

```text
Starting condition:
A test user account exists and is logged in.

Journey:
1. Open the clients page.
2. Confirm the empty state appears.
3. Create a client with name and email.
4. Confirm the client appears in the list.
5. Edit the client email.
6. Confirm the updated email appears after refresh.
7. Delete the client.
8. Confirm the empty state appears again.

Success criteria:
The user can complete the full client management journey without errors, broken layout, or wrong data.
```

## 8. Definition of Done

```text
[ ] Specification is clear
[ ] Technical plan is clear
[ ] Tasks are small and connected to the spec
[ ] Cursor implemented one task at a time
[ ] Acceptance criteria are met
[ ] Manual testing passes
[ ] CodeRabbit has no unresolved major/security issues
[ ] TestSprite journey passes
[ ] Security review confirms users can only access their own clients
[ ] README or portfolio notes mention client management if needed
[ ] I can explain how the feature works
```
