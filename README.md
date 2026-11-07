# ClipoTxt Releases

Official public release repository and update service for **ClipoTxt** — the local-first Windows desktop clipboard OCR utility.

---

## Downloads (v1.0.1)

| Package | Format | Description |
| :--- | :--- | :--- |
| [**ClipoTxt-Setup-v1.0.1.exe**](https://github.com/cvfoliox-dev/clipotxt-releases/releases/download/v1.0.1/ClipoTxt-Setup-v1.0.1.exe) | Windows Installer | Standard desktop installation with Start Menu, Desktop shortcuts, and uninstaller. |
| [**ClipoTxt-v1.0.1-windows-x64-portable.zip**](https://github.com/cvfoliox-dev/clipotxt-releases/releases/download/v1.0.1/ClipoTxt-v1.0.1-windows-x64-portable.zip) | Portable Archive | Zero-install archive. Extract anywhere and launch `ClipoTxt.exe`. |

---

## Cryptographic Checksums (SHA-256)

To verify download integrity in PowerShell:

```powershell
Get-FileHash -Algorithm SHA256 .\ClipoTxt-Setup-v1.0.1.exe
```

| File | SHA-256 Hash |
| :--- | :--- |
| `ClipoTxt-Setup-v1.0.1.exe` | `023dc45b9fb340ee23bbc79b8fdf4152ef89ca091bb4c875f1543f635604983a` |
| `ClipoTxt-v1.0.1-windows-x64-portable.zip` | `7a19377f1e83aa7b9c78c8033406befa8c6dfb6d0dbd2d260dc5c314d1bf1456` |

---

## Silent Enterprise Installation

```powershell
.\ClipoTxt-Setup-v1.0.1.exe /VERYSILENT /SUPPRESSMSGBOXES /NORESTART
```

---

## Update Service Manifest

The live version manifest for in-app software updates is hosted at:
`https://raw.githubusercontent.com/cvfoliox-dev/clipotxt-releases/main/version.json`
