ALDER GROVE SCHOOL — FREE APP SETUP (iPad guide)

WHAT THIS DOES
This adds basic Progressive Web App support to the existing GitHub Pages website.
Families can add the website to their phone home screen. Android browsers can use the
manifest and service worker; iPhone users can add it through Safari. This does not publish
a native app to Apple App Store or Google Play, and it does not provide push notifications
or secure parent logins.

STEP 1 — DOWNLOAD AND EXTRACT
1. Download alder_grove_free_app_files.zip.
2. On your iPad, open Files > Downloads and tap the ZIP to extract it.

STEP 2 — UPLOAD THE FIVE FILES TO GITHUB
1. Open https://github.com/gtj24fryc6-del/alder-grove-school
2. Open the repository's main Code page.
3. Tap Add file > Upload files (if Add file is hidden on iPad, use Safari's aA menu > Request Desktop Website).
4. Upload these files to the repository ROOT, alongside index.html and style.css:
   - manifest.webmanifest
   - service-worker.js
   - app-icon-192.png
   - app-icon-512.png
   - apple-touch-icon.png
5. Commit the changes to the main branch.

STEP 3 — EDIT index.html
1. In the repository, tap index.html.
2. Tap the pencil/Edit icon.
3. Find the opening <head> and closing </head>. Add the HEAD lines from
   PWA_CODE_TO_ADD_TO_INDEX.txt somewhere between them.
4. Find the closing </body> near the bottom. Paste the SCRIPT from
   PWA_CODE_TO_ADD_TO_INDEX.txt immediately before </body>.
5. Save/commit the change to main.

STEP 4 — WAIT FOR PUBLISHING
Wait 1–3 minutes, then open:
https://gtj24fryc6-del.github.io/alder-grove-school/
Refresh the page if needed. GitHub Pages publishes static files from the configured branch.

STEP 5 — ADD TO IPHONE
On the iPhone, open the site in Safari:
https://gtj24fryc6-del.github.io/alder-grove-school/
Tap Share > Add to Home Screen. Leave "Open as Web App" on if shown, then tap Add.

STEP 6 — ADD TO ANDROID
On Android, open the same URL in Chrome. Tap the three-dot menu and choose Install app
or Add to Home screen, then follow the prompts.

TESTING AND LIMITATIONS
- The app icon in this pack is a temporary green Alder Grove-inspired icon. Replace it with
  a proper square version of the school's official logo when available.
- Basic offline caching is included, but it is not a guarantee that every page will work offline.
- This is a public website/app. Do not add pupil names, medical details, EHCP information,
  private messages, or other confidential records to public files.
- This does not provide push notifications, accounts, databases, attendance systems, or App Store
  / Google Play publication.
- Before using it as the school's official app, verify all school details, safeguarding contacts,
  policies, privacy notices and legal requirements.
