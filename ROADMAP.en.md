<div align="center">

# Lunova SSH — Roadmap

**An SSH & SFTP client for macOS, Linux and Windows. Free, no subscriptions.**

[![Latest release](https://img.shields.io/github/v/release/tequilajet/lunova-ssh-releases?label=version&color=4c8dff)](https://github.com/tequilajet/lunova-ssh-releases/releases/latest)
[![Platforms](https://img.shields.io/badge/platforms-macOS%20·%20Linux%20·%20Windows-4c8dff)](https://github.com/tequilajet/lunova-ssh-releases/releases/latest)
[![Price](https://img.shields.io/badge/price-free-46c98b)](#what-we-wont-do)
[![Download](https://img.shields.io/badge/download-latest_release-ff5c6c)](https://github.com/tequilajet/lunova-ssh-releases/releases/latest)

[Русская версия](ROADMAP.md)

<img src="https://raw.githubusercontent.com/tequilajet/lunova-ssh-releases/main/docs/img/board.png" alt="Lunova SSH main screen" width="820">

</div>

---

## How to read this

There are no dates here on purpose: we don't promise timelines we can't
guarantee. The order under **What's next** roughly reflects priority — higher
means sooner. This page is updated with every release.

Missing something important? [Open an issue](https://github.com/tequilajet/lunova-ssh-releases/issues) —
it directly affects what gets built next.

---

## Already working

### 🔌 Connecting `██████████` 100%

- [x] Password, SSH key and ssh-agent authentication
- [x] Multiple keys per server — tried one after another
- [x] Host key check on first connect, warning when it changes
- [x] Import from `~/.ssh/known_hosts` and `~/.ssh/config`
- [x] Works correctly over VPN

### 🗂 Managing servers `█████████░` 90%

- [x] Server list with groups and one search box for everything
- [x] Quick connect without saving, plus a Recent list
- [x] Custom ordering inside a group
- [x] Move every server to another computer as one encrypted file
- [ ] Sync between devices

### 💻 Terminal `█████████░` 90%

- [x] Tabs and several sessions at once
- [x] Your local shell in the same window
- [x] Copy, paste and search in the output
- [x] Tabs restored after a restart
- [x] Font, size and color scheme of your choice
- [x] Saved commands with placeholders — one click drops them into the terminal
- [ ] Several terminals in one window

### 📁 Files (SFTP) `█████████░` 90%

- [x] Two panes side by side: your files and the server's
- [x] Upload and download with progress, pause and cancel
- [x] Drag and drop from Finder and Explorer
- [x] Create, rename and delete
- [x] Built-in editor for files on the server
- [ ] Bulk operations and whole folders

### 🔒 Security and updates `█████████░` 90%

- [x] Passwords live in the system keychain only, never in files
- [x] Honest warning when no system storage is available
- [x] In-app updates on all three systems
- [x] New version notice with the list of changes
- [x] English and Russian interface
- [ ] Signed builds

---

## In progress

| | What | Why |
|---|---|---|
| 🔏 | **Signed builds** for macOS and Windows | So the system stops warning you on first launch |

---

## What's next

| | Feature | What you get |
|---|---|---|
| 🚀 | **Jump hosts** | Reach servers that sit behind a bastion |
| 🔀 | **Port forwarding** | Databases and internal services, on your machine |
| 📦 | **Bulk file operations** | Transfer folders and multi-file selections |
| 🪟 | **Split panes** | Work with several servers at once |
| ☀️ | **Light theme** | For those who don't get along with dark |
| 📥 | **Import from other clients** | Move in without re-entering every server |

---

## Under consideration

Ideas we like but haven't committed to:

- **Syncing servers between devices** — through our own encrypted storage
- **Builds for ARM versions of Linux and Windows**

---

## What we won't do

- **No subscriptions or paid features.** The app stays free, in full. You can
  support development voluntarily — it unlocks nothing and obliges you to
  nothing.
- **No analytics, no tracking.** The app reaches the network only to check for
  updates and for the connections you make yourself.
- **No storing your passwords anywhere but your own computer's keychain.** No
  cloud, no servers of ours — they simply don't exist.

---

<div align="center">

### A look inside

<img src="https://raw.githubusercontent.com/tequilajet/lunova-ssh-releases/main/docs/img/host-form.png" alt="Adding a server" width="420"> <img src="https://raw.githubusercontent.com/tequilajet/lunova-ssh-releases/main/docs/img/settings.png" alt="Settings" width="420">

**[Download the latest release](https://github.com/tequilajet/lunova-ssh-releases/releases/latest)**

</div>
