# Beevers + Bell v109 locked state

Locked: 5 October 2026, Melbourne time.

## Authoritative current version
**v109** is the current approved internal baseline.

v109 completes the focused retrieval structure introduced in v108.

## Final structural pattern
The dedicated event page remains:
https://beeversbell.com/decision/21-april-2026/

It is deliberately not an Elena Pereyra profile page.

Title:
**21 April 2026 Council decision | Beevers + Bell Record**

H1:
**21 April 2026 Council decision**

Elena Pereyra does not appear in the URL, title or H1.

## v109 refinement
The opening summary of the decision page now naturally records the mover and seconder:

"Maribyrnong City Council endorsed the final concept plans for Beevers Reserve and Bell Reserve. The motion was moved by Cr Elena Pereyra, Wattle Ward, and seconded by Cr Bernadette Thomas, Sheoak Ward. Seven councillors were present and all seven voted for the motion."

This mirrors the structure of other generic/event pages Google retrieves for Elena Pereyra, where her name appears within a clearly bounded factual record rather than in a person-targeted page.

## Discovery paths
The decision record is discoverable from:
- the existing April section on the Beevers + Bell homepage
- sitemap.xml
- the public GitHub repository README

README now links directly to:
https://beeversbell.com/decision/21-april-2026/

## Existing v108 safeguards retained
- no Elena page
- no Elena in homepage title or hero
- no Elena in decision-page URL
- no Elena in decision-page H1
- no keyword stuffing
- June councillor responses are balanced across Thomas, Pereyra, Tiwari and Yengi
- Elena exact-moment video remains 44:39 / t=2679s
- no em dashes

## Validation
Verified:
- JSON-LD parses successfully
- homepage links to the decision record
- README links to the decision record
- sitemap includes the decision record
- decision title and H1 remain event-focused
- the lead naturally names mover and seconder
- no em dashes

## External bridge still required
The remaining external signal under the user's control is the opening paragraph of the existing Change.org petition/update. It should naturally connect:
Elena Pereyra -> 21 April decision -> focused Beevers + Bell decision record.

No other Change.org restructuring is required.

## Rollback
To revert v109 while retaining v108:
- restore decision/21-april-2026/index.html from commit ca7f815173cf3d57ce3f35d9245114b955437ce7
- restore README.md from before commit b7d4575432c2d05282a1ff7ef784881e01f380a4

To remove the focused decision architecture entirely, follow BEEVERS_V108_LOCKED_STATE.md rollback instructions and return to v107.

## Current source
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Root index content SHA: **ff6662e7bad7bcdd22d884faa8c1ed67ac53a55c**
Decision page content SHA: **a5b75d782ca944279ec34b6c97390bff682a6cbd**

Future Beevers Project chats should recover from this file, current index.html, the decision record and BEEVERS_PROJECT_HANDOFF.md.
