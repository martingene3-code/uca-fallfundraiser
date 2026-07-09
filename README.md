# Upward Christian Academy — Fundraiser Website

A 5-page static site: Home, About, Events, Donate, Contact.

## Before you publish, replace these placeholders
Search each page for text in `[brackets]` and fill in:
- Fundraiser goal amount and closing date (index.html, donate.html)
- School mailing address, office phone/email, office hours (donate.html, contact.html, footer)
- About page mission/community copy and values
- Real event names, dates, and descriptions (events.html, index.html)

## Publish with GitHub Pages (free hosting)
1. Create a new repository on GitHub (e.g. `uca-fundraiser`) — do NOT initialize it with a README.
2. In this folder, run:
   ```
   git init
   git add .
   git commit -m "Initial fundraiser site"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO.git
   git push -u origin main
   ```
3. On GitHub, go to your repo's **Settings → Pages**.
4. Under "Build and deployment," set **Source** to "Deploy from a branch," branch **main**, folder **/(root)**. Save.
5. GitHub will give you a live URL, usually `https://YOUR-USERNAME.github.io/YOUR-REPO/`, within a minute or two.

## Custom domain (optional)
If the school has its own domain, add it under Settings → Pages → Custom domain, and point your domain's DNS to GitHub Pages per [GitHub's instructions](https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site).
