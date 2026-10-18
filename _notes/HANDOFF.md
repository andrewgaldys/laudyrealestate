# Handoff: October 15, 2026 update

For Nick and Andrew. These notes live in the repository but are **not published** on laudyrealestate.com (`_config.yml` excludes `_notes/` and `README.md`).

## Pages

| Page | URL | Status |
|---|---|---|
| Home | `/` | Ready. New line: "Local Authority. Legal Insight. Concierge Service." |
| Explore | `/explore` | Hub for later expansion. `noindex` until it has its own content. |
| Waterfront | `/waterfront` | Restructured; **needs Nick's copy** in six places. |
| Neighborhoods: How to Choose | `/neighborhoods` | Needs Nick's intro. |
| Las Olas Isles, Harbor Beach, Coral Ridge, Rio Vista, Victoria Park | `/las-olas-isles` etc. | New. `noindex`; need character, pros and cons. |
| History | `/history` | New. `noindex`; **hold until archive permission is confirmed.** |
| About | `/about` | New Selected Transactions, Client Reviews and Press sections (`/about#press`). |

Dashed boxes labeled "Draft" mark every spot that needs copy or a decision. Pages that are mostly drafts carry `<meta name="robots" content="noindex, follow">` and are left out of `sitemap.xml`.

**To publish a draft page:** replace the dashed boxes with final copy, change its robots tag to `index, follow, max-image-preview:large, max-snippet:-1`, and add its URL to `sitemap.xml`.

## Copy Nick needs to write or approve

- **Waterfront:** Why Waterfront Matters; Depth at High Tide; Canal Width & Distance; Setbacks; Seawall Inspections; the questions he asks on every showing. Confirm or replace the carried-over "Questions to Ask" list. Keep it informational; the page states it is not legal advice.
- **How to Choose:** his intro.
- **Each neighborhood page:** Character, Pros, Cons. Confirm every "At a Glance" line (list below).
- **History:** introduction. No dates, names or prices unless each has a cited source.
- **About:** details for Solomar, Coral Ridge and Luna; client reviews; issue name, date and link for each Lifestyle Magazine feature.

## Assets still missing

- Photos for **Coral Ridge, Rio Vista and Victoria Park** (their banners are plain for now).
- **Newspaper clippings.** None were in the shared Drive folder. The three files named `NN99.pdf`, `NNN1.pdf` and `NPLI.pdf` turned out to be the Lifestyle Magazine pages.
- **Instagram video:** no URL or file was found.
- **Dropbox:** not connected to this session, so anything stored only there hasn't been reviewed.
- **Client reviews and transaction records.**

## Claims to verify before publishing

- **Neighborhood "At a Glance" lines** (carried over from the earlier site):
  - Las Olas Isles: Walk to Las Olas · Bascule bridges only · Narrow, deep lots
  - Harbor Beach: No bridges to the inlet · Gated and guarded · Estate-size lots
  - Coral Ridge: "Established streets from Sunrise to Oakland Park Boulevard" · Dockage varies by canal · Generous lots · Shops on Federal Highway
  - Rio Vista: "Between the New River and the Intracoastal" · Three waterways · Minutes from downtown · Compact to estate lots
  - Victoria Park: "Walkable streets just northeast of downtown" · Walk to Las Olas · Mostly dry lots · Townhome infill
- **Waterfront figures**, last reviewed September 30, 2026, with sources listed on the page: 17th Street Causeway bridge 55 ft closed; New River rail bridge 4 ft closed; dock reach 25 ft or 25% of waterway (ULDR §47-19.3); Broward seawall 4 ft NAVD88 minimum before 2035 and 5 ft by 2050.
- **History captions** are the archive's own titles, dates and catalog numbers, credited to History Fort Lauderdale. "Cole Hammock" is the archive's spelling (the neighborhood is Colee Hammock). One Rio Vista image (`rio-vista-1928.jpg`) has no catalog number on the contact sheet.
- **Lifestyle Magazine:** confirm the exact publication name, issue and date.
- **Selected transactions:** property type, Nick's role, price and closing date, checked against closing records. Publish only what the clients and brokerage allow.
- **"Esq." on a real estate site:** Nick should confirm it fits Florida Bar advertising rules. The footer already states that legal representation requires a separate engagement.
- **Optional:** the magazine lists the office as 1700 E Las Olas Blvd, Ste 206, Fort Lauderdale, FL 33301. It is not on the site; add it to the footer and structured data only if Nick wants it there.

## Permissions

- **History Fort Lauderdale photos** (`images/history/`): the files come from the archive's contact sheets. Before `/history` goes live, confirm reproduction permission, any fee and the exact credit line. If permission isn't granted, delete `images/history/` and the History page (and its links in the header, footer and Explore page).
- **Lifestyle Magazine pages** (`images/press-lifestyle-1..3.jpg`): confirm the publisher is fine with reposting the page images. Otherwise link to its online edition instead.
- **Portraits:** the About and Home portraits are from the `rDF9_` shoot Nick shared. Confirm the photographer's license covers website use. The vertical magazine photo of Nick in the chair was **not** used because its rights are unclear.
- **Drone and listing photos:** assumed to be Nick's own or licensed for his marketing.

## Giving Nick access to the GitHub repository

1. Nick creates a free GitHub account and sends Andrew his username. Never share passwords.
2. Andrew opens `github.com/andrewgaldys/laudyrealestate` → **Settings → Collaborators → Add people** → enters Nick's username.
3. Nick accepts the emailed invitation. On a personal-account repository, collaborators can edit and publish files but cannot change repository settings (Pages, custom domain, HTTPS).
4. Nick can then edit any page on github.com (pencil icon → **Commit changes**). The live site updates in 1–2 minutes.
5. **Optional safeguards:**
   - Turn on branch protection for `main` (require a pull request) so every change is reviewed before it goes live.
   - Move the repository into a free GitHub organization if Nick should co-own it or manage settings.
6. The domain's DNS is at GoDaddy. Whoever holds that account controls the domain. Recommended: point the `www` CNAME to `andrewgaldys.github.io` so `https://www.laudyrealestate.com` is covered too.

## Discovery

Each page has a descriptive title, a single H1, internal links and crawlable text, and `robots.txt` allows search and AI crawlers. None of this guarantees placement in Google, ChatGPT or any other search or answer engine. Original, reviewed content and real reputation signals matter more than page count.
