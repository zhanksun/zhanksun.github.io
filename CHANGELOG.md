# Website Change Log

This file tracks notable maintenance changes to the personal website source.
Use it for content edits, publishing hygiene, build notes, and follow-up items
that should not be forgotten.

## How To Update This File

Add new entries at the top of the dated log. Keep each entry short, and include:

- what changed
- why it changed
- any verification or follow-up needed

## 2026-06-28

### Performance

- Changed MathJax loading so it only runs on pages with `mathjax: true`, avoiding the MathJax script on the homepage and other non-math pages.
- Added `mathjax: true` to the existing pages that use inline math or LaTeX notation.

### Analytics

- Replaced the obsolete Universal Analytics ID `UA-92802615-2` with the GA4 Measurement ID `G-6VPR6BMQ1B`.
- Added a `google-gtag` analytics provider include that loads Google's GA4 `gtag.js` script.

### Profile And Metadata

- Updated the site description in `_config.yml` to reflect the current academic role, MBA program director role, and research focus.
- Added structured profile links for Google Scholar, ORCID, and the CityUHK staff profile.
- Updated the sidebar bio to include the MBA Program Director role.
- Updated `_data/authors.yml` so posts authored by Zhankun Sun use the current profile image and academic bio.

### Publications And Reading Pages

- Fixed the malformed Google Scholar link on `_pages/publications.md`.
- Resolved duplicate `/reading/` permalinks by moving the emergency department service-time note to `/reading/ed-service-time/`.
- Renamed the EV literature reading page title to better describe its content.

### Broken Link Cleanup

- Fixed case-sensitive image paths in `Research/staffing with pph.md`.
- Fixed case-sensitive image paths in `_posts/2021-03-12-Statistical Significance is dead.md`.
- Removed dead local image references from `reading/routing.md` because the referenced image files were not present.
- Removed dead local PDF links from `_posts/2020-01-01-interesting-papers.md` where the referenced PDF files were not present.

### Publishing Hygiene

- Added `midterm2026/` to the Jekyll exclude list and `.gitignore` so exam materials are not included in future generated site builds.
- Removed `midterm2026` exam files from the current tracked tree. If those files were already pushed to a public repository, Git history may still need to be cleaned separately.
- Added `.DS_Store` to `.gitignore`.

### Navigation

- Reverted the main navigation to the original public menu: `Publications`, `Teaching`, and `Grants`.

### Verification Notes

- Static checks found no duplicate permalinks after the cleanup.
- Static checks found no case-sensitive local-link problems after the cleanup.
- Full Jekyll build was not run because the local Ruby environment is missing Bundler `2.1.4`, which is required by `Gemfile.lock`.

## Follow-Up Ideas

- Install Bundler `2.1.4` or refresh the Ruby/Jekyll setup, then run a full local build.
- Consider setting `future: false` in `_config.yml` if future-dated posts should not be published.
- Confirm GA4 is receiving traffic after the next site deployment.
- Remove tracked `.DS_Store` files from Git history or at least from the current tree.
