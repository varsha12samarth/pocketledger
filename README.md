# PocketLedger — Personal Expense Tracker

PocketLedger is a lightweight, single-user web application for tracking daily
expenses, organizing spending by category, and monitoring progress against a
monthly budget. It was scoped as a Week 1 project-planning exercise for a
Junior Software Developer internship, focused on requirements gathering and
software design before implementation.

## Status

📋 **Planning phase.** This repository currently contains the project's
Software Requirements Document (SRD). Implementation will follow the
milestones outlined below.

## Project Vision

Tracking expenses by hand or in a generic spreadsheet is tedious and easy to
abandon. PocketLedger aims to let a user log an expense in under ten seconds
and immediately see how it affects their monthly budget, using a simple,
low-friction interface available on any device.

## Planned Tech Stack

| Layer | Technology |
|---|---|
| Front end | React |
| Back end | Node.js + Express (REST API) |
| Database | PostgreSQL |
| Auth | Email/password with bcrypt hashing + JWT sessions |
| Hosting | Free-tier PaaS (e.g. Render / Railway) |

## Core Features (MVP Scope)

- Account creation, login, and logout
- Add, edit, and delete expenses (amount, category, date, note)
- Custom and default expense categories
- Filter/search expenses by date, category, or keyword
- Monthly budget setting with visual status indicators
- Category breakdown summary and CSV export

See `docs/SRD.docx` for the full Software Requirements Document, including
functional and non-functional requirements, scope boundaries, constraints,
risks, and the development milestone roadmap.

## Roadmap

1. Requirements & Design
2. Core Backend (auth + expense API)
3. Core Frontend (add-expense flow, expense list)
4. Budgets & Reporting
5. Polish & QA
6. Deployment

## License

TBD
