# Secure Cloudflare proposal

This is a Worker + static assets deployment, not an assets-only Worker.

In Cloudflare, add these encrypted Worker secrets:
- PROPOSAL_PASSWORD = Aly
- SESSION_SECRET = a long random value

Do not put these secrets in GitHub.

Deploy with `npx wrangler deploy`.


Typography: Rustic Roadway is bundled locally in `RusticRoadway.otf` and used throughout the site.
