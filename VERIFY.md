# File Verification Guide

To ensure your download is authentic and unmodified, verify its checksum.

## ✅ Windows (PowerShell)

Run:
Get-FileHash .\Project_Revive_Setup.exe -Algorithm SHA256

Compare the output hash with the official checksum.

---

## ✅ Linux / Mac

Run:
sha256sum Project_Revive_Setup.exe

---

## ✅ Important

- The hash MUST match exactly
- If it does not match:
  ❌ DO NOT install the file
  ⚠️ It may be modified or unsafe

Always download from official sources only.
