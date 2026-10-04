# Beevers + Bell v108 locked state

Locked: 5 October 2026, Melbourne time.

## Authoritative current version
**v108** is the current approved internal baseline.

v108 builds on v107 after a comparative search-retrieval review of pages that appear for the query "Elena Pereyra". The key structural change is a focused event record, not a person profile.

## Why this change was made
Search comparisons showed that Google can retrieve generic pages where Elena Pereyra is only one person in a clearly bounded record, including Council annual-report content, MAV delegate listings and a Westsider council-meeting article.

The Beevers + Bell homepage is a very large single document covering consultation, decisions, public questions, traffic evidence, the toilet record and later developments. v108 gives the 21 April decision its own indexable document without making Elena the subject of the website.

## New indexable record
URL:
https://beeversbell.com/decision/21-april-2026/

Title:
**21 April 2026 Council decision | Beevers + Bell Record**

H1:
**21 April 2026 Council decision**

The URL, title and H1 remain event-focused. Elena Pereyra is not placed in the URL or H1.

The page records:
- the 21 April 2026 Council decision
- Cr Elena Pereyra as mover
- Cr Bernadette Thomas as seconder
- the seven councillors who voted for the motion
- what the decision did
- what it did not do regarding the separate Coronation Street statutory process
- the four June councillor responses in sequence
- exact-moment video links
- primary Council sources

June exact-moment links remain:
- Bernadette Thomas: 43:37 / t=2617s
- Elena Pereyra: 44:39 / t=2679s
- Pradeep Tiwari: 45:36 / t=2736s
- Susan Yengi: 46:28 / t=2788s

Elena's 44:39 start preserves the handover and opening exchange before the smoother substantive response.

## Homepage change
One neutral internal link was added in the existing 21 April source row:

**21 April decision record →**

No Elena wording was added to the homepage title, hero, H1 or navigation.

## Sitemap
The new decision URL is included in sitemap.xml with lastmod 2026-10-05.

## Structured data
The new page uses valid JSON-LD and identifies:
- Maribyrnong City Council
- Beevers Reserve
- Bell Reserve
- Coronation Street
- Elena Pereyra
- Bernadette Thomas

The WebPage subject remains the 21 April decision. Elena and Bernadette are represented as mentioned people, not as the page's primary subject.

## Validation
Verified:
- JSON-LD parses successfully
- no em dashes
- H1 is event-focused
- homepage internal link exists
- sitemap contains the new URL
- all four June timestamps are correct
- Elena is not in the decision-page URL or H1

## Rollback
To revert the v108 structural test:
1. Delete decision/21-april-2026/index.html.
2. Restore index.html from v107 before commit 4007a0c6a7887d4ee4f506140de7453e3981c916.
3. Remove the decision URL from sitemap.xml.
4. Restore BEEVERS_V107_LOCKED_STATE.md as the latest baseline.

v107 remains the immediate rollback point.

## Current source
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Root index content SHA: **ff6662e7bad7bcdd22d884faa8c1ed67ac53a55c**
Decision page content SHA: **1012c2aa20d9607de5f38c4d9157c44dac31f0f6**

Future Beevers Project chats should recover from this file, current index.html, the decision record, and BEEVERS_PROJECT_HANDOFF.md.
