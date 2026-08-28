# maestro-legal

Public Privacy Policy and Terms of Service pages for **Maestro**, a
local, approval-first artist-management tool. This repo holds only
those two pages (plus a small landing page) — no application source
code, no project documentation, no configuration, and no secrets.

These pages exist because some third-party developer platforms (e.g.
TikTok's developer portal) require a public URL for a Privacy Policy
and Terms of Service when registering an app.

## Contents

- `index.html` — minimal landing page
- `privacy.html` — Privacy Policy
- `terms.html` — Terms of Service
- `.nojekyll` — tells GitHub Pages to serve these files as plain
  static HTML, with no Jekyll build step

## Publishing via GitHub Pages

1. On GitHub, open this repo's **Settings** tab.
2. In the left sidebar, click **Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a
   branch**.
4. Under **Branch**, choose **main** and the **/ (root)** folder, then
   **Save**.
5. GitHub publishes the site at
   `https://jcvarx.github.io/maestro-legal/` (shown on the same
   settings page once live — the first deploy can take a minute or
   two).

Resulting pages:
- `https://jcvarx.github.io/maestro-legal/privacy.html`
- `https://jcvarx.github.io/maestro-legal/terms.html`

## Before submitting these URLs anywhere

Both `privacy.html` and `terms.html` contain a placeholder —
`[CONTACT EMAIL PLACEHOLDER — add a real address here before relying
on this page]` — in place of a contact email, since no public contact
address was available when these were written. Replace it with a real
address before relying on these pages for a platform submission.

## Keeping this repo minimal

This repo is meant to stay small and public-safe: static HTML only, no
build tooling, no analytics or tracking scripts, and no content beyond
what's needed for the two legal pages. Please don't add application
code, internal docs, or credentials here — that belongs in Maestro's
own (private) repository.
