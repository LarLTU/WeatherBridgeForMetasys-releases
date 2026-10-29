# Weather Bridge for Metasys — installer downloads

This repository publishes the installers for **Weather Bridge for Metasys**, with their license agreement and
third-party notices. It contains no source code.

**Not affiliated with Johnson Controls.** Weather Bridge for Metasys is an independent product. It is not affiliated
with, sponsored by, endorsed by or promoted by Johnson Controls International plc or its subsidiaries (JCI). Metasys is
a registered trademark of Johnson Controls; all other trademarks belong to their owners. This software is not a JCI
product, is not supported by JCI, and has no ties to JCI. It interacts with Metasys only through its published API.

- **Download:** the latest version is on the [Releases page](https://github.com/LarLTU/WeatherBridgeForMetasys-releases/releases/latest).
  Each release has the installer, `MetasysWeatherBridge-x.y.z.msi`, its SHA-256 checksum,
  `MetasysWeatherBridge-x.y.z.msi.sha256`, and the release notes.
- **Install or upgrade:** run the MSI as an administrator on the server. To upgrade, run the newer MSI over the
  installed one; settings, users and mappings are kept.
- **Check a download** (prints True when it matches), in PowerShell:

  ```powershell
  (Get-FileHash .\MetasysWeatherBridge-x.y.z.msi -Algorithm SHA256).Hash -eq (Get-Content .\MetasysWeatherBridge-x.y.z.msi.sha256).Split(' ')[0]
  ```

- **Hear about new versions:** in the bridge, **Settings → General & backup → Updates → Check for new versions**
  reads the latest release from this repository (1.7.6 and later).

Releases are published here automatically when a version is released.

## License and notices

Weather Bridge for Metasys is proprietary software, © 2026 Larry Sinkevicius, all rights reserved. Installing,
copying or using it is subject to the [license agreement](LICENSE), which the installer (1.7.7 and later) also
shows. Only the released installers are licensed for use; nothing here grants a right to redistribute them. The
open-source components the program includes, and the terms of the weather data sources it uses (OpenWeather,
MET Norway, US National Weather Service), are in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md).
