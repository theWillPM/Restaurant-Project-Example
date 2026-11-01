# Restaurant Project Example — SODV1251

An instructor-owned **planning and collaboration example** for the six-week Full-Stack Web Application final group project. This repository currently demonstrates **project organization**, not a completed POS application.

## Project scope
- Customer experience: browse menu, manage cart, place orders, view status.
- Vendor experience: manage orders, menu, inventory, and sales reports.
- Node.js/Express: serve SPA, implement custom REST routes and business logic, enforce authentication and role-based authorization.
- Database: persist users, products, orders, inventory, and transactions.
- Deployment: demonstrate a publicly accessible app backed by a deployed server and persistent database.

## Course checkpoints
| Date | Deliverable |
| --- | --- |
| **November 16, 2026** | UI design, database/API plans, GitHub Projects and meaningful issues |
| **November 23, 2026** | Express server, database, and first fully working frontend-to-API-to-database feature |
| **December 3, 2026** | Integrated ordering, vendor management, authentication, authorization, and inventory |
| **December 15, 2026** | Testing, deployment, documentation, and final demonstration |

## How to use the issues
Each issue explains an implementable task, acceptance criteria, a target checkpoint, and expected evidence. Issues are examples, not a mandatory implementation order. Link feature branches and PRs to issues (e.g. `Closes #11`). Teams should revisit priorities as dependencies become clear. The GitHub issue and pull-request templates are stored in `.github/`.

## Suggested GitHub Project columns
**Backlog → Ready → In Progress → In Review → Done**. GitHub Project statuses are not yet configured in this example.

## Student responsibility
Students are responsible for providing verifiable evidence of their own contributions through issues, commits, PRs, working demonstrations, and explanations. The instructor is not responsible for reconstructing undocumented work.

## Security notes
Do not commit API keys, secrets, tokens, database credentials, or real customer information. Enforce authorization on the server, not merely by hiding buttons in the UI. Verify prices and order ownership on the server.
