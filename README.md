# Nicholas Napoli, Esq. | laudyrealestate.com

A static site (HTML and CSS, no JavaScript, no build step) hosted on GitHub Pages from the `laudyrealestate` repository, served over HTTPS.

```
index.html          /               Home (four full-screen cards)
about.html          /about          Nicholas's own bio
neighborhoods.html  /neighborhoods  Five neighborhoods
waterfront.html     /waterfront     Boating Access Guide
style.css           All styles
video/              Home card 1 clip (1080p and a 720p version for phones)
images/             Photos
robots.txt          Allows search engines and AI crawlers (including OAI-SearchBot)
sitemap.xml         The four pages
CNAME               Custom domain for GitHub Pages. Keep this file.
```

GitHub Pages serves `about.html` at `/about`, so links never include `.html`.

## Publish changes

GitHub → `laudyrealestate` → **Add file → Upload files** → drag in the changed files → **Commit changes**. The live site updates in 1–2 minutes.

## Photos and video

Replace any photo by saving a new one **with the same file name** into `images/`. Use JPEG, ideally under 1 MB and about 2400 px wide for full-screen images. If a new photo shows something different, update its `alt` text in the HTML.

| File | Used on |
|---|---|
| `video/home-canal.mp4`, `video/home-canal-720.mp4`, `images/home-canal-poster.jpg` | Home card 1 (10-second clip from the Sep 22 drone video) |
| `home-market.jpg` | Home card 2 |
| `home-waterfront.jpg` | Home card 3 |
| `home-nick.jpg` / `home-nick-tall.jpg` | Home card 4 (desktop / phones) |
| `nick-napoli-hero.jpg` / `nick-napoli-hero-tall.jpg` | About hero (desktop / phones) |
| `about-city.jpg`, `about-site.jpg`, `about-development.jpg` | About page |
| `nick-napoli-portrait.jpg` | Search-engine and link-preview profile image |
| `neighborhoods-hero-drone.jpg` | Neighborhoods hero |
| `las-olas-isles-aerial.jpg` | Las Olas Isles (97 Hendricks Isle) |
| `harbor-beach-aerial.jpg` | Harbor Beach (Lucille Island) |
| `waterfront-hero-drone.jpg`, `waterfront-bridges.jpg`, `waterfront-frontage.jpg`, `waterfront-seawall.jpg` | Boating Access Guide |
| `contact-dusk.jpg` | "Let's Talk" section on inner pages |
| `og-image.jpg` | Link preview (1200×630) |

Coral Ridge, Rio Vista and Victoria Park have no verified photos yet, so they appear as text. Add a photo of each and they can become full-screen sections like Las Olas Isles and Harbor Beach.

## Content

- The About page is Nicholas's own text.
- "Inquire Now" opens a pre-filled email to nicknapolire@gmail.com.
- The Boating Access Guide figures are current as of September 30, 2026; recheck them when you update the "reviewed" date.

## Domain

HTTPS is enforced; the certificate renews automatically. Optional at GoDaddy (DNS): point `www` (CNAME) to `andrewgaldys.github.io` so `https://www.laudyrealestate.com` is covered too.
