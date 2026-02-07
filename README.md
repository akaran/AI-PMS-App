## Project Structure

/frontend
├─ /components        # Reusable UI components (no business logic)
├─ /pages             # Route-level pages (Wouter routes)
├─ /hooks             # Custom React hooks (UI logic only)
├─ /services          # API clients (fetch / TanStack Query)
├─ /lib               # Shared frontend utilities (formatters, helpers)
├─ /schemas           # Zod schemas (forms, API responses)
├─ main.tsx
├─ App.tsx
└─ index.css

/backend
├─ /controllers       # HTTP request/response only
├─ /routes            # Express route definitions
├─ /services          # Business logic
├─ /repositories      # Drizzle DB access only
├─ /schemas           # Zod schemas (requests, commands)
├─ /migrations        # SQL / Drizzle migrations (up & down)
├─ /config            # DB, env, app config
├─ app.ts             # Express app setup
├─ server.ts          # Server bootstrap
└─ env.ts             # Zod-validated env vars

/tests
├─ /backend           # Backend unit + integration tests
├─ /frontend          # Frontend tests
└─ /e2e               # Optional later (Playwright, etc.)

/docs
├─ api.md              # API contracts (optional but encouraged)
├─ decisions.md        # Architectural decisions (human-written)
└─ features            # Feature-level design approvals

AI_DEV_CONTRACT.md


## Project Structure

I want to develop a fully AI-driven PMS application using the following tech stack:

## Tech Stack
## Frontend

React (latest) - UI framework with Hooks
TypeScript - Type safety
Vite - Fast build tool and development server
Tailwind CSS - Utility-first styling
shadcn/ui - High-quality, accessible UI components (50+ components)
TanStack Query - Server-state management
Wouter - Lightweight routing
React Hook Form + Zod - Form handling and validation
Lucide React - Icon library
Framer Motion - Animations
Recharts - Data visualization and charting

Backend

Node.js - Runtime environment
Express.js - HTTP server framework
Drizzle ORM - Type-safe database queries
PostgreSQL - Primary database
JWT / Passport.js - Authentication and authorization
Zod - Runtime schema validation

Database

PostgreSQL - Development database (Replit)
Drizzle Kit - Database schema migrations