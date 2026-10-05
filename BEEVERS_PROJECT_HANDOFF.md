# Beevers + Bell Project Handoff

Locked: 1 October 2026, Melbourne time.

## Authoritative website state

- Current internal baseline: **v110**
- Repository: **beeversbell-ux/beevers-bell**
- Branch: **main**
- Live root: **index.html**
- Latest lock file: **BEEVERS_V110_LOCKED_STATE.md**
- Source-change commit: **030b1cae23ba866b97a52aebda9b85f789f399f9**
- Root content SHA: **ff6662e7bad7bcdd22d884faa8c1ed67ac53a55c**

v110 names the existing independent Star Weekly coverage explicitly in the Fred June section and Sources & Evidence. The article is **“Beevers and Bell plans blasted”** by Cade Lucas, published 19 May 2026. The site now states that the article quoted Fred Maddern and recorded Council's response before the June meeting. Source card 05 shows the full headline, date and byline, while the official 19 May Council-record link in Fred's action row remains unchanged. See **BEEVERS_V110_LOCKED_STATE.md**.

v109 completes the focused retrieval setup. The 21 April decision page's opening summary now naturally names Cr Elena Pereyra as mover and Cr Bernadette Thomas as seconder while keeping the URL, title and H1 event-focused. The public GitHub README now links directly to the decision record. No homepage hero/title changes or person-targeted page were added. The remaining external bridge is the opening paragraph of the existing Change.org update. See **BEEVERS_V109_LOCKED_STATE.md** for validation and rollback.

v108 adds a focused, indexable **21 April 2026 Council decision** record at https://beeversbell.com/decision/21-april-2026/. This is an event page, not an Elena Pereyra profile page. Its URL and H1 do not contain Elena's name. It records the mover, seconder, unanimous vote, what the April decision did and did not do, the four June councillor responses in sequence, exact-moment video links and primary Council sources. The homepage adds one neutral internal link labelled **21 April decision record →** in the existing April source row, and the new URL is in sitemap.xml. This structure was chosen after comparing pages that Google retrieves for Elena Pereyra even when she is only one person in a broader event or list. See **BEEVERS_V108_LOCKED_STATE.md** for validation and rollback.

v107 adds a deliberately subtle search-entity experiment while preserving the visible page. The existing 21 April mover/seconder rows use cleaner semantic article/heading markup for both Elena Pereyra and Bernadette Thomas, with CSS preserving the prior appearance. Their Person structured data now uses precise councillor titles, Maribyrnong City Council membership and exact identity profile references. README.md now neutrally documents the public source repository. WebPage dateModified and sitemap lastmod are 2026-10-05. A direct comparison confirmed normalized visible homepage text is identical to v106 and all href values are unchanged. No Elena title, hero, standalone page, extra visible wording or keyword stuffing was added. See **BEEVERS_V107_LOCKED_STATE.md** for rollback instructions.

v106 fully reverts the v105 numeral experiment. The public index.html is byte-for-byte identical to the v104 public site. The character-level transform applied to the 8 in 38.3% has been removed. No other public HTML, copy, layout, link, timestamp, SEO or metadata changes from v105 remain. v104’s June Elena timestamp refinement and v103’s source-link audit remain in force.

v103 carried forward v102 and completed a source-link audit. The June Fred Maddern secondary CTA now opens the official 19 May Council meeting record rather than the Star Weekly article. The nearby-resident cards now open the direct Phase 2 Engagement Summary, the Beevers toilet status card opens Council's 22 April update, and the misleading 'project FAQ' label now says 'project page'. Verified exact-moment video links were not changed. The homepage title remains **The Beevers + Bell Record | Kingsville, Maribyrnong**. No paid advertising, hidden text, cloaking, fake backlinks or doorway pages are used. No public-facing version number or build date should appear on the site.

## v103 source-link audit

A full hyperlink audit was performed across the live root. The page contains 74 links including repeated destinations and internal chronology anchors.

Keep these v103 corrections:
- Fred June secondary CTA: **VIEW 19 MAY COUNCIL RECORD ↗** → official 19 May 2026 Council meeting page.
- Star Weekly remains linked only where explicitly identified as independent media coverage in Sources & Evidence.
- Beevers Wales Street nearby-resident card → direct Phase 2 Engagement Summary Report.
- Coronation Street nearby-resident card → direct Phase 2 Engagement Summary Report.
- Beevers toilet current-status card → Council's 22 April Beevers + Bell update.
- **View Council project FAQ** changed to **View Council project page**.
- Do not alter the verified YouTube exact-moment links unless new evidence shows a timestamp is wrong.
- All internal chronology anchors currently resolve to existing section IDs.

