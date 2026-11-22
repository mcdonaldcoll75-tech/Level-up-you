# LEVEL UP — Phone app setup

LEVEL UP is a Progressive Web App (PWA). It can be added to an iPhone or Android home screen and has an offline app shell.

## Important
A PWA must be served from a secure HTTPS website to install and use service-worker offline caching. Opening `index.html` directly from Files is useful for previewing, but **will not install it as a proper app**.

## Easiest free publishing route: GitHub Pages
1. Sign in to GitHub (ask a parent/guardian to help with account setup if needed).
2. Create a new repository, e.g. `level-up-app`.
3. Upload every item in this folder, keeping the `icons` folder and its two PNG files.
4. In the repository, open **Settings → Pages**.
5. Under Build and deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish the site. Open the HTTPS URL it gives you.

## Add to iPhone
1. Open the published HTTPS link in **Safari**.
2. Tap the Share button.
3. Choose **Add to Home Screen**.
4. Enable **Open as Web App** if shown, then tap **Add**.

## Add to Android
Open the HTTPS link in Chrome, tap the menu, then choose **Install app** or **Add to Home screen**.

## What works
- The app's local progress, training, food ideas, study cards, outfit planner, reflections, business idea notes, virtual portfolio, weekly planner, goals and focus timer.
- Offline loading after the app has been opened online once and the service worker has installed.
- Export/import backup from the Progress centre.

## Limitations
- Progress is stored in that browser on that device. It does not automatically sync between devices.
- The AI assistant opens ChatGPT with a prepared prompt; it is not an embedded ChatGPT account connection.
- Market research opens external research sites. There is no guaranteed live stock-price feed and the portfolio is practice-only.
- Do not enter passwords, private financial information or sensitive personal details.
