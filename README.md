# FastFlow V1 🥑

GitHub Pages-ready Android PWA for intermittent fasting.

## Features
- 12:12, 14:10, 16:8, 18:6, 20:4 and custom fasting schedules
- Live fasting countdown and progress ring
- Start/end fast
- History, streak and completed-fast count
- Weight tracking, goal weight and chart
- Sleep duration, quality and notes
- Browser notifications for fasting milestones
- Dark mode
- Local device storage
- Offline service worker
- Android PWA install support
- Relative paths for GitHub Pages project sites

## Deploy to GitHub Pages
1. Create a GitHub repository.
2. Upload all files and the `icons` folder.
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**.
5. Select your main branch and `/ (root)`, then Save.
6. Open the HTTPS Pages URL in Chrome on Android.
7. Use Chrome's **Install app** prompt, if shown.

## Important notification limitation
This static GitHub Pages version uses browser notification permission and JavaScript timers. Reliable notifications while the app is completely closed would require a push-notification service/server, so V1 does not pretend otherwise.

## Data
Data is stored locally on the device with LocalStorage. No account or cloud sync is required.

## Health
FastFlow is a tracker, not medical advice. Fasting is not suitable for everyone. Seek qualified medical advice when appropriate.
