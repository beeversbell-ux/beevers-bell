# Beevers + Bell v115 locked state

Locked: 5 October 2026, Melbourne time.

## Authoritative current version
**v115** is the current approved internal baseline.

v115 hardens deployment and indexing verification after the nested decision-page 404 was diagnosed and fixed in v114.

## What v115 verifies automatically

### Artifact-level sitemap validation
Every URL listed in sitemap.xml is mapped to a file in the GitHub Pages artifact before deployment.

If a sitemap URL does not have a corresponding file, deployment fails.

### Live production-route validation
After GitHub Pages reports a successful deployment, the workflow fetches and validates:
- https://beeversbell.com/
- https://beeversbell.com/decision/21-april-2026/
- https://beeversbell.com/robots.txt
- https://beeversbell.com/sitemap.xml

It also verifies expected content in the homepage, decision page, robots.txt and sitemap.

Successful deployment run:
**37280878370**

The run log confirms:
- All sitemap URLs resolve to files in the Pages artifact.
- decision/21-april-2026/index.html is present in the artifact.
- GitHub Pages deployment reported success.
- Live production routes verified.

## Search Console status after manual indexing requests

Direct URL Inspection now reports:

Homepage:
- verdict: PASS
- coverage: Submitted and indexed
- robots: ALLOWED
- indexing: INDEXING_ALLOWED
- fetch: SUCCESSFUL
- crawled as: MOBILE
- latest crawl: 2026-10-05T07:50:37Z

Decision page:
- verdict: PASS
- coverage: Submitted and indexed
- robots: ALLOWED
- indexing: INDEXING_ALLOWED
- fetch: SUCCESSFUL
- crawled as: MOBILE
- latest crawl: 2026-10-05T07:48:26Z

## Indexing tracker
A dedicated GSC Wizard indexing tracker now watches:
- https://beeversbell.com/
- https://beeversbell.com/decision/21-april-2026/

Current tracker status at lock:
- total: 2
- indexed: 2
- not indexed: 0
- pending: 0
- errors: 0
- warnings: 0

## Sitemap
The sitemap was resubmitted after the deployment fix so Google can download it in the corrected live state.

## Technical audit
Verified:
- robots.txt allows all crawling
- both pages have index/follow robots directives
- no noindex
- no nofollow
- no meta refresh
- no JavaScript redirect
- no base-tag conflict
- one canonical per page
- homepage canonical is https://beeversbell.com/
- decision-page canonical is https://beeversbell.com/decision/21-april-2026/
- one H1 per page
- no broken same-page anchors on the homepage
- homepage has one internal link to the decision page
- decision page links back to the homepage/decision section
- JSON-LD parses successfully on both pages
- Elena Pereyra and Bernadette Thomas Person entities remain present in structured data
- sitemap contains both URLs once
- no em dashes introduced by this work

## Public-content state
v115 does not change public copy. Public content remains the approved v113 treatment plus v114 deployment fix.

## Search goal
The target remains actual inclusion of beeversbell.com in Google organic results for the bare query:
**Elena Pereyra**

The pages are now genuinely crawled and indexed, so future visibility checks are testing retrieval/ranking rather than deployment or indexing failure.

## Current source
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Root index content SHA: **4a30fb20861b16375c244e9441bec5bc2bb2efb9**
Workflow hardening commit: **b4d6979517bcd83c3086de5aed7f61022a5639c1**

Future Beevers Project chats should recover from this file, current index.html, current decision record, current workflow and BEEVERS_PROJECT_HANDOFF.md.
