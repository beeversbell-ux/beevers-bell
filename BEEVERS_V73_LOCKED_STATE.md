# Beevers + Bell v73 locked state

Locked: 28 September 2026, Melbourne time.

## Authoritative website baseline

The authoritative current website state is **v73**.

It is based on the v70 opening/content baseline, keeps the v71 explanatory roadmap structure, and removes the v72 numbered-circle treatment.

### Opening roadmap treatment

After the resident-concerns section and the paragraph beginning **“The wider park upgrades were broadly supported.”**, retain:

- the divider
- **HOW TO READ THIS RECORD**
- **This website follows the story in three parts.**
- three bordered cards:
  - **01** What residents were asked
  - **02** What Council endorsed
  - **03** What happened next

The **01 / 02 / 03 are simple red bold numbers with no circles**, positioned close to the card headings. Do not restore the circle treatment.

Everything else from the v70/v71 baseline remains unchanged unless deliberately revised later.

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

## Core evidence to preserve

- Beevers Phase 2 overall result: **52.7% did not support**, **38.3% supported**, **9.0% unsure**, a **14.4 percentage-point gap**.
- Wales Street online respondents: **24 opposed, 0 supported**. Nearby-resident subsets are contextual evidence and do not replace the overall consultation result unless a source establishes such a decision rule.
- Wider park upgrades were broadly supported.
- 21 April 2026: Council endorsed the concept. **Seven councillors present. Seven votes for.**
- Cr Elena Pereyra moved the April motion; Cr Bernadette Thomas seconded.
- May 2026: Director Infrastructure Services Patrick Jess first described the consultation as **“about 50/50.”**
- 16 June 2026: petition and public question time are the narrative turning point. Fred Madden’s questioning is an important part of the record.
- July 2026: the “about 50/50” description was repeated and residents again raised traffic, pedestrian safety and emergency access.
- The Coronation Street closure still requires a later statutory process and final Council decision.
- The Beevers toilet remains subject to review/prioritisation under the Public Toilet Plan.
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

The root `index.html` is now the source of truth for the current approved HTML. Do not revert to `beevers-bell-final-v5`, v53, older ChatGPT/Lovable drafts, or rebuild from scratch.

## Continuity instruction

Future Beevers Project chats should treat this file as a recovery point and continue from it without asking the user to re-explain the history.