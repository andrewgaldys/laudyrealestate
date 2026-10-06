# Nicholas Napoli, Esq. | laudyrealestate.com

A static site (HTML and CSS, no JavaScript, no build step) hosted on GitHub Pages from the `laudyrealestate` repository.

```
index.html          Home (four full-screen cards)
about.html          About Nicholas (his own bio)
neighborhoods.html  Neighborhood comparison
waterfront.html     Boating Access Guide
style.css           All styles
robots.txt          Allows search engines and AI crawlers (including OAI-SearchBot)
sitemap.xml         The four pages
CNAME               Custom domain for GitHub Pages. Keep this file.
favicon.svg
images/             Photos
```

## Publish changes

GitHub → `laudyrealestate` → **Add file → Upload files** → drag in the changed files → **Commit changes**. The live site updates in 1–2 minutes.

## HTTPS (one-time fix)

`https://laudyrealestate.com` currently fails because GitHub never issued a certificate for the domain.

1. GitHub → `laudyrealestate` → **Settings → Pages**.
2. Under **Custom domain**, click **Remove**. Then type `laudyrealestate.com` again and click **Save**.
3. Wait for "DNS check successful" and for the certificate (minutes, sometimes up to 24 hours).
4. Tick **Enforce HTTPS**.

Recommended at GoDaddy (DNS): point `www` (CNAME) to `andrewgaldys.github.io`.

## Photos

Replace any photo by saving a new one **with the same file name** into `images/`. Use JPEG, ideally under 1 MB and about 2400 px wide for full-screen images.

| File | Used on | Source |
|---|---|---|
| `homepage.jpg` | Home card 1 | Drone aerial |
| `home-market.jpg` | Home card 2 | Downtown drone still, Sep 28 |
| `home-waterfront.jpg` | Home card 3 | Intracoastal drone aerial |
| `home-nick.jpg` / `home-nick-tall.jpg` | Home card 4 (desktop / phones) | Portraits rDF9_7826 / rDF9_7828 |
| `nick-napoli-hero.jpg` / `nick-napoli-hero-tall.jpg` | About hero (desktop / phones) | Portraits rDF9_7796 / rDF9_7836 |
| `nick-napoli-portrait.jpg` | About, search-engine profile image | Portrait rDF9_7828 |
| `about-market.jpg` | About, Market Knowledge | Downtown drone still |
| `about-development.jpg` | About, Development | Hendricks Isle spec project drone still |
| `contact-dusk.jpg` | Contact section on inner pages | Downtown at sunset |
| `neighborhoods-hero-drone.jpg` | Neighborhoods hero | Downtown drone still |
| `las-olas-isles-aerial.jpg` | Las Olas Isles profile | 97 Hendricks Isle listing |
| `waterfront-hero-drone.jpg` | Waterfront hero | 1701 12th Court listing |
| `waterfront-bridges.jpg`, `waterfront-frontage.jpg` | Waterfront guide | 525 Isle of Capri, 97 Hendricks Isle listings |
| `harbor-beach-aerial.jpg`, `coral-ridge-aerial.jpg`, `rio-vista-aerial.jpg`, `victoria-park-streetscape.jpg` | Neighborhood profiles | **Still placeholders** |
| `og-image.jpg` | Link preview (1200×630) | Crop of `homepage.jpg` |

If a new photo shows something different, update its `alt` text in the HTML.

## Content

- The About page is Nicholas's own text. Edit it there, not in a summary.
- "Inquire Now" opens a pre-filled email to nicknapolire@gmail.com.
- The Waterfront guide figures are current as of September 30, 2026; recheck them when you update its "Reviewed" date.
