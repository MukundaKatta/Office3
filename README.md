# Office3 — o3labs.ai

**Marketing site for Officethree Technologies — AI-powered products for small businesses.**

**Live:** <http://o3labs.ai/>

This is the public-facing marketing site for **Officethree Technologies**.
The full product catalogue lives in sibling repos under the same
GitHub org — this repo is the front door.

## What's here

```
.
├── index.html        # main landing page (~3.1k lines, single file)
├── 404.html          # branded not-found page
├── privacy.html      # privacy policy
├── terms.html        # terms of service
├── sitemap.xml       # SEO sitemap
├── robots.txt
└── CNAME             # GitHub Pages → o3labs.ai
```

The site is intentionally a **single static HTML file** — no build
step, no JS framework, no CMS. Edit `index.html`, push, GitHub Pages
serves it.

## Product catalogue (other repos)

Officethree's open-source product lineup, all under
[github.com/MukundaKatta](https://github.com/MukundaKatta):

| Repo | What it is |
|------|------------|
| [QueryForge](https://github.com/MukundaKatta/QueryForge) | Natural language → SQL with zero LLM calls |
| [PromptLab](https://github.com/MukundaKatta/PromptLab) | A/B testing for prompts with real statistics |
| [parvati](https://github.com/MukundaKatta/parvati) | Tiny agentic workflow engine |
| [plutus](https://github.com/MukundaKatta/plutus) | Prediction-market analytics (Kelly, arb, Brier) |
| [prithvi](https://github.com/MukundaKatta/prithvi) | Static security scanner for Dockerfiles |
| [prajapati](https://github.com/MukundaKatta/prajapati) | Schema → HTML form / React component generator |
| [rama](https://github.com/MukundaKatta/rama) | Plan→act→observe agent loop |
| [rudra](https://github.com/MukundaKatta/rudra) | Function-scoped chaos engineering |
| [proppilot](https://github.com/MukundaKatta/proppilot) | AI property-management toolkit |
| [prometheus](https://github.com/MukundaKatta/prometheus) | Deep research agent pipeline |
| [parashurama](https://github.com/MukundaKatta/parashurama) | GitHub analytics dashboard |
| [promptpack](https://github.com/MukundaKatta/promptpack) | Package manager for Claude Code skills |
| [robotbrain](https://github.com/MukundaKatta/robotbrain) | Foundation-model platform for robotic manipulation |
| [Oradent](https://github.com/MukundaKatta/Oradent) | Open-source dental practice management |
| [rnht](https://github.com/MukundaKatta/rnht) | Rudra Narayana Hindu Temple platform |

## Editing the site

```bash
# Local preview (any static server will do)
python3 -m http.server 8000
open http://localhost:8000

# Then push — GitHub Pages takes a minute to re-deploy.
git add index.html
git commit -m "tweak hero copy"
git push
```

## License

Site copy is © Officethree Technologies. The product repos linked above
are individually MIT-licensed — see each repo for its license file.
