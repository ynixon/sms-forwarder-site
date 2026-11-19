# SMS Forwarder site / אתר מעביר SMS

Static GitHub Pages site for the private Android app **SMS Forwarder** (מעביר SMS, repository `ynixon/sms-forwarder`, package `com.ynixon.smsforwarder`). It exists so the app's Google OAuth consent screen has a public home page and privacy policy.

**סיכום בעברית:** אתר סטטי (GitHub Pages) עם דף בית ומדיניות פרטיות עבור אפליקציית מעביר SMS.

* Live site: https://ynixon.github.io/sms-forwarder-site/ (served from the `main` branch, root folder)
* `index.html` — home page (Hebrew and English): what the app does and its privacy summary
* `privacy.html` — privacy policy
* `style.css` — shared styles
* `.nojekyll` — tells GitHub Pages to publish the files as they are

## Editing and publishing

There is no build step. Edit the HTML/CSS files and push to `main`; GitHub Pages republishes automatically. Keep the text consistent with what the app actually does (see the app's README). Do not add secrets, tokens or personal data: this repository and the site are public.

## Limitations

The pages are static text only. If the app's permissions, scopes or data handling change, update both pages by hand.
