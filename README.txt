RUN GAME COORDINATOR — iPad PWA v1

FILES
- index.html: app
- manifest.json: installable web-app metadata
- sw.js: offline cache
- icon.svg: app icon

IMPORTANT
An iPad cannot permanently install this from a ZIP/file URL as a PWA. Put these files on any HTTPS static web host first.
Then on iPad:
1. Open the hosted URL in Safari.
2. Tap Share.
3. Tap Add to Home Screen.
4. Open Coordinator from the new Home Screen icon.
5. Open it once while online so the offline cache is installed.

The app stores game plans and charted snaps locally on that iPad using browser storage.
