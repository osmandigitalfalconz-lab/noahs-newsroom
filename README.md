# WLTLH Newsroom — Dateline-style template with Noah's content

A single-file site (`index.html`, no build step) that recreates the layout of
the Framer "Dateline — Newspaper Magazine" template, filled entirely with real
content from Noah Christopher's WLTLH newsroom (localnews.wltlh.com).

## What was matched from the template

- Cream page (#F5F0E6), near-black ink, scarlet accent (#E01E2E), beige bands,
  dark dispatch section, black footer with a giant wordmark.
- Didone-style serif headlines (Playfair Display, Georgia fallback) with
  uppercase letter-spaced sans labels, kickers and bylines.
- Live date/time strip, centred wordmark masthead, hairline-ruled section nav.
- Hero: numbered top-5 stories on the left, large visual on the right that
  cycles on its own (the template's photo advances independently of the
  headline — reproduced here); clicking a numbered story switches the lead.
- The wire strip, six desks with tabs, the long read with four numbered
  chapters and a red rule, Latest list with a sidebar, a dark section, a
  "why" band with stats and bureaus, a newsletter signup, and the footer.

## How Noah's content maps onto the template

| Template | WLTLH version |
|---|---|
| Dateline masthead | WLTLH — "Los Angeles · In Print & In Fiction" |
| World / Politics / Business / Tech / Culture / Sport | Investigation / Crime & Courts / City Life / The Valley / Arts & City / Los Angeles |
| Hero lead: fog story | The Julian Armitage concert (26 Oct) |
| The wire (times) | The wire (dates — no times exist in the source) |
| Long read: street-light ballot, 4 chapters | Campaign-finance investigation, 4 chapters, real section headings and opening lines |
| Latest + Most read sidebar | Latest (6 stories) + "The Confessor file" sidebar |
| Opinion: 6 columnists | From the books: The Confessor, The Rival, "Have a story? Tell Noah" |
| Podcast (dark band) | The WLTLH Dispatch (dark band) — WLTLH has a newsletter, not a podcast |
| Why Dateline: 412K readers, 38 reporters, 2014 | Why WLTLH: 06 desks, 05 neighbourhoods, 2026 first edition (all real counts) |
| Where we report from: London, Lagos, Mumbai, São Paulo, Berlin | The Valley, Sun Valley, North Hollywood, Hancock Park, Downtown |
| Morning edition 06:30 | The WLTLH Dispatch — "when the paper trail moves" |
| Footer address / email / phone | Omitted — no contact details exist for WLTLH; footer links to wltlh.com, localnews.wltlh.com, books.wltlh.com |

## Photos

`assets/` holds 9 real photographs (CC BY / CC BY-SA, found via Openverse) —
Walt Disney Concert Hall, Wilshire Boulevard, the downtown skyline over Echo
Park Lake, a container yard, a stage cast, champagne flutes, a grand hotel
lobby, a gavel and a stack of newspapers. Full credits and source links are in
`assets/CREDITS.md` and in the page footer. They are generic Los Angeles
scenes used as illustrations, not photographs of the fictional events reported.

## Rules followed

- Every headline, dek, date, byline and chapter line is real copy from
  localnews.wltlh.com (see `content.md` for the source list). Nothing was
  invented: no fake reader counts, no invented authors, no podcast.
- All story links point to https://localnews.wltlh.com/ (the newsroom
  homepage — no per-article URLs were published there). Book links go to the
  real book pages on books.wltlh.com.
- The Dispatch signup form does not pretend to subscribe anyone: submitting
  shows a note that signup lives on the newsroom site, with a link.
- Story "photos" are CSS typographic panels (no photos exist on the newsroom).

## Run / deploy

Open `index.html` in a browser. No build step. Google Fonts are loaded from
the web with serif/sans fallbacks if offline.
