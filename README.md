# site-previews

Temporary previews of proposed client-site changes, published by the portal
support-ticket runner (`trulyempoweredcode/ai-editor` -> `.github/workflows/ticket-drafting.yml`).

- Layout: `/{domain}/ticket-{ticket_id}/` served at
  `https://trulyempoweredcode.github.io/site-previews/{domain}/ticket-{ticket_id}/`
- Purpose: let Rick SEE a proposed change rendered, before merging the PR that
  would publish it to the client's live site.
- Nothing here is live. Safe to delete any folder at any time.
- `noindex` on the landing page and `.nojekyll` so paths are served verbatim.
