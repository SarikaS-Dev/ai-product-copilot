# Product Decision Log

This document records important product and technical decisions made during the development of AI Product Copilot.

---

## Decision #001

### Title

Backend & Database Selection

### Decision

Use **Supabase** instead of **Firebase**.

### Reason

AI Product Copilot manages highly relational data such as projects, PRDs, user stories, meeting notes, feedback, prompts, evaluations, and analytics. A PostgreSQL-based relational database provides better support for these relationships and enables more powerful querying.

### Trade-off

Slightly more setup and SQL knowledge compared to Firestore, but greater flexibility, scalability, and reporting capabilities.

### Status

Accepted

### Date

July 2026

---

## Decision #002

### Title

Product Positioning

### Decision

Position AI Product Copilot as a **context-aware AI workspace** rather than a collection of AI tools.

### Reason

Most AI assistants require users to repeatedly provide context. AI Product Copilot will retain project knowledge—including PRDs, customer feedback, meetings, roadmaps, and analytics—to deliver more accurate, consistent, and personalized recommendations throughout the product lifecycle.

### Trade-off

Requires additional engineering effort to maintain project memory and context, but creates a significantly better user experience and stronger product differentiation.

### Status

Accepted

### Date

July 2026
