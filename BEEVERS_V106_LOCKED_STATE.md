# Beevers + Bell v106 locked state

Locked: 2 October 2026, Melbourne time.

## Authoritative current version
**v106** is the current approved internal baseline.

v106 is a rollback of the v105 numeral experiment.

## Public site state
The public **index.html is byte-for-byte identical to the v104 public site**.

The v105 change that wrapped and horizontally transformed the digit 8 in **38.3% supported** has been fully removed.

No other public HTML, copy, layout, link, timestamp, SEO or metadata change was introduced by v105.

## Audit result
A direct comparison confirms:
- current index content SHA: **fccfefef0e3e6a4bfa62e6dd3068e6c61c3fc5b7**
- v104 index content SHA: **fccfefef0e3e6a4bfa62e6dd3068e6c61c3fc5b7**
- exact content match: **true**

The only repository changes after v104 besides the temporary public numeral experiment were internal documentation:
- BEEVERS_V105_LOCKED_STATE.md
- BEEVERS_PROJECT_HANDOFF.md updates

These are not rendered on the public website.

## Deployment
Rollback commit:
**ca0928c63fb4276ace164e74235c89b1ed1272d1**

Deployment run:
**36968974263**

Result:
**success**

## Existing locked principles
- calm, forensic, evidence-first
- simple surface, deep evidence
- person + documented action + date + primary source
- no em dashes
- June remains the hero turning point
- July remains the dark-slate follow-up chapter
- no public-facing version number or build date
- do not apply character-level transforms to headline numerals

Future Beevers Project chats should recover from this file, the current root index.html, and BEEVERS_PROJECT_HANDOFF.md.
