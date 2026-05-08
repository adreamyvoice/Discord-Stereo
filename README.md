<div align="center">

# Discord Stereo

**Make Discord voice chat sound way better — true stereo, high quality, no muffling.**

Works on Windows and Linux.

</div>

---

## What is this?

Discord normally squishes your microphone audio down to a low-quality mono signal. This tool patches your Discord app so it sends **clean stereo audio** instead. You only have to install it once, and the people you talk to don't need to do anything — they just hear you better.

**Before vs After:** [Before](https://ibb.co/XfdWfv42) — [After](https://ibb.co/jkBmKhrr)

---

## How to install

Pick your computer. The easiest option is **Stereo Hub** — one app that does it all.

> **Easiest:** Download **Stereo Hub** from the [latest release](https://github.com/adreamyvoice/Discord-Stereo/releases/latest), then run it. You'll need [Python 3.8+](https://www.python.org/downloads/) installed (one-click installer from python.org).

If you want the simpler one-file scripts instead:

### 🪟 Windows

1. Download [`Stereo Installer.bat`](https://github.com/adreamyvoice/Discord-Stereo/raw/main/Updates/Windows/Stereo%20Installer.bat).
2. **Right-click it → Run as administrator.**
3. Pick your Discord version when it asks. It restarts Discord for you.

That's it.

### 🐧 Linux

1. Open a terminal and run: `sudo apt install g++ python3 python3-tk`
2. Download [`discord-stereo-launcher.sh`](https://github.com/adreamyvoice/Discord-Stereo/raw/main/Updates/Linux/discord-stereo-launcher.sh).
3. In the terminal: `chmod +x discord-stereo-launcher.sh && ./discord-stereo-launcher.sh`
4. Pick **patcher mode** in the window that opens.

---

## Did it work?

Hop into a voice channel with a friend and ask if you sound clearer. That's the test.

---

## Common problems

**"It used to work, now it doesn't."** Discord updated. Wait for an update here, or join the Discord for help.

**"Permission denied / can't open file."** On Windows, run as Administrator. On Linux, the file is usually in `~/.config/discord/`.

**"Will I get banned?"** This only changes how *your* computer encodes audio. There are no known bans tied to this project, but technically modifying Discord violates their terms — use at your own risk.

**"Does the person I'm talking to need it too?"** No. Just you.

**"My voice is distorted."** The gain is too high. Keep it at **1×** unless you're really quiet.

---

## Get help / chat

- 💬 **[Join the Discord](https://discord.gg/gDY6F8RAfM)** — fastest way to get help
- 🐛 **[Report a bug](https://github.com/adreamyvoice/Discord-Stereo/issues)**

---

> ⚠️ Provided as-is for research and experimentation. Not affiliated with Discord Inc.
