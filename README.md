SHADOW X PANEL - Android phone-only APK build

1. Create a GitHub repository in your browser.
2. Upload the CONTENTS of this folder to the repository root (do not upload the outer folder itself).
3. Keep the .github/workflows/build-apk.yml path exactly as shown.
4. Open the repository Actions tab.
5. Select "Build SHADOW X PANEL APK" and choose Run workflow.
6. When the run succeeds, open it and download the SHADOW-X-PANEL-APK artifact.
7. Extract the downloaded artifact ZIP and install app-debug.apk.

This creates a debug/testing APK, not a Play Store release. The dashboard is a management UI; simulated CPU/RAM/FPS/ping values are not real device telemetry. Firebase must be configured separately if cloud player sync is needed.
