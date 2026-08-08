# SupportFlow

> A multi-tenant customer support SaaS platform built to showcase modern frontend engineering — responsive UI, type-safe React, and AI-assisted agent workflows.

[![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white)](https://tailwindcss.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Prisma-4169E1?logo=postgresql&logoColor=white)](https://www.prisma.io/)

**Live demo:** _Coming soon — project is in active development._

## Preview

_Screenshots will be added as core UI flows are implemented (dashboard, ticket inbox, knowledge base)._

| Dashboard | Ticket Inbox | Knowledge Base |
| --- | --- | --- |
| _Coming soon_ | _Coming soon_ | _Coming soon_ |

## About This Project

SupportFlow is a portfolio-grade SaaS application that demonstrates how to design and build a production-style support platform from the ground up. It covers the full surface area a frontend engineer typically owns in a B2B product: multi-tenant workspaces, role-based access, data-dense dashboards, and AI-assisted workflows that keep humans in the loop.

**What this project demonstrates:**

- Building a responsive, accessible UI with reusable React components
- Structuring a Next.js app with clear separation between server and client concerns
- Enforcing type safety across the stack with TypeScript and Prisma
- Integrating AI features as assistive tools — summaries, draft replies, and classification — not autonomous replacements for agents

## Project Status

This project is currently in the initial setup and development phase.

## Tech Stack

- **Frontend:** Next.js, React, TypeScript, Tailwind CSS
- **Backend & data:** PostgreSQL, Prisma
- **Auth & security:** Authentication, workspace-level authorization
- **AI:** API integration for agent-assist workflows
- **Tooling:** Git & GitHub

## Core Features

- Multi-tenant company workspaces
- Customer support portal
- Ticket management
- Customer management
- Team and role management
- Support analytics
- Knowledge base
- AI-assisted support workflows
- Responsive UI
- Authentication and authorization

## Target Users

- Customers
- Support Agents
- Managers
- Administrators

## AI Features

The AI assistant is designed to support human agents rather than replace them.

Planned AI capabilities include:

- Ticket summarization
- AI-generated replies
- Sentiment detection
- Ticket classification
- Knowledge-base recommendations

## Getting Started

_Setup instructions will be added once the application scaffold is in place._

```bash
# Planned workflow
git clone https://github.com/<your-username>/supportflow.git
cd supportflow
npm install
cp .env.example .env.local   # configure database and API keys
npx prisma migrate dev
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) to view the app.

## Development Principles

The project is being built incrementally with a focus on:

- Clean and maintainable code
- Reusable components
- Strong TypeScript typing
- Responsive design
- Accessibility
- Performance
- Secure data handling
- Practical AI integration

## License

This project is licensed under the MIT License.
