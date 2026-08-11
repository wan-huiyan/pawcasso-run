# pawcasso.run — the legal pages

The privacy policy and support page for **Pawcasso Run**, served by GitHub Pages.

- <https://pawcasso.run/privacy-policy.html>
- <https://pawcasso.run/support.html>

## These files are GENERATED. Do not edit them here.

Their source of truth is `docs/legal/privacy-policy.md` and
`docs/legal/support.md` in the app's own (private) repository. The HTML is built
from that markdown by `scripts/render_privacy_pages.py`, and a test there fails
if the two drift apart.

**Two copies of a legal document drift, and the copy that drifts is the one the
public reads** — which is the whole reason that test exists. Editing the HTML in
this repository would create exactly that split, silently: the app's repository
would go on describing behaviour this page contradicts.

To change either page: edit the markdown in the app repository, re-run the
renderer there, and copy the regenerated HTML here.

Both pages are self-contained — no CDN, no external font, no JavaScript, no
analytics, no cookies. That is deliberate: every third party these pages touch
would be a recipient the privacy policy has to name.
