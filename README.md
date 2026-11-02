# Hatch — downloads

Installers for **Hatch**, an open, end-to-end encrypted remote desktop. Get the latest from **[Releases](../../releases/latest)**.

| You're on | Download |
|---|---|
| Windows (most PCs) | `Hatch-Setup-<version>-x64.exe` |
| Windows on ARM (Surface Pro X, Snapdragon laptops) | `Hatch-Setup-<version>-arm64.exe` |
| Mac with Apple silicon | `Hatch-<version>-mac-arm64.dmg` |
| Intel Mac | `Hatch-<version>-mac-x64.dmg` |
| Linux | `Hatch-<version>-linux-x86_64.AppImage` |

**About the warnings.** The installers aren't code-signed, because signing certificates cost money.
- **Windows:** SmartScreen will warn. Click **More info › Run anyway**.
- **macOS:** open the app once, then go to System Settings › Privacy & Security and click **Open Anyway**. (Hatch 0.5.0 downloads from a browser may be reported as "damaged"; run `xattr -dr com.apple.quarantine /Applications/Hatch.app` once, or use 0.5.1 and later.)

**Updates.** On Windows and Linux, Hatch updates itself from this page with one click, under **Settings › About**. On macOS, Hatch tells you when a new version is out.

The `latest*.yml` files are the update feed the app reads. You don't need to download them.
