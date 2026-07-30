# GLX-Radio for Nextcloud

**GLX-Radio** is a custom Nextcloud application designed to bring seamless internet radio streaming directly to your private cloud environment. Featuring a clean, modern dark UI, a persistent top player, custom folder organization, and direct integration with radio-browser.info.
Currently, the app is only available in German; I am still working on a translation or a switch button to change the app's language to English.
---

## 📸 Overview & Screenshots

### 1. Main Dashboard (Overview)
The main interface features a persistent top player that keeps playing even when you navigate through different views, custom folder organization in the sidebar, live stream status, detailed station info, and your most played stations statistics.

<p align="center">
  <img src="https://raw.githubusercontent.com/Dreamdancer100/Nextcloud-GLX-Radio/main/overview.png" alt="GLX-Radio Overview" width="850">
</p>

---

### 2. External Radio Stations
Directly search and explore popular external radio stations live from `radio-browser.info` (sorted by popularity) and add them straight to your favorites with a single click.

<p align="center">
  <img src="https://raw.githubusercontent.com/Dreamdancer100/Nextcloud-GLX-Radio/main/external%20radio%20stations.png" alt="External Radio Stations" width="850">
</p>

---

### 3. Settings Page
Configure station logos, link your custom Nextcloud storage folder for icons (e.g., `/RadioLogos`), create custom sorting folders for your sidebar, and manage app configurations.

<p align="center">
  <img src="https://raw.githubusercontent.com/Dreamdancer100/Nextcloud-GLX-Radio/main/settings%20page.png" alt="Settings Page" width="850">
</p>

---

### 4. Built-in Help & Instructions (Benutzung)
Comprehensive built-in instructions covering everything from playing streams, adding custom stations manually, editing/deleting favorites, managing folders, to export and import options.

<p align="center">
  <img src="https://raw.githubusercontent.com/Dreamdancer100/Nextcloud-GLX-Radio/main/app%20description.png" alt="App Description & Usage" width="850">
</p>

---

## ✨ Features
- **Persistent Top Player:** Play, pause, skip through favorites, control volume, and view real-time track info seamlessly across views.
- **External Radio Integration:** Live search via `radio-browser.info` to discover thousands of stations.
- **Custom Folders & Sidebar:** Organize your favorites into custom categories (e.g., *Trance & Techno*, *80's*).
- **Logo Management:** Assign custom icons via URL or directly pick image files from your Nextcloud storage.
- **Export & Import:** Securely back up or restore your station list and folder structures as a file.
- **Most Played Statistics:** Keep track of your favorite and most frequently listened radio stations.

## Requirements
- Nextcloud (compatible with recent major versions)
- PHP 8.0 or higher

## Installation
1. Download or clone this repository into your Nextcloud `apps/` directory (ensure the folder is named `glxradio`).
2. Enable the app through your Nextcloud Administrator panel.

## License
This project is licensed under the **AGPL-3.0-or-later** license. See the [LICENSE](LICENSE) file for details.
