# Atelier Store

Ecommerce app scaffold.

## Stack
- Next.js (App Router) + TypeScript
- Tailwind CSS
- Better Auth (`src/lib/auth.ts`, route at `/api/auth/*`)
- Drizzle ORM + Postgres on Neon (`src/db`, `drizzle.config.ts`)

## Setup
1. `npm install`
2. `cp .env.example .env.local` and fill in values
3. `npm run dev`

## Scripts
`dev`, `build`, `start`, `lint`, `db:generate`, `db:migrate`, `db:push`, `db:studio`

## Status
Initial scaffold only: no schemas, auth flows, UI, payments or deployment yet.
