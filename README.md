# ClipoTxt Releases

Official public release repository and update service for **ClipoTxt** — the local-first Windows desktop clipboard OCR utility.

---

## Downloads (v1.0.0)

| Package | Format | Description |
| :--- | :--- | :--- |
| [**ClipoTxt-Setup-v1.0.0.exe**](https://github.com/cvfoliox-dev/clipotxt-releases/releases/download/v1.0.0/ClipoTxt-Setup-v1.0.0.exe) | Windows Installer | Standard desktop installation with Start Menu, Desktop shortcuts, and uninstaller. |
| [**ClipoTxt-v1.0.0-windows-x64-portable.zip**](https://github.com/cvfoliox-dev/clipotxt-releases/releases/download/v1.0.0/ClipoTxt-v1.0.0-windows-x64-portable.zip) | Portable Archive | Zero-install archive. Extract anywhere and launch `ClipoTxt.exe`. |

---

## Cryptographic Checksums (SHA-256)

To verify download integrity in PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\ClipoTxt-Setup-v1.0.0.exe
```

| File | SHA-256 Hash |
| :--- | :--- |
| `ClipoTxt-Setup-v1.0.0.exe` | `0a59da1943b9797361c8ba6bd9c02d2d3d57de4fca4b8e72ee8697bdb13aeed5` |
| `ClipoTxt-v1.0.0-windows-x64-portable.zip` | `cd769bf316444236482b80f3c7cd75d094e03fa62e9bfeeb1bf8097c3e54ba38` |

---

## Silent Enterprise Installation

```powershell
.\ClipoTxt-Setup-v1.0.0.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART /CURRENTUSER
```

---

## Update Service Manifest

The live version manifest for in-app software updates is hosted at:
`https://raw.githubusercontent.com/cvfoliox-dev/clipotxt-releases/main/version.json`
