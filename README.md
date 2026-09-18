# Quite Orbit M LLC — Website

Single-page static website for Quite Orbit M LLC (quiteorbit.com), built to satisfy
Apple Developer Program's requirement for a working company website.

## Structure

- `index.html` — all page content and markup
- `styles.css` — all styling
- No build step, no dependencies, no backend.

## Deploying

This is a plain static site, so both Vercel and Netlify will deploy it with zero
configuration once pushed to a GitHub repo:

1. Push this folder to a new GitHub repository.
2. On Vercel or Netlify, "Import" / "Add new site" from that repo.
3. Leave build settings blank (no build command, no output directory — or set
   output directory to `.` if the platform requires one).
4. Point the custom domain `quiteorbit.com` at the deployment (DNS setup is a
   separate manual step).
