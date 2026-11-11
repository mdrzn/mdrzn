<div align="center">

# Hey, I'm Federico 👋

### Solo developer from Italy building practical AI products, web tools and small Mac apps.

I turn small, annoying problems into focused software — usually with AI somewhere in the loop.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/mdrzn)
[![Hacker News](https://img.shields.io/badge/Hacker_News-FF6600?style=for-the-badge&logo=ycombinator&logoColor=white)](https://news.ycombinator.com/user?id=mdrzn)

</div>

---

## What I'm building

<table>
<tr>
<td width="50%" valign="top">
<a href="https://prezziallapompa.it"><img src="assets/prezzi-alla-pompa.webp" alt="Prezzi alla Pompa" width="100%"></a>

**[⛽ Prezzi alla Pompa](https://prezziallapompa.it)**<br>
Daily fuel-price averages and trends across Italy, built on official MIMIT data — with a map of every station and side-by-side comparisons.
</td>
<td width="50%" valign="top">
<a href="https://buongiornoai.it"><img src="assets/buongiornoai.webp" alt="BuongiornoAI" width="100%"></a>

**[☀️ BuongiornoAI](https://buongiornoai.it)**<br>
Practical AI news and guides for an Italian audience: a free newsletter three times a week, plus short explainer videos.
</td>
</tr>
</table>

## Open source

### Mac apps

<table>
<tr>
<td width="50%" valign="top" align="center">
<a href="https://github.com/mdrzn/menustats"><img src="https://raw.githubusercontent.com/mdrzn/menustats/main/docs/tour.webp" alt="MenuStats" width="72%"></a>
</td>
<td width="50%" valign="top" align="center">
<a href="https://github.com/mdrzn/cursor-trail"><img src="https://raw.githubusercontent.com/mdrzn/cursor-trail/main/docs/fantasmi.gif" alt="CursorTrail" width="100%"></a>
</td>
</tr>
<tr>
<td valign="top">

**[📊 MenuStats](https://github.com/mdrzn/menustats)**<br>
A menu bar system monitor for people who build things: CPU, memory, sensors, apps, listening ports, AI agent sessions (with Claude Code token usage), per-app volume and keep-awake — in one panel, with themes and ten menu bar looks.

[![Release](https://img.shields.io/github/v/release/mdrzn/menustats?style=flat-square&color=4FD1A5&label=release)](https://github.com/mdrzn/menustats/releases/latest)
![macOS](https://img.shields.io/badge/macOS-14.2+-111?style=flat-square&logo=apple)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

</td>
<td valign="top">

**[✨ CursorTrail](https://github.com/mdrzn/cursor-trail)**<br>
A lightweight cursor trail for macOS: a fading gradient line or ghost copies of the pointer, with every option of the Windhawk mod it's inspired by, plus an animated rainbow.

[![Release](https://img.shields.io/github/v/release/mdrzn/cursor-trail?style=flat-square&color=8B00FF&label=release)](https://github.com/mdrzn/cursor-trail/releases/latest)
![macOS](https://img.shields.io/badge/macOS-14+-111?style=flat-square&logo=apple)
![Swift](https://img.shields.io/badge/Swift-F05138?style=flat-square&logo=swift&logoColor=white)

</td>
</tr>
</table>

All three Mac apps install with Homebrew:

```sh
brew tap mdrzn/tap && brew trust mdrzn/tap
brew install --cask --no-quarantine mdrzn/tap/menustats mdrzn/tap/cursortrail mdrzn/tap/screenshot-uploader
```

### Screenshots → remote Claude Code

When Claude Code runs on a server over SSH, it can't see the screenshot on your desktop. These upload it for you and put the remote path on your clipboard:

```
📸 take a screenshot  →  ⬆️ upload over SSH  →  📋 /tmp/screenshots/shot.png  →  paste into Claude Code
```

<table>
<tr>
<td width="50%" valign="top">

**[🍎 claude-screenshot-uploader](https://github.com/mdrzn/claude-screenshot-uploader)**<br>
A native Mac menu bar app: uploads the moment a screenshot is saved, clipboard images with ⌥⌘U, drag and drop, multiple servers with a connection test.

[![Stars](https://img.shields.io/github/stars/mdrzn/claude-screenshot-uploader?style=flat-square&color=F5B942)](https://github.com/mdrzn/claude-screenshot-uploader/stargazers)
[![Release](https://img.shields.io/github/v/release/mdrzn/claude-screenshot-uploader?style=flat-square&label=release)](https://github.com/mdrzn/claude-screenshot-uploader/releases/latest)
![macOS](https://img.shields.io/badge/macOS-111?style=flat-square&logo=apple)

</td>
<td width="50%" valign="top">

**[🪟 windows-screenshot-uploader](https://github.com/mdrzn/windows-screenshot-uploader)**<br>
The same workflow on Windows: a system-tray app that picks up screenshots from the clipboard and uploads them.

[![Stars](https://img.shields.io/github/stars/mdrzn/windows-screenshot-uploader?style=flat-square&color=F5B942)](https://github.com/mdrzn/windows-screenshot-uploader/stargazers)
![Windows](https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</td>
</tr>
</table>

---

<div align="center">

**Build small. Ship often. Keep it useful.**

</div>
