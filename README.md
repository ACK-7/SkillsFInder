# Skills Finder

A community resource directory demo for school leavers aged 18–25 in Uganda who want to compare practical training by location, duration, and cost. Built for the Ishvexa Hub Web Development internship.

## Run locally

Open `index.html` in a browser. No installation, account, build step, or backend is required for Week One. Internet access is not needed. Reload the page after editing a file.

Later JSON loading will require a local web server; instructions will be added when that feature exists.

## Current version

- One semantic HTML page with header, navigation, main content, sections, six static fictional listings, and footer.
- Working section links, skip link, and native expandable course summaries.
- Shared CSS with a responsive layout, visible keyboard focus, and system fonts.
- Prominent demo-data notice. No real applications, contact links, or personal information collection.

## Project structure

```text
Skills FInder/
  index.html                 First working directory page
  assets/css/styles.css      Shared design tokens and page styles
  content-sources.md         Content and asset inventory
  docs/                     Local development notes (ignored by Git)
  .gitignore                Local files excluded from version control
  README.md                 Scope and setup instructions
```

The planning document and wireframes remain in the sibling `Week one` folder; the internship handbook remains in the workspace root.

## Planned scope

1. Week Two: dedicated Directory, Centre Details, and About pages, consistent navigation, active-page indicators, and responsive/keyboard evidence.
2. Week Three: keyword search across centre, course, and skill area; filters for location, skill, cost, and duration; reset and no-results states; eight documented manual tests.
3. Week Four: move records to local JSON with stable IDs; validate data; implement loading, empty, success, and failure states and recovery.
4. Weeks Five and Six: tester feedback, browser/accessibility checks, fixes, recorded walkthroughs, reproducible handover, and portfolio case study.

Search and filter controls are not displayed until they work. Current navigation targets sections of this first page. Native course summaries are a temporary Week One aid, not the planned dedicated centre details page.

## Data and credits

All centre names, descriptions, courses, fees, and durations are invented demonstration content. Real place names provide illustrative location context and do not establish that a centre exists there. Any resemblance to a real provider is coincidental. No verified availability or certification is claimed. See [content-sources.md](content-sources.md).

## Checks

Source inspection passed for local link targets, unique IDs, heading levels, page landmarks, and the six sample listings. Browser appearance and keyboard checks remain pending. This project has no configured lint, typecheck, test runner, or build command. Do not treat source inspection as completed browser or accessibility validation.

Development notes and detailed check records are kept locally in the ignored `docs/` folder and are not included in a repository clone. Required internship test evidence must be shared separately with reviewers.

## Contribution and AI assistance

The project concept, audience, scope, sitemap, and wireframes come from the intern's supplied Skills Finder Week One brief. Codex generated the initial HTML, CSS, and supporting project records with AI assistance. The intern should review, understand, adapt, and accurately explain this code before submission. Do not claim independent authorship of AI-generated work.

## Weekly submission

The Week One package still needs the repository URL and commit reference, actual browser/link-check results, and both public progress-post URLs. Use the official Ishvexa Hub handle supplied during onboarding. No posts have been created or published by this setup.
