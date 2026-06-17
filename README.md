# xCloud Pulse

A native macOS **menu bar** app to monitor your xCloud sites and servers — site health, SSL, backups, vulnerabilities, server resources & services — without leaving your desktop.

<p align="center">
  <em>Live status in your menu bar · one click to every site & server.</em>
</p>

## Download

> Requires **macOS 14 (Sonoma)** or newer.

| Mac | Download |
|-----|----------|
| **Apple Silicon** (M1/M2/M3/M4) | [⬇︎ xCloud‑Pulse‑Apple‑Silicon.dmg](https://github.com/xCloudDev/xCloud-Pulse/raw/master/xCloud-Pulse-Apple-Silicon.dmg) |
| **Intel** | [⬇︎ xCloud‑Pulse‑Intel.dmg](https://github.com/xCloudDev/xCloud-Pulse/raw/master/xCloud-Pulse-Intel.dmg) |

Not sure which one? Click the  Apple menu → **About This Mac**. A "Chip" starting with **Apple** = Apple Silicon; a "Processor" that says **Intel** = Intel.

## Install

1. Open the downloaded `.dmg`.
2. Drag **xCloud Pulse** into your **Applications** folder.
3. On first launch macOS may block it (the app isn't notarized yet):
   - **Right‑click** the app in Applications → **Open** → **Open** in the dialog.
   - If it still won't open, run this once in Terminal:
     ```bash
     xattr -dr com.apple.quarantine "/Applications/xCloud Pulse.app"
     ```

## Connect your account

1. Click the **xCloud** icon in the macOS menu bar (top‑right).
2. Open **Settings** and paste your xCloud **API token**, then **Save Token**.
3. Click **Test Connection** — you should see *"Connected successfully"*, and your sites & servers will load.

Create an API token from your xCloud account settings. Read scopes are enough for monitoring; write scopes enable actions like server reboot, service restart, trigger backup, cache purge, and vulnerability scan.

## Features

- **Menu bar summary** — sites/servers counts and an at‑a‑glance health indicator.
- **Site details** — status, SSL, backups (remote/local), vulnerability breakdown, performance and CPU/RAM/Disk history charts.
- **Server details** — resources, services (with restart), reboot, and monitoring history; disconnected servers highlighted.
- **Search** sites and servers, and deep‑link straight to the xCloud dashboard.
- Optional **write actions** (reboot, service restart, backup, cache purge, scan) behind a settings toggle.

## Updating

Download the latest `.dmg` from the table above and replace the app in **Applications**.
