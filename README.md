# 📝 mdnotes

> **The ultra-efficient Markdown note-taker for power users of the terminal.**

Built for those who need to capture ideas fast, organize them cleanly, and render them beautifully—all without leaving the command line. No Vim expertise required.

---

## ✨ Features

### 🚀 High-Speed Workflow
- **Interactive Home:** Number-based navigation for quick access.
- **Full-Screen Focus:** A distraction-free editing environment with line numbers and scroll support.
- **Instant Switching:** Hit `Alt+N` while editing to save your place and jump into a brand-new note immediately.

### 🛡️ Safety & Comfort
- **Auto-Save:** Background engine saves your work every 2 minutes. Never lose a thought.
- **Smart Hotkeys:**
  - `Alt + S`: Force manual save.
  - `Alt + Z`: Full undo support.
  - `Esc + Enter`: Save and exit back to the main menu.
- **Vim-Free:** Pure, intuitive text entry.

### 🎨 Rich Experience
- **Live Cheatsheet:** `Alt + 0` (or the toolbar) shows MS Word-style formatting tips.
- **Beautiful Rendering:** Native Markdown rendering using the `rich` engine.

---

## 🛠️ Installation

### 1. Requirements
Ensure you have Python 3 and the core engines:
```bash
pip install rich prompt-toolkit
```

### 2. Setup
Download the `mdnotes` script and make it executable:
```bash
chmod +x mdnotes
mv mdnotes ~/bin/
```

### 3. Alias
Add this to your `~/.bashrc` for instant access:
```bash
alias mdnotes='~/bin/mdnotes'
```

---

## 🎹 Keyboard Mastery

| Action | Hotkey |
| :--- | :--- |
| **Save Place** | `Alt + S` |
| **New Note (Inline)** | `Alt + N` |
| **Undo** | `Alt + Z` |
| **Format Help** | `Alt + 0` |
| **Save & Exit** | `Esc + Enter` |

---

## 📄 Storage
All your notes are stored locally in:
`~/md_notes/`

---

*Built with ❤️ for the CLI community.*