## v106 rollback audit

The v105 38.3% numeral experiment was fully reverted.

A direct comparison confirms the current public index is exactly identical to the v104 public index:
- current SHA: **fccfefef0e3e6a4bfa62e6dd3068e6c61c3fc5b7**
- v104 SHA: **fccfefef0e3e6a4bfa62e6dd3068e6c61c3fc5b7**

No other public-site changes were introduced by v105. The only other post-v104 changes were internal lock/handoff documentation.

## Most recent visible refinement

The transition into **THE CONSULTATION** was tightened.

Keep:
- one heavy divider line
- no double divider
- obvious chapter separation
- less dead space than earlier builds

Spacing:
- desktop opening bottom: 40px
- desktop consultation top: 40px
- mobile opening bottom: 24px
- mobile consultation top: 24px

## Opening rules

Keep the current opening roadmap:
- HOW TO READ THIS RECORD
- This website follows the story in three parts.
- 01 What residents were asked
- 02 What Council endorsed
- 03 What happened next

The numbers remain simple red bold numbers with **no circles**.

Do not revert to earlier circle treatments.

## Core editorial and design rules

- calm, forensic, evidence-first
- simple surface, deep evidence
- person + documented action + date + primary source
- April → May → June → July chronology
- keep Beevers toilet and Coronation Street road closure analytically separate
- distinguish overall consultation from nearby-resident subsets
- do not overstate what the record proves
- primary sources preferred
- private resident material de-identified where appropriate
- no em dashes
- June remains the hero turning point
- July remains the dark-slate follow-up chapter
- one chronology device per idea
- one chapter divider per transition


## v81 interaction refinement

### July
Keep this visual reading order:
1. JULY · WHAT HAD CHANGED?
2. 21 JULY 2026 · PUBLIC QUESTION TIME
3. After June, what new safety information reached councillors?
4. Question / Answered by tiles
5. COUNCIL RESPONSE
6. quoted answer

### June councillor tiles
The four councillor response tiles remain fully clickable and now include permanent mobile-visible exact-moment cues:
- Thomas: 43:37
- Pereyra: 44:39
- Tiwari: 45:36
- Yengi: 46:28

Use the wording **▶ WATCH EXACT MOMENT · [timestamp] ↗**. The point is to make the direct-to-timestamp YouTube behavior obvious without relying on hover.

## v82 exact-moment refinement

### Beevers toilet record
The two Public Question Time source tiles now link directly to the exact Council recording moments and use the same visible timestamp cue as the June councillor tiles:
- 19 May Patrick Jess: **12:30** → YouTube **Cap4VfGyqHI**, offset **750s**
- 21 July Patrick Jess: **39:44** → YouTube **05x3GgMxzZI**, offset **2384s**

Use the wording **▶ WATCH EXACT MOMENT · [timestamp] ↗**.

The whole tile remains clickable. Keep the treatment restrained:
- no “smoking gun” wording
- no warning icon treatment
- no oversized YouTube branding
- no duplicate CTA
- leave the surrounding explanation and published 52.7% / 38.3% figures unchanged

The purpose is source verification, not added argument.

## v83 CTA refinement

### Beevers toilet record exact-moment links
The 19 May and 21 July source tiles keep the same verified timestamps and direct recording links:
- 19 May Patrick Jess: **12:30**
- 21 July Patrick Jess: **39:44**

The cream-section CTA is now a compact dark-ink button with:
- white **WATCH EXACT MOMENT**
- gold timestamp + arrow
- no giant YouTube treatment
- no extra warning or accusatory language
- no full-width button

This is intentionally different from the June treatment because June already sits on a dark background where gold has sufficient contrast.

## v84 CTA refinement

### Beevers toilet record exact-moment links
The 19 May and 21 July direct source links remain:
- 19 May Patrick Jess: **12:30**
- 21 July Patrick Jess: **39:44**

