This repo is the static site for affluenter.com (GitHub Pages). The Vault pages are edited directly; there is no generator
for them. The `/hoa/` pages come from `website/make_hoa_pages.py` in `affluenter-hoa`: regenerate them there and copy the
output in, don't hand-edit them.

The three TrayShift policy pages (`/trayshift/terms/`, `/trayshift/privacy/`, `/trayshift/licenses/`) are generated from the app's own
texts by `ci/legal_pages.py` in `trayshift-game`: edit the text there and re-run it, don't hand-edit the page text. On `main` they
are the `--policy-only` version (no links to the unpublished TrayShift landing and support pages) until launch.
