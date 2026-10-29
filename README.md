# Weather Bridge for Metasys — installer downloads

This repository only publishes the installers for **Weather Bridge for Metasys**. It contains no source code.

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
