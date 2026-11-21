# Inox Pro

Offline desktop billing for steel traders: GST invoices, client ledger, Cash and Bank accounts, stock, and E-Way bills.
Your data stays on your computer, in an encrypted database.

## Download

Get the latest installer from the [**Releases**](../../releases/latest) page:

- **Mac** (Apple Silicon, M1 or newer): `Inox.Pro_<version>_aarch64.dmg`
- **Windows**: `Inox.Pro_<version>_x64-setup.exe`

(Ignore the "Source code" links on the release page; they contain only this README.)

## Install

**Mac**
1. Open the `.dmg` and drag **Inox Pro** into **Applications**.
2. Open the app. macOS says "Apple could not verify Inox Pro is free of malware". Click **Done** (not "Move to Bin"). This happens because the app is not yet signed with an Apple certificate.
3. Open **System Settings → Privacy & Security**, scroll to the **Security** section, and click **Open Anyway** next to the message about "Inox Pro". Enter your Mac password or use Touch ID, then click **Open Anyway** again.
4. This is needed only the first time. If the button is gone, try opening the app once more and it comes back.

If macOS says the app is "damaged", run this once in Terminal and open it again:
```
xattr -cr "/Applications/Inox Pro.app"
```

**Windows**
1. Run the `.exe`. It installs for your user account only, so no administrator password is needed.
2. If SmartScreen says "Windows protected your PC", choose **More info**, then **Run anyway**. The warning appears because the app is not yet signed with a Windows certificate.

## Licence

Inox Pro needs a licence key. Open **Settings → Plan & licence** and paste the key you were given. Without an active plan the app is read-only: you can still view, export and back up your data.

## Updating

Install the newer version over the old one. Your data is kept. Make a backup first from **Settings → Backup & restore**.

## Support

Contact the person who gave you your licence key.