The cream-section CTA now uses:
- deep muted navy **#263b4a**
- white label and white timestamp/arrow
- compact inline button
- no gold
- no red
- no CTA top rule
- more breathing room above
- the section divider below remains the only transition rule

The June councillor tiles remain unchanged.

## v85 June flow refinement

### Fred Maddern → councillor responses
The June chapter now presents the sequence as:
- **39:07** Fred’s three questions begin
- councillors are invited to respond
- no councillor answers Fred in the moment
- **40:57** the meeting moves to the next public question
- **43:37** Cr Thomas asks to return to the Beevers questions
- the councillor response tiles follow

Fred’s direct video button now reads:
**▶ WATCH FRED’S THREE QUESTIONS · 39:07 ↗**

Between Fred’s card and the councillor tiles, keep the compact transition:
**WHAT HAPPENED NEXT**
**43:37 · Cr Thomas asked to return to the Beevers questions.**
**The councillor responses began from there.**

The response heading is:
**COUNCILLOR RESPONSES**
**The questions came back to the floor.**

Do not add a separate video for the waiting interval. Do not add interpretive or accusatory language. The sequence itself is the point.

## v86 Fred question-chip links

The three existing Fred question chips in the June chapter are now directly tappable:
- **▶ TRAFFIC-COUNT TIMING** → 39:07
- **▶ WALES STREET PLAYGROUND** → 39:30
- **▶ WHAT COUNCILLORS KNEW BEFORE THE VOTE** → 40:20

Each is a standard anchor to the official 16 June YouTube recording. No JavaScript, additional component or new explanatory copy is used.

Keep the existing gold **WATCH FRED’S THREE QUESTIONS · 39:07 ↗** button underneath as the full-sequence option.

## v87 cream-section CTA simplification

The 19 May and 21 July exact-moment links remain at **12:30** and **39:44** respectively.

Their visual treatment is now intentionally quieter:
- transparent background
- thin neutral outline
- dark ink text
- slightly smaller padding/type
- no filled navy block
- no new accent colour

This is a visual tidy-up only. The source links, timestamps and surrounding text are unchanged.

## v88 May/July source-card tidy-up

The 19 May and 21 July Patrick Jess tiles keep the same quotes, timestamps and direct video links:
- 19 May: **12:30**
- 21 July: **39:44**

The cream-section presentation is now quieter:
- the **WHAT THAT MEANS HERE** explainer has a transparent background and thinner red rule
- the exact-moment action is a plain deep-navy text link with a simple underline, not a filled or outlined box
- the extra divider directly beneath the source card is removed
- spacing now does more of the separation work

Do not reintroduce a filled navy button here. The aim is to keep the source obvious without adding another competing block.

## v89 May/July source-action alignment

The Patrick Jess source actions remain:
- 19 May: **12:30**
- 21 July: **39:44**

Both now follow the same visual order:
1. quoted wording
2. **▶ WATCH EXACT MOMENT · [timestamp] ↗**
3. explanatory/context material where applicable

The source action is plain deep-navy text, with no filled/outlined button and no underline/rule. Keep it visually subordinate to the quote but clearly tappable.

## v90 May-to-July bridge tidy-up

The factual bridge between the May and July Patrick Jess source moments is unchanged.

Its presentation is now deliberately quieter:
- no filled background
- no red left-side bar
- one thin top rule
- smaller red kicker
- smaller sans-serif body copy
- tighter padding and spacing

The intent is to preserve the chronology while removing another competing visual block from the mobile view.

## v91 technical SEO baseline

No visible page design or wording changed.

Added to the homepage:
- canonical: **https://beeversbell.com/**
- robots meta: **index, follow**
- Open Graph metadata
- Twitter summary metadata
- WebSite JSON-LD structured data

Added root crawl files:
- **robots.txt** allows crawling and points to the sitemap
- **sitemap.xml** contains the canonical homepage and a 2026-09-29 lastmod

The GitHub Pages workflow now copies both files into the published `_site` directory and verifies their expected contents before deployment.

SEO deployment run **36563428746** completed successfully.

Next external setup step: create a **Domain property** for `beeversbell.com` in Google Search Console, verify it using Google’s TXT record in Cloudflare DNS, submit `sitemap.xml`, then use URL Inspection on `https://beeversbell.com/` and request indexing.

## v92 factual SEO and Search Console status

