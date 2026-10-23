# 🍵 Matcha

A native macOS browser built on WebKit, inspired by Arc, plus a self-hostable server to sync it across your Macs.

---

## Matcha, the browser

Matcha keeps everything in a sidebar and gives the page the rest of the window.

- **Spaces**: separate groups of tabs, each with its own colors, switched with a swipe or ⌃1 to ⌃9
- **Profiles**: each one has its own cookies and logins
- **Command bar** to open tabs and run actions from the keyboard
- **Split view**, **Peek** (Shift+click a link to preview it) and a floating **mini window** (⌥⌘N)
- **Web extensions**: Safari extensions, Chrome `.crx`, Firefox `.xpi` and unpacked folders
- **Import from Arc**: your Spaces, pinned tabs, folders and favorites
- Available in English, French, German, Spanish and Italian

Requires **macOS 15.4** or later. A single download runs on both Apple silicon and Intel Macs.

📦 **[Download Matcha](https://github.com/MatchaBrowser/Matcha/releases)**

> Builds are not notarized yet: the first time you open Matcha, macOS asks you to confirm in System Settings › Privacy & Security.

---

## Sync Server

The server Matcha uses to sync your profiles, Spaces, tabs, extensions and settings between Macs. Run it yourself, for you alone or for a few people.

- **End-to-end encrypted**: everything is encrypted on the Mac with your master password. The server stores data it cannot read.
- Written in Go and shipped as a Docker image
- SQLite or PostgreSQL
- Registration open to anyone, by invitation only, or closed

📦 **[Sync Server releases](https://github.com/MatchaBrowser/SyncServer/releases)**

```sh
docker pull ghcr.io/matchabrowser/syncserver
```

> In development: the sync settings are not in the app yet.
