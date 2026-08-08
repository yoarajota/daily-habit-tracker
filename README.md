# Nunca Pare de Lutar

Daily habit tracker for teams and accountability groups.

## What it does

Users log their daily activities — exercise, study, rest days — and the dashboard shows everyone's entries in real time.

## Tech Stack

- **Framework:** Next.js 14 (App Router)
- **Language:** TypeScript
- **Database:** Supabase (PostgreSQL + Auth)
- **UI:** Radix UI + TailwindCSS + shadcn/ui
- **i18n:** Locale-based routing (pt / en)

## Features

- Email/password authentication
- Daily check-in form (custom name, description, rest day toggle)
- Shared dashboard with all users' entries for the current day
- Historical view grouped by date
- User profiles with avatars
- Server actions for data fetching and form submission

## Getting Started

```bash
cp .env.example .env.local
npm install
npm run dev
```
