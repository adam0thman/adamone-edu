# AdamOne Edu — coming soon / wkrótce

Bilingual (PL-first, EN subtitles) one-pager announcing the upcoming official
site at **adamone.edu.pl**. Static — one `index.html`, no build step.

**Live:** https://adam0thman.github.io/adamone-edu/
(repo `adam0thman/adamone-edu` is public — GitHub Pages on the Free plan
requires public repos)

## Local preview

```sh
python3 -m http.server 8000
# → http://localhost:8000
```

## Connecting the domain later (adamone.edu.pl)

1. Repo → Settings → Pages → Custom domain → enter `adamone.edu.pl`, save
   (this writes a `CNAME` file).
2. At the DNS provider add:
   - `A` records for `@` → GitHub's IPs (`185.199.108.153`–`.156`)
   - `CNAME` for `www` → `adam0thman.github.io`
3. Wait for the certificate, then tick **Enforce HTTPS**.
