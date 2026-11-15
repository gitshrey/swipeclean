# SwipeClean — Tinder-Style Gallery Cleaner & Space Saver (Android + Web)

SwipeClean lets you declutter your phone's camera roll, WhatsApp media, screenshots, and large 4K videos with fast Tinder-style swipes:
- **Swipe Left (`←`)**: Queue photo/video into the **Trash Queue**
- **Swipe Right (`→`)**: Safely **Keep** photo/video on device
- **Swipe Up (`↑`)**: Mark as **★ Favorite**
- **1-Tap Permanent Storage Purge**: Uses Android's native `MediaStore.createDeleteRequest()` API to permanently erase trashed photos & videos from device flash storage and reclaim gigabytes of space.

## How to Generate the Android APK on GitHub Actions
1. Upload this repository (or just `.github/workflows/build-android.yml` and `index.html`) to a GitHub repository.
2. Go to the **Actions** tab in your GitHub repo and click **Build SwipeClean Android APK** → **Run workflow**.
3. Once completed (~2 minutes), download **SwipeClean-Installable-APK** from the workflow Artifacts and install `app-release.apk` on your Android phone.
