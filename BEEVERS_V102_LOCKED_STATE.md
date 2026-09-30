# Beevers + Bell v102 locked state

Locked: 1 October 2026, Melbourne time.

## Authoritative current version
**v102** is the current approved internal baseline.

It carries forward v101 and refreshes crawl signals after the neutral search-result metadata change.

## v102 change

### Crawl signals refreshed
The live homepage still uses the neutral search framing:
**The Beevers + Bell Record | Kingsville, Maribyrnong**

The live description remains:
**A sourced resident record of the Beevers and Bell Reserve consultation, Council decisions and subsequent public questions in Kingsville, City of Maribyrnong.**

No councillor name has been reintroduced into the homepage title or lead description.

Technical freshness signals were updated:
- WebPage structured-data `dateModified`: **2026-10-01**
- sitemap `lastmod`: **2026-10-01**
- page cache-bust marker refreshed

Robots remain open to crawling and the sitemap remains declared at:
**https://beeversbell.com/sitemap.xml**

## Important expectation
Google may continue showing the previous cached title and snippet until it recrawls and reprocesses the page. The live site itself is already using the neutral metadata.

## Publication
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Current approved internal version: **v102**
Index crawl-signal commit: **c15b521cf19c537d5294944e8db4857eba7f5b0d**
Sitemap commit: **052fbdfc15f5c4f3ce7fe3887c80ed509871b55a**
Latest deployment run: **36762635907**
Deployment result: **success**

Future Beevers Project chats should recover from this file, the current root index.html, sitemap.xml and BEEVERS_PROJECT_HANDOFF.md.
