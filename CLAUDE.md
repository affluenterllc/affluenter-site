This repo is the static site for affluenter.com (GitHub Pages). The Vault pages are edited directly; there is no generator
for them. The `/hoa/` pages come from `website/make_hoa_pages.py` in `affluenter-hoa`: regenerate them there and copy the
output in, don't hand-edit them.

The three TrayShift policy pages (`/trayshift/terms/`, `/trayshift/privacy/`, `/trayshift/licenses/`) are generated from the app's own
texts by `ci/legal_pages.py` in `trayshift-game`: edit the text there and re-run it (full version, no `--policy-only`), don't
hand-edit the page text. The TrayShift landing (`/trayshift/`) and support (`/trayshift/support/`) pages are published since
Nov 23 2026 (needed for AdMob/Play verification); they are edited directly here.
