# HIDUSBF

USB polling-rate overclocking for mice, keyboards and controllers, plus PlayStation controller tools (stick check, calibration, lights).

## Download

Get the latest **HIDUSBF-x.y.z-Setup.exe** from [Releases](https://github.com/KazboXIII/HIDUSBF/releases/latest) and run it. HIDUSBF installs to Program Files and adds a Start menu entry.

After that, HIDUSBF checks this page for new versions while its loading window is up and offers to install them. You can turn that off in **About > Updates**.

Each release has a `.sha256` file next to the installer, so you can check the download:

```powershell
Get-FileHash .\HIDUSBF-4.0.0-Setup.exe -Algorithm SHA256
```

## Notes

- Windows 8.1 or later, 64-bit. Needs administrator rights, because it installs and manages the hidusbf filter driver.
- The installer isn't code-signed yet, so Windows SmartScreen may warn the first time. Choose **More info > Run anyway**.
- Uninstalling HIDUSBF leaves the driver in place. Remove it first from **Driver > Uninstall service** in the app if you want it gone.

Report problems in [Issues](https://github.com/KazboXIII/HIDUSBF/issues).
