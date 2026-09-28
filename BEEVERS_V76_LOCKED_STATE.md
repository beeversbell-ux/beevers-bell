# Beevers + Bell v76 locked state

Locked: 28 September 2026, Melbourne time.

## Authoritative website baseline

The authoritative current website state is **v76**.

It carries forward the v73 locked baseline and the subsequent targeted refinements. Do not rebuild from scratch or revert to older ChatGPT/Lovable drafts.

### Changes since v73

#### v74
- Removed the duplicate rule before the 19 May Public Question Time block.
- Tightened the handoff from the published Phase 2 figures into the May chronology.
- Clarified the start of Council’s Public Toilet Plan/framework section with one deliberate chapter transition rather than ambiguous spacing.
- Changed the framework heading to a clearer question-led treatment.

#### v75
- Removed redundant section-bottom rules where the next chapter already had its own strong chapter rule.
- Design rule locked: **one chapter transition rule, not stacked thin + thick dividers.**

#### v76
- Reworked only the Beevers “threshold question” block because it was visually crowded and over-explained on mobile.
- Replaced the nested red/black rail treatment with:
  1. one strong top rule
  2. one red question label
  3. one concise question heading
  4. one black 19 May Public Question Time banner
  5. one evidence statement
  6. one explicit safety guardrail
  7. one short “WHAT THE RECORD SHOWS” conclusion panel
- Current question wording: **“Has Beevers been shown to satisfy Council’s Public Toilet Plan?”**
- Current guardrail: **“This does not establish that the toilet is unsafe.”**
- Current conclusion: the public record presented on the site does not establish that Beevers has already completed the Public Toilet Plan assessment/review.
- The wider toilet-framework evidence immediately above and the source links immediately below remain in place.

## Opening roadmap treatment

After the resident-concerns section and the paragraph beginning **“The wider park upgrades were broadly supported.”**, retain:

- the divider
- **HOW TO READ THIS RECORD**
- **This website follows the story in three parts.**
- three bordered cards:
  - **01** What residents were asked
  - **02** What Council endorsed
  - **03** What happened next

The **01 / 02 / 03 are simple red bold numbers with no circles**, positioned close to the card headings. Do not restore the circle treatment.

## Editorial and reader-experience rules

The site is a calm, forensic, evidence-first resident-led public record for Kingsville. Its operating principle is **simple surface, deep evidence**.

The chronology is the spine:

1. Consultation and what residents were asked
2. 21 April 2026 Council endorsement
3. May questions and first “about 50/50” description
4. 16 June petition/public questions as the major turning point
5. July follow-up, including the repeated “50/50” description and traffic, pedestrian-safety and emergency-access questions
6. Later process, including further traffic assessment and statutory road-closure steps

Keep the Beevers Reserve public-toilet issue and Coronation Street road-closure issue analytically separate. Use primary sources, documented action + date + person where relevant, and de-identification for private residents. Do not invent motives or certainty.

### Visual hierarchy rule now locked

- Major chapter transition: **one strong rule + chapter label/heading**
- Internal content transition: spacing, banner, card or rail only where it serves a clear function
- Never stack a thin section divider with a heavy chapter rule
- Avoid nested competing rails
- On mobile, every visual treatment must answer: **is this a new chapter, a new dated beat, or supporting evidence?**
- Do not introduce a new decorative device unless it improves that hierarchy

## Core evidence to preserve

- Beevers Phase 2 overall result: **52.7% did not support**, **38.3% supported**, **9.0% unsure**, a **14.4 percentage-point gap**.
- Wales Street online respondents: **24 opposed, 0 supported**. Nearby-resident subsets are contextual evidence and do not replace the overall consultation result unless a source establishes such a decision rule.
- Wider park upgrades were broadly supported.
- 21 April 2026: Council endorsed the concept. **Seven councillors present. Seven votes for.**
- May 2026: Director Infrastructure Services Patrick Jess first described the consultation as **“about 50/50.”**
- 16 June 2026: petition and public question time are the narrative turning point.
- July 2026: the “about 50/50” description was repeated and residents again raised traffic, pedestrian safety and emergency access.
- The Coronation Street closure still requires a later statutory process and final Council decision.
- Council’s 22 April 2026 project update states the planned Beevers toilet will be reviewed under the Public Toilet Plan 2019–2029 and later installed through the public toilet delivery program rather than as part of the park upgrades.
- The 21 April 2026 Council report sought endorsement of the concept plans and retained the public toilet on the Beevers concept plan.
- Later Council correspondence says earlier traffic work will be peer reviewed and a secondary assessment obtained.
- Emergency-service input is planned for the later road-closure process.
- **$150,000** was allocated to Bell Reserve in the 2026/27 budget, with later delivery timing.

Retain consultation-board evidence, traffic-report scope/guardrails, ambulance and garbage-truck street context, source-desk links, resident privacy rules and the distinction between public sources and private correspondence.

## Publication state

Repository: **beeversbell-ux/beevers-bell**  
Branch: **main**  
GitHub Pages: enabled.

Current deployment method:

1. workflow extracts `beevers-bell-production.zip` for the asset bundle
2. legacy v66/v67 patches run against the packaged base
3. the root `index.html` is then overlaid as the authoritative approved current page
4. GitHub Pages deploys `_site`

The root `index.html` is the source of truth for the approved current HTML.

## Current publishing checkpoint

- Current approved version: **v76**
- Current index commit: **d5f20ee6280d32cba7c686787274907fe10735d4**
- Repository: **beeversbell-ux/beevers-bell**
- Do not revert to `beevers-bell-final-v5`, v53, older Lovable drafts, or earlier temporary HTMLs.

## Continuity instruction

Future Beevers Project chats should treat **BEEVERS_V76_LOCKED_STATE.md** plus the current root `index.html` as the recovery point and continue from them without asking the user to reconstruct the history.
