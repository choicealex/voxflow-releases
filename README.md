# VoxFlow releases

Downloads for **VoxFlow**, a free macOS app for AI voiceovers on your videos. Write a script, pick a voice from local engines (Piper, Kokoro, Qwen), line it up on your video's timeline and export the finished video. Everything runs on your Mac: no cloud, no account, no per-character credits.

This repository only hosts the installers. Grab the latest `.dmg` from **[Releases](../../releases/latest)**.

## Requirements

- macOS 13 or later
- Apple Silicon (M1 or later)

## Installing

1. Open the downloaded `.dmg` and drag **VoxFlow** to **Applications**.
2. VoxFlow isn't notarized by Apple yet, so macOS blocks it on first launch. Open it once, then go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway**, then confirm. (Right-click → Open no longer bypasses this on current macOS.)
3. If macOS says the app is "damaged", run this in Terminal:

   ```
   xattr -dr com.apple.quarantine /Applications/VoxFlow.app
   ```
