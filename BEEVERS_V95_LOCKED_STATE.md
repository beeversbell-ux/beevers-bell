# Beevers + Bell v95 locked state

Locked: 29 September 2026, Melbourne time.

## Authoritative current version
**v95** is the current approved internal baseline.

It carries forward v94 and strengthens Elena Pereyra search relevance without changing the visible opening or visual hierarchy.

## v95 search-signal changes

### Search title and description
The HTML title is now:
**Beevers & Bell Kingsville | Elena Pereyra, Maribyrnong Council**

The meta description now states that the sourced record includes the 21 April 2026 motion moved by Cr Elena Pereyra.

Open Graph and Twitter title/description were aligned to the same factual context.

### Visible lower-page semantic context
The opening remains unchanged.

Lower in the existing sources section, source card 02 now reads:
**21 April decision · Elena Pereyra moved the motion**

Its description records:
- Cr Elena Pereyra as mover
- Cr Bernadette Thomas as seconder
- Beevers Reserve and Bell Reserve concept-plan motion

The existing April decision role for Elena now has a stable fragment id:
**#elena-pereyra**

### Structured data
Replaced the single WebSite JSON-LD node with an @graph containing:
- WebSite
- WebPage
- Elena Pereyra Person entity
- Bernadette Thomas Person entity

The WebPage description explicitly connects:
Elena Pereyra → 21 April 2026 → Beevers and Bell Reserve consultation → Maribyrnong City Council.

The Elena Person node records:
- name: Elena Pereyra
- role: Wattle Ward Councillor
- worksFor: Maribyrnong City Council
- sameAs: official Maribyrnong City Council councillor page

No party affiliation, evaluative label, misconduct allegation or campaign language was added.

## Verification
v95 content commit:
**9e2d53ee60b1159242b17ed69d3dac56dcd1411a**

v95 index blob/content SHA:
**7118ebe51003e6df01b90fb568d8f35f854f4aa6**

Deployment run:
**36568390728**

Result:
**success**

Source checks passed:
- Elena exact name present in HTML title
- Elena exact name present in meta description
- Elena source heading present
- Elena stable fragment present
- JSON-LD parses successfully
- WebSite, WebPage and Person nodes present
- official Council councillor page attached as sameAs

## Existing locked principles
- Do not visually bloat the opening for SEO.
- Public-facing build/version/date remains hidden.
- June remains the hero turning point.
- July remains the dark-slate follow-up chapter.
- Calm, forensic, evidence-first.
- Simple surface, deep evidence.
- Beevers toilet and Coronation Street road closure remain analytically separate.
- Do not overstate what the record proves.
- Ombudsman response remains off the website.
- Do not add unsupported political or misconduct labels for SEO.

Future Beevers Project chats should recover from this file, the current root index.html, and BEEVERS_PROJECT_HANDOFF.md.
