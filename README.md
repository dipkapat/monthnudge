# MonthNudge

Recurring monthly document checklists and bounded email reminders for solo bookkeepers.

## Development

```bash
npm install
cp .env.example .env
npm run db:migrate
npm run dev
```

## Tech Stack

- Server: TypeScript + Fastify + Prisma + PostgreSQL
- Web: React + Vite + TypeScript + Tailwind
- Scheduler: BullMQ + Redis
- Email: SMTP adapter
- Billing: Stripe
