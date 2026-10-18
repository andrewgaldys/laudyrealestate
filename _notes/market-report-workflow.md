# Proposal: monthly Broward County single-family market report

**Status: proposal only. Nothing is published or automated.**

## Before the first report

1. **Data access:** confirm Nick's MLS membership gives him Matrix access to Broward County closed and active single-family data.
2. **Reuse rights:** confirm in writing (MLS rules or the MLS's compliance staff) that aggregated statistics may be published on a public website, and the required attribution and disclaimer. Do not publish listing-level details unless they meet IDX rules.
3. **Scope:** Broward County, single-family detached, all price ranges. Optionally add a Fort Lauderdale city cut and a waterfront cut once the base report is routine.

## Each month (around the 10th, so late closings have posted)

1. **Pull:** in Matrix, run a saved search for the previous calendar month and the same month a year earlier. Export to CSV and save it as `broward-sf-YYYY-MM.csv` with the date it was pulled.
2. **Metrics:**
   - closed sales
   - median sale price
   - median days on market
   - new listings
   - active listings at month end
   - months of supply
   - median percent of original list price received
   - number of listings with a price reduction, if the export supports it
3. **Compare:** month over month and year over year. Use the same search criteria every month and note any change.
4. **Commentary:** Nick writes three to five sentences in his own words on what changed and what it means for buyers and sellers.
   - Do not copy, summarize or automatically reword anyone else's blog or report.
   - Do not let a tool generate the commentary.
5. **Build:** Andrew adds a page from a fixed template (for example `/market-report-2026-10`) and links it from Explore.
6. **Review:** Nick checks every figure against the saved export and approves the page before it goes live. **No review, no publish.**
7. **Cite** on the page:
   - "Source: [MLS name], Matrix. Broward County single-family homes, [Month Year]. Data retrieved [date]. Information deemed reliable but not guaranteed."
   - A short methodology note: property type, geography, date range, and how medians and months of supply are calculated.
8. **Archive:** keep the CSV and the approved page so past reports can be audited.

## Page template (proposed)

- Title: "Broward County Single-Family Market Report, [Month Year]"
- A row of four to six headline figures, each with its change from the prior year
- Nick's commentary
- Methodology and source
- "Inquire Now" contact band

## What this will not do

- Publish data before Nick reviews it.
- Republish or paraphrase other agents' or brokerages' reports.
- Guarantee placement in search or AI answers. The value is a consistent, original, cited monthly record.
