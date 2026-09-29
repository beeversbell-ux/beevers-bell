# Beevers + Bell v86 locked state

Locked: 29 September 2026, Melbourne time.

## Authoritative current version
**v86** is the current approved internal baseline.

It carries forward v85 and adds one low-risk source-navigation refinement inside Fred Maddern’s June question block.

## v86 change

### Each Fred question chip is now directly tappable
The three existing question chips remain visually compact, but are now plain HTML links to the corresponding point in the official 16 June Council recording:

- **TRAFFIC-COUNT TIMING** → 39:07
- **WALES STREET PLAYGROUND** → 39:30
- **WHAT COUNCILLORS KNEW BEFORE THE VOTE** → 40:20

Each chip now includes a small play triangle to signal that it opens video.

The whole-chip interaction is implemented with standard anchor links only:
- no JavaScript
- no new component
- no state
- no structural rebuild
- no added explanatory copy

The existing gold **WATCH FRED’S THREE QUESTIONS · 39:07 ↗** button remains available for readers who want to watch the sequence from the beginning.

## Existing locked principles
- Public-facing build/version/date remains hidden.
- June remains the hero turning point.
- July remains the dark-slate follow-up chapter.
- Keep the circle-free opening roadmap.
- One chapter divider per transition.
- Calm, forensic, evidence-first.
- Simple surface, deep evidence.
- April → May → June → July chronology.
- Beevers toilet and Coronation Street road closure remain analytically separate.
- Do not overstate what the record proves.
- Ombudsman response remains off the website for now.

## Publication
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Current approved root file: **index.html**
Current approved internal version: **v86**
Visible-content commit: **7640ce99b9f1e801655321f6b9251e4f96113e79**
Visible-content deployment run: **36519588230**
Visible-content deployment result: **success**

Future Beevers Project chats should recover from this file, the current root index.html, and BEEVERS_PROJECT_HANDOFF.md.
