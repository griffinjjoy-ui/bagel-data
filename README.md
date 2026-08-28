# bagel-data

Published sports-data modules for the Bagel college tennis app. Generated
weekly by the app's data pipeline; served to the app via GitHub Pages.
Plain published sports data (rankings, schedules, results) — no personal
data of any kind. The app fetches `v1/manifest.json` at launch and pulls
changed modules; a missing or unreachable copy just means the app uses the
data baked into that build.
