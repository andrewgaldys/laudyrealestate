# Nicholas Napoli, Esq. | laudyrealestate.com

A static site (HTML and CSS, no JavaScript, no build step) hosted on GitHub Pages from the `laudyrealestate` repository, served over HTTPS. This README and `_notes/` are excluded from the published site by `_config.yml`.

```
index.html            /                 Home (four full-screen cards, video first)
explore.html          /explore          Hub for guides, history and press (to flesh out)
waterfront.html       /waterfront       Waterfront buyer's guide
neighborhoods.html    /neighborhoods    How to choose your neighborhood
las-olas-isles.html   /las-olas-isles   Neighborhood guides (5 pages)
harbor-beach.html     /harbor-beach
coral-ridge.html      /coral-ridge
rio-vista.html        /rio-vista
victoria-park.html    /victoria-park
history.html          /history          Archive photographs
about.html            /about            Bio, transactions, reviews, press (/about#press)
style.css             All styles
video/                Home loop (1080p and 720p) and the Las Olas Isles banner
images/               Photos; images/history/ holds the archive photographs
robots.txt            Allows search engines and AI crawlers
sitemap.xml           Published, indexable pages only
CNAME                 Custom domain for GitHub Pages. Keep this file.
_config.yml           Keeps README.md and _notes/ off the live site
_notes/               Handoff notes and the market-report proposal (not published)
```

GitHub Pages serves `about.html` at `/about`, so links never include `.html`.

## Navigation

Every page shares one header: Explore, Waterfront, Neighborhoods (dropdown), the name, History, About and Contact.
- At 1440 px and wider, three links sit on each side of the name.
- Narrower screens show the name with one row of links beneath it.
- Phones show two rows of three.

The Neighborhoods dropdown opens on hover or keyboard focus. On a phone, the first tap opens it.

When adding a page, copy the header from an existing page and add the link to the header and footer.

## Draft content

Dashed boxes labeled "Draft" mark copy Nick still needs to write or approve. Pages that are mostly drafts are `noindex` and left out of `sitemap.xml`. See `_notes/HANDOFF.md` for the full list and the steps to publish a page.

## Publish changes

GitHub → `laudyrealestate` → **Add file → Upload files** → drag in the changed files → **Commit changes**. The live site updates in 1–2 minutes.

## Photos and video

Replace any photo by saving a new one **with the same file name** into `images/`. Use JPEG, ideally under 1 MB and about 2400 px wide for full-screen images. If a new photo shows something different, update its `alt` text.

| File | Used on |
|---|---|
| `video/home-canal.mp4`, `video/home-canal-720.mp4`, `images/home-canal-poster.jpg` | Home card 1: the canal flight crossfading into a slow push across the Intracoastal |
| `home-market.jpg`, `home-waterfront.jpg`, `home-nick.jpg`, `home-nick-tall.jpg` | Home cards 2–4; Explore banner |
| `video/las-olas-isles.mp4`, `images/las-olas-isles-poster.jpg` | Las Olas Isles banner (Hendricks Isle, Jul 1 drone footage) |
| `las-olas-isles-aerial.jpg`, `harbor-beach-aerial.jpg` | Neighborhood tiles; Harbor Beach banner |
| `nick-napoli-hero.jpg`, `nick-napoli-hero-tall.jpg`, `about-portrait-tall.jpg` | About hero and the vertical portrait beside the legal paragraph |
| `about-city.jpg`, `about-site.jpg`, `about-development.jpg` | About; `about-development.jpg` also on Waterfront (Setbacks) |
| `press-lifestyle-1..3.jpg` | About, Press (Lifestyle Magazine pages) |
| `history/*.jpg` | History (History Fort Lauderdale archive; permission pending) |
| `waterfront-*.jpg`, `neighborhoods-hero-drone.jpg`, `contact-dusk.jpg`, `og-image.jpg` | Waterfront, Neighborhoods, contact sections, link previews |

## Content rules

- The About page bio is Nicholas's own text.
- No historical claims, prices, statistics, reviews or sales figures go live without a checked source and Nick's approval.
- "Inquire Now" opens a pre-filled email to nicknapolire@gmail.com.

## Domain

HTTPS is enforced and the certificate renews automatically. Optional, at GoDaddy (DNS): point `www` (CNAME) to `andrewgaldys.github.io` so `https://www.laudyrealestate.com` is covered too.
