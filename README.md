# AdamOne Edu — coming soon / wkrótce

Bilingual (PL-first, EN subtitles) one-pager announcing the upcoming official
site at **adamone.edu.pl**. Static — one `index.html`, no build step.

**Live:** https://adamone.edu.pl/ (also: https://adam0thman.github.io/adamone-edu/)

DNS (Cloudflare, gray-cloud/DNS-only): 4× A `@` → `185.199.108–111.153`,
CNAME `www` → `adam0thman.github.io`. HTTPS enforced, cert covers both
`adamone.edu.pl` and `www.adamone.edu.pl`.

## Local preview

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

Brand emblem: `emblem.svg` — A1E seal, used as favicon and header mark.

## Domain

Connected 2026-08-31 — `CNAME` file in repo root, cert approved, HTTPS
enforced. Repo `adam0thman/adamone-edu` is public — GitHub Pages on the
Free plan requires public repos.
