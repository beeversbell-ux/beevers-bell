# Beevers + Bell v77 locked state

Locked: 28 September 2026, Melbourne time.

## Authoritative current version
**v77** is the current approved baseline.

It carries forward v76 and repairs the regressions introduced in the local v77 preview.

## Changes locked in at v77
- Coronation Street explainer is no longer a large wall of serif text.
  - now split into two short paragraphs
  - first sentence is the emphasis line
  - explanatory sentence is normal body scale
- Coronation Street question cards retain their structure but use slightly smaller mobile text.
- July remains a dark section so inherited light-on-dark components remain legible.
- July now uses a **dark slate** background rather than full black, so it remains visually distinct from June without competing with June as the hero section.
- The redundant three-card July scan was removed.
- The remaining **THE SEQUENCE** block is the single chronology device and is broken into:
  - June
  - July
  - Status
- The July quote has been reduced so it does not overpower the June section.
- July caption, question/answer context and emergency-service blocks remain explicitly readable on the dark background.
- Space between **WHERE THINGS STAND NOW** and **WHAT HAPPENS NEXT** has been tightened.
- Do not revert to the cream-background July experiment from the local preview. That caused inherited contrast failures.

## Visual hierarchy rules
- June remains the hero turning point.
- July is a follow-up chapter.
- One chronology device per idea.
- Avoid stacked or competing visual treatments.
- Major chapter transitions should be unmistakable, but supporting explanation should not be set at hero scale.
- On mobile, explanatory copy should be broken into short blocks before increasing font size.

## Existing locked principles
- Calm, forensic, evidence-first.
- Simple surface, deep evidence.
- April → May → June → July chronology.
- Beevers toilet and Coronation Street road closure remain analytically separate.
- Use primary sources, dated actions and evidence guardrails.
- Do not overstate what the record proves.
- Keep the circle-free opening roadmap from v73.
- Keep the v75 rule: one chapter divider, not stacked thin + thick lines.
- Keep the v76 threshold-question structure and guardrail.

## Publication
Repository: **beeversbell-ux/beevers-bell**
Branch: **main**
Current approved root file: **index.html**
Current approved version: **v77**
Current commit: **2b821e7c0ad41aa4b3d59f837ee49c94c2909853**

Future Beevers Project chats should recover from this file and the current root index.html, not from older local preview files.