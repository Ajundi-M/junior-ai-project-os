# Core Philosophy

This system exists to help you build professional projects while improving as a software engineer.

## Principles

### 1. Understand before building

Never build from a vague idea.

You must understand:

- user
- problem
- goal
- main features
- data
- risks
- project level

### 2. Clarify before planning

Before creating a plan, ask questions.

Good software starts with clear requirements.

### 3. Specification before implementation

Serious features should not go straight into Cursor.

For Level 2, Level 3, and Level 4 work, define the feature first with Spec Kit:

- specification: what should be built
- technical plan: how it should be built
- task list: what Cursor should implement one step at a time

This keeps the specification as the source of truth and prevents vague vibe coding.

### 4. Plan before coding

Coding should follow a plan.

The plan should include:

- project level
- stack choice
- architecture
- pages
- database
- API
- UI/UX
- testing
- deployment
- documentation

### 5. Build one feature at a time

Do not ask AI to build the full app in one prompt.

Bad:

```text
Build the entire dashboard.
```

Good:

```text
Implement task CLIENT-01 from the Spec Kit task list: create the client list page with loading, empty, and error states.
```

### 6. Review before moving forward

Every feature needs review.

Use:

- your own self-review
- AI review against the specification
- CodeRabbit review for pull requests

### 7. Test before deployment

Testing is not optional.

At minimum:

- manual testing
- main user journey testing
- form validation checks
- error state checks

For serious projects:

- unit tests
- integration tests
- TestSprite E2E/user journey testing

### 8. Document before showing

A professional project needs clear documentation.

Employers and clients should understand:

- what the project does
- why you built it
- what technologies you used
- how to run it
- what features exist
- what you learned
- what you would improve

### 9. AI is a team, not magic

Use AI as:

- planner
- architect
- specification helper
- implementer
- reviewer
- teacher

Do not use AI as a blind code generator.

### 10. Security is part of professionalism

Even portfolio projects should avoid careless security mistakes.

Never expose:

- API keys
- service role keys
- database passwords
- private tokens
- user secrets

### 11. Every project must teach you something

At the end of each feature, write short learning notes:

```text
What I built:
What I learned:
What was difficult:
What I still do not fully understand:
```
