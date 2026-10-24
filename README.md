# IND AMICUS LEGAL — static website redesign

This is a multi-page, responsive static HTML/CSS/JavaScript redesign intended for the existing GitHub Pages project:
`https://vksgupta29.github.io/legal2/`

## Included pages
- `index.html` — home
- `firm.html` — firm overview and founding partner placeholder
- `practice-areas.html` — practice categories
- `sectors.html` — illustrative industry sectors
- `insights.html` — legal insights landing page and editorial checklist
- `contact.html` — editable official contact particulars
- `disclaimer.html` — draft disclaimer
- `privacy.html` — draft privacy policy framework
- `terms.html` — draft terms of use
- `assets/styles.css` — shared responsive design system
- `assets/site.js` — accessible mobile navigation and dynamic footer year

## Before publishing — required owner review
1. Replace every bracketed placeholder in `contact.html`, `firm.html`, `disclaimer.html`, `privacy.html` and `terms.html`.
2. Verify all factual statements about the firm, its founder, qualifications, enrolment details, practice and sectors.
3. Obtain Indian professional-conduct review of the full website, including Rule 36 BCI compliance, permitted website particulars, disclaimer wording, site-entry mechanism (if any), page content, contact presentation and any enquiry process.
4. Confirm the actual privacy/data flow: GitHub Pages logs, analytics, third-party scripts, any email/contact mechanism, retention and privacy contact. Do not publish the privacy template unchanged.
5. Check external links, spellings, page content, and all links on desktop and mobile.
6. Add real, dated legal insights only after checking primary sources and later developments. The current topic examples are not current legal updates.
7. Decide whether to load Google Fonts from Google. If not, remove the `@import` in `assets/styles.css`; the CSS includes local system fallbacks.

## Deploy to the existing GitHub Pages project
**Recommended safe approach:** preview in a separate branch or local folder first. Keep a backup of the current site.

1. Download and unzip this package.
2. Open the existing repository `vksgupta29/legal2` on GitHub.
3. Back up the current contents (or create a branch such as `redesign-preview`).
4. Upload the files and folders from this package to the same publishing root where the current `index.html` lives. Do not upload the enclosing ZIP itself.
5. Keep the relative links as provided. They are designed to work from a project path such as `/legal2/`.
6. Commit to the preview branch and configure a preview/deployment workflow if available. Otherwise test locally first.
7. When ready, merge or copy the reviewed files into the configured publishing branch/folder.
8. Verify **Settings → Pages** still points to the intended branch/folder and check the live URL after deployment.

## Important limitations
- This package does not connect to the GitHub repository or publish changes automatically.
- There is no working contact form or server-side processing in this static package. Contact details are placeholders. Do not add a form without choosing and reviewing a secure processing method.
- This is a design and content starter, not legal advice or a certification of compliance.
- No analytics, tracking scripts, client testimonials, case results, rankings or advertising integrations have been added.
- The hero artwork is made in CSS, avoiding stock imagery and external image dependencies.

## Suggested pre-launch tests
- [ ] Test every link and page on mobile and desktop.
- [ ] Test keyboard-only navigation and focus visibility.
- [ ] Check contrast and automated accessibility results.
- [ ] Run PageSpeed Insights and review any significant issues.
- [ ] Check Search Console after launch.
- [ ] Review page titles, descriptions, sitemap/robots setup and canonical URLs.
- [ ] Have the legal notices and all professional claims reviewed before public release.
