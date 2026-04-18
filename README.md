<h1 align="center">Record Message</h1>

<p align="center">
  A modern, desktop WhatsApp campaign manager to broadcast messages efficiently.
</p>

<p align="center">
  <a href="https://github.com/Record10/record-message-public/releases/latest">
    <img src="https://img.shields.io/github/v/release/Record10/record-message-public?label=Download&style=for-the-badge" alt="Download Latest Release"/>
  </a>
</p>

---

## Features

- **WhatsApp Web Integration** — Links locally and runs entirely from your machine.
- **Bulk Messaging** — Send campaigns to lists of contacts easily.
- **Cross-Platform** — Available for macOS, Windows, and Linux.
- **Modern UI** — Beautiful dark/light themes.

---

## Download

Head to the [**Releases**](https://github.com/Record10/record-message-public/releases/latest) page and download the installer for your operating system:

| Platform             | File                        |
| -------------------- | --------------------------- |
| **macOS**            | `Record Message-0.1.0-mac.zip` / `.dmg` |
| **Windows**          | `Record Message Setup 0.1.0.exe` |
| **Linux (AppImage)** | `Record Message-0.1.0.AppImage` |
| **Linux (Debian)**   | `record-message_0.1.0_amd64.deb` |

---

## Installation

### macOS

1. Download the `.dmg` file from the [Releases](https://github.com/Record10/record-message-public/releases/latest) page.
2. Open the `.dmg` file and drag **Record Message** into your **Applications** folder.
3. **Important — the app is unsigned.** macOS will block it on first launch. To allow it, run the following command in Terminal **once** after installation:

   ```bash
   xattr -cr "/Applications/Record Message.app"
   ```

4. Now you can open Record Message normally from Applications.

### Windows

1. Download the setup `.exe` file from the [Releases](https://github.com/Record10/record-message-public/releases/latest) page.
2. Run the installer and follow the on-screen instructions.
3. **The app is unsigned**, so Windows SmartScreen may show a warning. Click **"More info"** and then **"Run anyway"** to proceed with the installation.

### Linux

#### AppImage

1. Download the `.AppImage` file from the [Releases](https://github.com/Record10/record-message-public/releases/latest).
2. Make it executable and run:

   ```bash
   chmod +x Record\ Message-*.AppImage
   ./Record\ Message-*.AppImage
   ```

#### Debian / Ubuntu (.deb)

1. Download the `.deb` file.
2. Install it:

   ```bash
   sudo dpkg -i record-message_*.deb
   ```

---

## Troubleshooting

### macOS — "App is damaged and can't be opened"

This happens because the app is not signed with an Apple Developer certificate. Run the following command to remove the quarantine flag:

```bash
xattr -cr "/Applications/Record Message.app"
```

### Windows — SmartScreen warning

Click **"More info"** → **"Run anyway"**. This warning appears because the app is not signed with a Windows code-signing certificate.
