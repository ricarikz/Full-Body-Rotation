FULL BODY ROTATION — VERSION 2

This update reuses the original Full Body Rotation project and GitHub Pages structure.

UPLOAD TO EXISTING GITHUB REPOSITORY
1. Open your existing Full-Body-Rotation repository.
2. Select Add file > Upload files.
3. Upload all seven files in this folder into the repository ROOT (not a nested folder).
4. GitHub should show replacements for existing filenames; commit changes to main.
5. Wait for GitHub Pages deployment, then refresh the existing app. If an old cached version persists, close the app and reload the website in Samsung Internet, or clear only the site's cached files (not site data).

DATA
The new app uses localStorage key fullBodyRotationV2 and starts with no sessions or measurements. The previous app used fullBodyRotationV1. Old records remain separately in browser storage but are not imported. Version 2 updates preserve version 2 data unless you explicitly reset, restore a backup, or clear browser/site data.

Export a JSON backup from Settings regularly. The restore function accepts version 2 backups only. Data does not automatically sync between browsers/devices.

TRACKING
Each exercise shows the prescribed set count and rep target. Enter weight (0 for bodyweight), reps or seconds per side, and mark completed sets. Completed sets are saved with the workout. Previous results appear for the same exercise on the same workout day.

Charts use recorded measurements and sets, and can be filtered to last 30 days, 90 days, or all time. The volume metric uses external weight × reps, so bodyweight-only exercises show 0 external-load volume.

The app uses a service worker for offline-friendly operation after initial loading. GitHub Pages must be served over HTTPS for service-worker installation.
