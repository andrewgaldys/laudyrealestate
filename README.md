# Nick Napoli: Fort Lauderdale Waterfront Real Estate

A static site (HTML and CSS, no JavaScript, no build step) for GitHub Pages.

```
index.html          Home
waterfront.html     Boating-access guide
neighborhoods.html  Five-neighborhood comparison
about.html          About Nick, plus the contact form
style.css           All styles
robots.txt          Allows search engines and AI crawlers
sitemap.xml         The four pages
favicon.svg
images/             Placeholder JPGs, one per final photo
```

## Deploy to GitHub Pages

1. Push these files to the root of a repository.
2. Go to **Settings → Pages**, set the source to the `main` branch and the `/ (root)` folder.
3. To use a custom domain, enter it under **Custom domain** (GitHub adds a `CNAME` file), then point DNS at GitHub Pages and turn on **Enforce HTTPS**.
4. Submit `https://www.yourdomain.com/sitemap.xml` in Google Search Console and Bing Webmaster Tools.

## Replace before launch

Find and replace these across every file, including the JSON-LD blocks:

| Placeholder | Replace with |
|---|---|
| `https://www.yourdomain.com` and `yourdomain.com` | The live domain (canonicals, Open Graph, JSON-LD, robots.txt, sitemap.xml, the form `_subject`) |
| `nick@yourdomain.com` | Nick's email (the `mailto:` links and JSON-LD) |
| `(954) 555-0100`, `+19545550100`, `+1-954-555-0100` | Nick's phone, in all three formats |
| `[BROKERAGE NAME]` | The brokerage's licensed name, exactly as registered |
| `[Brokerage office street address]`, `[ZIP]` | The brokerage office address |
| `[sales associate]`, `[sales associate / broker associate]` | Nick's license type |
| `[SL#######]` | Nick's Florida license number |
| `https://formspree.io/f/your-form-id` (about.html) | Your form endpoint. GitHub Pages can't process forms, so connect Formspree, Basin or a similar service. Until then the email links work. |

Optional: add `"sameAs": [...]` to the Person node in the JSON-LD with Nick's brokerage profile and LinkedIn URLs.

Florida Administrative Code rule 61J2-10.025 requires the brokerage's licensed name in advertising. It's in the footer on every page; confirm the placement with the broker.

## Images

Every `images/*.jpg` is a labeled navy placeholder. Overwrite each one with the final photo **using the same file name and aspect ratio**, so the HTML doesn't need to change. Then check each `alt` attribute still describes what the photo shows.

| File | Size | Used on |
|---|---|---|
| `hero-fort-lauderdale-drone.jpg` | 2400×1350 | Home hero |
| `waterfront-hero-drone.jpg` | 2400×1100 | Waterfront hero |
| `neighborhoods-hero-drone.jpg` | 2400×1100 | Neighborhoods hero |
| `about-hero-intracoastal.jpg` | 2400×1100 | About hero background |
| `nick-napoli-portrait.jpg` | 1200×1500 | About portrait, JSON-LD |
| `guide-waterfront-card.jpg`, `guide-neighborhoods-card.jpg` | 1600×1000 | Home guide cards |
| `las-olas-isles-aerial.jpg`, `harbor-beach-aerial.jpg`, `coral-ridge-aerial.jpg`, `rio-vista-aerial.jpg`, `victoria-park-streetscape.jpg` | 1600×1000 | Neighborhood profiles |
| `og-image.jpg` | 1200×630 | Social share preview |

Keep hero files under about 400 KB (JPEG quality 70–80). To use drone video on the home hero, follow the comment above the hero in `index.html`.

## Content review

Search the HTML for `VERIFY` comments. Each one marks copy written in Nick's voice, or a claim about his practice, that he must confirm before launch. The About page lists only checkable facts. Don't add awards, reviews, testimonials or sales figures unless they're documented and allowed under Florida advertising rules.

The guide pages cite public figures as of September 30, 2026. Re-check them at each review and update the "Last reviewed" dates, `dateModified` in the JSON-LD, and `lastmod` in `sitemap.xml`:

- 17th Street Causeway bridge: 55 ft closed clearance (USCG / 33 CFR 117)
- FEC New River rail bridge: about 4 ft closed clearance, closures capped at 60 minutes (Federal Register, Oct. 25, 2021)
- Fort Lauderdale ULDR §47-19.3: docks may project up to 25% of waterway width or 25 ft, whichever is less; piles up to 30% or 25 ft
- Broward County Code Ch. 39, Art. XXV: minimum 4 ft NAVD88 before 2035 if designed for 5 ft by 2050
- The City of Fort Lauderdale's current seawall minimum: the copy deliberately tells readers to confirm it with the City

## robots.txt

All crawlers are allowed. The last group in the file covers AI **training** crawlers (GPTBot, ClaudeBot, Google-Extended, CCBot and others). If Nick wants to appear in AI search answers without his content being used for model training, change that group's `Allow: /` to `Disallow: /`. Deleting the group won't work, because those bots would fall back to the `User-agent: *` rule. The search and answer-engine bots, including OAI-SearchBot, are in their own group.
