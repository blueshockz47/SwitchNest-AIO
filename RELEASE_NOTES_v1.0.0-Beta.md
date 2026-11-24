# SwitchNest AIO v1.0.0-Beta

**First public beta — Windows 10/11 (64-bit)**

SwitchNest AIO brings useful Nintendo Switch 2 companion tools together in a portable Windows application. This first beta is for users who would like to test the app and share feedback.

## Features

- **Offline hotspot tools:** Configure and manage a local Windows hotspot with DNS and HTTP services for supported connectivity workflows.
- **FTP Manager:** Browse files on your PC and Switch 2 side by side, transfer files, and use drag-and-drop.
- **Homebrew Manager:** Explore the curated catalog, check supported GitHub releases, download verified NRO assets, and install supported NRO files over FTP.
- **Network monitoring:** View service status, connected-device information, diagnostics, and hotspot settings.
- **Portable app:** Extract and run; no traditional Windows installer is required.

## Downloads

- `SwitchNest-AIO-v1.0.0-Beta.zip` — portable Windows application.
- `SwitchNest-AIO-v1.0.0-Beta-source.zip` — application source, build instructions, and regression tests.
- `SHA256SUMS` — checksums for both ZIP files.

**Note:** The asset names above are the intended published release names. Attach the actual validated files before publishing.

## Getting started

1. Extract the Windows ZIP, open the `SwitchNest` folder, and read `README-FIRST.txt`.
2. Launch `SwitchNest-AIO.exe` normally (not as administrator). Keep `_internal` and `SwitchNest-Service-Helper.exe` together.
3. In **Settings**, set your preferred hotspot **SSID and Wi-Fi password first**, then apply the settings before starting services.
4. In Windows Settings → Network & internet → Mobile hotspot, turn **Power saving Off**.
5. Start the hotspot in SwitchNest AIO and connect your Switch 2 using your configured Wi-Fi credentials.
6. For FTP, start the FTP server on your Switch 2 first, then use **Find Switch IP** in FTP Manager or Homebrew Manager.

## Beta testing and feedback

This is an early release. Please report reproducible bugs through [GitHub Issues](https://github.com/blueshockz47/SwitchNest-AIO/issues), including your Windows version, network adapter, app version, steps to reproduce, and any relevant error messages. Remove IP addresses, passwords, MAC addresses, and other personal details from screenshots and logs.

## Safety and compatibility

Windows Mobile Hotspot and Internet Connection Sharing can still provide internet access even when local DNS/HTTP services are running. **Do not assume your console is isolated**; independently verify isolation using a separate test device before connecting it. Keep Windows Firewall enabled. Back up important files before transferring or installing homebrew.

Homebrew catalog entries are third-party projects. A verified download does not guarantee compatibility or safety.

SwitchNest AIO is an independent community project and is not affiliated with or endorsed by Nintendo.

Thank you for testing and helping improve the project!
