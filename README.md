# ViralBoost AI — Android starter

A simple offline-first starter app for planning TikTok content. It includes:
- Caption templates in English and Mexican Spanish
- Quick video hooks
- A content planner
- A manual video performance tracker

This starter does **not** connect to TikTok, use a live AI service, auto-post, or guarantee viral reach. The content generator uses built-in templates. User entries are stored locally on the device.

## Build an APK using GitHub from your phone

1. Create a new **public** GitHub repository named `ViralBoostAI` (public is easiest for the included workflow).
2. Upload the contents of this project ZIP into the repository root. Make sure `.github/workflows/build-apk.yml` is included; GitHub mobile may hide dot-folders, so use the browser in desktop mode if needed.
3. Open the repository's **Actions** tab.
4. Select **Build ViralBoost AI APK**. If asked, enable Actions. Tap **Run workflow** if the workflow has not run automatically.
5. Wait for the workflow to finish successfully.
6. Open the completed workflow run, find **Artifacts**, and download `ViralBoostAI-debug-apk`.
7. Extract the ZIP artifact to get `app-debug.apk`. Tap the APK to install it. Android may ask you to allow your browser or file manager to install unknown apps; only allow this for the APK you built from your own repository, then turn the permission off afterward.

## Notes
- This is a debug APK for personal testing, not a Play Store release.
- The app is built from a local HTML interface inside a minimal Android WebView wrapper.
- Do not add secrets or API keys to a public repository.
