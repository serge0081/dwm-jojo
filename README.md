# 🌀 dwm-jojo — My Personalized Nordic Tiling Environment

A fully customized and unified tiling window manager setup based on **suckless dwm**, styled with the **Nord color scheme** and enhanced with personal configs for **kitty**, **slstatus**, **dmenu**, and **lf**.  
Minimal, fast, expressive, and built for workflow.

---

## 📸 Screenshots

> *(Replace these with your actual screenshots)*

### 📼 Desktop Overview  
![Desktop Screenshot](screenshots/desktop.png)

### 🧱 Tiled Workspace  
![Tiling Screenshot](screenshots/tiling.png)

### 🐱 Kitty + lf Preview  
![Kitty + LF Screenshot](screenshots/kitty_lf.png)

### 🔍 dmenu  
![dmenu Screenshot](screenshots/dmenu.png)

---

## 🔧 Dependencies

### Required for **dwm**
Make sure these packages are installed before building:
- **make**
- **gcc** (or any C compiler)
- **libx11** (X11 core library)
- **libxft** (font rendering)
- **libxinerama** (multi-display support)
- **libxrender**
- **libxext**

### Optional / Recommended (for your full setup)
These enhance your patched build of dwm-jojo:

#### For status2d, glyphs & bar icons:
- **nerd-fonts** (or any patched font)
- **otf-font-awesome** (optional)
- **libxft-bgra** (if needed for emoji/colored glyph support)

#### For Kitty terminal:
- **kitty**  
- **fcitx / ibus** (if using input methods)

#### For slstatus:
- **slstatus** (custom build included)  
- **acpi**, **procfs**, or distro equivalents for battery/CPU/temp

#### For dmenu:
- **dmenu** (your patched build)
- **libxft**
- **libx11**

#### For lf file manager:
- **lf**
- **ueberzugpp** or **sixel support** in terminal (for image previews)
- **kitty** (required for kitty-style previews)
- Optional helpers: `bat`, `fzf`, `mediainfo`, `ffmpegthumbnailer`

---

## ✨ dwm Features & Patches

- **Nord Color Scheme** across the entire UI  
- **Bar Height Patch** for better readability and aesthetic balance  
- **Cfact Patch** allowing fine-grained window ratio control  
- **Vanity Gaps** for clean spacing and modern layout  
- **Rainbow Tags** for instant visual tagging of workspaces  
- **status2d Support** enabling segmented, color-coded bar information  
- **Lightweight & Fast**, staying true to the suckless philosophy  

---

## 🧩 Additional Components in the Setup

### 🐱 Kitty Terminal (Nord-themed)
- Custom `kitty.conf` with Nord colors  
- Smooth, minimal fonts  
- Works perfectly with image previews in lf  
- Matches the whole DWN theme visually  

### 📊 slstatus (with status2d)
- Custom modules & color segments  
- Clean system information  
- Integrated directly into the dwm bar  

### 🔍 dmenu (Personal Build)
- Nord color palette  
- Clean, simple, patched for your workflow  
- Fully consistent with the rest of the UI  

### 📁 lf File Manager (Custom Config)
- Efficient keybindings  
- Kitty-compatible image previews  
- Minimal and Nord-aligned  

---

## 🎨 Philosophy

A cohesive, calm, and aesthetic workflow built on:  
- **Nord colors**  
- **Minimal principles**  
- **Fast tools**  
- **Personal expression**  

Everything works together — **dwm, kitty, slstatus, dmenu, and lf** — to form a unified environment that feels clean, responsive, and truly yours.
