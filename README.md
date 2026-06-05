# rainripples.rest

Personal portfolio site for RainRipples (Sabine). Speculative fiction, webcomics, music, storytelling.

## Stack
- Single HTML file (`rainripples_v4.html`) with inline CSS and JS — no build step, no dependencies
- Hosted on **GitHub Pages** → `sorainripples/rainripples.rest`
- Custom domain via **Porkbun** DNS → `rainripples.rest`

## How it deploys
1. Edit `rainripples_v4.html` locally
2. `git add . && git commit -m "message" && git push`
3. GitHub Pages auto-deploys on push — live within ~60 seconds

## DNS (Porkbun)
Four A records pointing `@` to GitHub's IPs (`185.199.108–111.153`) and a CNAME `www → sorainripples.github.io`.

## Assets
All images live in `/Assets/` — reference them as `Assets/filename.ext` in the HTML.
