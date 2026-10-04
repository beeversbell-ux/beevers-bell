# Beevers + Bell v107 locked state

Locked: 5 October 2026, Melbourne time.

## Authoritative current version
**v107** is the current approved internal baseline.

v107 is a deliberately subtle search-entity experiment built on v106. It does not change the visible homepage copy, title, hero, navigation, evidence wording, links, or councillor emphasis.

## What changed

### Decision-record semantics
The existing 21 April mover and seconder rows were converted from generic div/strong markup to semantic article/heading markup.

- Cr Elena Pereyra remains labelled exactly as before as the Wattle Ward councillor who moved the motion.
- Cr Bernadette Thomas remains labelled exactly as before as the Sheoak Ward councillor who seconded the motion.
- Both are treated consistently.
- CSS explicitly preserves the prior typography and spacing.

### Entity identity markup
The existing Person structured data was refined without changing visible copy.

Elena Pereyra:
- jobTitle: Councillor, Wattle Ward
- memberOf: Maribyrnong City Council, typed as GovernmentOrganization
- sameAs: https://greens.org.au/vic/person/elena-pereyra

Bernadette Thomas:
- jobTitle: Councillor, Sheoak Ward
- memberOf: Maribyrnong City Council, typed as GovernmentOrganization
- sameAs: https://greens.org.au/vic/person/bernadette-thomas

Both remain in the WebPage `mentions` graph. Neither is promoted to `about`.

### Repository context
README.md now neutrally documents what the source repository contains, including the 21 April mover/seconder roles and the live record URL.

### Crawl metadata
- WebPage dateModified: 2026-10-05
- sitemap.xml lastmod: 2026-10-05

## Verified non-changes
A direct v106-to-v107 comparison confirmed:
- normalized visible homepage text is identical
- all 75 href values are identical and in the same order
- homepage title remains: **The Beevers + Bell Record | Kingsville, Maribyrnong**
- H1 remains: **Beevers + Bell**
- no extra visible Elena wording was added
- no standalone Elena page was created
- no homepage keyword stuffing, hero change, or title change was made

## June exact-moment links
Keep:
- Bernadette Thomas: 43:37
- Elena Pereyra: 44:39
- Pradeep Tiwari: 45:36
- Susan Yengi: 46:28

Elena's 44:39 start preserves the handover into her response.

## Rollback
If the v107 experiment is not wanted, restore:
- index.html from v106 / commit ca0928c63fb4276ace164e74235c89b1ed1272d1
- the previous minimal README.md
- sitemap.xml lastmod to 2026-10-01

v106 lock file remains the clean rollback reference.

## Current source
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Root source of truth: **index.html**
Root content SHA: **99d42d0aa2b9cb8dd873b25e1e2376c694cf6167**

Future Beevers Project chats should recover from this file, the current root index.html, and BEEVERS_PROJECT_HANDOFF.md.
