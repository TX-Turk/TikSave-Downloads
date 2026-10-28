# TikSave downloads

Windows installers and setup notes for TikSave. This repository contains distribution files only; it does not contain application source or development history.

## Windows 1.4.2

[Download TikSave for Windows](https://github.com/TX-Turk/TikSave-Downloads/releases/download/v1.4.2/TikSave-1.4.2-Windows-x64-Setup.exe)

Requires 64-bit Intel/AMD Windows 10 version 2004 or later, or Windows 11. Close TikSave and run the installer over your existing version; settings, history and saved files stay in place. On first installation, open **TikSave → Settings → Install media tools**. Initial media-tool setup downloads roughly 255 MB from upstream publishers and requires internet. .NET is included. The installer is unsigned; Windows may show an unknown-publisher or SmartScreen notice.

Version 1.4.2 improves sports and web-video inspection, including shared Veo Follow Cam recordings, source codec verification, higher-quality renditions and separate audio. It includes the previous precise-clip repair. Private Veo recordings need official Veo access/export; TikSave does not import another browser’s sign-in. Extractor coverage does not guarantee every site or subscription. Live sports transfers were verified on Mac; Windows account-specific sports transfers remain unverified.

TikSave includes link downloads, standalone single/batch media conversion, audio extraction, trimming, output settings, a persistent queue and conditional F1 TV account integration. F1 TV requires your own authorized account and an available unprotected replay. Live F1 login/race/clip behavior on Windows has not been verified. Protected NBA League Pass full-game downloads are unavailable. Previews depend on the codecs installed on your PC.

The release passed 139 Windows core/media checks and installer install/upgrade from 1.4.1/launch/navigation/light-dark/uninstall checks with history/settings/media preservation on a hosted Windows runner. Physical-PC accessibility and the complete Windows 10/11 compatibility matrix remain unverified.

The release includes a checksum and setup instructions. Verify the EXE in PowerShell with:

```powershell
Get-FileHash .\TikSave-1.4.2-Windows-x64-Setup.exe -Algorithm SHA256
```

Expected SHA-256: `d477796f31491d58f1105089cb634911ee8053a937869b320ef73ce6d376b9e1`.

TikSave's license and redistributed dependency notices are included in the installer. Media tools are downloaded separately and use their own licenses. No personal account credentials, media or queue data are distributed. Save only content you have permission to download.
