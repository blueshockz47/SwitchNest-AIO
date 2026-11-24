# SwitchNest AIO v1.0.0-Beta

**First Public Beta · Windows 10/11 (64-bit) · Portable**

SwitchNest AIO is a Windows companion application that brings hotspot management, FTP file transfers, homebrew discovery, and network diagnostics into one interface. This is our first public beta release, and we welcome testing and feedback.

## ⬇️ Download for Windows

### **[Download SwitchNest AIO v1.0.0-Beta](https://github.com/blueshockz47/SwitchNest-AIO/releases/download/v1.0.0-Beta/SwitchNest-AIO-v1.0.0-Beta.zip)**

**Most users should download the Windows ZIP above.** No installer is required: extract the archive and launch `SwitchNest-AIO.exe` from the `SwitchNest` folder.

| Download | Description |
| --- | --- |
| **[Windows portable ZIP](https://github.com/blueshockz47/SwitchNest-AIO/releases/download/v1.0.0-Beta/SwitchNest-AIO-v1.0.0-Beta.zip)** | Ready-to-run Windows application — recommended for most users |
| [Source ZIP](https://github.com/blueshockz47/SwitchNest-AIO/releases/download/v1.0.0-Beta/SwitchNest-AIO-source.zip) | Application source, build instructions, and tests for developers |
| [SHA-256 checksums](https://github.com/blueshockz47/SwitchNest-AIO/releases/download/v1.0.0-Beta/SHA256SUMS) | Verify the integrity of the two uploaded ZIP files |

**Note:** GitHub's automatically generated `Source code (zip)` and `Source code (tar.gz)` files are snapshots of this repository, not the Windows application. Use the separately uploaded source ZIP if you want the application source.

## What's included

### Hotspot & Network Tools
- Configure and control a Windows Mobile Hotspot for supported local connectivity workflows.
- Use local DNS and HTTP services to respond to supported connectivity checks.
- Monitor hotspot, bridge, DNS, HTTP, and connected-device status.
- Access hotspot settings and troubleshooting information from the application.

### FTP File Manager
- Browse Windows and Switch 2 files side by side.
- Upload and download files, create folders, and navigate directories.
- Drag files between supported locations and manage transfers with progress information.
- Use **Find Switch IP** to help locate your console after starting its FTP server.

### Homebrew Manager
- Browse a categorized homebrew catalog and discover supported community projects.
- Check supported GitHub repositories for available NRO releases.
- Download eligible NRO assets and transfer supported files to your console over FTP.
- View clear connection guidance and transfer feedback.

### Portable Windows Build
- Extract and run without a traditional installer.
- Includes `README-FIRST.txt` and the MIT license.
- Includes a separate service helper for operations that require elevated Windows permissions.

## First-time setup

1. Download and **extract** the Windows ZIP. Do not run the app from inside the ZIP.
2. Open the `SwitchNest` folder and read `README-FIRST.txt`.
3. Launch `SwitchNest-AIO.exe` normally. Keep the `_internal` folder and `SwitchNest-Service-Helper.exe` alongside it.
4. **Before starting the hotspot**, open **Settings** in SwitchNest AIO and configure your preferred **Wi-Fi name (SSID) and password**. Apply the settings while services are stopped.
5. In Windows **Settings → Network & internet → Mobile hotspot**, set **Power saving** to **Off**.
6. Start the hotspot and connect your Switch 2 using the configured Wi-Fi credentials.
7. For FTP transfers, **start an FTP server on your Switch 2 first**, then click **Find Switch IP** in FTP Manager or Homebrew Manager.

## Important beta notes

- This is a **beta**, and behavior depends on your Windows version, Wi-Fi adapter, driver, permissions, and network configuration.
- **Do not assume the hotspot blocks internet access.** Windows Mobile Hotspot and Internet Connection Sharing (ICS) can route traffic even when local DNS/HTTP services are running. Verify isolation independently with another test device before connecting your console.
- Keep Windows Firewall enabled. Back up important files before FTP transfers or homebrew installation.
- Homebrew projects listed in the catalog are third-party software; listings and successful downloads do not guarantee compatibility or safety.

## Source code and license

Original SwitchNest AIO code is distributed under the **[MIT License](https://github.com/blueshockz47/SwitchNest-AIO/blob/main/LICENSE)**. Third-party dependencies and bundled components retain their respective licenses.

Developers can download the [application source ZIP](https://github.com/blueshockz47/SwitchNest-AIO/releases/download/v1.0.0-Beta/SwitchNest-AIO-source.zip), which includes the build script and regression tests.

## Feedback and bug reports

Please report issues through **[GitHub Issues](https://github.com/blueshockz47/SwitchNest-AIO/issues)**. Include the app version, Windows version, Wi-Fi adapter, reproduction steps, and relevant error messages. Remove passwords, MAC addresses, IP addresses, and other personal details from screenshots and logs.

**Thank you for helping test the first public beta of SwitchNest AIO.**

*SwitchNest AIO is an independent community project and is not affiliated with or endorsed by Nintendo.*
