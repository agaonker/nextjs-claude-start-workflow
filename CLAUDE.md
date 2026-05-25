# ToDo App - Claude Development Harness Rules

## Tech Stack
- Next.js 15+ (App Router)
- React 19 / TypeScript
- Tailwind CSS / shadcn/ui
- LocalStorage / Prisma (SQLite) for state
- Runtime & Package Manager: Bun

## Architecture & Code Style
- Use Server Components (`page.tsx`) for data fetching by default.
- Use Client Components (`'use client'`) only for interactive UI elements (e.g., input forms, toggle buttons).
- Strictly adhere to TypeScript strict mode. No `any`.
- Self-contained components go in `@/components/ui/`.

## Development Commands
- Install: `bun install`
- Add Package: `bun add <package>`
- Dev Server: `bun --bun run dev`
- Build: `bun --bun run build`
- Lint: `bun run lint`
- Test: `bun test`
