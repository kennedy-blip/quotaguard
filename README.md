# QuotaGuard

Full-stack token-bucket rate limiter, burst simulator, and HTTP rate-limit header inspector. Built with Vite, React, TypeScript, Tailwind CSS v4, and Vercel Functions.

## Local development

```bash
npm install
vercel dev
```

Open the local Vercel URL. `npm run dev` starts the Vite UI with a local in-memory API fallback.

## Deployment

Import this repository into Vercel. Framework preset: Vite. Build command: `npm run build`; output directory: `dist`.

> Demo API keys and counters are seeded in-memory examples. Serverless memory is ephemeral and per-instance; use a shared store such as Redis for production-grade distributed quotas.
