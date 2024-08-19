# Next.js reproduction of issue #68805

To run this repo you'll need a Postgres database connection string.

1. Copy `.env.example` to `.env` and ensure the DATABASE_URI is correct
1. Run `pnpm dev` - see that it works
1. Run `pnpm dev --turbo` to see that it fails

### Rolling back to Next.js 15 canary 83

If you roll back the Next.js version to canary 83, you'll see that Turbopack works.
