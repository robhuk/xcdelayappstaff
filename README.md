# Overtime / Train Delay PWA

Complete PWA files for https://robhuk.github.io/xcdelayappstaff/

## Publish to GitHub Pages
Upload the contents of this folder (including `icons/`) to the root of `robhuk/xcdelayappstaff` and commit to the branch configured for GitHub Pages. Keep the `/xcdelayappstaff/` path unchanged.

Features: responsive staff report form, date defaults to today, headcode format validation, 0–999 whole-minute delay, Other reason text field, revised book-off time calculation, email draft generation, clipboard copy, local auto-save, manifest, Option 2 app icons and offline service worker.

Email subject: `Late book off from HEADCODE DD/MM/YY`
Email body: `Hello, due to the late running of HEADCODE due to REASON please book me off at NEW-BOOK OFF With a delay of XX minutes`

The recipient remains blank for the user to select. Form data stays in the browser's local storage; it is not uploaded to a server.

## Install
iPhone/iPad: open the published site in Safari → Share → Add to Home Screen.
Android/desktop Chromium: use the browser's Install app option when available.
Open the site once online first so its files can be cached for offline launch.
