# Aurevia Studio

Aurevia Studio is a desktop app for AI-powered video creation on macOS and Windows.

## Download

Get the newest version from the **[latest release](https://github.com/byalitariq/Aurevia-Releases/releases/latest)**.

| Platform | File | Notes |
|---|---|---|
| macOS (Apple Silicon: M1/M2/M3/M4) | `Aurevia-macOS-arm64-<version>.zip` | [Latest release](https://github.com/byalitariq/Aurevia-Releases/releases/latest) |
| macOS (Intel) | `Aurevia-macOS-x86_64-<version>.zip` | [Latest release](https://github.com/byalitariq/Aurevia-Releases/releases/latest) |
| Windows (installer) | `Aurevia-Windows-Setup-<version>.exe` | [Latest release](https://github.com/byalitariq/Aurevia-Releases/releases/latest) |
| Windows (portable) | `Aurevia-Windows-Portable-<version>.zip` | [Latest release](https://github.com/byalitariq/Aurevia-Releases/releases/latest) |
| Checksums | `SHA256SUMS` | [Latest release](https://github.com/byalitariq/Aurevia-Releases/releases/latest) |

## Install

### macOS

1. Pick the right zip:
   - **Apple Silicon** (M1, M2, M3, M4): `arm64`
   - **Intel**: `x86_64`
   - Not sure? Apple menu > About This Mac. "Chip: Apple M…" means arm64; "Processor: Intel…" means x86_64.
2. Unzip it and move `Aurevia.app` to your Applications folder.
3. On first launch macOS Gatekeeper may block the app. Either:
   - Right-click (or Control-click) `Aurevia.app` > **Open**, then click **Open** again, or
   - Try to open it once, then go to **System Settings > Privacy & Security** and click **Open Anyway**.

### Windows

1. Run `Aurevia-Windows-Setup-<version>.exe`, or unzip the Portable zip and run `Aurevia.exe`.
2. If Windows SmartScreen shows "Windows protected your PC", click **More info** > **Run anyway**.

## Verify your download

Each release includes a `SHA256SUMS` file. Download it into the same folder as your file, then compare.

macOS (Terminal):

```sh
shasum -a 256 -c SHA256SUMS --ignore-missing
```

Windows (PowerShell):

```powershell
Get-FileHash .\Aurevia-Windows-Setup-<version>.exe -Algorithm SHA256
```

Check that the printed hash matches the line for that file in `SHA256SUMS`. If it doesn't match, don't run the file; download it again.

## Problems?

Open an issue in this repository's [Issues](https://github.com/byalitariq/Aurevia-Releases/issues) tab.
