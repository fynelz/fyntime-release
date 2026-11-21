# FynTime Keeper — Official Releases, Checksums & Documentation

**FynTime™** ([www.fyntime.com](https://www.fyntime.com)) is a parental control and family safety platform for **Windows 10 & Windows 11 PCs**, **Macs**, and **mobile devices**, built by [FynEtiq LLC](https://www.fynetiq.com).

It helps parents and kids agree on daily screen time budgets, shared gaming pools (across Roblox, Minecraft, Fortnite, and Steam), bedtime curfews, and safe web browsing across Google Chrome and Microsoft Edge.

FynTime works as a **companion for Microsoft Family Safety** (preventing tampering and fixing browser/app gaps) or as a **complete replacement** on standard local Windows user accounts.

---

## Official Links

- **Website**: [https://www.fyntime.com](https://www.fyntime.com)
- **Windows 10 & 11 Protection Overview**: [https://www.fyntime.com/windows](https://www.fyntime.com/windows)
- **Windows Installer Downloads**: [https://www.fyntime.com/downloads](https://www.fyntime.com/downloads)
- **Android Parent App (Google Play)**: [FynTime Keeper: Family Safety](https://play.google.com/store/apps/details?id=com.fyntime.keeper.parent)
- **Parent Setup & Troubleshooting Guides**: [https://www.fyntime.com/guides](https://www.fyntime.com/guides)
- **Frequently Asked Questions**: [https://www.fyntime.com/faq](https://www.fyntime.com/faq)
- **Transparency & Data Minimization Policy**: [https://www.fyntime.com/what-it-does](https://www.fyntime.com/what-it-does)
- **Privacy Policy**: [https://www.fyntime.com/privacy](https://www.fyntime.com/privacy)

---

## Latest Production Release: `v1.0.16` (Windows 10 & 11, macOS)

All official installers are served from `https://dl.fyntime.com/` and can be verified against the SHA-256 checksums below:

| Package | Platform | Download URL | SHA-256 Checksum |
| :--- | :--- | :--- | :--- |
| `FynTimeSetup-1.0.16+a96021e.exe` | Windows 64-bit (`x64`) | [Download EXE](https://dl.fyntime.com/ftlxq/FynTimeSetup-1.0.16+a96021e.exe) | `a96021edf479c3ba003fdd94b4a5233326e70d444937dd57e08df6a02e9a2245` |
| `FynTimeSetup-1.0.16+2f5b515-arm64.exe` | Windows ARM64 (`arm64`) | [Download ARM64 EXE](https://dl.fyntime.com/ftlxq/FynTimeSetup-1.0.16+2f5b515-arm64.exe) | `2f5b5150a0e6ceb7b3022503e97699464508f8508768e99bb0cf2f423d3f1968` |
| `FynTimeSetup-1.0.16+6dc4236-macos.pkg` | macOS | [Download PKG](https://dl.fyntime.com/ftlxq/FynTimeSetup-1.0.16+6dc4236-macos.pkg) | `6dc4236ba1c6d9cffd36b0d7043f6c4d760b1a01134d580589042fee6f0ae224` |

### Verify Checksum

PowerShell (Windows):

```powershell
Get-FileHash .\FynTimeSetup-1.0.16+a96021e.exe -Algorithm SHA256
```

Terminal (macOS):

```bash
shasum -a 256 FynTimeSetup-1.0.16+6dc4236-macos.pkg
```

---

## FynTime Keeper vs. Microsoft Family Safety

| Capability | Microsoft Family Safety | FynTime Keeper |
| :--- | :--- | :--- |
| **Browser Filtering** | Microsoft Edge only (forces blocking Chrome) | Enforces domain limits and safe search across **Chrome & Edge** |
| **Gaming Budgets** | Separate per-app timers (kids hop between games) | **Shared App Groups** pool Roblox, Minecraft & Steam into one budget |
| **Tamper Resistance** | Single `WpcMonSvc` service | Dual interlocking LocalSystem services (`Keeper MR` & `Keeper RS`) |
| **Offline Enforcement** | Requires cloud sync to lock or update | **100% offline encrypted local cache** |
| **Countdown Warnings** | Sudden screen lock mid-game | Polite **15, 10, 5, 2, and 1-minute warnings** + 1-click bonus time request |
| **Windows Account Type** | Requires cloud Microsoft child account | Works with **local standard Windows accounts** or Microsoft accounts |
| **Privacy & Trust** | Extensive cloud activity telemetry | Visible tray icon, **zero keystroke logging**, **zero screenshots**, domain-only web logs |

---

## Parent Guides & Troubleshooting

1. [Microsoft Family Safety Screen Time Not Working on Windows 11? Causes & Permanent Fix](https://www.fyntime.com/guides/microsoft-family-safety-screen-time-not-working)
2. [How to Filter Chrome, Edge & Alternate Browsers on a Child Windows PC](https://www.fyntime.com/guides/block-chrome-brave-browsers-microsoft-family-safety)
3. [How to Set One Shared Daily Gaming Limit Across Roblox, Minecraft & Steam on Windows](https://www.fyntime.com/guides/shared-gaming-time-limit-roblox-minecraft-steam)
4. [How Kids Bypass Windows Parental Controls (Task Manager & Clock Tricks) & How to Stop It](https://www.fyntime.com/guides/stop-task-manager-clock-bypass-windows-parental-controls)
5. [Best Microsoft Family Safety Alternatives for Windows 10 & 11 PCs (2026 Comparison)](https://www.fyntime.com/guides/microsoft-family-safety-alternatives-windows)

---

© 2026 [FynEtiq LLC](https://www.fynetiq.com). All rights reserved.
