# Semantic Grid Redirect

This repository contains a simple redirect page for semanticgrid.ai domain.

## Purpose

Redirects visitors from https://semanticgrid.ai to the GitHub repository.

## Deployment

Deploy to Vercel:

```bash
vercel --prod
```

Then configure the domain:
1. In Vercel Dashboard, go to this project settings
2. Add domain: semanticgrid.ai
3. Remove semanticgrid.ai from the main web app project (keep beta.apegpt.ai there)

## Files

- `index.html` - Fallback HTML page with meta refresh and JavaScript redirect
- `vercel.json` - Server-side redirect configuration (primary method)

Both methods ensure the redirect works reliably.
