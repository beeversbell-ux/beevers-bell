# Beevers + Bell v91 locked state

Locked: 29 September 2026, Melbourne time.

## Authoritative current version
**v91** is the current approved internal baseline.

It carries forward v90 with no visible design/content changes and adds the first technical SEO layer for indexing and sharing.

## v91 technical SEO changes

### Homepage metadata
Added to index.html:
- robots directive: index, follow
- canonical URL: https://beeversbell.com/
- Open Graph title, description, URL and site name
- Twitter summary-card metadata
- WebSite JSON-LD structured data

Existing visible title and meta description remain consistent with the site’s factual purpose.

### Crawl/discovery files
Added:
- robots.txt
  - allows all crawlers
  - references https://beeversbell.com/sitemap.xml
- sitemap.xml
  - includes the canonical homepage URL
  - lastmod: 2026-09-29

### Deployment workflow
Updated .github/workflows/deploy-pages.yml so the approved root files:
- index.html
- robots.txt
- sitemap.xml

are copied into _site before the GitHub Pages artifact is uploaded.

The workflow also explicitly tests that robots.txt and sitemap.xml exist in the deployment artifact and contain the expected beeversbell.com URLs.

## Verification
Visible-content / SEO deployment commit:
**f8ea8c85bdd7136575064d213f85bc9142479c84**

Deployment run:
**36563428746**

Result:
**success**

All deployment steps completed successfully, including:
- Overlay current approved site
- Configure GitHub Pages
- Upload Pages artifact
- Deploy to GitHub Pages

The current execution environment could not independently resolve beeversbell.com over public DNS, so live HTTP retrieval from this environment was not available. This is an environment-network limitation, not a failed GitHub Pages deployment. Search Console live URL testing will be the next external end-to-end check.

## Existing locked principles
- Public-facing build/version/date remains hidden.
- No visible design change in v91.
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

Future Beevers Project chats should recover from this file, the current root index.html, and BEEVERS_PROJECT_HANDOFF.md.
