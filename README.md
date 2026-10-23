# TikSave downloads

Windows installers and setup notes for TikSave. This repository contains distribution files only; it does not contain application source or development history.

## Windows 1.4.0

[Download TikSave for Windows](https://github.com/TX-Turk/TikSave-Downloads/releases/download/v1.4.0/TikSave-1.4.0-Windows-x64-Setup.exe)

Requires 64-bit Intel/AMD Windows 10 version 2004 or later, or Windows 11. Run the installer, then open **TikSave → Settings → Install media tools**. Initial media-tool setup downloads roughly 255 MB from upstream publishers and requires internet. .NET is included. The installer is unsigned; Windows may show an unknown-publisher or SmartScreen notice.

TikSave includes link downloads, standalone single/batch media conversion, audio extraction, trimming, output settings, a persistent queue and conditional F1 TV account integration. F1 TV requires your own authorized account and an available unprotected replay. Live F1 login/race/clip behavior on Windows has not been verified. Protected NBA League Pass full-game downloads are unavailable. Previews depend on the codecs installed on your PC.

The release passed 73 Windows core/media checks and installer install/upgrade/launch/navigation/light-dark/uninstall checks on a hosted Windows runner. Physical-PC accessibility and the complete Windows 10/11 compatibility matrix remain unverified.

The release includes a checksum and setup instructions. Verify the EXE in PowerShell with:

```powershell
Get-FileHash .\TikSave-1.4.0-Windows-x64-Setup.exe -Algorithm SHA256
```

Expected SHA-256: `f1e9571e3f4b27f51855ccdf93d54c6de1d13b34221843bf48b2d411bdfeab95`.

TikSave's license and redistributed dependency notices are included in the installer. Media tools are downloaded separately and use their own licenses. No personal account credentials, media or queue data are distributed. Save only content you have permission to download.
