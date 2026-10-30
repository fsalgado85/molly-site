# Molly code updates

Molly.app checks `latest.json` here and installs newer code by itself (sha256-checked).
Files are written by `app/scripts/release.mjs` in the molly-desktop repo. Each zip contains app code only:
no settings, keys, tokens, personal data, native binaries or voice models.
