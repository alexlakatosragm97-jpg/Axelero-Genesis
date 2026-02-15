# Axelero Genesis – AI FPS Optimizer for NVIDIA RTX GPUs (Windows)

**Axelero Genesis** is a real-time performance optimizer for PC gaming.  
It automatically detects your active game and applies **safe OS-level tuning** to stabilize frame-time and improve responsiveness — **no overclocking, no file editing**.

> ⚙️ Focus: **smooth frame-time**, **lower stutter**, **better input feel**  
> ✅ Safe tuning: power plan, process priority, background noise reduction (best-effort)

---

## 🚀 Official Download
**Gumroad (Windows build):**  
https://lakatosphere6.gumroad.com/l/gmnxn

---

## 🧠 What it does (in simple terms)
When a supported game becomes the foreground window, Axelero Genesis can:
- Detect the game process (even when started via launchers)
- Set **High** process priority (best-effort)
- Switch Windows power plan to **High / Ultimate performance** (best-effort)
- Keep tracking runtime + active target
- Avoid false positives via blacklist + launcher handoff logic

✅ **No GPU BIOS changes**  
✅ **No manual overclocking**  
✅ **No game file modifications**

---

## 🎯 Key Features
- **Auto Target Detection** (Foreground game recognition)
- **Launcher → Game Handoff** (Epic / Steam / etc.)
- **Safe Boost Actions**
  - Process priority (High)
  - Optional CPU affinity (advanced)
  - Windows power plan switch (best-effort)
- **UI Telemetry**
  - Target name
  - Boost status
  - Runtime counter
  - GPU name & VRAM (where supported)

---

## 🖥️ Supported (Beta scope)
**Windows 10 / 11**  
**NVIDIA RTX GPUs** (tested on: RTX 3060 Ti; expanding to 30/40 series)

Games (examples):
- Fortnite
- Call of Duty / Warzone
- Cyberpunk 2077
- Any fullscreen / borderless game window (with rules)

---

## 📸 UI Preview
![Axelero Genesis UI](assets/ui-demo.png)

---

## ⚡ Quick Start
1. Download from Gumroad
2. Run Axelero Genesis
3. Start your game (Epic/Steam/etc.)
4. When the game is detected, UI changes to **Target: ACTIVE**
5. Enjoy smoother gameplay

---

## 🛡️ Safety & Transparency
Axelero Genesis uses **best-effort Windows APIs**:
- It may fail silently on some systems (permissions, policies, custom power plans)
- It never forces unsafe hardware settings
- Any tuning is reversible by closing the app (power plan restore if enabled)

**Important:** This software does **not** guarantee FPS gains.  
Results depend on hardware, drivers, game engine, and system state.

---

## ❓ FAQ (short)
**Does it overclock my GPU?**  
No.

**Can it break anti-cheat?**  
It does not inject into games. It only uses OS-level settings like priority/power plan.  
Still, use at your own risk.

**Why does antivirus sometimes warn?**  
Performance tools can look suspicious because they manage processes/power plans.  
Always download only from the official link above.

---

## 📌 Roadmap
- Multi-GPU detection improvements
- Better frametime logging
- Optional profiles per game
- Installer improvements (Advanced Installer)
- “Mining mode” research (separate product line)

---

## 📄 License
Axelero Genesis is a commercial product.  
This repository is a **public product page + documentation**.

For business inquiries:
- Email: (add your contact)
- TikTok: @axelerogenesis
