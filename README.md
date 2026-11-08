# NEXUS privacy policy site

Generated from `release/documentation/PRIVACY-POLICY.md` by
`npm run privacy:site`. Do not edit `index.html` directly — edit the policy
and regenerate, so the published page and the release documentation cannot
drift apart.

## Publishing on GitHub Pages

1. Create a **public** repository, for example `nexus-privacy-policy`.
   Do not put the NEXUS source or the extension ZIP in it — this repository
   exists only to serve one page.
2. Upload the contents of this folder (`index.html` and `.nojekyll`) to the
   repository root on the `main` branch.
3. **Settings → Pages → Build and deployment**: source **Deploy from a branch**,
   branch **main**, folder **/ (root)**. Save.
4. Wait for the deployment to finish, then open
   `https://YOUR-USERNAME.github.io/nexus-privacy-policy/` in a private window
   and confirm it loads for a signed-out visitor.
5. Paste that URL into the Chrome Web Store listing under
   **Privacy practices → Privacy policy URL**.

## Before you publish

- [ ] The contact email placeholder is replaced with an address you control.
- [ ] You have read the whole policy and agree with every statement in it.
- [ ] The repository is **public** — a 404 for signed-out visitors fails review.

A note on the email: whatever address you put here will be scraped. A dedicated
address, or an alias that forwards to your real inbox, is usually a better
choice than a personal one.
