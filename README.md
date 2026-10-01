# Nick Napoli: Fort Lauderdale Waterfront Real Estate

A static site (HTML and CSS, no JavaScript, no build step) for GitHub Pages.

```
index.html          Home
waterfront.html     Boating Access Guide
neighborhoods.html  Neighborhood comparison
about.html          About Nick
style.css           All styles
robots.txt          Allows search engines and AI crawlers
sitemap.xml         The four pages
favicon.svg
images/             Photos (labeled placeholders until replaced)
```

## Publish changes

GitHub → your repository → **Add file → Upload files** → drag in the changed files → **Commit changes**. The live site updates in 1–2 minutes.

## Still to replace

| Placeholder | Where |
|---|---|
| `yourdomain.com` | Every page, robots.txt, sitemap.xml |

## Images

Replace any photo by saving a new one **with the same file name** into `images/`. No code changes needed. Use JPEG, ideally under 1 MB.

| File | Shape | Used on |
|---|---|---|
| `homepage.jpg` | Wide | Home hero (real photo) |
| `tile-ocean-access.jpg`, `tile-bridge-clearance.jpg`, `tile-deepwater-dockage.jpg`, `tile-seawall.jpg` | Tall (3:4) | Home tiles |
| `guide-neighborhoods-card.jpg`, `guide-waterfront-card.jpg` | Any | Home image/text blocks |
| `contact-dusk.jpg` | Wide | Contact band, every page |
| `waterfront-hero-drone.jpg` | Wide | Waterfront hero |
| `waterfront-bridges.jpg`, `waterfront-frontage.jpg` | Tall (4:5) | Waterfront image/text blocks |
| `neighborhoods-hero-drone.jpg` | Wide | Neighborhoods hero |
| `las-olas-isles-aerial.jpg`, `harbor-beach-aerial.jpg`, `coral-ridge-aerial.jpg`, `rio-vista-aerial.jpg`, `victoria-park-streetscape.jpg` | Landscape | Neighborhood profiles |
| `nick-napoli-hero.jpg` | Wide, Nick on the right | About hero |
| `about-hero-intracoastal.jpg` | Any | About "Approach" block |
| `nick-napoli-portrait.jpg` | 4:5 | Search-engine profile data only |
| `og-image.jpg` | 1200×630 | Social share preview |

If a new photo shows something different, update its `alt` text in the HTML.

## Content review

Search the HTML for `VERIFY`: those lines describe Nick's practice and need his sign-off. Publish only checkable facts on the About page. The guide figures are current as of September 30, 2026; recheck them when you update the "Reviewed" date.

## robots.txt

All crawlers are allowed. To stay in AI search but opt out of AI model training, change `Allow: /` to `Disallow: /` in the training-crawler group (deleting the group would not block them).
