# Globant — AI-Powered Solutions in Financial Services (MENA)

Conversion-focused landing page for Globant's MENA financial-services campaign.
Static site, no build step — `index.html` plus a local `images/` folder.

## Live site

Published via GitHub Pages: **https://shemoelnexa.github.io/globant/**

## Local preview

```bash
python3 -m http.server 8139
# then open http://127.0.0.1:8139/
```

## Notes

- All asset paths are relative, so the site works from the repo subpath.
- The lead form is front-end only (shows a confirmation popup on submit); wire it to
  your backend / Pardot before going live.
- Client logos and case-study metrics are placeholders pending final licensed
  assets and confirmed figures.
