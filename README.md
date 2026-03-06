# ⚡ Lanthanum Nuker V4 – Executable Version

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows-blue?style=for-the-badge&logo=windows">
  <img src="https://img.shields.io/badge/Discord%20API-v10-brightgreen?style=for-the-badge&logo=discord">
  <img src="https://img.shields.io/badge/Executable-EXE-red?style=for-the-badge&logo=windows">
  <img src="https://img.shields.io/badge/License-MIT-purple?style=for-the-badge">
</p>

<p align="center">
  <b>🚀 Ready‑to‑run Windows executable of the high‑speed asynchronous Discord server nuker.</b><br>
  <b>🔋 No Python installation required – just download and run.</b>
</p>

---

## 🔥 Features

| | |
|---|---|
| ✅ **Self‑contained executable** | No Python, no dependencies, no setup. |
| ⚡ **Fully asynchronous** | Uses `aiohttp` & `asyncio` for maximum speed. |
| 🧠 **Smart rate‑limit handling** | Automatically respects Discord’s rate limits. |
| 🔄 **Parallel execution** | Controls concurrency to avoid hitting limits. |
| 🕸️ **Webhook spammer** | Creates webhooks on all text channels and spams them in parallel without freezing. |
| 👥 **Unban all** | Correctly fetches all banned users using pagination. |
| 🎨 **Colour‑coded console** | Green for success, red for failure, with timestamps. |
| 🧹 **Compact menu** | Screen clears after each command, showing the menu again. |
| 🪟 **Optimised for Windows** | Uses native console API for title and clear. |

---

## 📋 System Requirements

- **Windows 7 / 8 / 10 / 11** (64‑bit recommended)
- **No additional software required** – the executable contains everything.

---

## 🚀 How to Use

1. **Download** the `LanthanumNuker.exe` from the [releases page](../../releases) (or compile it yourself).
2. **Double‑click** the `.exe` file to run it.
3. **Enter your bot token** and the target **guild ID** when prompted.
4. **Choose a command** from the menu by typing the corresponding number.
5. **Watch the magic happen** – logs will appear in real time.

> ⚠️ **The bot must have the necessary permissions** in the target server (e.g., `Ban Members`, `Manage Channels`, `Manage Roles`, etc.).

---

## Developer : RussiabHarvey
## Discord Username : russianharvey

## 🛠️ Available Commands

| Command | Description |
|--------|-------------|
| `01` | Ban all members (except the bot) |
| `02` | Kick all members (except the bot) |
| `03` | Unban everyone |
| `04` | Create text channels |
| `05` | Create voice channels |
| `06` | Create categories |
| `07` | Delete all channels |
| `08` | Create new roles |
| `09` | Display server information |
| `10` | Mass‑ping (send messages to random text channels) |
| `11` | Mass‑DM (direct message all members) |
| `12` | Rename all channels |
| `13` | Grant administrator permissions to the `@everyone` role |
| `14` | Rename all members |
| `15` | Delete all emojis |
| `16` | Delete all stickers |
| `17` | Delete vanity URL |
| `18` | Webhook spammer (creates webhooks on every text channel and sends bulk messages) |
| `0x90` | Full server nuke (ban all → delete all channels → create 200 channels → spam 2000 messages) |
| `0`   | Shut down the program |

---

<img width="1434" height="672" alt="Screenshot 2026-03-06 055855" src="https://github.com/user-attachments/assets/530db911-294f-4508-8847-106ecce10e97" />

