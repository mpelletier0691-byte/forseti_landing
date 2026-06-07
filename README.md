# Forseti landing (GitHub Pages)

Public site: **https://mpelletier0691-byte.github.io/forseti_landing/**

Static site for **Forseti** by Asvaettir Labs (Michael David Pelletier).  
Contact: **asvaettirlabs.dev@gmail.com**

## Pages

| File | URL |
|------|-----|
| `index.html` | Home + Official links hub |
| `privacy-policy.html` | Privacy Policy (Play Console) |
| `terms-of-use.html` | Terms of Use |
| `styles.css` | Shared Forseti theme |

## Update from main Forseti repo

```bash
FORSETI_LANDING_REPO=~/Desktop/Projects/forseti_landing \
  ~/Desktop/Projects/Forseti/scripts/sync_landing_site.sh

cd ~/Desktop/Projects/forseti_landing
git add -A
git commit -m "Sync Forseti landing: Play, privacy, terms, legal disclaimers."
git push origin main
```

## Play Store button

Primary CTA uses the public listing:

`https://play.google.com/store/apps/details?id=com.forseti`

## GitHub Pages

Repo **Settings → Pages** → branch **main**, folder **/ (root)**.
