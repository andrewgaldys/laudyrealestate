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
- **History:** introduction is in ("I’m a good realtor."). Any added text needs a cited source for dates, names or prices.
- **About:** details for the Luna sale; issue name, date and link for each Lifestyle Magazine feature.

## Assets still missing

- Photos for **Coral Ridge, Rio Vista and Victoria Park** (their banners are plain for now).
- **Newspaper clippings:** done (October 23). Four public-domain clippings from the Library of Congress's Chronicling America archive (1906–1907 coverage of Everglades drainage at Fort Lauderdale) are on `/history`. The three Drive files named `NN99.pdf`, `NNN1.pdf` and `NPLI.pdf` were the Lifestyle Magazine pages, not clippings.
- **Instagram video:** no URL or file was found.
- **Dropbox:** not connected to this session, so anything stored only there hasn't been reviewed.
- **Luna transaction record.** Zillow lists a $1.9M sale whose details would not load. Luna Ocean Residences #1001 (704 N Ocean Blvd, Pompano Beach, MLS A11910906) was listed near that price, but no sale record or listing agent was found, so the card shows a photo from that listing and a Draft box. Nick should confirm the unit, price, his role and the closing date, or name the right property.

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
- **Featured Transactions** (from Nick's Zillow profile, October 23, 2026): Coral Ridge, Fort Lauderdale (2898 NE 26th St), $7,250,000, 5 bed, 5.5 bath, 4,690 sq ft, represented the buyer, sold April 2026 (BEX Realty shows April 10, 2026); Solemar, Pompano Beach (1116 N Ocean Blvd #1801), $3,375,000, 3 bed, 3.5 bath, 2,428 sq ft, represented the seller, sold August 3, 2026. Zillow counts half baths as full (6 and 4); the cards use the listing counts. The site shows the neighborhood or building, not the street address. Luna is still a draft. Nick should confirm each line and that the brokerage and clients are fine with it.
- **Client reviews** are copied word for word from Zillow (NoahSimon4, June 2022; brittanyj 399, February 2022; Anna Koontz, February 2022), with a link to the profile. Zillow's terms limit reusing its content, so Nick may prefer Zillow's own review badge or the reviewers' permission. One review says he is "relatively new to the real estate game"; it is kept verbatim.
- **"Esq." on a real estate site:** Nick should confirm it fits Florida Bar advertising rules. The footer already states that legal representation requires a separate engagement.
- **Optional:** the magazine lists the office as 1700 E Las Olas Blvd, Ste 206, Fort Lauderdale, FL 33301. It is not on the site; add it to the footer and structured data only if Nick wants it there.

## Newspaper clippings

Scans from the Library of Congress, Chronicling America (public domain, published before 1931), each linked to its page:
- The Sun (Jacksonville), July 7, 1906: "Everglades Drainage Not a Dream" with Governor Broward's July 4 telegram from Fort Lauderdale. The page header reads "June 30"; the date shown is the Library's issue date.
- The Sun (Jacksonville), March 10, 1906, p. 2: "Dredge Building at Fort Lauderdale"
- The Pensacola Journal, March 17, 1907, p. 4: "With Governor Broward on the Everglades Drainage Work"
- The Sun (Jacksonville), February 3, 1906, p. 4: news brief on material arriving at Fort Lauderdale

The archive has no newspaper published in Fort Lauderdale itself, and no Rio Vista, Victoria Park or Las Olas coverage before 1931.

## Header

At 1600 px and wider, each side of the name has three equal-width slots, so the links mirror exactly. Below 1600 px the name sits on top with one centered row of links; phones get two centered rows.

## Permissions

- **History Fort Lauderdale photos** (`images/history/`): the files come from the archive's contact sheets. Before `/history` goes live, confirm reproduction permission, any fee and the exact credit line. If permission isn't granted, delete `images/history/` and the History page (and its links in the header, footer and Explore page).
- **Lifestyle Magazine pages** (`images/press-lifestyle-1..3.jpg`): confirm the publisher is fine with reposting the page images. Otherwise link to its online edition instead.
- **Portraits:** the About and Home portraits are from the `rDF9_` shoot Nick shared. Confirm the photographer's license covers website use. The vertical magazine photo of Nick in the chair was **not** used because its rights are unclear.
- **Drone and listing photos:** assumed to be Nick's own or licensed for his marketing.
- **Featured Transactions photos** (`images/featured-*.jpg`), each credited under the photo:
  - `featured-coral-ridge.jpg`: the seller's listing photo, courtesy of Compass Florida, LLC. Nick represented the buyer, so this photo isn't his. Ask Compass or the photographer for permission, or replace it with Nick's own photo.
  - `featured-solemar.jpg`: Nick's own listing (Fidelity Real Estate LLC, MLS A11983771). It keeps the MLS watermark.
  - `featured-luna.jpg`: from MLS A11910906 (watermark kept). Confirm whose listing it was before publishing.
  - MLS rules may limit showing listing photos after a sale; Nick should check with his MLS.

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
