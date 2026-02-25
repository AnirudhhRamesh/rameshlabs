# rameshlabs.com

Minimal placeholder site for Ramesh Labs.

## Publish steps

1. Create a new GitHub repository (suggested name: `rameshlabs.com`).
2. Push this folder to that repo.
3. In the repo settings, enable GitHub Pages:
   - Source: `Deploy from a branch`
   - Branch: `main` / `(root)`
4. Add the custom domain `rameshlabs.com` in GitHub Pages settings.
5. In Namecheap, set the DNS records:
   - A records (host `@`) to GitHub Pages IPs
   - CNAME (host `www`) to your GitHub Pages domain, e.g. `anirudhhramesh.github.io`

If you already have a user page at `anirudhhramesh.github.io`, this won’t break it. A separate project repo + custom domain is independent.
