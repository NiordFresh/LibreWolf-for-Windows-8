<img width="128" height="128" alt="librewolf" src="https://github.com/user-attachments/assets/407f38a9-8d71-4ad5-88b5-d781cf8b7f3b" />

# LibreWolf for Windows 8+

LibreWolf is a privacy-focused web browser based on Firefox, designed to enhance security and eliminate telemetry and data collection. It is free and open-source, providing users with a hardened browsing experience out of the box without requiring additional configuration.

LibreWolf is not officially supported on older operating systems such as Windows 8/8.1, as it follows upstream Firefox requirements. The last Firefox ESR versions compatible with Windows 8/8.1 limit official support for newer LibreWolf releases. This repository provides a newer, patched version of LibreWolf, enabling it to run on Windows 8+, so users can continue receiving updated features and important security fixes.

<img width="1280" height="768" alt="banner" src="https://github.com/user-attachments/assets/4a529ca9-11dd-4ce0-afb4-ea346730b438" />
<hr>

# Compatibility

| Version | Windows 8.1 | Windows 8 | Windows 7 (with VxKex) | Windows 7 | Installer [.exe] | Portable [.7z] | Portable [.zip] |
| ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- | ------------- |
| STD153.0.4-1 | ✅ | ⚠️* | ❓ | ❌ | [Download](https://github.com/NiordFresh/LibreWolf-for-Windows-8/releases/download/STD153.0.4-1/librewolf_STD153.0.4-1_win8_installer-NFX.exe) | [Download](https://github.com/NiordFresh/LibreWolf-for-Windows-8/releases/download/STD153.0.4-1/librewolf_STD153.0.4-1_win8_portable-NFX.7z) | [Download](https://github.com/NiordFresh/LibreWolf-for-Windows-8/releases/download/STD153.0.4-1/librewolf_STD153.0.4-1_win8_portable-NFX.zip) |
| STD150.0-1 | ✅ | ⚠️* | ❓ | ❌ | N/A | [Download](https://github.com/NiordFresh/LibreWolf-for-Windows-8/releases/download/STD150.0-1/librewolf_STD150.0-1_win8_portable-NFX.7z) | [Download](https://github.com/NiordFresh/LibreWolf-for-Windows-8/releases/download/STD150.0-1/librewolf_STD150.0-1_win8_portable-NFX.zip)|

<hr>

> *Technically possible by adding "MOZ_DISABLE_CONTENT_SANDBOX=1", however, it requires additional "api-ms-win-shcore-scaling-l1-1-1.dll" ripped from W8.1 in order to run...

> k64.dll wrapper used is created by [EAZY BLACK](https://git.chefkiss.dev/WinRevived/Wrappers/releases/tag/v1.0.0).

# Not satisfied? Check out my other ports:
- [Mullvad Browser for Windows 8+](https://github.com/NiordFresh/MullvadBrowser-for-Windows-8) - Privacy-focused web browser developed to minimize fingerprinting.
- [Tor Browser for Windows 8+](https://github.com/NiordFresh/TorBrowser-for-Windows-8) - Free, open-source web browser designed to protect user privacy and anonymity.
- [LibreWolf for Windows 8+](https://github.com/NiordFresh/LibreWolf-for-Windows-8) - Privacy-focused web browser based on Firefox, designed to enhance security.
- [Zen Browser for Windows 8+](https://github.com/NiordFresh/ZenBrowser-for-Windows-8) - Modern web browser based on the Firefox engine, designed with a focus on simplicity.

> © Powered by NiordFresh. 