Search Console setup completed:
- Domain property `beeversbell.com` verified via Cloudflare DNS.
- Correct sitemap `https://beeversbell.com/sitemap.xml` submitted successfully and discovered 1 page.
- URL Inspection showed the homepage is already on Google and indexed.
- Live Test showed the page is available to Google and can be indexed.
- A fresh indexing request was accepted into Google’s priority crawl queue.

v92 then strengthened factual search context without adding unsupported labels:
- Maribyrnong City Council
- Your City, Your Voice
- Phase 1 engagement
- Phase 2 engagement
- Beevers Reserve
- Bell Reserve
- Coronation Street
- Pick My Park
- Victorian Government
- Kingsville
- Melbourne’s inner west
- Yarraville, Seddon, West Footscray and Footscray as City of Maribyrnong municipal context

Opening now explicitly describes the two engagement phases and the local municipal context.
Source cards 13 and 14 cover Phase 1 and Your City, Your Voice + Pick My Park.
Structured data was expanded with factual entities and local-search terms.

Do not add `corruption`, `misleading`, `misdirection` or comparable labels purely for SEO unless a future sourced record specifically supports carefully attributed wording.

## v93 opening restored after SEO pass

The v92 opening was judged too visually heavy. v93 restores the pre-v92 opening:
- top bar back to **Kingsville · City of Maribyrnong**
- intro label back to **HOW THE “YOUR CITY, YOUR VOICE” CONSULTATION UNFOLDED**
- removes the extra visible Phase 1/Phase 2 explainer from the opening
- removes the extra visible local-context paragraph listing Yarraville, Seddon, West Footscray and Footscray
- preserves the original opening flow and spacing

Technical/factual SEO remains in:
- canonical/robots/sitemap
- Open Graph/Twitter metadata
- JSON-LD structured data
- lower-page source cards for Phase 1 and Pick My Park

Rule going forward: SEO must not visibly bloat the opening or compromise the reader experience.

## v94 May/July readability + factual councillor search context

May and July 50/50 moments now deliberately mirror each other:
- black date / PUBLIC QUESTION TIME banner
- Patrick Jess + Director role
- concise setup
- large clickable quote source card
- prominent exact-moment footer (12:30 May, 39:44 July)
- compact 52.7 / 38.3 / 9.0 evidence panel
- May shows 14.4 percentage-point gap
- July says the published figures had not changed

Removed:
- paragraph-heavy May explainer
- large July "used the 50/50 description again" heading
- duplicated separate July result key

For factual search context, the April decision section now states:
**Cr Elena Pereyra · Wattle Ward · moved the motion to endorse the Beevers Reserve and Bell Reserve final concept plans.**

Structured data also includes factual Person entities for Pereyra and Bernadette Thomas.

## v95 Elena Pereyra search relevance

The page opening and main design were not changed.

Search-relevance changes:
- HTML title now includes **Elena Pereyra**
- meta description links her name to the **21 April 2026 motion**
- Open Graph/Twitter metadata aligned to the same factual wording
- source card 02 now says **21 April decision · Elena Pereyra moved the motion**
- existing April role gets stable fragment **#elena-pereyra**
- JSON-LD now uses an @graph with WebSite, WebPage and Person entities
- Elena Person entity is tied to her current official Maribyrnong councillor listing with `sameAs`

This is intended to improve exact-name relevance without bloating the visible opening or adding unsupported labels.

## v96 May/July visual correction

The v94 comparison redesign was too heavy. v96 restores the established May/July layout while preserving v95 SEO.

Restored:
- original May/July banners and speaker hierarchy
- original May explainer
- original July heading/result key
- secondary treatment of 9.0% unsure

Removed:
- three-column equal-weight result panels
- full-width watch bar
- v94 comparison CSS

Retained improvement:
- standalone black exact-moment source buttons at 12:30 and 39:44

Search Console live test passed: URL available to Google and page can be indexed.

## v97 explicit published-result vs 50/50 contrast

May now uses one vertical sequence inside the existing red-rule explainer:
- **COUNCIL’S PUBLISHED PHASE 2 RESULT**
  - 52.7% did not support
  - 38.3% supported
- **14.4 percentage points apart**
- **HOW IT WAS DESCRIBED IN MAY**
  - “about a 50/50 split”

July mirrors the logic:
- **PUBLISHED FIGURES HAD NOT CHANGED**
  - 52.7% did not support
  - 38.3% supported
