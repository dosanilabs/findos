# FinDos — GitHub Pages Website

A static, responsive landing page for FinDos, developed by Shakeel Dosani / Dosani Labs.

## Publish
1. Create a **public** GitHub repository named `findos` in the `dosanilabs` account.
2. Upload the **contents** of this folder (not the ZIP itself) to the repository root.
3. Open **Settings → Pages → Build and deployment** and select **Deploy from a branch**, branch `main`, folder `/(root)`.
4. Visit `https://dosanilabs.github.io/findos/` once GitHub Pages finishes deploying.

## Add the APK download link
When your APK is ready, publish it to **GitHub Releases** or use your trusted APK hosting URL. In `index.html`, find:

`<span class="button button-primary button-disabled" ...>Android download coming soon ...</span>`

Replace the span with an anchor, for example:

`<a class="button button-primary" href="YOUR_ACTUAL_APK_URL" download>Download FinDos for Android ↓</a>`

Remove the nearby “download link will be available” notice and update FAQ wording accordingly.

**Never use a fake Play Store badge or imply the APK is on Google Play if it isn't.**

## Notes
- Screenshots are the actual images supplied for FinDos. They show an empty account state and are labeled accordingly.
- This is a static website: no backend, user analytics, or third-party tracking scripts.
- Google Fonts is used for typography; it may require internet access.
- Keep Android signing keys and private credentials **out of the repository**.


## Android APK download
Official v1.0 APK: https://github.com/dosanilabs/findos/releases/download/v1.0.0/findos1.0.apk
The website download button links directly to this release asset.

## Updated screenshots and app themes

This version includes genuine Android screenshots showing sample balances, transactions, analytics, Udhar, budgets, and the theme settings screen. All screenshots live in `assets/`.

The APK button links to `https://github.com/dosanilabs/findos/releases/download/v1.0.0/findos1.0.apk`.
