# FTG Mini-Sites

Viral micro-sites and mini-apps for F--k The Game. Single-file HTML apps deployed to Cloudflare Pages via Git integration.

## Sites

| Site | Path | Cloudflare Project Root |
|------|------|------------------------|
| Truth or Chaos | `/truth-or-chaos/` | `/truth-or-chaos` |
| Pour Decisions | `/pour-decisions/` | `/pour-decisions` |
| Would You Rather | `/would-you-rather/` | `/would-you-rather` |

## Deploying a New Site

1. Add your `index.html` to a new folder: `/new-site-name/index.html`
2. `git add`, commit, push
3. In Cloudflare Dashboard: Pages → Create → Connect to Git → select this repo
4. Set "Root directory" to `/new-site-name`
5. Deploy — future pushes auto-deploy

## Cloudflare

- Account: `130374ea76fed829e9222376c53843e7`
- All projects point at this repo with different root directories
