Lanthanum Nuker V4 – Executable Version
<p align="center"> <img src="https://img.shields.io/badge/Platform-Windows-blue"> <img src="https://img.shields.io/badge/Discord%20API-v10-brightgreen"> <img src="https://img.shields.io/badge/Async-aiohttp-orange"> <img src="https://img.shields.io/badge/Executable-EXE-red"> </p><p align="center"> <b>Ready‑to‑run Windows executable of the high‑speed asynchronous Discord server nuker.<br> No Python installation required – just download and run.</b> </p>
🔥 Features
Self‑contained executable – no Python, no dependencies, no setup.

Fully asynchronous – uses aiohttp and asyncio for maximum speed.

Smart rate‑limit handling – automatically respects Discord’s rate limits.

Parallel execution – controls concurrency to avoid hitting limits.

Webhook spammer – creates webhooks on all text channels and spams them in parallel without freezing.

Unban all – correctly fetches all banned users using pagination.

Colour‑coded console – green for success, red for failure, with timestamps.

Compact menu – screen clears after each command, showing the menu again.

Optimised for Windows – uses native console API for title and clear.

📋 System Requirements
Windows 7 / 8 / 10 / 11 (64‑bit recommended)

No additional software required – the executable contains everything.

🚀 How to Use
Download the LanthanumNuker.exe from the releases page (or compile it yourself).

Double‑click the .exe file to run it.

Enter your bot token and the target guild ID when prompted.

Choose a command from the menu by typing the corresponding number.

Watch the magic happen – logs will appear in real time.

⚠️ The bot must have the necessary permissions in the target server (e.g., Ban Members, Manage Channels, Manage Roles, etc.).

🛠️ Available Commands
Command	Description
01	Ban all members (except the bot)
02	Kick all members (except the bot)
03	Unban everyone
04	Create text channels
05	Create voice channels
06	Create categories
07	Delete all channels
08	Create new roles
09	Display server information
10	Mass‑ping (send messages to random text channels)
11	Mass‑DM (direct message all members)
12	Rename all channels
13	Grant administrator permissions to the @everyone role
14	Rename all members
15	Delete all emojis
16	Delete all stickers
17	Delete vanity URL
18	Webhook spammer (creates webhooks on every text channel and sends bulk messages)
0x90	Full server nuke (ban all → delete all channels → create 200 channels → spam 2000 messages)
0	Shut down the program
📦 Building the Executable Yourself
If you prefer to build the .exe from source, follow these steps:

Install Python 3.8+ and PyInstaller:

bash
pip install pyinstaller aiohttp colorama
Download the Lanthanum.py source.

Run:

bash
pyinstaller --onefile --console --name "LanthanumNuker" Lanthanum.py
The executable will be in the dist folder.

Note: Some antivirus programs may flag the generated .exe as a false positive due to its network activity. This is normal.

⚠️ Disclaimer
This tool is intended for educational purposes only.

Using it against servers you do not own is strictly prohibited and violates Discord's Terms of Service.

The author is not responsible for any misuse or damage caused by this program.

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.

<p align="center"> Made with ❤️ by <b>RusianHarvey</b> </p>
