# Circa Accountants — Website

Static marketing site for Circa Accountants Ltd (Reg. 04506788).
Two pages, no build step, deployed to Vercel.

## Structure

```
.
├── index.html        # Home page
├── careers.html      # Careers page (linked from nav + footer)
├── vercel.json       # cleanUrls + security headers
└── .gitignore
```

## Local preview

Just open the files in a browser:

```bash
open index.html
```

Or run a tiny local server (any of these work):

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying

This repo is connected to Vercel — every push to `main` redeploys
automatically. Pull requests get their own preview URL.

## Contact

`info@circaaccountants.co.uk`
