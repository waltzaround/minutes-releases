# Minutes

Private meeting notes that never leave your laptop. Minutes records a meeting, transcribes it, works out who said what and drafts the notes, all on your own computer.

Website: https://minutes.walt.online

This repository only hosts release downloads. Get the latest build from [Releases](https://github.com/waltzaround/minutes-releases/releases/latest).

## Install (macOS 14.6+, Apple Silicon)

1. Download `Minutes_<version>_aarch64.dmg` and drag Minutes to Applications.
2. Preview builds are not yet signed or notarised, so macOS will say the app can't be verified. To open it the first time, run:

   ```bash
   xattr -dr com.apple.quarantine /Applications/Minutes.app
   ```

   or open it once from Finder with right-click → Open, then confirm in System Settings → Privacy & Security.
3. On first launch Minutes checks your computer and downloads the speech and language models it needs (about 3–25 GB).

Windows builds are in testing and not yet published.
