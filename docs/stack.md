# Recommended Stack for Trichygold (AI-ready jewelry e-commerce)

## Frontend (Web)
- **Next.js 14 (App Router) + React 18** for SEO, SSR, and performance.
- **TypeScript** for maintainability.
- **Tailwind CSS + Radix UI** for fast, accessible UI composition.
- **Framer Motion** for micro-animations and luxury feel.

## Backend/API
- **Next.js Route Handlers** for tight integration, or **NestJS** for a dedicated API.
- **tRPC** for type-safe API calls (optional but recommended).
- **Prisma** for database access and migrations.

## Data Stores
- **PostgreSQL** (primary relational DB).
- **Redis** (sessions, cache, carts, rate limits).

## E-commerce
- **Stripe** for payments + webhooks.
- **Shippo** or **EasyPost** for shipping labels and rates.
- **Algolia** (or Typesense) for product search and filtering.

## CMS/Content
- **Sanity** or **Contentful** for editorial content, product stories, and campaigns.

## AI Integration Layer
- **OpenAI/Anthropic** for product recommendations, support chatbot, and marketing copy.
- **RAG stack**: vector store (Pinecone/Weaviate/pgvector) + embeddings pipeline.
- **Feature flags**: LaunchDarkly or OpenFeature for AI feature rollout.

## Observability & Ops
- **Sentry** for error tracking.
- **OpenTelemetry** for tracing.
- **Vercel** (web), **Fly.io** or **Render** (API) for deployment.

## CI/CD
- **GitHub Actions** for tests, lint, build, and deploy workflows.
