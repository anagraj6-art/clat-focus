CLAT FOCUS — personal CLAT study timer

FILES
- index.html: app
- manifest.webmanifest: installable app settings
- sw.js: offline cache
- icon.svg: app icon

IMPORTANT
For the browser to offer a proper "Install app" / "Add to Home screen" PWA experience, host these files on an HTTPS static site. Opening index.html directly is fine for testing, but service workers and full PWA installation require HTTPS (or localhost).

EASY TABLET INSTALL
1. Upload the four files to a static HTTPS host (for example, a private GitHub Pages repository/site or another static host).
2. Open the hosted index.html in Chrome on the Galaxy Tab S6 Lite.
3. Open Chrome menu (⋮) and choose "Install app" or "Add to Home screen".
4. Launch CLAT FOCUS from the home screen.

The timer and study totals are stored locally in the browser on that tablet. Clearing browser site data will erase them. The app does not send study data anywhere.

DEFAULTS
- Focus: 50 minutes
- Break: 10 minutes
- Daily target: 240 minutes
- Subjects: English, Current Affairs & GK, Legal Reasoning, Logical Reasoning, Quantitative Techniques


YOUTUBE STUDY MODE
- The app now has a YouTube Study Mode panel.
- Add trusted YouTube lecture URLs and open them from the saved list.
- This is a study-link launcher, not an Android app blocker.
- For app-level blocking, configure Samsung Digital Wellbeing Focus mode to pause YouTube during study. Keep Chrome available if you plan to open lecture links in the browser.
