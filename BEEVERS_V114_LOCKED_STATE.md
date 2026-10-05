# Beevers + Bell v114 locked state

Locked: 5 October 2026, Melbourne time.

## Authoritative current version
**v114** is the current approved internal baseline.

v114 fixes a GitHub Pages deployment bug that caused the focused 21 April decision page to return a live 404 even though the file existed in the repository.

## Root cause
The Pages workflow extracted the production site and overlaid only:
- index.html
- robots.txt
- sitemap.xml

It did not copy:
decision/21-april-2026/index.html

As a result, Search Console live testing correctly reported:
**Page cannot be indexed: Not found (404)**

## Fix
The Pages workflow now:
- creates _site/decision/21-april-2026/
- copies decision/21-april-2026/index.html into the Pages artifact
- validates that the deployed decision file exists
- validates that the decision-page title is present
- validates that sitemap.xml contains the decision-page URL

Deployment run 37278998075 completed successfully.

## Public-content state
No public copy, Elena wording, title, H1, chronology, media treatment, or video timestamp was changed by v114.

The current homepage remains the v113 public-content state.

## Search indexing next step
After deployment, run Search Console **Test Live URL** again for:
https://beeversbell.com/decision/21-april-2026/

Only after the live test stops returning 404 should Request Indexing be used.

## Current source
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Root index content SHA: **4a30fb20861b16375c244e9441bec5bc2bb2efb9**
Workflow fix commit: **1d86a3344064b09df9ea5be886807052277c9fc7**

Future Beevers Project chats should recover from this file, current index.html, current decision record, and BEEVERS_PROJECT_HANDOFF.md.
