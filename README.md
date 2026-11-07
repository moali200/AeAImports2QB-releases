# AeAImports2QB – releases

Installer and updates for **AeAImports2QB**, a Windows desktop app that turns donations from Stripe,
PayPal, Suran and paper checks into QuickBooks Online deposits for review and posting.

This repository contains only the released app. The source code is private.

## Install
1. Open the latest release (under **Releases** on the right) and download `AeAImports2QB-win-Setup.exe`.
2. Run it. It installs for your Windows user only and doesn't need administrator rights.
   If Windows shows "Windows protected your PC", click **More info**, then **Run anyway**.
3. Start **AeAImports2QB** from the Start menu. The first time, it offers to open **Settings** so you
   can import the settings file you were given (you'll also need its passphrase).
4. Click **QBO Login** and sign in to QuickBooks.

## Updates
The app checks for a new version when it starts and asks before restarting to install it.
Your data, settings and sign-in are kept in `%LOCALAPPDATA%\AeAImports2QB` and aren't changed by updates.

## Uninstall
Windows Settings → Apps → Installed apps → AeAImports2QB → Uninstall.
Your data in `%LOCALAPPDATA%\AeAImports2QB` is left in place; delete that folder to remove it too.

## Privacy
Releases contain no API keys, passwords, sign-in tokens or donor data. Keys are entered or imported on
each PC and stored encrypted for that Windows user.

© AeA. All rights reserved. Provided for use by AeA.
