# Power Platform Connect

## Download and Install (v1.0.0)

| OS | Architecture | Download Link |
|----|--------------|---------------|
| **Windows** | x64 | [Download Setup](https://github.com/attosol/attosol-power-platform-connect/releases/download/v1.0.0/Attosol.Power.Platform.Connect.Setup.1.0.0.exe) |
| **macOS** | Apple Silicon (arm64) | [Download DMG](https://github.com/attosol/attosol-power-platform-connect/releases/download/v1.0.0/Attosol.Power.Platform.Connect-1.0.0-arm64.dmg) |
| **macOS** | Intel (x64) | [Download DMG](https://github.com/attosol/attosol-power-platform-connect/releases/download/v1.0.0/Attosol.Power.Platform.Connect-1.0.0.dmg) |
| **Linux** | x64 | [Download AppImage](https://github.com/attosol/attosol-power-platform-connect/releases/download/v1.0.0/Attosol.Power.Platform.Connect-1.0.0.AppImage) |

## Installation Notes & Troubleshooting

### macOS ("App is damaged and can't be opened")
Because this application is not code-signed and notarized by an Apple Developer account, macOS Gatekeeper may flag it as "damaged" when downloaded from the internet. **This is not actual file corruption.** To fix this, open your terminal and remove the quarantine attribute from the downloaded file before opening it:
```bash
xattr -cr ~/Downloads/Attosol.Power.Platform.Connect-*.dmg
```
*(Replace the filename with the exact name of the file you downloaded).*

### Windows ("Windows protected your PC")
Microsoft Defender SmartScreen might warn you that it prevented an unrecognized app from starting. Click on **"More info"** and then select **"Run anyway"** to proceed with the installation.

### Linux
AppImage files must be made executable before they can be run. You can do this by right-clicking the file -> Properties -> Permissions -> "Allow executing file as program", or by running the following command in your terminal:
```bash
chmod +x Attosol.Power.Platform.Connect*.AppImage
```

---
*For any other issues, please open an issue in this repository.*
