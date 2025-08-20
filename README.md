# SMX-Console
A stage manager's best friend

# 🎭 SMX Console

**SMX Console** is a cross-platform desktop application built with [Electron](https://www.electronjs.org/) and React to support **stage management, cueing, and technical coordination** in live performance environments.  
It’s designed with a focus on **amateur dramatics (am-dram)**, but flexible enough to be useful in **professional theatre, events, film, TV, and other areas such as theme park operations**.

---

## 🌟 Purpose

Theatre and live events can be chaotic — and many groups (especially smaller am-dram companies) don’t have access to expensive professional software or cueing systems. **SMX Console** provides a free, lightweight, and highly customizable tool for:

- Stage Managers
- DSMs / Calling Stage Managers
- Lighting, Sound, Flys, and other tech operators
- Production teams in events, film, or any cue-driven environment

It aims to *assist where helpful*, **not replace people** — giving operators digital tools that improve clarity, timing, and coordination without getting in the way.

---

## ✨ Features

### 🎬 Show & Cue Management
- Create and edit cue lists with:
  - Cue numbers
  - Descriptions
  - Department tags (LX, SQ, Fly, Deck, FX, Spot, etc.)
- Reorder cues via drag-and-drop
- Keyboard shortcuts for fast cue navigation (`space`, arrow keys, etc.)
- Highlighted **current cue** when in show mode

### 🎛️ Control Modes
- **Setup Mode**  
  Build and edit your show file, add notes, tweak settings.
- **Show Mode**  
  Locked-down environment with clear, minimal controls for live calling and operation.

### ⏱️ Timing Tools
- Stage timer widget (overall runtime)
- Interval countdown widget
- Call time notifier for crew / cast calls

### 🗂️ Widgets & Toggles
- Show / hide widgets depending on production needs
- Notebook widget for quick notes
- Call times table for pre-show organisation

### 📌 Cue Controls
- Integrated **Prev / Next Cue buttons**  
- Optional **Pinned Controls** that stay at the top of the screen while you scroll

### 💾 Show File Handling
- Save/load show files in JSON
- Future-proof design for sharing or archiving productions

---

## 🛠️ Tech Stack

- **Electron** – cross-platform desktop runtime
- **React + TypeScript** – renderer frontend
- **Zustand** – global state management
- **TailwindCSS** – styling
- **electron-builder** – packaging and distribution

---

## 🚀 Installation & Usage

### From Source
```bash
# Clone repo
git clone https://github.com/yourusername/smx-console.git
cd smx-console

# Install dependencies
npm install

# Run in dev
npm run dev
