# LUCIVARYN

**Illumination That Transforms.**

Dashboard feature: **THE LUCIVARYN WAY**  
Subtitle: *From Revelation to Transformation.*

This is the first working, mobile-first starter for the LUCIVARYN application.

## Included in this starter
- Six stages: RECEIVE → UNDERSTAND → DEVELOP → MULTIPLY → ALIGN → RELEASE
- Workspaces for Revelation Library, Bible Study Centre, Content Studio, Prayer, Seven-Day Series, Calendar, and Reminders
- Create, edit, delete, search, and favorite entries
- Browser-local persistence using localStorage
- JSON export and import backup
- Dated entries and in-app reminder list
- Responsive layout for Android Chrome
- Basic installable PWA manifest and service worker

## Important limitations — not yet implemented
- Email/password and Google authentication are **not active**. No fake login is shown. A real auth provider and configuration are required.
- Data stays in the current browser/device. There is no cross-device cloud sync.
- Reminders are visible in the app but do not trigger push notifications or alarms while it is closed.
- Seven-Day Series currently exists as a workspace category; a dedicated seven-day editor is still to be built.
- No AI writing or live Bible lookup is connected.
- This is a starter, not a completed production release. Back up data regularly.

## Publish using GitHub Pages
1. Upload `index.html`, `manifest.json`, `sw.js`, and `README.md` to the root of the existing private repository.
2. In GitHub repository Settings → Pages, select deployment from the `main` branch and `/ (root)` if that option is available.
3. Save and wait for the deployment link.
4. Open the site in Chrome on Android. Use Chrome's menu and choose **Install app** or **Add to Home screen** if offered.

Note: GitHub Pages availability and deployment settings depend on repository/account settings. Do not make the repository public just to test without deciding that first.

## Data safety
The app saves entries in browser storage. Browser data can be removed by device cleanup or browser settings. Use Export backup and keep the JSON file safe. Import merges by entry ID and replaces entries with matching IDs.