- **HOW IT WAS DESCRIBED AGAIN IN JULY**
  - “about 50/50 as we've reported previously”

No side-by-side metric boxes. 9.0% unsure stays secondary. Standalone black exact-moment source buttons remain.

## v98 sharpened May/July contrast

May:
- keeps the existing red-rule explainer
- 52.7% / 38.3% stay as simple bullets
- **14.4** is the single visual hinge
- closes with: the description immediately above was “about a 50/50 split”
- 9.0% unsure + advisory note are secondary and italic
- removes the repeated “HOW IT WAS DESCRIBED IN MAY” block

Between May and July:
- now explicitly links the petition to the 14.4-point gap vs the 50/50 description

July:
- published figures had not changed
- **The same 14.4-point gap remained**
- the 50/50 description was used again in July
- 9.0% unsure remains secondary and italic
- avoids repeating the full July quote inside the evidence block

## v99 final May/July handoff

- deliberate pause after both exact-moment source buttons before the contrast/evidence block
- May/July red rules trimmed to the exact content they frame
- bridge kept deliberately intermediate, not a hero block
- bridge now says:
  **By June, the discrepancy was formally before Council.** The petition specifically contrasted Council’s published 52.7% / 38.3% Phase 2 figures with the “50/50” description. Council formally received the petition. **In July, the 50/50 description was used again.**

This is intentionally factual and chronological. It does not use “lied” or imply that a particular officer personally read the petition.

## v100 transparent authorship and organic discoverability

The main page now identifies **Chris Walton** as the creator and maintainer of The Beevers + Bell Record through:
- standard author metadata
- structured Person authorship
- a factual external identity reference to the public Change.org update
- a quiet visible footer credit

Keep this transparent. Do not add hidden keywords, cloaking, fake backlinks, doorway pages or paid placements disguised as organic material.

## v101 search-result framing

The homepage search presentation was deliberately toned down after the Google result appeared too targeted.

Use:
**The Beevers + Bell Record | Kingsville, Maribyrnong**

Meta description:
**A sourced resident record of the Beevers and Bell Reserve consultation, Council decisions and subsequent public questions in Kingsville, City of Maribyrnong.**

Apply the same neutral framing to Open Graph, Twitter metadata and the WebPage structured-data name/description.

Structured-data subjects:
- `about`: Maribyrnong City Council, Beevers Reserve, Bell Reserve, Coronation Street
- `mentions`: Elena Pereyra, Bernadette Thomas, Your City Your Voice, Pick My Park, Victorian Government

Do not put Elena Pereyra back into the homepage title or lead meta description unless explicitly requested. Her name remains naturally discoverable through the documented body content and entity markup.

Chris Walton authorship signals remain in place.

Google may continue to display an older cached title/snippet until recrawl.

## v102 crawl refresh

The screenshot taken after v101 still showed Google's older cached title/snippet:
**Beevers & Bell Kingsville | Elena Pereyra, Maribyrnong Council**

The live homepage itself is already neutral:
**The Beevers + Bell Record | Kingsville, Maribyrnong**

To strengthen ordinary recrawl signals without paid promotion:
- WebPage `dateModified` updated to **2026-10-01**
- sitemap `lastmod` updated to **2026-10-01**
- cache-bust marker refreshed
- robots remains open and points to the sitemap

Do not interpret the old Google snippet as the current live metadata. It is a stale search presentation until Google reprocesses the page.

## Petition website insert

The Change.org petition predates the website. The agreed top insert is:

**NEW: RESIDENT WEBSITE LAUNCHED 28 SEPTEMBER 2026**

This petition was launched in May 2026. Following months of consultation, Council meetings, correspondence and petition updates, a dedicated resident website has now been created to bring the record together in one place.

**THE BEEVERS + BELL RECORD**  
https://beeversbell.com

**ORIGINAL PETITION STARTS HERE ↓**

Then leave a blank line and continue the original petition unchanged.

Formatting:
- bold the three heading/separator lines above
- no italics
- no bullet list in this new insert
- keep it compact for Change.org mobile

## Recovery rule

Future chats should start from:
1. current root **index.html**
2. **BEEVERS_V104_LOCKED_STATE.md**
3. this handoff file

Do not use old local v70-v72 preview files as authoritative.
