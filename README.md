# Qimma Habits — Android APK project

This project wraps the supplied `Habits.html` in a lightweight Android WebView app.

## Build a free personal APK with GitHub Actions

1. Create a private repository on GitHub.
2. Upload the contents of this folder to the repository (keep the `.github` folder).
3. Open the repository's **Actions** tab and enable Actions if prompted.
4. Run **Build Qimma Habits APK** using **Run workflow**, or push to the `main` branch.
5. When the workflow finishes, open its run and download the `Qimma-Habits-APK` artifact.
6. Extract the downloaded ZIP and install `app-debug.apk` on your Android phone.

The app loads the HTML locally. Its habit data uses browser `localStorage`, with DOM storage enabled in WebView. Keep regular backups from the app's own backup feature. The Google Fonts stylesheet in the original HTML requires internet to load those fonts; the app itself and its local HTML do not require a hosted website.

Package: `com.qimma.habits`
App label: `Qimma Habits`
Minimum Android: 6.0 (API 23)
