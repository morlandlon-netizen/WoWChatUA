# WoWChatUA — Ukrainian Chat Translator for World of Warcraft

Real-time Ukrainian chat translation overlay + WoW addon for Windows 10/11.

## Download & Setup
1. Install the **WoWChatUA** addon from **[CurseForge](https://www.curseforge.com/wow/addons/wowchatua)** (recommended via the CurseForge App).
2. Download **`WoWChatUA.exe`** from **[GitHub Releases](https://github.com/morlandlon-netizen/WoWChatUA/releases/tag/v1.0.0)**.
3. Start World of Warcraft and run `WoWChatUA.exe`.
4. Drag and resize the overlay over your `General` chat box, then press **`F9`** to lock it.

## Hotkeys
- **`F9`** — Lock / unlock overlay (click-through mode)
- **`~`** *(hold)* — Temporarily hide overlay to click quest/item links in WoW chat
- **`F7` / `F10`** — Open Ukrainian → English reply bar (copies to clipboard, `↑`/`↓` for history)
- **`F8`** — Toggle hide / show overlay
- **`/ua`** *(in-game)* — Show / hide Quick-Phrase Combat Bar

## Build from Source
```bash
py -m pip install mss pyinstaller
py -m PyInstaller --onefile --noconsole --name WoWChatUA translator_overlay.py
