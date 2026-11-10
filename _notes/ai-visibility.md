# Getting Nick into AI answers

Goal: when someone asks ChatGPT, Gemini, Claude or Perplexity for "the best realtor in Fort Lauderdale" or "the best waterfront realtor in Fort Lauderdale", Nick and laudyrealestate.com appear.

**Nothing can guarantee this.** These assistants answer "best" questions by searching the web and repeating what independent sources say: reviews, directories, press and lists. The site helps them describe Nick accurately, but other sources decide whether he is named.

## Where things stand (October 23, 2026)

- A web search for "laudyrealestate.com Nicholas Napoli" returned nothing, so search engines haven't picked the site up yet. That comes first.
- Nick has 3 Zillow reviews, all from 2022. Agents who get named usually have dozens of recent reviews on Google and Zillow.
- The Waterfront page is the one most likely to be quoted for "waterfront realtor", and it still has six Draft boxes waiting for Nick's copy. (Done November 2: Nick's final copy is in.)
- The site already allows AI crawlers (`robots.txt`).

## Done on the site (October 23, not yet live)

- The home page title now reads "Fort Lauderdale Realtor for Waterfront Homes | Nicholas Napoli, Esq."
- The structured data (the hidden profile search engines read) now links Nick's Zillow and Traded profiles. It lists Fort Lauderdale and Broward County as his service area, plus the five neighborhoods and waterfront homes as his subjects.
- An IndexNow key file (`fe3a30e62eba959f7034e70806b8274c.txt`) lets the site tell Bing and other engines about new or changed pages. ChatGPT's search draws on Bing.

## Andrew: one-time setup (about an hour)

1. **Google Search Console** (Gemini and Google's AI answers): add the domain `laudyrealestate.com`, verify it with the TXT record Google gives you at GoDaddy (DNS), then submit `https://laudyrealestate.com/sitemap.xml`.
2. **Bing Webmaster Tools** (ChatGPT and Copilot): sign in and choose "Import from Google Search Console". The sitemap comes with it.
3. **GoDaddy:** point `www` to `andrewgaldys.github.io` so both addresses work.

## Nick: these matter most

1. **Google Business Profile**, set up as a service-area real estate agent (no public address needed). Use the same name, phone and website as the site: "Nicholas Napoli, Esq.", (954) 815-8278, laudyrealestate.com. This is Google's main source for local "best realtor" answers.
2. **Reviews:** ask recent clients (the Coral Ridge buyer, the Solemar seller) for a Google review and a Zillow review. Ask them to say in their own words what he did, for example "waterfront" or "Las Olas Isles". Never write reviews for them or pay for reviews.
3. **Matching profiles:** add the website link to his Zillow profile, Instagram bio, LinkedIn, Realtor.com and Homes.com profiles, and his agent page on Fidelity's site. Use the same name and phone everywhere.
4. **Deals and press:** submit closed deals to Traded (it already shows Coral Ridge). Ask Lifestyle Magazine for its online article link. Pitch the waterfront guide to South Florida outlets (Sun Sentinel real estate, South Florida Business Journal, neighborhood associations).
5. **Answer the questions below.** His own specific answers become the Waterfront and neighborhood pages. AI assistants quote first-hand specifics far more than general marketing copy.

**Don't call him "the best" on the site.** Because the site uses "Esq.", Florida Bar advertising rules apply, and they restrict claims that can't be verified (such as "best", "top" or "expert"). Being named "best" by reviewers and journalists is what counts anyway.

## Questions for Nick (a voice memo is fine)

Waterfront page:
1. When you show a waterfront home, what do you check first, and why?
2. How do you find out the water depth at a dock, and what depth do buyers with a 40 ft or larger boat need?
3. Which bridges or canal widths have changed a client's decision? Give one real example without names.
4. What do you look for in a seawall, and when do you tell a buyer to get an engineer?
5. What setback or permit rule surprises buyers most?
6. What do you ask the seller on every waterfront deal?

Neighborhood pages (Las Olas Isles, Harbor Beach, Coral Ridge, Rio Vista, Victoria Park):
7. In two or three sentences each: who is the neighborhood right for, one thing you love about it, and one honest drawback?

About and FAQ:
8. How does your law background change what you do for a buyer or seller? Stay within what the Bar allows.
9. What kinds of deals do you want more of (waterfront, condos, new construction, commercial)?
10. Which areas outside Fort Lauderdale do you regularly work in?

## Check progress monthly

Ask ChatGPT, Gemini, Claude and Perplexity the same five questions on the first of each month, and record whether Nick is named and which sources each one cites.
1. Best realtor in Fort Lauderdale
2. Best waterfront realtor in Fort Lauderdale
3. Realtor who is also a lawyer in Fort Lauderdale
4. Las Olas Isles realtor
5. Who is Nicholas Napoli, Fort Lauderdale realtor?

The cited sources show where to get listed next. Expect months, not weeks.

November 9: the five neighborhood guides and How to Choose are now indexed and in the sitemap, each with cited sources.

## November 10: search setup behind the pages (not yet live)

- Every indexable page now carries the same full profile in its structured data. It covers:
  - Nick as Realtor, developer and attorney, with The Florida Bar and the National Association of REALTORS® as memberships.
  - His service area: Fort Lauderdale, Pompano Beach, Broward County and South Florida, plus the five neighborhoods.
  - His services and subjects, with waterfront first, and the Lifestyle profiles.
- The guides are marked as articles by Nick, with each neighborhood's location and the cited sources.
- "South Florida" was added to:
  - The home page title and description.
  - The Waterfront description.
  - The footer tagline, which now reads "Waterfront and residential real estate, Fort Lauderdale and South Florida".
- The home page description no longer says "superior market knowledge". Florida Bar rules restrict comparative claims.
- New `llms.txt`: a plain summary of Nick and the guides for AI assistants. It's a new convention and not every assistant reads it, but it costs nothing.
- Not added on purpose: review stars in structured data. Google doesn't allow marking up reviews copied from Zillow, and it can penalize it.

Still open:
- A web search on November 10 found neither laudyrealestate.com nor a Realtor profile for Nick. Search Console and Bing setup comes first.
- An Avvo listing for "Nicholas Vivinetto Napoli" (Fort Lauderdale, admitted 2026) is probably Nick. Once he confirms, add his Avvo and Florida Bar profile links to `sameAs` on every page. They are strong proof of the "attorney" claim.
- The home page has fewer than 100 words of visible text, so the guides and About do most of the work for AI answers.

