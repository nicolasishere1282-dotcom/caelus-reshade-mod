# XCS - Xyxy's Caelus Shaders

**One-click ReShade shader installer for Caelus / Aisaka Player (2020 Roblox)**

![XCS Banner](https://raw.githubusercontent.com/nicolasishere1282-dotcom/caelus-reshade-mod/main/CaelusShaderDistro/XCS_Icon.png)

XCS automatically installs ReShade and 41 shader packs into your Caelus/Aisaka folder. No manual ReShade setup, no config tweaking - run the installer, launch the game, press F10.

---

## Installation

1. Go to **[Releases](https://github.com/nicolasishere1282-dotcom/caelus-reshade-mod/releases)**
2. Download the latest `XCS_vX.X.zip`
3. Extract the zip anywhere
4. Run **`XCS_Installer.exe`**
5. Click **INSTALL SHADERS**
6. Launch Caelus / Aisaka, press **F10** to open the ReShade overlay

The installer automatically detects your Caelus folder. If it can't, use Browse to navigate to it.

**Requirements:** Caelus: Aisaka installed, Windows 10/11

## Uninstall

Open `XCS_Installer.exe` again, select your Caelus folder, click **UNINSTALL**. Your settings are backed up automatically.

## Features

- **41 shader packs** (Barbatos, qUINT, AstrayFX, GShade, CShade, ZenteonFX, and many more)
- **Custom red UI theme** - the F10 menu is styled with red buttons/sliders to match XCS branding
- **Auto-updates** - the app checks GitHub Releases and shows a yellow banner when a new version drops
- **Smart installer** - backs up existing files, fixes config paths automatically
- **One-click uninstall** - removes everything, keeps your backups safe
- **Roblox-style UI** - rounded corners, custom title bar, Comic Sans vibes
- **Download counter** in the footer bar so you can see how many people are using it

## Theme Changer

Press **F10 > Settings (gear icon) > Style dropdown** to switch between:

- **Custom** (default) - dark red theme
- **Light** - white/light
- **Dark** - dark blue

## Building from Source

You need the .NET Framework 4.x compiler (built into Windows).

```
cd CaelusShaderInstaller
C:\Windows\Microsoft.NET\Framework\v4.0.30319\csc.exe /target:winexe /out:XCS_Installer.exe /reference:System.Windows.Forms.dll /reference:System.Drawing.dll /reference:System.dll Program.cs /win32icon:XCS_Icon.ico
```

## Credits

- [ReShade](https://reshade.me) - The post-processing framework that makes this possible
- All the shader developers whose work is included in this package

---

*Not affiliated with Caelus, Aisaka, or Roblox Corporation.*
